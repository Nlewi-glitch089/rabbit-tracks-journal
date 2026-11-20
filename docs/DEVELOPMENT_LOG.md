# Rabbit Tracks — Development Log

This log records the work I actually complete while building Rabbit Tracks. It tracks implementation progress, what I learn, technical decisions, problems, and the next steps.

I won't use this as a list of tasks I hope to finish. Planned work and completed work should always be clearly distinguished.

---

## 1. Project Reset and Planning

**Status:** Initial planning completed.

**Work completed:**
- Decided to rebuild Rabbit Tracks using a new, separate repository.
- Retained the personal research-journal concept.
- Established a more deliberate development approach focused on understanding the implementation.
- Created the initial project overview and first-version requirements.
- Identified the main application screens and navigation.
- Established one shared editor for Questions and Discoveries.

**Outcome:**

Established a clearer direction for the rebuild and separated the new project from the previous implementation.

---

## 2. Wireframing and User Flows

**Status:** Initial wireframes and user flows completed.

**Work completed:**
- Created preliminary wireframes in Excalidraw.
- Designed the dashboard and sidebar navigation.
- Mapped the process of creating and saving a research entry.
- Mapped the process of finding and reopening existing research.
- Established one shared editor for Questions and Discoveries.
- Documented the intended navigation and interactions in `USER_FLOWS.md`.

**Outcome:**

Established the initial screen layouts and the main paths users will follow through the application. The wireframes provide a reference for frontend implementation.

---

## 3. Repository and Documentation Setup

**Status:** Initial repository and documentation setup completed.

**Work completed:**
- Created the `rabbit-tracks-journal` repository for the rebuild.
- Organized project documentation inside the `docs/` directory.
- Added the initial README, requirements, technical plan, design notes, user flows, and development log.
- Recorded the initial project direction and planned application screens.

**Outcome:**

Established a separate place for the rebuild and its planning material. This section records repository and documentation preparation; it does not mean the application features have been implemented.

---

## 4. Current Development Phase — React Frontend

**Status:** Starting November 20, 2026. Frontend implementation is beginning; application features are not yet marked complete.

**Current approach:**

I'm starting with React, JavaScript, and CSS rather than building a separate plain-JavaScript version and converting it later. I want to understand how the pieces fit together as I build the actual application.

The initial work will focus on:
- Setting up the React development environment.
- Understanding the application entry point and component structure.
- Building the initial application shell.
- Establishing the shared page layout and navigation.
- Applying the first layer of CSS.

**Learning focus:**

I'm using Codecademy courses alongside implementation to strengthen my understanding of HTML, CSS, JavaScript, and React. I'm studying in a deliberate order and applying concepts to Rabbit Tracks rather than jumping between unrelated topics. The sequence is recorded in `LEARNING_PLAN.md`.

I'm also responsible for understanding the CSS I write. The visual direction is Alice in Wonderland-inspired, but I want to create it with approachable styling that I can explain and maintain myself.

---

## 5. Current Milestones and Next Steps

The current target is Demo Day on December 4, 2026.

1. **November 20–22:** set up React and build the initial application shell.
2. **November 23–26:** build the shared layout, navigation, dashboard, and research library.
3. **November 27–29:** implement the shared entry editor and question/discovery workflows.
4. **November 30–December 1:** complete essential functionality and implement the selected data-persistence approach.
5. **December 2–3:** test the application, resolve issues, refine responsive styling, and prepare the demonstration.
6. **December 4:** Demo Day.

These are planned milestones. I'll update this section as work is completed and adjust the sequence when necessary.

---

## 6. Ongoing Development Entry Format

For each new development entry, I'll record:

**Date:**

**What I worked on:**
- What I implemented or changed.

**What I learned:**
- Concepts I studied and how they connect to the application.

**Problems I ran into:**
- Errors, confusing behavior, or decisions that needed more investigation.

**How I addressed them:**
- What I tested, changed, or learned while resolving the problem.

**What's next:**
- The next concrete task.

---

The purpose of this log is to maintain an accurate record of the work behind Rabbit Tracks, including the learning process—not simply track a list of planned features.