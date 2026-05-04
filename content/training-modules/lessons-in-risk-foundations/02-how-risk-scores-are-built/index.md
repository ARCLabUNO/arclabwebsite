---
title: How Risk Scores Are Built
weight: 2
lastmod: 2026-05-01
show_date: false
show_reading_time: false
show_share: false
show_related: false
show_authors: false
---

<style>
.arc-module {
  margin-top: 1.5rem;
}

.arc-module-hero {
  background: linear-gradient(135deg, #111827 0%, #1f3a5f 100%);
  color: #f9fafb;
  padding: 2.25rem;
  border-radius: 14px;
  margin-bottom: 1.5rem;
  box-shadow: 0 8px 24px rgba(0,0,0,0.18);
}

.arc-module-kicker {
  font-size: 0.82rem;
  font-weight: 700;
  letter-spacing: 0.05em;
  text-transform: uppercase;
  color: #cbd5e1;
  margin-bottom: 0.75rem;
}

.arc-module-hero h2 {
  margin: 0 0 0.8rem 0;
  color: #ffffff;
  font-size: 2rem;
  line-height: 1.2;
}

.arc-module-hero p {
  margin: 0;
  color: #e5e7eb;
  font-size: 1.08rem;
  line-height: 1.75;
  max-width: 42rem;
}

.arc-module-thesis {
  margin: 0 0 2rem 0;
  padding: 1rem 1.1rem;
  background: linear-gradient(135deg, rgba(96,165,250,0.16), rgba(59,130,246,0.08));
  border: 1px solid rgba(96,165,250,0.35);
  border-left: 4px solid #60a5fa;
  border-radius: 12px;
  color: #eff6ff;
  box-shadow: 0 6px 18px rgba(0,0,0,0.12);
}

.arc-module-thesis strong {
  display: block;
  margin-bottom: 0.35rem;
  font-size: 0.8rem;
  letter-spacing: 0.05em;
  text-transform: uppercase;
  color: #93c5fd;
}

.arc-module-thesis p {
  margin: 0;
  line-height: 1.7;
  font-size: 1.05rem;
  font-weight: 600;
}

.arc-module-section {
  margin: 1.75rem 0;
  padding: 1.5rem;
  background: #1f2937;
  border-radius: 14px;
  border: 1px solid #374151;
  box-shadow: 0 6px 18px rgba(0,0,0,0.12);
}

.arc-module-section h2 {
  margin: 0 0 0.75rem 0;
  color: #f9fafb;
  font-size: 1.45rem;
}

.arc-module-section p,
.arc-module-section li {
  color: #e5e7eb;
  line-height: 1.75;
  font-size: 1rem;
}

.arc-module-section ul {
  margin: 1rem 0 1rem 1.25rem;
  padding: 0;
}

.arc-module-key {
  margin-top: 1rem;
  padding: 1rem 1.1rem;
  background: #1f3a5f;
  color: #f9fafb;
  border-radius: 12px;
  border-left: 4px solid #60a5fa;
}

/* FIGURE BLOCK */

.arc-module-figures {
  margin: 2rem 0;
  padding: 1.5rem;
  background: #111827;
  border: 1px solid #374151;
  border-radius: 14px;
}

.arc-module-figures-kicker {
  font-size: 0.72rem;
  font-weight: 800;
  letter-spacing: 0.08em;
  text-transform: uppercase;
  color: #93c5fd;
  margin-bottom: 0.5rem;
}

.arc-module-figures h2 {
  margin: 0 0 0.75rem 0;
  color: #f9fafb;
  font-size: 1.45rem;
}

.arc-module-figures p {
  color: #e5e7eb;
  line-height: 1.75;
}

.arc-module-figure-single img {
  width: 100%;
  height: auto;
  border-radius: 12px;
  display: block;
  margin-top: 1rem;
  box-shadow: 0 8px 22px rgba(0,0,0,0.18);
}

/* APPROACHES */

.arc-module-approach {
  margin-top: 1rem;
}

.arc-module-approach:first-of-type {
  margin-top: 0.75rem;
}

/* BOTTOM */

.arc-module-bottom {
  margin-top: 2rem;
  padding: 1.5rem;
  background: linear-gradient(135deg, #111827 0%, #1e293b 100%);
  color: #f9fafb;
  border-radius: 14px;
  box-shadow: 0 8px 24px rgba(0,0,0,0.16);
}

.arc-module-bottom h2 {
  margin: 0 0 0.65rem 0;
  color: #ffffff;
  font-size: 1.3rem;
}

.arc-module-bottom p {
  margin: 0;
  color: #dbe4ee;
  line-height: 1.75;
}

/* NAV ROW */

.arc-module-nav-row {
  margin-top: 2rem;
  display: flex;
  justify-content: space-between;
  gap: 1rem;
  align-items: stretch;
}

/* BACK BUTTON */

.arc-module-back,
.arc-module-back:visited,
.arc-module-back:hover,
.arc-module-back:focus,
.arc-module-back:active {
  display: flex;
  align-items: center;
  justify-content: center;
  padding: 0.9rem 1.2rem;
  background: #1f3a5f;
  color: #fff !important;
  border-radius: 10px;
  text-decoration: none;
  font-weight: 500;
  border: none;
  white-space: nowrap;
}

.arc-module-back:hover,
.arc-module-back:focus {
  background: #27496d;
  color: #fff !important;
  text-decoration: none;
}

/* NEXT BUTTON */

.arc-module-next-link {
  display: block;
  padding: 1rem 1.2rem;
  background: #0f172a;
  border: 1px solid #374151;
  border-radius: 12px;
  text-decoration: none;
  transition: all 0.2s ease;
  max-width: 320px;
}

.arc-module-next-link:hover {
  transform: translateY(-2px);
  box-shadow: 0 10px 22px rgba(0,0,0,0.18);
  border-color: #60a5fa;
}

.arc-module-next-link span {
  display: block;
  font-size: 0.7rem;
  letter-spacing: 0.08em;
  text-transform: uppercase;
  color: #93c5fd;
  margin-bottom: 0.25rem;
}

.arc-module-next-link strong {
  color: #f9fafb;
  font-size: 0.95rem;
}

/* MOBILE */

@media (max-width: 768px) {
  .arc-module-nav-row {
    flex-direction: column;
  }

  .arc-module-next-link,
  .arc-module-back {
    width: 100%;
  }
}
</style>

<div class="arc-module">

<div class="arc-module-hero">
  <div class="arc-module-kicker">Module 2 · Risk Tool Lessons</div>
  <h2>Where risk scores come from.</h2>
  <p>
    In the last module, we saw that a risk score reflects what tends to happen among people
    with similar scores. So where do those scores come from? They are built from a set of
    factors, or “items,” that are combined into a single score.
  </p>
</div>

<div class="arc-module-thesis">
  <strong>Key takeaway</strong>
  <p>Risk scores are built from multiple items, and how those items are combined matters.</p>
</div>

<div class="arc-module-section">
  <h2>What Goes Into a Risk Score</h2>
  <p>
    Each item captures something about a person. Common examples include:
  </p>
  <ul>
    <li><strong>prior history</strong></li>
    <li><strong>age</strong></li>
    <li><strong>substance use</strong></li>
    <li><strong>employment</strong></li>
    <li><strong>peer associations</strong></li>
  </ul>
  <p>
    These items are then combined into a single score.
  </p>
  <div class="arc-module-key">
    <strong>The idea:</strong> A risk score is built by combining information across multiple items.
  </div>
</div>

<div class="arc-module-section">
  <h2>From Items to a Score</h2>
  <p>
    The figure below shows a simplified example of how items are combined into a score.
  </p>
</div>

{{< risk-score-built-figure >}}

<div class="arc-module-section">
  <h2>Two Common Approaches</h2>
  <p>There are two common ways to combine items into a score:</p>

  <div class="arc-module-approach">
    <p><strong>1. Burgess-style scoring</strong> (e.g., LS/CMI; ORAS)</p>
    <ul>
      <li>Items are typically binary (0/1)</li>
      <li>Each item contributes equally</li>
      <li>Simple and easy to hand score</li>
    </ul>
  </div>

  <div class="arc-module-approach">
    <p><strong>2. Statistically weighted scoring</strong> (e.g., COMPAS; STRONG-R)</p>
    <ul>
      <li>Items can have different weights</li>
      <li>Weights reflect relationships with outcomes, such as recidivism</li>
    </ul>
  </div>
</div>

<div class="arc-module-section">
  <h2>Why This Matters</h2>
  <p>
    The same inputs can produce different scores depending on how they are combined.
  </p>
  <p>
    Burgess-style tools emphasize simplicity and transparency. Weighted approaches often
    achieve higher predictive accuracy, though the magnitude of that improvement varies.
  </p>
</div>

<div class="arc-module-bottom">
  <h2>Bottom Line</h2>
  <p>
    Risk scores are built from a set of items. The way those items are combined shapes
    what the score means and how well it performs.
  </p>
</div>

<div class="arc-module-nav-row">
  <a class="arc-module-back" href="/training-modules/lessons-in-risk-foundations/">
    ← Back to Modules
  </a>

  <a class="arc-module-next-link" href="/training-modules/lessons-in-risk-foundations/03-same-score-different-person/">
    <span>Next Module</span>
    <strong>Same Score, Different Person →</strong>
  </a>
</div>

</div>