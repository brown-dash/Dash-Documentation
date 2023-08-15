---
layout: default
title: Collaboration
parent: Features
permalink: /features/collaboration/
nav_order: 3
---

*[HTML]: Hyper Text Markup Language
*[W3C]:  World Wide Web Consortium
*[NPM]: Node Package Manager
*[IDE]: Integrated Development Environment
*[MERN]: MongoDB, Express, React, NodeJS
*[Yarn]: Yet Another Resource Negotiator
*[ACLs]: Access Controls

# Collaboration & ACLs
{: .no_toc }

<details open markdown="block">
  <summary>
    Table of contents
  </summary>
  {: .text-delta }
1. TOC
{:toc}
</details>

## Description 
For each document, individual users, groups, and guests can have permissions called Access Control Levels (ACLs) that determine the degree to which they can modify the document. These permissions include:

| ACL | Description |
| :------------------| :---------- |
| Admin              |  Users with Admin permission can: <br> - Change ACLs <br> - Delete and minimize documents <br> - Delete and add content <br> - Resize documents <br> - Move documents   |
| Edit               |  Users with Edit permission can: <br> - Delete and minimize documents <br> - Delete and add content <br> - Resize documents <br> - Move documents |
| Augment            |  Users with Augment permission can: <br> - Delete  only their own content <br> - Add content <br> - Resize documents <br> - Move documents | 
| View               |  Users with View permission cannot edit, delete, or move any documents |
| Not shared         |  These users will not be able to view the contents of the Dashboard or document. |

## Guests 
Guest users are never able to make changes to shared documents: any edits made on a guest account will not be transferred to the original document. If the guest permission is set to View rather than Not-Shared, individuals without specified permission to this document will be able to see it. To allow guest users view your document, send them the guest URL that can be found in the Share menu for that document. Alternatively, guest users can access documents by their ID.

## Developer Mode Functionalities

- **Upgrade Nested:**
When a parent document with nested child documents is shared at a permission level more restrictive than the permission levels of its children, the children automatically adopt the more restrictive permission. However, in order for nested child documents to adopt parent permissions that are less restrictive than their current permission, the ‘Upgrade Nested‘ checkbox must be selected.
- **Layout:**
Layout permissions refer to the ability to move and resize documents. A document’s layout permissions are initially simply the permissions of the document that the selected document is nested inside of - until they are explicitly set otherwise.