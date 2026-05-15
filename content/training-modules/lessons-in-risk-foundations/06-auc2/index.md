---
title: Same AUC, Different Behavior
weight: 6
lastmod: 2026-05-15
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

.arc-module-nav-row {
  margin-top: 1.5rem;
  display: flex;
  justify-content: space-between;
  gap: 1rem;
  align-items: stretch;
}

.arc-module-back,
.arc-module-back:visited,
.arc-module-back:hover,
.arc-module-back:focus,
.arc-module-back:active {
  display: inline-block;
  padding: 0.6rem 1.2rem;
  background: #1f3a5f;
  color: #fff !important;
  border-radius: 6px;
  text-decoration: none;
  font-weight: 500;
  border: none;
}

.arc-module-back:hover,
.arc-module-back:focus {
  background: #27496d;
}

.arc-module-next-link,
.arc-module-next-link:visited,
.arc-module-next-link:hover,
.arc-module-next-link:focus,
.arc-module-next-link:active {
  display: inline-block;
  padding: 0.75rem 1.2rem;
  background: #0f172a;
  color: #fff !important;
  border: 1px solid #374151;
  border-radius: 8px;
  text-decoration: none;
  font-weight: 500;
  text-align: right;
}

.arc-module-next-link:hover,
.arc-module-next-link:focus {
  background: #1f3a5f;
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
  display: block;
  color: #f9fafb;
  font-size: 0.95rem;
}

@media (max-width: 768px) {
  .arc-module-nav-row {
    flex-direction: column;
  }

  .arc-module-next-link {
    text-align: left;
  }
}
</style>

<div class="arc-module">

<div class="arc-module-hero">
  <div class="arc-module-kicker">Module 6 · Risk Tool Lessons</div>
  <h2>Same AUC does not mean same tool.</h2>
  <p>
    In the last module, we saw that AUC measures how well a tool ranks people from
    lower to higher risk. But two tools can have the same AUC and still behave very differently.
  </p>
</div>

<div class="arc-module-thesis">
  <strong>Key takeaway</strong>
  <p>AUC measures ranking—not how scores map to real-world decisions.</p>
</div>

<div class="arc-module-section">
  <h2>Same Ranking Ability, Different Scores</h2>
  <p>
    Both tools in the figure below have the same AUC. That means they are equally good
    at ranking individuals from lower to higher risk.
  </p>

  <p>
    But their scores behave very differently in practice.
  </p>

  <div class="arc-module-key">
    <strong>The idea:</strong> Two tools can rank equally well while producing very different risk estimates.
  </div>
</div>

{{< same-auc-different-behavior-figure >}}

<div class="arc-module-section">
  <h2>How the Scores Differ</h2>

  <ul>
    <li>At a score of 20, one tool corresponds to about 20% risk while the other corresponds to about 40%</li>
    <li>At a score of 80, one tool corresponds to about 75% risk while the other corresponds to about 45%</li>
  </ul>

  <p>
    The tools have the same ranking ability, but they produce very different risk estimates.
  </p>
</div>

<div class="arc-module-section">
  <h2>Why This Matters</h2>

  <ul>
    <li>Decisions are based on scores and probabilities—not just ranking</li>
    <li>Tools with the same AUC can lead to different classifications</li>
    <li>Policy outcomes can differ even when AUC is identical</li>
  </ul>
</div>

<div class="arc-module-bottom">
  <h2>Bottom Line</h2>
  <p>
    AUC is useful, but it does not tell you everything about how a tool performs.
    Two tools can rank people equally well while behaving very differently in practice.
  </p>
</div>

<div class="arc-module-nav-row">
  <a class="arc-module-back" href="/training-modules/lessons-in-risk-foundations/">
    ← Back to Modules
  </a>
</div>

</div>