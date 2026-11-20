# Rabbit Tracks — Technical Plan

## How I'm Approaching Development

I'm rebuilding Rabbit Tracks from the ground up, starting with a clear foundation instead of trying to implement everything at once.

I want to understand how each part of the application works, why it's needed, and how the pieces connect. I'm building the frontend with React, JavaScript, and CSS from the beginning. I won't create a separate plain-JavaScript version just to convert it into React later.

I'll introduce additional tools and technologies when there's a reason for them, rather than adding dependencies before I need them. The backend and persistence approach will be decided after the initial frontend structure and data requirements are clearer.

## Frontend Structure

I'll keep the initial project structure straightforward and let it grow with the application.

Possible responsibilities include:

- `components/` — reusable interface elements such as the sidebar, navigation items, buttons, and research-entry cards.
- `pages/` — the main application screens, such as the dashboard, research library, and entry editor.
- `assets/` — images, icons, and other visual resources.
- `styles/` — CSS files for shared styles and, where useful, individual components or pages.
- `App.jsx` — the main application component that brings the interface together.
- `main.jsx` — the entry point that mounts the React application.

This is an initial guide, not a requirement to create every folder immediately. I'll choose the simplest structure that supports the code I actually have.

## Development Sequence

1. Set up the React project and verify that the development environment runs.
2. Understand the entry point, JSX, components, and how the application renders.
3. Build the shared page layout and sidebar navigation.
4. Create the dashboard and research library views.
5. Build the shared research-entry editor.
6. Implement the question and discovery workflows.
7. Add search, filtering, and source-reference handling.
8. Decide how entries should be saved and persisted, then implement the appropriate approach.
9. Test the main user workflows and refine the responsive interface.

I'll build and test in small increments instead of waiting until the end to find out whether everything works together.

## CSS and Visual Implementation

The visual direction is Alice in Wonderland-inspired: curious, storybook-like, and a little whimsical.

I want to create that feeling with CSS I can understand. I'll focus on the fundamentals first:

- Selectors and the cascade.
- Colors, typography, spacing, and borders.
- The box model and sizing.
- Flexbox and Grid for layout.
- Responsive rules and readable interfaces.
- Simple transitions or decorative details only when they serve the design.

I'll favor clear class names, reusable CSS variables for shared values, and straightforward selectors. I don't need complex animations, elaborate effects, or a CSS framework to make the theme work.

The goal is to understand and own the styling, even if the result is less polished than a professionally designed interface.

## Learning Along the Way

I'm not treating AI-generated code as a substitute for understanding the application. I'll use Codecademy, official documentation, experimentation, and AI assistance to work through unfamiliar concepts.

Before using a concept in the application, I want to understand:
- What problem it solves.
- How it works.
- Why it belongs in this part of the application.
- How it connects to the code already in place.

I'll write as much of the implementation myself as possible, test it, investigate errors, and explain what the code does. The ordered Codecademy study sequence is in `LEARNING_PLAN.md`.

## Testing and Documentation

I'll test each feature as it is built. When something fails, I'll record the error, investigate the cause, and document the resolution when it is useful for future work.

The README, requirements, design notes, technical plan, and development log should stay consistent with the actual application. Planned work must not be described as completed work.