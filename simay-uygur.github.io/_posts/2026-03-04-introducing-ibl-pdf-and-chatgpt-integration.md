---
layout: post
title: "IBL PDFs to Courses + ChatGPT-Powered Q&A"
date: 2026-03-04
---

One of the core goals of **Ubien** is to make existing Inquiry-Based Learning (IBL) material usable in a modern, AI-supported learning environment — without rewriting everything from scratch.

In this post we highlight two key capabilities we're building into the platform:

## IBL PDFs → Structured Online Courses

Many IBL textbooks already come as **PDFs with inherent bookmarks and structure** (chapters, sections, problems, etc.). Ubien uses that existing structure as a starting point to automatically create an online course:

- **Parse IBL PDFs** and read their bookmarks and headings  
- **Extract inquiry questions and activities** from the material  
- **Map sections to course modules and steps**, preserving the original learning flow  
- **Generate a navigable course** that mirrors the textbook, but is now interactive and web-based  

The idea is that instructors can upload an IBL PDF they already use, and quickly get a structured, browser-based course out of it — instead of manually copying and pasting content into a new LMS.

## ChatGPT API for Question Answering

Once the course is generated, learners often need clarification or extra guidance on individual steps. To support this, Ubien integrates with the **ChatGPT API**:

- Learners can **answer questions directly on each activity or concept**  
- The system sends context (e.g., the current question, surrounding text, and learner progress) to the ChatGPT API  
- The AI responds with **targeted explanations, hints, or follow-up questions** that stay aligned with the IBL philosophy (guiding instead of just giving final answers)  

In practice, this means a student can click “Question”, which is an extracted question from the pdf, in the course and immediately get conversational help, rather than waiting for office hours or email replies.

## What’s Next?

Future posts will dive deeper into:

- How we **align AI responses with the intent of the original IBL material**  
- Our approach to **tracking learner progress and misconceptions**  
- The technical details of our **PDF parsing pipeline and ChatGPT integration**  

If you’re interested in IBL, AI tutoring, or would like to try the platform with your own materials, stay tuned for more updates.

