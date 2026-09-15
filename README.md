# AWS Module 03 — Study Checklist

An interactive, self-saving checklist for working through AWS Module 3: Networking, Security, Database, Developer Tools, and Management & Governance.

## What it is

A single-page HTML app that turns the module syllabus into a trackable study plan. Every topic is broken into three actions — **Read**, **Practical**, and **Memorize** — so you're not just ticking "done," you're tracking what stage of learning you're actually at.

## Files

| File | Description |
|---|---|
| `aws-module3-checklist.html` | The app. Open it in any browser — no install, no server needed. |
| `README.md` | This file. |

## Features

- **17 topics, 51 checks** across 5 categories: Networking & Content Delivery, Security Identity & Compliance, Database, Developer Tools, and Management & Governance.
- **Three-part tracking per topic** — Read / Practical / Memorize — each independently checkable.
- **Autosave** — every checkbox toggle and every keystroke in Field Notes saves automatically (debounced, ~500ms after you stop typing). A "saved HH:MM:SS" indicator in the sidebar confirms it stuck.
- **Progress ring + per-category breakdown** in the sidebar, so you always know how far through each section you are.
- **Field Notes panel** — a free-form markdown scratchpad at the bottom for your own gotchas and exam traps. Supports `**bold**`, `*italic*`, `` `code` ``, and `- bullet` lists, with an Edit/Preview toggle.
- **Reset button** — clears all progress and notes if you want to start over (asks for confirmation first).
- **Persists across sessions** — your state is stored server-side and tied to your account, so it's still there next time you open the file, even in a new browser tab or after closing the app.

## How to use it

1. Open `aws-module3-checklist.html` in a browser.
2. Work through each category top to bottom, or jump to a section using the sidebar nav.
3. Check off Read / Practical / Memorize as you complete each stage for a topic.
4. Jot down anything worth remembering in Field Notes as you go.
5. Come back anytime — everything picks up exactly where you left it.

## Notes

- Built as a standalone artifact inside Claude — the checklist content (topics, read/practical/memorize descriptions) is hardcoded to Module 3's syllabus, so it won't reflect changes made outside this file.
- Storage is scoped to your account within this environment. If you move the HTML file elsewhere or open it outside Claude, it won't carry your saved progress with it.
