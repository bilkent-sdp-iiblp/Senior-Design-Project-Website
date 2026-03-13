---
layout: default
title: Home
---

<div class="hero-section">
  <h1 class="hero-title">Ubien: Immersive Inquiry-Based Learning Platform</h1>
  <p class="hero-subtitle">Transforming Education Through AI-Powered Interactive Learning</p>
</div>

## Project Overview

Inquiry-based learning empowers students to explore subjects by answering guiding questions, enabling them to understand material as if they had discovered it themselves. However, traditional Inquiry-Based Learning (IBL) textbooks require an instructor to guide students through the learning process, making it challenging to implement in online learning environments.

Our platform bridges this gap by leveraging Large Language Models (LLMs) to create an intelligent, self-guided learning experience. Students can upload IBL textbooks, and our system automatically generates an interactive online course with an AI instructor that guides learners through a series of thought-provoking questions.

## Key Features

### AI-Powered Instruction
Our LLM-based instructor adapts to each student's learning pace and style, providing personalized guidance through the inquiry process.

### Animated Instructor Avatars
Experience learning with expressive animated instructors featuring:
- **Synchronized synthesized speech** for natural communication
- **Facial expressions and gestures** that convey personality
- **Dynamic posture and gaze** for engaging interactions

### Interactive Learning Experience
Students learn through discovery, guided by an AI instructor that makes the experience feel as immersive as learning from a real teacher in a classroom setting.

## Technology Stack

Our platform combines a modern backend with AI and web technologies:
- **Go** for the core backend services and orchestration
- **PostgreSQL 16** as the primary relational database
- **Docker** for containerized deployment and reproducible environments
- **ChatGPT API** for conversational guidance and question answering
- **Large Language Models** for intelligent instruction and inquiry generation
- **Character Animation Systems** and **speech synthesis** for immersive interactions
- **Web-based frontend** for accessible delivery in the browser

---

<div class="cta-section">
  <p>Learn more about our team and project progress on the <a href="{{ site.baseurl }}/about/">About Us</a> page.</p>
</div>

## Latest Updates

<ul class="post-list">
  {% for post in site.posts limit:3 %}
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

