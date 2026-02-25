---
layout: default
title: Marrubio Portfolio
permalink: /
---

<style>
:root {
  --main-color: #0b4a6f;
  --accent: #f29f05;
  --bg: #f8fbff;
  --panel: #ffffff;
  font-family: 'Poppins', 'Segoe UI', sans-serif;
}
body {
  background: var(--bg);
  color: #111;
}
.hero {
  padding: 4rem 0 3rem;
  background: linear-gradient(135deg, rgba(11, 74, 111, 0.9), rgba(2, 32, 69, 0.95));
  color: white;
  border-radius: 1.5rem;
  margin-bottom: 3rem;
}
.hero h1 {
  margin: 0 0 0.5rem;
  font-size: clamp(2.5rem, 4vw, 3.5rem);
}
.hero h2 {
  color: #ffffff;
  margin: 0 0 0.5rem;
  font-size: clamp(2.25rem, 3.5vw, 3rem);
}
.hero p {
  max-width: 640px;
  line-height: 1.7;
}
.btn-primary {
  display: inline-flex;
  align-items: center;
  gap: 0.75rem;
  background: var(--accent);
  color: #021b2a;
  padding: 0.9rem 1.8rem;
  border-radius: 999px;
  text-transform: uppercase;
  font-weight: 700;
  letter-spacing: 0.05em;
  border: none;
}
.section-card {
  background: var(--panel);
  border-radius: 1rem;
  padding: 1.5rem;
  box-shadow: 0 20px 45px rgba(2, 32, 69, 0.12);
  margin-bottom: 1rem;
}
.grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(240px, 1fr));
  gap: 1.25rem;
}
.projects-preview h3 {
  margin-top: 0;
}
.cta {
  margin-top: 3rem;
  padding: 2rem;
  border-radius: 1.25rem;
  background: rgba(2, 32, 69, 0.07);
}
</style>

<div class="hero">
  <div class="section-card" style="background:none; box-shadow:none; padding:2rem;">
    <p style="text-transform: uppercase; letter-spacing: 0.6em; font-size: 0.8rem; color: rgba(255,255,255,0.9);">
      Solution Architect · Sopra Steria Valencia</p>
    <h2>I design modern cloud-native systems with intent and clarity.</h2>
    <p>This portfolio highlights resilient architectures, infrastructure craftsmanship, and DevOps practices that keep fast-moving teams in sync. Navigate via the menu or bold call-to-actions.</p>
    <a class="btn-primary" href="/projects/">View featured projects</a>
  </div>
</div>

<section>
  <div class="section-card">
    <h2>Core focus areas</h2>
    <p>I deliver cloud-ready platforms with a mix of solution architecture, infrastructure automation, and DevOps enablement. Every engagement mixes reliability, observability, and human-centered collaboration.</p>
    <div class="grid">
      <div>
        <h3>Modern architectures</h3>
        <p>Microservices, event-driven solutions, and hybrid pipelines that serve enterprise and team-level goals.</p>
      </div>
      <div>
        <h3>Infrastructure</h3>
        <p>Azure and AWS landing zones, policy-as-code, and secure networking for production-ready environments.</p>
      </div>
      <div>
        <h3>DevOps enablement</h3>
        <p>Automated pipelines, rehearsal environments, and observability practices that empower delivery teams.</p>
      </div>
    </div>
  </div>
</section>


<section>
  <div class="section-card">
    <h2>Beyond work</h2>
    <p>Technology is a lifelong obsession—whether I am architecting distributed systems, collecting PC games that surprise me, or hiking in the mountains to keep perspectives fresh.</p>
    <ul>
      <li>PC gaming for design research and quick reflex training.</li>
      <li>Nature hikes that recharge creativity and curiosity.</li>
      <li>Exploring emerging tools in cloud, automation, and observability.</li>
    </ul>
  </div>
</section>

<section class="cta">
  <h2>Let's talk</h2>
  <p>Share your next challenge or opportunity. We can begin with a short video call to define priorities and sketch a plan of action.</p>
  <a class="btn-primary" href="/contact/">Reach out</a>
</section>
