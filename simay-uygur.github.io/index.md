---
layout: default
title: Home
---

<div class="hero-section">
  <p class="hero-kicker">CS 491/492 Senior Design Project</p>
  <h1 class="hero-title">Ubien</h1>
  <p class="hero-subtitle">An AI-supported platform for turning books into engaging inquiry-based courses.</p>
</div>

## Project Overview

Inquiry-Based Learning (IBL) encourages students to work through guiding questions and build understanding through discovery. Ubien brings that learning flow into an online course experience with uploaded books, guided questions, animated avatars, and progress tracking.

Everyone can upload IBL books to generate related online courses. Ubien also supports **regular** books by converting them into IBL-style learning material and creating a related course inside the app.

## Feature Areas

<div class="feature-grid">
  <article class="feature-card">
    <h3>IBL Book Course Generation</h3>
    <p>Upload IBL books and generate related online courses with sections, slides, and questions organized for inquiry-based learning.</p>
  </article>
  <article class="feature-card">
    <h3>Any Book to IBL Course</h3>
    <p>Upload regular books, convert them into IBL-style books, and create related courses directly inside the app.</p>
  </article>
  <article class="feature-card">
    <h3>Animated Avatars and Voice</h3>
    <p>Male and female animated avatars appear on slides and questions, with Amazon Polly text-to-speech making course material more engaging.</p>
  </article>
  <article class="feature-card">
    <h3>Guidance and Progress</h3>
    <p>Guided question support helps learners move through activities, while progress tracking shows completed sections, slides, and questions.</p>
  </article>
</div>

## Why Choose Ubien?

<div class="feature-grid">
  <article class="feature-card">
    <h3>Compared with LMS Platforms</h3>
    <p>Tools like Moodle and Canvas are strong for course management, grading, and administration. Ubien focuses on transforming book content into IBL-style course structure and fixing parsing issues in the same workflow.</p>
  </article>
  <article class="feature-card">
    <h3>Compared with Course Authoring Tools</h3>
    <p>Tools like Articulate Rise are strong for building polished training content. Ubien is optimized for converting source books into inquiry-based slides and questions, then refining structure through split-and-correct editing.</p>
  </article>
  <article class="feature-card">
    <h3>Compared with AI Tutor Tools</h3>
    <p>AI tutors like Khanmigo are great for conversational support. Ubien combines guided help with course generation, slide-level progress tracking, and avatar-led delivery from slide content.</p>
  </article>
  <article class="feature-card">
    <h3>Compared with Course Catalog Platforms</h3>
    <p>Catalog platforms like Coursera are strong for ready-made course access. Ubien is built for people who want to upload their own books, convert them to IBL flow, and control course structure directly.</p>
  </article>
</div>

## Technical Direction

Ubien combines PDF and book processing, AI-assisted course generation, guided question support, avatar presentation, Amazon Polly text-to-speech, and web-based progress tracking.

---

<div class="cta-section">
  <p>Project reports, team information, and reserved document links are available on the <a href="{{ '/about/' | relative_url }}">About and Documents</a> page.</p>
</div>

## Latest Updates

<ul class="post-list">
  {% for post in site.posts limit:5 %}
  <li>
    <h3>
      <a href="{{ post.url | relative_url }}">
        {{ post.title }}
      </a>
    </h3>
    <p class="post-meta">
      {{ post.date | date: "%B %-d, %Y" }}
    </p>
    <p>
      {{ post.excerpt | strip_html | truncate: 160 }}
    </p>
  </li>
  {% endfor %}
</ul>
