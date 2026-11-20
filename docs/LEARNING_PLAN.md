# Rabbit Tracks — Learning Plan

## Purpose

I'm using Codecademy to strengthen the skills I'm applying while building Rabbit Tracks. I don't want to jump between unrelated courses or learn React without understanding the web technologies it builds on.

This sequence moves from page structure, to styling, to JavaScript, and then React. The courses are listed in a recommended order so I can see how each topic connects to the next.

**Important:** I do not need to finish every course before I write application code. I'll study alongside development, focusing on the lessons that support the feature I'm currently building. I'll apply each concept in Rabbit Tracks and return to a course when I need more practice.

Codecademy's catalog and course availability can change. The courses below were listed as free when this plan was prepared in November 2026. Some additional features, such as certificates or certain practice tools, may require a paid plan.

## Recommended Course Order

### 1. Learn HTML — 7 hours

[Open Learn HTML](https://www.codecademy.com/learn/learn-html)

**Why first:** HTML provides the structure and meaning of a web page. React uses JSX to describe interface structure, so understanding elements, forms, and semantic markup makes JSX easier to understand.

**Focus on:**
- Elements and document structure.
- Headings, paragraphs, links, and images.
- Semantic HTML.
- Forms and input elements.

**Rabbit Tracks connection:** Understand the structure of the dashboard, navigation, research cards, and entry editor.

### 2. Learn CSS — 6 hours

[Open Learn CSS](https://www.codecademy.com/learn/learn-css)

**Why second:** CSS controls how the HTML structure looks. Learning it before adding lots of React components will make it easier to understand the difference between the interface structure and its presentation. Codecademy recommends completing Learn HTML first.

**Focus on:**
- CSS syntax and selectors.
- Classes and applying styles.
- The cascade and specificity.
- Colors, typography, backgrounds, and spacing.
- Visual rules for organizing interface elements.

**Rabbit Tracks connection:** Build the Alice in Wonderland-inspired visual identity using styles I understand and can maintain.

### 3. Learn CSS: Box Model and Layout — 2 hours

[Open Learn CSS: Box Model and Layout](https://www.codecademy.com/learn/learn-css-box-model-and-layout)

**Why here:** Before arranging a full application, I need to understand how much space elements occupy and how they are positioned.

**Focus on:**
- Content, padding, borders, and margins.
- Element sizing.
- Display and positioning.
- How layout choices affect surrounding elements.

**Rabbit Tracks connection:** Size the sidebar, dashboard sections, research cards, forms, and content area.

### 4. Learn CSS: Flexbox and Grid — 4 hours

[Open Learn CSS: Flexbox and Grid](https://www.codecademy.com/catalog/language/html-css)

**Why here:** Flexbox and Grid solve different layout problems. They help arrange interface elements without relying on arbitrary spacing or positioning.

**Focus on:**
- Flexbox for arranging items in a row or column.
- Alignment, spacing, and wrapping.
- Grid for two-dimensional layouts.
- Choosing the layout tool that fits the problem.

**Rabbit Tracks connection:** Arrange the application shell, sidebar, dashboard sections, and responsive research-library layout.

### 5. Learn JavaScript: Fundamentals — 4 hours

[Open Learn JavaScript: Fundamentals](https://www.codecademy.com/learn/learn-javascript-fundamentals)

**Why here:** This is a shorter introduction to JavaScript behavior and control flow before moving into the larger JavaScript course.

**Focus on:**
- Basic JavaScript syntax.
- Values and expressions.
- Conditional logic.
- Repetition and program flow.

**Rabbit Tracks connection:** Understand how the application can respond to user actions and make decisions based on the data it receives.

### 6. Learn JavaScript — 15 hours

[Open Learn JavaScript](https://www.codecademy.com/learn/introduction-to-javascript)

**Why sixth:** This course develops the JavaScript foundation React relies on. It covers variables, conditionals, functions, scope, arrays, and loops. The shorter Fundamentals course is a warm-up; this is the more complete core course.

**Focus on:**
- Variables and data types.
- Conditionals and loops.
- Functions.
- Arrays and objects.
- Scope and basic program structure.
- Working with data and functions.

**Rabbit Tracks connection:** Understand how research entries are represented, how user actions change data, and how lists of entries can be processed.

### 7. Learn React — 13 hours

[Open Learn React](https://www.codecademy.com/learn/react-101)

**Why last in the core sequence:** React builds on JavaScript and uses JSX to describe interfaces. Codecademy lists Learn HTML and Learn JavaScript as prerequisites for this course.

**Focus on:**
- JSX.
- React components.
- Components interacting through props.
- State and hooks.
- React programming patterns.
- Styling React applications.
- Forms and user input.

**Rabbit Tracks connection:** Build the actual application: reusable interface components, navigation, research-entry forms, lists, and interactive screens.

## How the Topics Connect

The relationship between these subjects is important:

1. **HTML describes the content and structure** of a page.
2. **CSS controls how that structure is presented** and arranged.
3. **JavaScript adds behavior and works with data.**
4. **React uses JavaScript and JSX to build interfaces from components**, manage changing data, and update what users see.

React does not replace the need to understand HTML, CSS, or JavaScript. It gives us a way to organize and manage an interactive interface.

## Later Study — Only When the Project Needs a Backend

I won't start backend courses just to collect more topics. Once the frontend workflows and data requirements are clear, I can study the tools needed for the persistence approach we choose.

Possible next courses include:

- **Learn Node.js: Fundamentals** — an introduction to the JavaScript runtime used for server-side development. [Open the course](https://www.codecademy.com/learn/learn-nodejs-fundamentals).
- **Learn Node.js** — a broader introduction to Node.js and backend application concepts. [Open the course](https://www.codecademy.com/learn/learn-node-js).
- **Learn MongoDB** — an introduction to a document database and basic CRUD operations. [Open the course](https://www.codecademy.com/learn/learn-mongodb).

These are future options, not confirmed technology choices for Rabbit Tracks. I'll first decide what the application needs and then follow the relevant learning path.

## Study Rules

To keep my learning connected to the project:

- Follow the course order instead of switching between unrelated topics.
- Review concepts I already know rather than repeating every lesson automatically.
- Don't rush through a course just to mark it complete.
- After learning a concept, identify where it appears in Rabbit Tracks.
- Practice the concept in a small example before using it in a larger feature.
- Write my own code and be able to explain it.
- Keep notes on confusing concepts, errors, and what helped me understand them.
- Don't add a library or tool just because a course mentions it; first understand whether the project needs it.

## Progress Tracking

I'll update this section as I study.

| Order | Course | Status |
|---|---|---|
| 1 | Learn HTML | Not started |
| 2 | Learn CSS | Not started |
| 3 | Learn CSS: Box Model and Layout | Not started |
| 4 | Learn CSS: Flexbox and Grid | Not started |
| 5 | Learn JavaScript: Fundamentals | Not started |
| 6 | Learn JavaScript | Not started |
| 7 | Learn React | Not started |

Course completion is not the only measure of progress. The goal is to understand the material and apply it confidently while building Rabbit Tracks.