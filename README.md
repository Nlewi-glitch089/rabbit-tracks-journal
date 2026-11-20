# Rabbit Tracks

Rabbit Tracks is a personal research journal that gives people one place to keep track of their questions, discoveries, notes, and sources.

I wanted to build something that makes it easier to follow an idea, write down something interesting, and come back to it later without having information scattered across different places. The goal is to create a simple, organized space where research can grow over time.

## Project Status

I'm rebuilding Rabbit Tracks from the ground up. The planning, initial requirements, wireframes, user flows, and repository documentation are in place. I'm now beginning frontend development.

The application is not yet complete. Features will be marked as finished only after they have been implemented and tested. I'll keep the development log updated with what I actually work on, what I learn, problems I encounter, and the decisions I make.

## What I'm Building

The first version is focused on the main research-journal experience:

- **Dashboard:** start a new entry, search, and return to recently updated research.
- **Research library:** browse, search, and filter saved entries.
- **Questions and discoveries:** organize entries by type.
- **Shared research-entry editor:** create and edit either type of entry using the same editor.
- **Sources:** keep references connected to the research they support.
- **Settings:** provide basic application preferences.

Questions and discoveries will share the same underlying entry structure. The selected type will determine how an entry is categorized and displayed.

## Technology

The current frontend plan is:

- React
- JavaScript
- CSS

I'll introduce additional tools or technologies only when the application needs them and after documenting why they're being used. The persistence and backend approach will be decided as the frontend and data requirements become clearer.

## Design Direction

Rabbit Tracks will have an Alice in Wonderland-inspired visual theme. I want it to feel like a curious, slightly whimsical storybook journal without making the interface difficult to read or use.

I'm writing the CSS myself as part of the learning process. The styling should be understandable and maintainable, not unnecessarily complicated. A handmade result is fine; understanding how I built it matters more than making every detail look professionally polished.

## Development Plan

The current target is to have a usable first version ready for Demo Day on **December 4, 2026**.

- **November 20–22:** establish the React project foundation and build the initial application shell.
- **November 23–26:** implement the main layout, navigation, dashboard, and research library.
- **November 27–29:** build the shared entry editor and the question/discovery workflows.
- **November 30–December 1:** complete the remaining essential functionality and determine/implement the appropriate data-persistence approach.
- **December 2–3:** test the complete experience, fix issues, refine responsive styling, and prepare the demo.
- **December 4:** Demo Day.

This is a working schedule, not a claim that these features are already complete. If a task changes, I'll update the plan and explain why.

## Learning and Development Approach

I'm using my B.U.I.L.D. approach throughout development:

1. **Begin with the problem** — understand what needs to be solved.
2. **Understand requirements** — define what the feature should do.
3. **Interrogate AI** — ask questions and understand unfamiliar concepts before using generated code.
4. **Lay out the blueprint** — plan the structure and implementation.
5. **Develop deliberately** — write, test, debug, explain, and document the work.

I'll also use Codecademy's free courses as a structured study resource. The course sequence and how it connects to this project are documented in [the learning plan](docs/LEARNING_PLAN.md).

## Project Documentation

The `docs/` folder contains the planning and development material:

- [Project overview](docs/PROJECT_OVERVIEW.md) — purpose, audience, and application areas.
- [First version requirements](docs/REQUIREMENTS.md) — the initial feature scope and acceptance criteria.
- [Technical plan](docs/TECHNICAL_PLAN.md) — application structure and development sequence.
- [User flows](docs/USER_FLOWS.md) — how users move through the main tasks.
- [Design notes](docs/DESIGN_NOTES.md) — visual direction, wireframes, and interface behavior.
- [Development decisions](docs/DECISIONS.md) — the reasoning behind key choices.
- [Learning plan](docs/LEARNING_PLAN.md) — the ordered Codecademy study sequence.
- [Development log](docs/DEVELOPMENT_LOG.md) — work completed, lessons learned, problems, and next steps.

## Getting Started

Setup instructions will be added after the React project scaffold and its dependencies are in place.