# Rabbit Tracks — Development Decisions

This document records the decisions I've made while planning and building Rabbit Tracks. I want to keep track of why I chose a particular approach, especially when a decision affects how the application is organized or how users interact with it.

## 1. Rebuilding the Application

**Decision:** Start with a new repository and rebuild the application from the ground up.

**Why:** I want a clean foundation where I understand how the project is organized and how each part works. I'm keeping the original concept, but I'm not carrying the old implementation forward as the foundation for this version.

## 2. Using React From the Start

**Decision:** Build the frontend directly with React, JavaScript, and CSS.

**Why:** I want to learn and apply React while developing the actual application. Building a separate plain HTML/CSS/JavaScript version and converting it later would create an extra implementation step. I'll learn the underlying HTML, CSS, and JavaScript concepts alongside React so I understand what React is organizing and simplifying.

## 3. One Editor for Questions and Discoveries

**Decision:** Use one shared editor for both entry types.

**Why:** Questions and discoveries have the same basic editing needs. Maintaining two separate editors would create unnecessary duplication. The entry type will determine how an item is categorized.

## 4. Dedicated Entry Creation Page

**Decision:** Give research entry creation its own page.

**Why:** I want users to have enough room to write and organize their research. A dedicated page also keeps the dashboard from becoming cluttered with editing controls.

## 5. Sidebar Navigation

**Decision:** Use a left-hand sidebar for the main navigation.

**Why:** The main sections should be easy to access without requiring users to return to the dashboard every time they want to move somewhere else.

## 6. No Dashboard Statistics

**Decision:** Keep numerical statistics and analytics out of the initial dashboard.

**Why:** The dashboard should help users continue their research. I would rather use that space for recent entries and useful actions than numbers that aren't necessary to the main experience.

## 7. Alice in Wonderland-Inspired Visual Direction

**Decision:** Give Rabbit Tracks an Alice in Wonderland-inspired, storybook-like visual identity.

**Why:** I want the application to feel curious and whimsical while remaining practical as a research journal. The theme should come through in thoughtful colors, typography, and small decorative details rather than complicated effects that make the interface harder to use.

## 8. Understandable, Self-Written CSS

**Decision:** Write and maintain the application's CSS myself, using straightforward CSS fundamentals.

**Why:** Understanding how the interface is styled is part of the project for me. I would rather create a simpler result that I can explain and maintain than rely on elaborate styling techniques I don't understand yet.

I'll add to this document whenever I make another decision that changes the direction, structure, or behavior of Rabbit Tracks.