---
layout: home
title: Welcome to My Portfolio
---

<style>
.page-content {
  text-align: center;
}

page-content > h1 {
  text-align: center;
}

.portfolio-intro {
  background: linear-gradient(135deg, rgba(100, 200, 255, 0.1) 0%, rgba(50, 150, 255, 0.05) 100%);
  border-left: 4px solid #00a8ff;
  padding: 30px;
  margin: 30px auto;
  border-radius: 8px;
  line-height: 1.8;
  max-width: 900px;
}

.project-card {
  background: linear-gradient(135deg, rgba(30, 30, 40, 1) 0%, rgba(40, 40, 55, 1) 100%);
  border: 1px solid rgba(100, 200, 255, 0.2);
  padding: 30px;
  margin: 30px auto;
  border-radius: 10px;
  transition: all 0.3s ease;
  box-shadow: 0 4px 15px rgba(0, 0, 0, 0.2);
  max-width: 900px;
}

.project-card:hover {
  transform: translateY(-5px);
  border-color: rgba(100, 200, 255, 0.5);
  box-shadow: 0 8px 25px rgba(0, 168, 255, 0.2);
}

.project-title {
  font-size: 1.6em;
  font-weight: 700;
  color: #00d4ff;
  margin-bottom: 15px;
  margin-top: 0;
}

.meta-badge {
  display: inline-block;
  background: rgba(0, 212, 255, 0.1);
  border: 1px solid rgba(0, 212, 255, 0.3);
  padding: 6px 12px;
  border-radius: 20px;
  color: #00d4ff;
  font-weight: 500;
  margin-right: 10px;
  margin-bottom: 15px;
  font-size: 0.9em;
}

.project-description {
  color: #e0e0e0;
  line-height: 1.7;
  margin: 15px 0;
  text-align: left;
}

.features-list {
  color: #e0e0e0;
  margin: 15px 0;
  padding-left: 20px;
  text-align: left;
}

.features-list li {
  margin: 8px 0;
  line-height: 1.6;
}

.tech-tag {
  display: inline-block;
  background: rgba(100, 200, 255, 0.15);
  border: 1px solid rgba(100, 200, 255, 0.3);
  padding: 6px 12px;
  border-radius: 4px;
  font-size: 0.85em;
  color: #64c8ff;
  margin-right: 8px;
  margin-bottom: 8px;
}

.cta-button {
  display: inline-block;
  background: linear-gradient(135deg, #00a8ff 0%, #0087cc 100%);
  color: white;
  padding: 12px 24px;
  border-radius: 6px;
  text-decoration: none;
  margin-top: 15px;
  margin-right: 10px;
  transition: all 0.3s ease;
  font-weight: 600;
  border: 1px solid rgba(0, 212, 255, 0.3);
}

.cta-button:hover {
  transform: scale(1.05);
  box-shadow: 0 6px 20px rgba(0, 168, 255, 0.4);
  background: linear-gradient(135deg, #00c8ff 0%, #00a8ff 100%);
}

.section-title {
  font-size: 2.2em;
  font-weight: 700;
  color: #ffffff;
  margin-top: 50px;
  margin-bottom: 10px;
  border-bottom: 3px solid #00a8ff;
  padding-bottom: 10px;
  display: inline-block;
  margin-left: 0;
}

.nav-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(240px, 1fr));
  gap: 20px;
  margin: 30px auto;
  max-width: 1000px;
}

.nav-item {
  background: rgba(50, 50, 70, 0.8);
  border: 1px solid rgba(100, 200, 255, 0.2);
  padding: 20px;
  border-radius: 8px;
  transition: all 0.3s ease;
  line-height: 1.6;
}

.nav-item:hover {
  background: rgba(100, 100, 120, 0.8);
  border-color: rgba(100, 200, 255, 0.5);
}

.nav-item strong {
  color: #00d4ff;
  display: block;
  margin-bottom: 10px;
}

.text-center {
  text-align: center;
  color: #00a8ff;
  font-weight: 600;
  margin-top: 50px;
  font-size: 1.1em;
}

hr {
  border: none;
  height: 2px;
  background: linear-gradient(90deg, transparent, rgba(100, 200, 255, 0.3), transparent);
  margin: 40px 0;
}
</style>

<div class="portfolio-intro" style="text-align: center; border-left: none; border-top: 3px solid #00a8ff; border-bottom: 3px solid #00a8ff;">

## Welcome to My Portfolio

Hey there! I'm a software engineer with **10+ years of backend development experience**. I specialize in building REST APIs, cloud solutions, and AI applications. This portfolio showcases my GitHub projects.

**Click on any project below** to explore the repository and see the full code and documentation.

</div>

---

## 🚀 My Projects

Here are my featured projects:

<div class="project-card">
<h3 class="project-title">Digital Gym Buddy</h3>

<span class="meta-badge">🐍 Python</span>
<span class="meta-badge">⚡ Active</span>
<span class="meta-badge">🤖 AI-Powered</span>

<p class="project-description">
An intelligent Telegram bot that serves as an automated workout tracker, powered by OpenAI and Google APIs. The bot listens to voice and text messages, extracts workout data using GPT, and logs it to Google Sheets for tracking and analysis.
</p>

**Key Features:**

<ul class="features-list">
<li>Voice-to-text conversion using Whisper API</li>
<li>Intelligent data extraction using GPT</li>
<li>Google Sheets integration for logging</li>
<li>Automatic streak calculation</li>
</ul>

**Technologies:**

<span class="tech-tag">Telegram Bot API</span>
<span class="tech-tag">OpenAI</span>
<span class="tech-tag">Google Sheets</span>
<span class="tech-tag">Python</span>
<span class="tech-tag">GSPread</span>

<a href="https://github.com/brownpanda667-dotcom/Digital-Gym-Buddy" target="_blank" class="cta-button">👉 View on GitHub</a>

</div>

<div class="project-card">
<h3 class="project-title">My Portfolio Blog</h3>

<span class="meta-badge">📝 Jekyll</span>
<span class="meta-badge">✅ Active</span>
<span class="meta-badge">🌐 GitHub Pages</span>

<p class="project-description">
A personal portfolio blog website built with Jekyll and hosted on GitHub Pages. Designed for sharing technical articles, tutorials, and project documentation.
</p>

**Key Features:**

<ul class="features-list">
<li>Fully responsive design</li>
<li>Clean, elegant interface</li>
<li>Markdown-based content</li>
<li>Fast static site generation</li>
<li>Version controlled on GitHub</li>
<li>Automatic CI/CD deployment</li>
</ul>

**Technologies:**

<span class="tech-tag">Jekyll</span>
<span class="tech-tag">GitHub Pages</span>
<span class="tech-tag">Markdown</span>
<span class="tech-tag">HTML/CSS</span>

<a href="https://github.com/brownpanda667-dotcom/blog" target="_blank" class="cta-button">👉 View on GitHub</a>

</div>

---

## 📚 How to Navigate

<div class="nav-grid">

<div class="nav-item">
<strong>🔗 Explore Projects</strong>

Click on any project link above to open the repository in a new tab. Browse the code and read the README for details.
</div>

<div class="nav-item">
<strong>📖 Read Blog Posts</strong>

Scroll down to find my latest blog posts, tutorials, and technical articles.
</div>

<div class="nav-item">
<strong>💻 View the Code</strong>

All repositories are open source. Check out the implementation details and best practices.
</div>

<div class="nav-item">
<strong>🤝 Let's Connect</strong>

Interested in collaborating? Check out my GitHub profile for more details.
</div>

</div>

<p class="text-center">
✨ Thanks for visiting! Happy exploring! ✨
</p>
