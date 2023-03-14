## Filetree Redesign (WIP)
## Owner:
- Adriana
## Stakeholders:
- Tyler
- Seeking eng help

## Abstract
The filetree is a central surface of the workspace with persistent usability issues. As we replace the sidebar with the navigator for workspace v2, we should prioritize a seamless file management experience. This includes 1. fixing existing usability issues and 2. introducing new configuration features to the filetree to enhance workflow in the workspace.

## Current resources
- [Tyler's Filetree Mania Figma](https://www.figma.com/file/ysNJHeLLcREMEP5VChNTOQ/File-tree-mania?node-id=0%3A1)
- [Drag and Drop Bug Evidence](https://replit.slack.com/archives/C85MLAXU2/p1657036479147099)
- [Multiselect Slack Discussion](https://replit.slack.com/archives/C0308MFK63W/p1655790706397929)

## Goals

### Primary Metric Impacted 
Which metric(s) are affected by this experiment?  
What are the measures of success?  
What are the guardrail metrics in place?

#### Expected Impact - based on if the launch/expt is successful

### Expected Learnings 
What are we hoping to learn from this launch/experiment? Can be certain assumptions or hypotheses that are being tested and/or validated 
Assumptions:
- Users want to be able to perform bulk actions on files
- Users want to be able to sort and filter files within the filetree
- Users want to be able to customize the organziation of their filetree

## Requirements

### Usability fixes
- improve drag and drop interactions with automatic scrolling
- multiselect files to move, open, rename, duplicate, download, delete, etc.
- allow file moving from context menu
- improve discoverability of file name and file content search
- improve mobile interactions, generally

### New features
- sort tree by file type, recently edited
- filter tree by file type
- arbitrary ordering of files
- file favoriting
- filetree sections / headers
- custom folder icons
- custom file types

### User flows & Surfaces 
All users are impacted in the workspace.

### Milestones
1. Usability fixes
   - goal: alleviate persistent issues with the current filetree
2. New features
   - goal: enhance use workflow by improving file management experience

## Technical decisions
High-level notes of the technical discussion we had in the meeting

## Open Questions
Things we couldn’t figure out in this meeting
This might require some prototyping or another meeting to hash out

## Future considerations
We probably didn’t get to do everything we’d like in this project. What are some cool ideas for the future?
