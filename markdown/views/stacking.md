---
layout: default
title: Stacking
parent: Views
permalink: /Views/stacking/
nav_order: 3
---

# Stacking View

{: .no_toc }

<details open markdown="block">
  <summary>
    Table of contents
  </summary>
  {: .text-delta }
1. TOC
{:toc}
</details>

## Description:

Displays a set of documents in one or more scrollable stacks. By default, all documents are placed in a single stack. If a key is specified, multiple stacks will show up side-by-side, each containing documents sharing the same value for that key. Additionally, each value is displayed as an editable text field with a colored background at the top of the stack.

## Good for:

Categorizing documents by specified keys while maintaining a live preview of each document
Navigating Dash as a “Trello Board”

## Objects & actions:

- Categorizing documents by a specified key: when a key is specified via typing in the “Group by” input box besides the perspectives pulldown, the default single stack transforms and displays multiple stacks side-by-side, each containing documents sharing the same value for that key.
- Updating the value of a specified key
  - For a single document: click and drag the desired document, then drop it into the target stack to update its value
  - For a stack: click on the title (value) at the top of the stack to edit or delete the value
- Reposition documents within a stack: click and drag the desired document, then drop it into the target location within the stack to reposition it vertically. This will not affect its metadata.
- Navigating Dash as a “Trello Board” - when combined with a document view showing only a document’s title, this essentially becomes a Trello board
