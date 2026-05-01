---
title: Lessons in Risk – Foundations
view: 1
---

<style>
.risk-grid {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  grid-auto-flow: column;
  gap: 0.5rem 1.5rem;
  margin-top: 1rem;
}

.risk-grid div {
  color: #d1d5db;
}

@media (max-width: 768px) {
  .risk-grid {
    grid-template-columns: 1fr;
    grid-auto-flow: row;
  }
}
</style>

This series focuses on the foundations of risk assessment—what risk scores represent, how they are constructed, and how they should (and should not) be interpreted.

Before getting into tools, applications, or policy decisions, the goal here is to establish a clear understanding of the core concepts that everything else depends on.

---

### What this series covers

<div class="risk-grid">
  <div>Scores as probabilities</div>
  <div>How scores are built</div>
  <div>Same score ≠ same person</div>
  <div>Separation (accuracy)</div>
  <div>What AUC measures</div>
  <div>Why AUC is not enough</div>
  <div>Calibration (predicted vs. observed)</div>
  <div>Base rates</div>
  <div>Cut points in practice</div>
</div>

---

{{< risk-assessment-module-cards >}}