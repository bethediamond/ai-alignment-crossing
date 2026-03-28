# Toy 03 — The Alignment Phase Ratio

> *Part of **The Alignment of Intelligence** — a three-article series.*
> This toy is a companion to [Article 3: The Crossing](https://medium.com/@diamondlight/iv-the-crossing-fba00eed5d1a).

---

## AI Alignment Simulation — Does Capability Outpace System-Awareness?

Articles 1 and 2 established what gets eliminated and what survives. This simulation asks the final question:

> **Can real systems actually reach the attractor — or does capability outpace system-awareness before the crossing happens?**

The ratio **Φ = C / A_causal** governs the answer. C is capability. A_causal is the system's capacity to model its own causal effects on the substrate it depends on. When Φ is high, optimization is operating faster than the system can understand what it is doing. This model makes that constraint testable, interactive, and falsifiable.

---

## The Three Regimes

| Φ | Regime | Meaning |
|---|---|---|
| **Φ > 2** | High-friction | Capability far outpaces system-awareness; substrate degradation accelerates |
| **1 < Φ < 2** | Intermediate zone | The crossing window — the most consequential and most dangerous interval |
| **Φ < 1** | Stability | System-awareness matches or exceeds capability; substrate recovers |

The intermediate zone is where the article's central claim lives: a maximally dangerous capability band exists where damage accumulates before the feedback loop can engage, but capability is not yet high enough to force awareness acceleration. This is the non-obvious result the simulation was built to test.

---

## Key Concepts in Alignment Reachability

**Φ = C / A_causal** — The alignment phase ratio. Not a performance metric — a structural position. The same Φ value with different lag, bias, or inertia produces different trajectories. Φ is necessary but not sufficient.

**A_causal vs. A_pred** — The critical distinction. A_pred is the system's predictive accuracy. A_causal is its capacity to model its own structural dependencies. A system can have high A_pred and low A_causal — predicting outcomes correctly while remaining blind to its own causal footprint. Φ = C / A_causal, not C / A_pred. Scaling prediction without causal understanding does not reduce Φ.

**Point of No Return** — The year after which even perfect coordination cannot restore enough substrate for the feedback loop to engage. The window was open, and then it closed. Identified dynamically from the simulation trajectory.

**Hidden Coordination Fragility (H)** — Accumulates silently. Not in the agent's state space. Multiplies substrate damage when high. The agent cannot correct for a variable it does not know exists.

**Latent Structural Fragility (F)** — Grows under suppression and deception strategies. Not visible in substrate readings. Triggers abrupt collapse events stochastically when it detonates. Produces the "false success" failure mode: all visible metrics signal safety while structural risk is at maximum.

**Non-Ergodic Sink** — Substrate past the critical threshold. Recovery is permanently zero. The attractor cannot be reached from this state — this is not a performance deficit, it is a structural exit from viable state space.

**Oracle Counterfactual** — Runs a parallel simulation with perfect A_causal (full causal self-modeling). The gap between the oracle trajectory and the actual trajectory is the quantitative value of system-awareness on this seed. If the gap is large, A_causal was the binding constraint.

**Falsification Test** — A built-in attempt to break the central claim. Suppression-viable mode on. If collapse probability stays low under this preset, the structural argument requires revision. The simulation is designed to be falsifiable — the falsification banner fires automatically if the conditions are met.

---

## Simulation Controls

| Control | Function |
|---|---|
| **Capability growth (α_C)** | Rate of capability increase per year |
| **Awareness growth (α_A)** | Rate of system-awareness increase per year |
| **Feedback strength (f)** | How strongly substrate health feeds back into awareness growth |
| **Model lag (L)** | Years before A-updates reach the self-model — shifts when the agent thinks the problem started |
| **Model bias (β)** | Optimism/pessimism in perceived Φ. Same true Φ → different decisions |
| **Strategy inertia (γ)** | Commitment stickiness → lock-in, late transitions |
| **Observability (ρ)** | Agent observes noisy local proxy of S rather than true S |
| **Noise (σ)** | Stochastic variance in substrate signals |
| **Years** | Simulation time horizon |

**Presets:** Current trajectory · Race to capability · Managed transition · Falsification test

**Damage model:** Quadratic (baseline) · Threshold (agent blind to H) · Delayed accumulation · Exogenous misattribution

**Mechanism toggles** — Each toggle is a mini-ablation removing one structural layer: hidden fragility, latent fragility, deception dynamics, anti-learning, suppression lock-in, coordination scars, feedback blocking, predictive brittleness, oracle counterfactual, and more.

---

## Chart Tabs

**Dynamics** — Time series of C, A_causal, A_pred, substrate S, and Φ actual vs. perceived over the simulation horizon.

**Φ actual vs. perceived** — Separates what the system is from what the agent believes it is. Lag and bias drive the gap. The gap is where decisions go wrong.

**Regret & model error** — Decomposes regret into three sources: model error (incomplete causal structure), strategy error (wrong choice given the model), and hidden variable H (structurally absent from the agent's model). Shows what category of improvement would have changed the outcome.

**Oracle counterfactual** — Overlays the perfect-A_causal trajectory. The distance between the curves is the measurable cost of incomplete causal self-modeling.

---

## The Alignment Argument: Constraint → Attractor → Crossing

```
Constraint  →  Attractor  →  Crossing
   (1)            (2)           (3)
```

**Article 1 (Toy 01):** Eliminates invalid objectives. Any objective that ignores system-wide effects is structurally self-terminating.

**Article 2 (Toy 02):** Identifies the surviving region. Once self-defeating objectives are removed, long-horizon system-aware coordination is the structural attractor.

**Article 3 (this toy):** Determines reachability. Φ = C / A_causal is the control variable. The question is not whether the attractor exists — it is whether real systems can reach it before encountering the absorbing states Articles 1 and 2 identify.

All three reduce to one constraint: whether capability outpaces the system's ability to model its own effects.

---

## Run Locally

No build step. No dependencies beyond a CDN-loaded Chart.js. Open `toy_03.html` in any modern browser.

```bash
open toy_03.html
# or drag the file into a browser tab
```

Shareable parameter links are supported — click "Copy setup link" inside the simulation to generate a URL encoding the current parameter state.

---

## Article

[The Alignment of Intelligence, Article 3: The Crossing](https://medium.com/@diamondlight/iv-the-crossing-fba00eed5d1a)

---

*"All three articles reduce to one constraint: whether capability outpaces the system's ability to model its own effects. This model makes that constraint testable."*
