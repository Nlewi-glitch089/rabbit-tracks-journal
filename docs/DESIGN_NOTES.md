# Rabbit Tracks — Design Notes

## 1. Design Direction

Rabbit Tracks is a personal research journal with an Alice in Wonderland-inspired visual identity.

I want the interface to feel like opening a curious storybook or a well-kept journal: whimsical, inviting, and a little unexpected, while still being comfortable to use for reading and writing.

The theme should come through in the details rather than overwhelm the application. Possible visual references include:
- Storybook-like typography and headings.
- Warm paper, ink, and muted color combinations.
- Subtle references to rabbit holes, pocket watches, teacups, playing cards, keys, and curious garden details.
- Small decorative touches that support the atmosphere without competing with the research content.

These are design directions, not a checklist that every screen must contain. I'll use the Excalidraw wireframes as the starting point for layout and adjust visual details as I implement the interface.

## 2. Design Principles

- **Readable first:** research titles, notes, forms, and navigation must remain easy to read.
- **Whimsical, not cluttered:** use theme details selectively.
- **Consistent:** shared elements should look and behave the same across screens.
- **Understandable CSS:** write styles I can explain, debug, and change myself.
- **Responsive:** the interface should remain usable at desktop and smaller screen widths.
- **My own work:** the first version does not need to look like a professionally produced design system. I want to understand how I created the visual experience.

## 3. CSS Approach

I'll build the styling from CSS fundamentals instead of relying on a large framework or complicated effects.

The main areas I'll practice are:
- Selectors, classes, and the cascade.
- Color, typography, borders, and spacing.
- The box model and sizing.
- Flexbox and Grid for page layout.
- Responsive styling.
- Simple hover and focus states.

I'll use clear class names and may introduce CSS custom properties for repeated colors, spacing, and other shared values once the design has a consistent palette.

Decorative effects and animations are optional. They should only be added when I understand how they work and they don't interfere with usability or accessibility.

## 4. Main Layout and Navigation

The application uses a left-hand sidebar for its primary navigation.

The sidebar contains:
- Dashboard
- Research Library
- Questions
- Discoveries
- Sources
- Settings

The navigation should remain consistent as users move between the main application sections. At smaller widths, the layout may need to adapt so the navigation and content remain usable.

## 5. Dashboard

The dashboard is the application's landing page.

It includes:
- A welcome message.
- A search field.
- A New Research Entry action.
- A Recently Updated Research section.
- A View All link to the Research Library.
- The main sidebar navigation.

Recent research includes both questions and discoveries, with the entry title, category, and last-updated information.

The dashboard should help users continue their research or start something new. It will not include statistics or analytics in the first version.

## 6. Research Entry Editor

Creating or editing a research entry takes users to a shared editor.

The editor contains:
- Entry title field.
- Question or Discovery selector.
- Writing area for notes and research.
- Source reference section.
- Save and Cancel actions.

Both entry types use the same editor. The selected type determines how the entry is categorized after saving.

## 7. Research Library

The Research Library displays saved research entries in one central location.

Users can:
- Browse their saved entries.
- Search for specific research.
- Distinguish questions from discoveries.
- View when an entry was last updated.
- Open an entry to review its contents.

Each entry should display enough information to help users recognize it without opening every item.

## 8. Individual Research Entry

Selecting an entry from the Research Library opens its viewing experience.

This view displays:
- The entry title.
- Its category.
- Saved notes and research.
- Associated source references.
- An Edit Entry action.

Users can review their existing work and return to the shared editor when they want to make changes.

## 9. Questions, Discoveries, Sources, and Settings

These sections are accessible through the sidebar.

Questions and Discoveries display entries according to their selected categories.

Sources provides access to references associated with saved research.

Settings provides access to basic application preferences. These sections should remain simple in the first version.

## 10. User Flows and Wireframes

The initial Excalidraw wireframe covers the main dashboard, creating and saving a research entry, and finding and reviewing an existing entry.

The accompanying user-flow documentation maps how users move between these screens and interact with the application.

The wireframes provide a structural reference. The implemented interface can evolve as long as the main user needs and workflows remain supported.

## 11. Implementation Reference

The frontend will be implemented directly in React, JavaScript, and CSS. The design should use reusable components where they make the interface easier to maintain, with shared navigation and a common layout across screens.

I'll create the styling myself and keep it at a level I can understand. The Alice in Wonderland theme should be recognizable through thoughtful colors, typography, and small details—not through complicated CSS or effects.

This document will be updated when implementation decisions result in meaningful changes to the interface.