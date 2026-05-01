---
layout: post
title: "Safer Course Creation and Rich Progress Tracking"
date: 2026-03-13
---

This update focuses on two important areas for Ubien: **safer course creation** and **finer-grained progress tracking** for learners.

## Safer Course Creation

When converting IBL PDFs into interactive courses, things can occasionally go wrong, such as malformed PDFs, missing structure, or intermittent service issues. Ubien handles these cases with:

- **Retry behavior** when course creation fails for recoverable reasons
- **Cleanup for failed or partial courses** so broken entries do not remain in the course list

The goal is to keep the system tidy and reduce confusion for users and students when something goes wrong in the background.

## Detailed Progress Tracking per Slide and Question

Ubien tracks and displays learner progress within a course:

- Each **slide, step, and question** can be tracked as **done / not done**.
- Ubien computes an overall **progress percentage** for the course based on these items.
- Learners can **see their progress** directly in the UI, so they know how far they have come and what remains to be completed.

This makes it easier to:

- Resume a session exactly where you left off
- Get a clear sense of completion for long IBL sequences
- Identify which questions or sections still need attention

Progress indicators and summaries help learners follow long IBL sequences more clearly.
