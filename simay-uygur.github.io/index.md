---
layout: home
title: Home
---

<style>
/* Enhanced Professional Styling */
* { box-sizing: border-box !important; }
body { 
  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif !important; 
  line-height: 1.7 !important; 
  color: #2c3e50 !important;
  background-color: #ffffff !important;
}
main h1, main h2, main h3, .page-content h1, .page-content h2, .page-content h3, .wrapper h1, .wrapper h2, .wrapper h3 { 
  font-weight: 600 !important; 
  color: #1a1a1a !important; 
  margin-top: 2em !important; 
}
main h1, .page-content h1, .wrapper h1 { 
  font-size: 2.5em !important; 
  border-bottom: 3px solid #667eea !important; 
  padding-bottom: 0.3em !important; 
  margin-bottom: 1em !important;
}
main h2, .page-content h2, .wrapper h2 { 
  font-size: 2em !important; 
  border-bottom: 2px solid #e0e0e0 !important; 
  padding-bottom: 0.3em !important; 
  margin-top: 2.5em !important; 
  color: #2c3e50 !important;
}
main h3, .page-content h3, .wrapper h3 { 
  font-size: 1.5em !important; 
  color: #34495e !important; 
  margin-top: 2em !important; 
  font-weight: 600 !important;
}
.hero-section { 
  text-align: center !important; 
  padding: 4em 2em !important; 
  margin: 2em 0 3em 0 !important; 
  background: linear-gradient(135deg, #667eea 0%, #764ba2 100%) !important; 
  color: white !important; 
  border-radius: 12px !important; 
  box-shadow: 0 10px 30px rgba(102, 126, 234, 0.3) !important; 
}
.hero-section h1, .hero-section .hero-title { 
  font-size: 2.8em !important; 
  font-weight: 700 !important; 
  margin-bottom: 0.5em !important; 
  border: none !important; 
  color: white !important; 
  padding-bottom: 0 !important; 
  text-shadow: 0 2px 4px rgba(0,0,0,0.1) !important;
}
.hero-section p, .hero-section .hero-subtitle { 
  font-size: 1.3em !important; 
  font-weight: 300 !important; 
  opacity: 0.95 !important; 
  margin: 0 !important; 
  color: white !important; 
}
.cta-section { 
  background: linear-gradient(to right, #f8f9fa 0%, #ffffff 100%) !important; 
  padding: 2em !important; 
  border-radius: 8px !important; 
  margin: 3em 0 !important; 
  border-left: 5px solid #667eea !important; 
  text-align: center !important; 
  box-shadow: 0 2px 8px rgba(0,0,0,0.05) !important;
}
.cta-section a { 
  font-weight: 600 !important; 
  color: #667eea !important; 
  text-decoration: none !important;
  transition: all 0.3s ease !important;
}
.cta-section a:hover { 
  color: #5568d3 !important; 
  text-decoration: underline !important;
}
main a, .page-content a, .wrapper a { 
  color: #667eea !important; 
  transition: all 0.2s ease !important; 
  text-decoration: none !important;
}
main a:hover, .page-content a:hover, .wrapper a:hover { 
  color: #5568d3 !important; 
  text-decoration: underline !important;
}
main p, .page-content p, .wrapper p { 
  margin-bottom: 1.3em !important; 
  line-height: 1.8 !important; 
  color: #4a4a4a !important;
}
.wrapper { 
  max-width: 1200px !important; 
  margin: 0 auto !important; 
  padding: 0 2em !important;
}
/* Post List Styling */
.post-list { 
  list-style: none !important; 
  padding: 0 !important; 
  margin: 2em 0 !important;
}
.post-list li { 
  background: #ffffff !important; 
  border: 1px solid #e0e0e0 !important; 
  border-radius: 8px !important; 
  padding: 1.5em !important; 
  margin-bottom: 1.5em !important; 
  transition: all 0.3s ease !important;
  box-shadow: 0 2px 4px rgba(0,0,0,0.05) !important;
}
.post-list li:hover { 
  box-shadow: 0 4px 12px rgba(102, 126, 234, 0.15) !important; 
  transform: translateY(-2px) !important;
  border-color: #667eea !important;
}
.post-list h3 { 
  margin-top: 0 !important; 
  margin-bottom: 0.5em !important;
}
.post-list .post-meta { 
  color: #888 !important; 
  font-size: 0.9em !important; 
  margin-bottom: 0.5em !important;
}
.post-list a { 
  color: #2c3e50 !important; 
  font-weight: 600 !important;
}
.post-list a:hover { 
  color: #667eea !important;
}
/* Feature Cards */
ul li { 
  margin-bottom: 0.8em !important; 
  line-height: 1.6 !important;
  padding-left: 0.5em !important;
}
strong { 
  color: #2c3e50 !important; 
  font-weight: 600 !important;
}
/* Page Heading */
.page-heading { 
  display: none !important;
}
.post-list-heading {
  display: none !important;
}
.rss-subscribe {
  display: none !important;
}
/* Responsive */
@media (max-width: 768px) {
  .hero-section { padding: 2.5em 1.5em !important; }
  .hero-section h1, .hero-section .hero-title { font-size: 2em !important; }
  .hero-section p, .hero-section .hero-subtitle { font-size: 1.1em !important; }
  main h1, .page-content h1, .wrapper h1 { font-size: 2em !important; }
  main h2, .page-content h2, .wrapper h2 { font-size: 1.6em !important; }
  .wrapper { padding: 0 1em !important; }
}
</style>

<div class="hero-section">
  <h1 class="hero-title">Ubien: Immersive Inquiry-Based Learning Platform</h1>
  <p class="hero-subtitle">Transforming Education Through AI-Powered Interactive Learning</p>
</div>

## Project Overview

Inquiry-based learning empowers students to explore subjects by answering guiding questions, enabling them to understand material as if they had discovered it themselves. However, traditional Inquiry-Based Learning (IBL) textbooks require an instructor to guide students through the learning process, making it challenging to implement in online learning environments.

Our platform bridges this gap by leveraging Large Language Models (LLMs) to create an intelligent, self-guided learning experience. Students can upload IBL textbooks, and our system automatically generates an interactive online course with an AI instructor that guides learners through a series of thought-provoking questions.

## Key Features

### 🤖 AI-Powered Instruction
Our LLM-based instructor adapts to each student's learning pace and style, providing personalized guidance through the inquiry process.

### 🎭 Animated Instructor Avatars
Experience learning with expressive animated instructors featuring:
- **Synchronized synthesized speech** for natural communication
- **Facial expressions and gestures** that convey personality
- **Dynamic posture and gaze** for engaging interactions

### 📚 Interactive Learning Experience
Students learn through discovery, guided by an AI instructor that makes the experience feel as immersive as learning from a real teacher in a classroom setting.

## Technology Stack

Our platform combines cutting-edge technologies:
- **Large Language Models** for intelligent instruction
- **Character Animation Systems** for immersive interactions
- **Speech Synthesis** for natural communication
- **Web-based Platform** for accessibility

---

<div class="cta-section">
  <p>Learn more about our team and project progress on the <a href="{{ site.baseurl }}/about/">About Us</a> page.</p>
</div>

## Latest Updates



