---
layout: post
title: "IBL PDFs to Courses + ChatGPT-Powered Q&A"
date: 2026-03-04
---

One of the core goals of **Ubien** is to make existing Inquiry-Based Learning (IBL) material usable in a modern, AI-supported learning environment — without rewriting everything from scratch.

In this post we highlight two key capabilities in the platform:

## IBL PDFs → Structured Online Courses

Many IBL textbooks already come as **PDFs with inherent bookmarks and structure** (chapters, sections, problems, etc.). Ubien uses that existing structure as a starting point for creating an online course:

- **Parse IBL PDFs** and read their bookmarks and headings
- **Extract inquiry questions and activities** from the material
- **Map sections to course modules and steps**, preserving the original learning flow
- **Generate a navigable course** that mirrors the textbook, while keeping the material editable

The idea is that people can upload an IBL PDF they already use and get a structured, browser-based course instead of manually copying and pasting content into a new LMS.

## ChatGPT API for Question Answering

Once a course is generated, learners may need clarification or extra guidance on individual steps. To support this, Ubien integrates with the **ChatGPT API**:

- Learners can **answer questions directly on each activity or concept**
- The system sends context (e.g., the current question, surrounding text, and learner progress) to the ChatGPT API
- The AI responds with **targeted explanations, hints, or follow-up questions** that stay aligned with the IBL philosophy (guiding instead of just giving final answers)

Students can open an extracted course question and receive conversational support that helps them keep working through the problem.

## What’s Next?

Related updates cover:

- How we **align AI responses with the intent of the original IBL material**
- Our approach to **tracking learner progress and misconceptions**
- The technical details of our **PDF parsing pipeline and ChatGPT integration**

If you’re interested in IBL, AI tutoring, or would like to try the platform with your own materials, stay tuned for more updates.
