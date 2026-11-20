# Rabbit Tracks — First Version Requirements

## What I'm Building First

I'm building the main research-journal experience: creating entries, organizing them, and finding them again.

The first version should do these things well before I add more complicated features. The application will be built with React, JavaScript, and CSS. These requirements describe the intended behavior; they do not mean the features have already been implemented.

## Main Screens

### 1. Dashboard

The dashboard is the first screen users see when they open Rabbit Tracks.

It will include:
- A welcome message.
- A button to create a new research entry.
- A search field.
- A section showing recently updated research.
- A link to view the full research library.
- A sidebar for navigating the application.

Recent research will include both questions and discoveries.

### 2. Research Library

This is where users can browse their saved research entries.

It will include:
- A list of saved entries.
- The entry title and a short preview.
- An indication of whether an entry is a question or discovery.
- Information about when an entry was last updated.
- Search and basic filtering.

### 3. Research Entry Editor

Questions and discoveries will use the same editor. I don't want to maintain two separate editing experiences when the entries share the same basic structure.

The editor will include:
- A title.
- An entry type selector.
- A writing area for notes and research.
- A place to add source references.
- Save and Cancel actions.

Users will choose whether an entry is a question or discovery when creating or editing it.

### 4. Questions

This screen will show research entries categorized as questions.

### 5. Discoveries

This screen will show research entries categorized as discoveries.

### 6. Sources

This screen will provide a place to review sources connected to research entries. A source should remain associated with the entry it supports.

### 7. Settings

This screen will contain basic application preferences. I'll keep it simple until there's a clear need for additional settings.

## Core User Workflows

The first version should support these workflows:

1. Open the dashboard and start a new research entry.
2. Enter a title, choose Question or Discovery, add notes, and add source references.
3. Save the entry.
4. Find the saved entry in the research library.
5. Search or filter entries to narrow down the results.
6. Open an entry to review its notes and sources.
7. Edit an existing entry and save the changes.
8. Navigate between the dashboard, library, questions, discoveries, sources, and settings.

## What I'm Leaving Out of the First Version

I don't want to add features just because they sound interesting. These are outside the initial scope:

- AI-generated research and summaries.
- Automated recommendations.
- Advanced analytics and statistics.
- Complex citation integrations.
- User accounts and authentication unless they become necessary for the agreed first-version use case.
- Features that don't directly improve creating, organizing, or revisiting research.

## Visual and Usability Requirements

- The interface should have an Alice in Wonderland-inspired, curious storybook feel.
- The theme should support the experience rather than make the application harder to use.
- Text, forms, navigation, and entry content must remain readable.
- The layout should work at common desktop and mobile widths.
- CSS should be written in a way I can understand, explain, and maintain. I don't need elaborate effects or complicated styling techniques to make the theme recognizable.
- Shared interface elements should look and behave consistently across screens.

## What Needs to Work Before I Consider the First Version Usable

A user should be able to create an entry, choose its type, save it, find it in the research library, open it again, and make changes.

Search and navigation should make it possible to move around the application without getting lost. The notes and source references should remain connected to the correct research entry.

The first version should also provide clear feedback when there are no entries to display or when an action cannot be completed.

## Development Milestones

The current target is Demo Day on December 4, 2026.

| Dates | Focus | Intended result |
|---|---|---|
| Nov 20–22 | React foundation and application setup | React project running with an initial application shell |
| Nov 23–26 | Layout, navigation, dashboard, and library | Main screens and navigation structure in place |
| Nov 27–29 | Shared editor and entry workflows | Create, view, and edit questions and discoveries |
| Nov 30–Dec 1 | Essential functionality and persistence | Core workflow works with an appropriate data-saving approach |
| Dec 2–3 | Testing and refinement | Main workflows tested; responsive and visual issues addressed |
| Dec 4 | Demo Day | Demonstrate the working application and explain its implementation |

These are targets, not completed milestones. I'll revise them if implementation reveals a better sequence or a necessary change in scope.