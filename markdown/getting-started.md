---
layout: page
title: Getting Started
permalink: /getting-started/
nav_order: 3
---

# Getting Started

{: .no_toc }

<details open markdown="block">
  <summary>
    Table of contents
  </summary>
  {: .text-delta }
1. TOC
{:toc}
</details>

## Import and Content Creation

There are multiple ways that you can import into Dash. The essential ways are as follows:

- **Drag and drop**: drag any of the accepted file types from your computer or a webpage and drop it into your dashboard.
- **Import**: import using the import menu on the left hand side
- **Begin typing `:`** to bring up the document menu, from which you can create a document.

## Documents

Everything in Dash is considered a document. Documents store data as arbitrary key-value pairs.

### Document Types

Dash supports several document types, each with unique capabilities. The primary types are as follows:

- **[Text](documents/text.md)**: rich (RTF) text documents that support various text and hypertext features
- **[Webpages](documents/webpage.md)**: HTML webpages from external sites
- **[PDFs](documents/pdf.md)**: PDF files created outside of Dash
- **[Temporal Media](documents/tempMedia/temporal-media.md)**: audio and video files
- **Ink**: ink strokes drawn with the pen or polygon tool
- **Images**: digital images from external sources

### Selecting Documents

There are three ways to select a document in Dash. To select a single document, simply left-click or right-click the desired document to bring it into focus.

You can select multiple documents via marquee or shift-click. To use the marquee tool, right-click on the canvas to invoke the marquee; then, drag the bounding area to include your desired documents. To use shift-click, hold down the shift key while left-clicking on multiple documents.

To select text in PDFs and webpages (not text documents), click and drag to highlight the desired text.

### Editing Documents

The following editing functions are universal to all document types:

- **Document chrome**: floating set of tools to change document properties
  - Accessed via single selection (left or right click)
- **Properties panel**: panel displaying document type-specific actions
  - Accessed via (A) the double arrows in the top right or (B) the single arrow on the right edge of the screen
- **Right-click menu**: menu displaying actions on documents
  - Accessed by right-clicking anywhere on the target document or left-clicking the settings icon on each document

All documents also have a context-sensitive toolbar. The toolbar contents vary depending on the document type.

### Transforming Documents

There are four main ways to transform a document: move, resize, open in a new tab or tile, and close.

- **Move**
  - **Selected documents**: click and drag on the title to move the document, then drop at the desired location.
  - **Unselected documents**: hover over the document to bring it into focus, then click/drag/drop to the desired location.
- **Resize**
  - **Size**: click and drag the corner handles in the border chrome.
  - **Border radius**: click and drag the small circle in the bottom right corner of the border chrome.
- **Open in a new tab or tile**
  - Click on the rightmost “open in a new tile” icon in the header chrome to open a full view of the document in a new tile (defaults to alias).
- **Close**
  - **Selected documents**: click on the leftmost “x” icon in the header chrome to close the document. Alternatively, click on the trash icon under the “actions” subpanel of the properties panel to close the document.
  - **Unselected documents**: right-click anywhere in the document to bring up the right-click menu, then click “close”.

## Views

Views represent various ways to visualize a collection. Users can toggle different views through the pull-down menu in the leftmost region of the context-sensitive toolbar. Alternatively, they can open a new view as an alias by right-clicking on the current collection and selecting the desired perspective. The default view is freeform.

### Freeform

**Description**: unbounded 2D space in the form of a canvas

**Good for**:

- User-driven spatial organization and document layouts
- Visualizing document relationships, e.g., neighborhoods/clusters of related materials, nesting, and linking
- “Raw” document views to get a sense of individual layouts

### Schema

**Description**: table view of documents. Each document is a row, and each column displays the contents (values) stored with the unique document key. Nested collections can be expanded in-line. The title, author, date last modified, text, and context columns are displayed by default, and users can manually add more columns with existing keys or user-defined keys.

**Good for:**

- Maintaining structured viewing and sorting of data
- Manipulating documents via key-value pairs
- Working with search functionality
- Navigating Dash an an “Excel sheet”

### Tree

**Description**: a hierarchal outline of documents. Each item is expandable into sub-items, and sub-items range from a sub-tree of documents stored inside the current document to a live preview of the current document.

**Good for**:

- Viewing hierarchical relationships between documents
- Navigating Dash as a file directory
- Manipulating document z-indices (overlay layer)

### Stacking

**Description**: scrollable stacks of documents. All documents are placed in a single stack by default. If a key is specified, multiple stacks will show up side-by-side, each containing documents sharing the same value for that key.

**Good for**:

- Categorizing documents by specified keys while maintaining a live preview of each document
- Navigating Dash as a “Trello Board”

### Masonry

**Description**: 2D grid of tiles that avoids empty space. Documents automatically reflow and wrap as the aspect ratio is reszied. Documents can be categorized via unique keys, which displays each category in a separate grid. Multiple categories are vertically stacked.

**Good for**:

- Avoiding vertical or horizontal padding required by grid perspectives
- Navigating Dash as a “Pinterest Board”

## Links and Anchors

A link is a bidirectional reference from one document to another. The link itself is also a document, so we can add tags and key-value pairs to it. The same source selection (aka anchor) can link to multiple destinations, which range from an entire document to a portion of a document (eg. an annotation in a PDF, highlighted phrase in text, etc.)

There are two ways to create links: drag and drop or linkboard.

### Drag and drop

Drag and drop creates a 1:1 link between documents that both appear on the screen at a given time, whether in the same tab or in two different tiles.

1. Select the desired source document and navigate to its bottom toolbar.
2. Click and drag the link icon. Drop it onto the desired destination document.

Once a document is created, two messages will appear: one confirming successful link creation, and another prompting users for an optional link label. Labels may be modified later thorugh the link menu. The document will then display a number displaying the number of links it contains.

### Linkboard

Linkboards function as a clipboard: they "copy" source documents to the linkboard until they are cleared or linked to another source. This is convenient for creating multiple links with the same source and/or creating links while maintaining another workflow.

1. Select the desired source document and navigate to its bottom toolbar.
2. Left-click the "make link" button.
   1. A popup bar will display at the bottom of the screen with two options: one to toggle displaying or hiding optional link labels, and one to clear the current linkboard.
3. Complete the link by clicking the "complete link" button in the bottom toolbar of the target document.

## Annotation and Markup

## Collaboration

## [Trails](../features/trails)
