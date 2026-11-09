# Rabbit Tracks — User Flows

This document explains how I expect someone to navigate and interact with Rabbit Tracks. I want to map out the main actions before building the individual screens so the application feels connected rather than like a collection of separate pages.

## 1. Opening the Application

When someone opens Rabbit Tracks, they land on the dashboard.

From there, they can start a new research entry, search for something they've saved, revisit recent research, or navigate to another section using the sidebar.

## 2. Creating a Research Entry

When someone clicks **New Research Entry**, they are taken to a dedicated editor page.

They can:
- Enter a title.
- Choose whether the entry is a Question or Discovery.
- Write notes and information.
- Add references to sources.
- Save or cancel their changes.

Both entry types use the same editor.

### What Happens After Saving?

After clicking Save, the user is taken to the Research Library.

Their new entry should appear in the library with its title, entry type, and last-updated information. From there, they can open it again or continue browsing their research.

I chose this destination because it gives users an immediate view of their saved work instead of sending them back to the dashboard without showing where the entry went.

**User flow:**

Dashboard → New Research Entry → Research Entry Editor → Save → Research Library

## 3. Finding Existing Research

Users can visit the Research Library to browse everything they've saved.

They can also visit Questions or Discoveries to see entries belonging to a particular category.

Selecting an entry opens it so the user can read or edit its contents.

## 4. Searching

The dashboard and research library will provide access to search.

Users should be able to search through their saved research and find the entry they're looking for.

## 5. Working With Sources

Users can associate sources with their research entries.

The Sources section will provide a place to review those references without having to search through every individual entry.

## 6. Editing Existing Research

When a user opens an existing entry, they should be able to review its contents and make changes.

The same editor used to create entries will be used to edit them.

## 7. Saving Changes

When a user saves an entry, the changes should be reflected wherever that entry appears, including the Research Library, Questions or Discoveries, and recent research on the dashboard.

I'll update these flows as I work through the wireframes and decide how each interaction should behave.