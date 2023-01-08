---
layout: default
title: Trails
parent: Features
permalink: /features/trails/
nav_order: 3
has_children: true
---

# Trails
{: .no_toc }

<details open markdown="block">
  <summary>
    Table of contents
  </summary>
  {: .text-delta }
1. TOC
{:toc}
</details>

"The human mind does not work that way. It operates by association. With one item in its grasp, it snaps instantly to the next that is suggested by the association of thoughts, in accordance with some intricate web of trails carried by the cells of the brain. It has other characteristics, of course; trails that are not frequently followed are prone to fade, items are not fully permanent, memory is transitory. Yet the speed of action, the intricacy of trails, the detail of mental pictures, is awe-inspiring beyond all else in nature." 
- As We May Think, Vannevar Bush (1945)

Presentation Trails allow the user to navigate through selected documents with a predefined path.

With presentation trails you can easily go from authoring mode, to presentation mode - and turn whatever you are working on into a smooth presentation. Presentation Trails work best when all of the documents are contained within Freeform collections, as it makes use of pan and zoom to navigate between documents.

## Creating and Accessing Trails

There are two ways to open up the Presentation Trails sidebar:
- **Menu panel:** The trails button in the lefthand menu will open up a list of your existing trails which you can open by double clicking, as well as a "New Trail" button to create a new presentation.
- **Pinning a document:** Using the document decorations ‘Pin to Presentation’ button, you can pin any document to the Active Presentation. If you have not created a presentation yet, this will begin a new one and open the Trails sidebar on the right side of your workspace. If you have a previous presentation (or multiple) you closed, it will pin the document to the most recent presentation and open it up.

## Objects & Actions

### Adding documents to a trail

#### Regular pin:
To pin any document to the presentation trail simply select a document and use the ‘Pin’ button in the document decorations to add it to the presentation trail. If the user has not yet created a presentation trail, then this button will also create a new presentation trail and add that specific document as the first slide in the trail.

#### Pin with view:
Pinning with view pins the canvas with the specific pan and zoom you have it set to, allowing you to show a view of multiple documents laid out on a collection. You can pin with view in two ways:
- **Top menu bar:** this pins the canvas with the pan and zoom of the tab as you are currently viewing it
- **Marquee menu:** this option appears when you right click and drag on the canvas to create a marquee selection and pins the canvas with the marquee bounds as the viewport

### Slides
Slides are used to visually represent the path that the trail would follow. Unlike the conventional Powerpoint "slide", a trails slide is just any pinned item in a presentation, whether it's a document, collection, view, etc. A single node can be pinned multiple times throughout a presentation, potentially with different content or layout aspects that change, but each of these instances is a unique slide.

Selected slides are indicated by the blue outline and the light blue background, on each slide the user can find: 
- Slide title: in bold on the far left hand side of the slide
- M: The duration of the movement to the slide
- D: The duration for which the slide will remain in focus for Auto-Present
- Slide specific expand and minimise options
- The option to remove the slide from the presentation (Note: does not remove slide from the collection or database, only from the presentation). 

They can be rearranged, retitled, and expanded to show a preview of what is in the slide. 

### Transitions

**Movement:** Specify the type of movement from the following options, as well as the amount of time that the movement from one document to the next will take:
Pan and zoom: Center the document in the containing collection and zoom in on it so it takes 75% of the height or width of the screen depending on what fits.
Pan: Center the document maintaining the current scale of the containing collection
Jump Switch: Switch to the zoomed in document with no transition time
None: Nothing happens when this slide is the active one in the trail.

**Visibility & Duration**
- ide before: When this toggle is on the document will appear hidden before it is presented in the presentation trail
- Hide after: When this option is toggled on after the slide is presented it will not appear in the presentation trail.
- Lightbox: Open the document in Lightbox view, instead of navigating to it within the collection. This can be useful for navigating Websites/PDF etc.
- Slide duration: Choose the amount of time that the slide will remain in focus when in Auto-present mode.

**Effects**
Choose to have an effect on the entrance of the selected document. The possible effects include: Fade In, Flip, Rotate, Bounce, and lastly Roll. 

### Presenting