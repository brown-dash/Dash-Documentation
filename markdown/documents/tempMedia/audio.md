---
layout: default
title: Audio
parent: Temporal Media
grand_parent: Documents
permalink: /documents/tempMedia/audio
nav_order: 1
---

# Audio
{: .no_toc }

<details open markdown="block">
  <summary>
    Table of contents
  </summary>
  {: .text-delta }
1. TOC
{:toc}
</details>
The audio document allows the user to record and play back audio or play back imported audio files.

## Creating Audio Documents
To create an audio document, navigate to the Tools Menu and drag off an audio button onto your collection.

You can also create an audio document by navigating to the Import Menu and importing an audio file from outside of Dash or by dragging and dropping a file in from an external source.

## Actions

### Pre-Recording
- **Record:** Pressing the black record button on a new empty audio document begins a recording
- **Dictation:** Selecting the grey transcript button before beginning the recording creates a text document that transcribes what you say after you begin recording.

### During Recording
- **Pause/Play:** This button pauses and resumes the recording.
- **Stop:** This button stops the recording.
- **Dictation:** Transcription can also be started during the recording by selecting the button and then left clicking the generated text document. This creates a timecode in the document of the time 

### Post-Recording
- **Pause/Play:** This button pauses or plays the audio document from the current time indicated by the red line on the timeline and the timestamp in the bottom left corner.
- **Trimming:** Clicking the scissor icon displays the trim controls. Dragging either of the handles at the end of the timeline will change the range the clip is being trimmed to. Selecting the check icon will finish the trim and display the new altered clip. Trimming is not destructive so a shortened clip can always be lengthened again up to its original duration. Markers that are cut off by trimming a clip will be cut down to the portion that remains in the range of the new clip. If a marker is entirely out of range it will no longer play. Lengthening the clip again will increase the marker up to its initial length.
- **Region Markers:** To create a region marker, click on the desired starting time on the timeline and drag until the desired ending time. The region marker will play audio from the the marker's start to end.
- **Label Markers:** To create a label marker, shift-click the desired time on the timeline. The label marker will playback audio from the start time of the marker to the end of the entire audio clip.

Both types of markers can be deleted by right clicking on them to display the context menu and then selecting delete.

## Right-Click Menu
The following audio-specific items can be found in the right-click menu for an audio document:
- **Play/Don't play when link is selected:** Toggle this option to play/don’t play the audio at the linked time when a link has been selected
- **Hide/Don't hide ranged markers:** Toggle this option to hide/not hide the ranged markers
- **Hide/Don't hide label markers:** Toggle this option to hide/not hide the label markers
- **Play/Don't play markers on click:** Toggle this option to play/not play the ranged/labels markers when they are selected

## Link Audio Documents
While recording, if the user creates any text documents, it will automatically be linked to the audio document at the creation time. While recording, the user can generate timestamps for the text document by pressing enter or pausing for 10 seconds (this can be toggled in the text document’s context menu). Linking to the audio document will generate a link at the current time. Linking to range/label markers will generate a link corresponding to their start/end time.