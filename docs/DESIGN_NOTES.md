# Rabbit Tracks Journals — Design Notes

## 1. Design Direction

Rabbit Tracks Journals is designed around a straightforward research-journal experience. The interface should make it easy to start an entry, organize saved research, and return to previous work.

I'm prioritizing clear navigation, readable content, and a layout that doesn't overwhelm users with unnecessary information.

The initial design is based on hand-created Excalidraw wireframes.

## 2. Main Layout and Navigation

The application uses a left-hand sidebar for its primary navigation.

The sidebar contains:
- Dashboard
- Research Library
- Questions
- Discoveries
- Sources
- Settings

This navigation remains accessible as users move between the main application sections.

## 3. Dashboard

The dashboard is the application's landing page.

It includes:
- A welcome message.
- A search field.
- A New Research Entry action.
- A Recently Updated Research section.
- A View All link to the Research Library.
- The main sidebar navigation.

Recent research includes both questions and discoveries, with the entry title, category, and last-updated information.

The dashboard is intended to help users continue their research or start something new. It will not include statistics or analytics.

## 4. Research Entry Editor

Creating a research entry takes users to a dedicated editor page.

The editor contains:
- Entry title field.
- Question or Discovery selector.
- Writing area for notes and research.
- Source reference section.
- Save and Cancel actions.

Both entry types use the same editor. The selected type determines how the entry is categorized after saving.

## 5. Research Library

The Research Library displays saved research entries in one central location.

Users can:
- Browse their saved entries.
- Search for specific research.
- Distinguish questions from discoveries.
- View when an entry was last updated.
- Open an entry to review its contents.

Each entry should display enough information to help users recognize it without opening every item.

## 6. Individual Research Entry

Selecting an entry from the Research Library opens its dedicated viewing page.

This page displays:
- The entry title.
- Its category.
- The saved notes and research.
- Associated source references.
- An Edit Entry action.

Users can review their existing work and return to the shared editor when they want to make changes.

## 7. Questions, Discoveries, Sources, and Settings

These sections are accessible through the sidebar.

Questions and Discoveries display entries according to their selected categories.

Sources provides access to references associated with saved research.

Settings provides access to basic application preferences.

These sections follow the same overall layout and navigation structure as the rest of the application.

## 8. User Flows and Wireframes

The initial Excalidraw wireframe covers three main views:

1. Dashboard.
2. Creating a research entry and saving it.
3. Finding an existing entry and reviewing it.

The accompanying user-flow documentation maps how users move between these screens and interact with the application.

These wireframes serve as the reference for the initial frontend implementation.

## 9. Implementation Reference

The initial frontend will be built to match the established wireframe using HTML, CSS, and JavaScript before transitioning into React.

The design should remain consistent across screens, with shared navigation and a common layout where appropriate.

This document will be updated when implemented design decisions result in meaningful changes to the interface.