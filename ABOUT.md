# Leadership Diary — Josh Yule
**MDes, Leadership by Design — CCA, Summer 2026**

Live: https://curious-dango-f4ca9b.netlify.app/leadership-diary.html

---

## What this is

A custom-built digital diary for tracking leadership growth across the LBD program. Built from scratch as a single HTML file — no frameworks, no backend — and deployed publicly so it can be graded and shared.

The diary is an extension of my personal design system. Same typography, same color palette, same interaction style as my portfolio. The goal was to make something that felt like mine, not a form or a template.

---

## What's inside

**Baseline Assessments**
Self-scores across three frameworks: SCARF (neurological drivers), VIA Strengths (character), and Superpowers (leadership style). The through-line I keep noticing is autonomy — it shows up across all three.

**Clifton Strengths**
My top 5: Input, Woo, Strategic, Individualization, Ideation. These aren't abstract labels — they show up constantly in how I work and how I lead.

**Journey Timeline**
A visual record of the program's arc — sessions, offsites, guest speakers — plotted as a timeline I can reflect on at the end.

**Weekly Entries**
The core of the diary. Each entry captures a key insight, a goal, something I'll do differently, a mood rating, and tags. Entries are stored locally in the browser and can be exported as JSON for backup.

**Mural Board**
A visual upload board for images, artifacts, and documentation from the program. Drag and drop to add, click to view full size, caption each image.

---

## How it was built

- Plain HTML, CSS, and JavaScript — no frameworks, no build step
- Data lives in the browser's `localStorage` — nothing is sent to a server
- Published entries are baked into the HTML so any visitor sees the same content
- Deployed to Netlify via CLI
- Source on GitHub: https://github.com/yulebesorry/style-guide

---

## Program context

This diary is part of **Module 2 — Self Leadership** in the MDes Leadership by Design program at CCA. The program runs June–July 2026 and includes guest speakers, offsites, and workshops focused on leadership as a design practice.
