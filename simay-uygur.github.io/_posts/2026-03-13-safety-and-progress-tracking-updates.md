---
layout: post
title: "Safer Course Creation and Rich Progress Tracking"
date: 2026-03-13
---

Today we rolled out two important improvements to Ubien: **safer course creation** and **finer-grained progress tracking** for learners.

## Safer Course Creation

When converting IBL PDFs into interactive courses, things can occasionally go wrong (e.g., malformed PDFs, missing structure, or intermittent service issues). To make this experience more robust:

- If course creation fails, we now **automatically retry** the process instead of immediately giving up.  
- Any **failed or partial courses are cleaned up**, so you do not end up with broken entries in the course list.  

This keeps the system tidy and reduces confusion for instructors and students when something goes wrong in the background.

## Detailed Progress Tracking per Slide and Question

We also improved how Ubien tracks and displays learner progress within a course:

- Each **slide, step, and question** in a course is now tracked as **done / not done**.  
- Ubien computes an overall **progress percentage** for the course based on these items.  
- Learners can **see their progress** directly in the UI, so they know how far they have come and what remains to be completed.  

This makes it easier to:

- Resume a session exactly where you left off  
- Get a clear sense of completion for long IBL sequences  
- Identify which questions or sections still need attention  

We will continue iterating on this, including visual progress indicators and summaries for instructors in future updates.

