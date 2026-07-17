# DSA// Tracker

A single-file, offline-first web app for tracking daily DSA (Data Structures & Algorithms) practice — sorted by topic, with streaks, notes, and a "Problem of the Day" hero.

No build step, no backend, no dependencies to install. Open the HTML file in a browser and it works.

## Features

- **Topic-wise sorted problems** — 137 problems across 11 topics (Arrays, Linked List, Greedy Algorithm, Recursion, Backtracking, Binary Search, Stack & Queue, String, Binary Tree, Graph, Dynamic Programming), grouped into collapsible sections.
- **Problem of the Day** — automatically shows the next unsolved problem at the top of the page, with a one-click "Mark solved" button.
- **Search & filter** — search problems by name, and filter by status (all / solved / unsolved).
- **Solved checkbox** — mark any problem solved or unsolved; the date it was solved is recorded automatically.
- **Streak tracking** — counts consecutive days on which at least one problem was solved.
- **Activity heatmap** — a 14-week, GitHub-style calendar showing how many problems were solved on each day.
- **Per-problem notes** — add free-form notes to any problem (approach, edge cases, complexity) to revisit later. Notes autosave as you type.
- **Progress bars** — overall progress and per-topic progress at a glance.

## Tech Stack

- Plain **HTML, CSS, and JavaScript** — no frameworks, no build tools.
- **`localStorage`** for persistence — all progress, notes, and streak data stay in your browser on your device. Nothing is sent anywhere.
- Problem data (topic, name, link) is embedded directly in the file, sourced from `dsa_preparation.json`.

## Getting Started

1. Download `dsa-tracker.html`.
2. Open it in any modern browser (Chrome, Firefox, Edge, Safari) — double-click the file, no server required.
3. Start solving. Check off problems as you go, and your streak and heatmap will update automatically.

> **Note:** Progress is stored per browser profile on a single device. Clearing browser data/cache will erase it. There is currently no export/import or sync across devices.

## Project Structure

```
dsa-tracker.html   → the entire app (markup, styles, and logic in one file)
```

## Roadmap Ideas

- Export/import progress as JSON (for backup or moving between devices)
- Difficulty tags and a "revise again" flag for spaced repetition
- Dark/light theme toggle
- Weekly/monthly solve-count summary

## Developer

**Payal Rakshit**

## License

Personal project — free to use and modify for your own practice.
