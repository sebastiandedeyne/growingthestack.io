---
title: Event Sourcing made Simple
link: https://kickstarter.engineering/event-sourcing-made-simple-4a2625113224
date: 2018-06-12
---

Event sourcing is a hot topic (well, it's heating up). Kickstarter's engineering team decided to dive in and build their next product with a home-grown event sourced approach.

Author Philippe Creux compares event sourcing to Git:

> Most software developers use a tool to keep track of code history. Git is a fantastic example that’s used widely across the industry. Type git log and you can see all the changes made to a codebase. Who made the change, when it happened, what the change was, why the change was made and how the change was performed. Git is also a time machine, that allows you to go back in time and see what the code looked like back then. You can also replay history and play what-if scenarios: go back in time, checkout a new branch, commit a change, and replay all the events commits that happened after that.

A more formal definition by Martin Fowler is:

> All changes to an application state are stored as a sequence of events

The article serves as a hands-on guide to build a pragmatic event sourced system. It's an interesting topic for both back- and frontend developers. If you're a frontend developer, you might already be applying event sourcing ideas with state management libraries like Redux.
