---
title: What AUC Actually Measures
weight: 5
lastmod: 2026-05-11
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

.arc-module-nav-bottom {
  margin-top: 1.5rem;
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
  color: #fff !important;
  text-decoration: none;
}

.arc-module-nav-row {
  margin-top: 1.5rem;
  display: flex;
  justify-content: space-between;
  gap: 1rem;
  align-items: stretch;
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
  color: #fff !important;
  text-decoration: none;
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
  <div class="arc-module-kicker">Module 5 · Risk Tool Lessons</div>
  <h2>AUC is about ranking.</h2>
  <p>
    Assessment tools are often described using something called “AUC.” AUC stands for
    “Area Under the Curve,” but conceptually it answers a simple question: how often does
    the tool correctly rank people?
  </p>
</div>

<div class="arc-module-thesis">
  <strong>Key takeaway</strong>
  <p>AUC measures ranking—not how risk scores behave in practice.</p>
</div>

<div class="arc-module-section">
  <h2>What AUC Means</h2>
  <p>
    Imagine randomly picking two people from two groups:
  </p>
  <ul>
    <li>one person who reoffended</li>
    <li>one person who did not reoffend</li>
  </ul>
  <p>
    The AUC is the probability that the tool assigns a higher score to the person who
    reoffends.
  </p>
  <div class="arc-module-key">
    <strong>The idea:</strong> AUC asks how well the tool orders people from lower to higher risk.
  </div>
</div>

{{< auc-ranking-figure >}}

<div class="arc-module-section">
  <h2>How to Read AUC Values</h2>
  <ul>
    <li><strong>AUC = 0.50</strong> → no better than chance</li>
    <li><strong>AUC = 0.75</strong> → correctly ranks pairs 75% of the time</li>
    <li><strong>AUC = 1.00</strong> → perfect separation</li>
  </ul>
</div>

<div class="arc-module-section">
  <h2>What AUC Is Not About</h2>
  <p>
    AUC is not about exact probabilities. It is also not about individual predictions.
  </p>
  <p>
    It tells you how well the tool ranks people from lower to higher risk, not whether a
    specific score corresponds to a useful or well-separated probability in practice.
  </p>
</div>

<div class="arc-module-bottom">
  <h2>Bottom Line</h2>
  <p>
    AUC measures ranking. It tells you how often a tool orders people correctly, but it
    does not fully explain how risk scores behave in real decision settings.
  </p>
</div>


<div class="arc-module-nav-row">
  <a class="arc-module-back" href="/training-modules/lessons-in-risk-foundations/">
    ← Back to Modules
  </a>

  <a class="arc-module-next-link" href="/training-modules/lessons-in-risk-foundations/06-auc2/">
    <span>Next Module</span>
    <strong>Same AUC, Different Behavior →</strong>
  </a>
</div>

</div>
