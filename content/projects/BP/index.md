---
title: Safe Identification-Based Adaptive Control for Time-Varying State Feedback Systems
date: 2026-04-16
# external_link: https://github.com/chengjie1127/Bipedal-Robot-Control
tags:
  - Adaptive control
  - Constrained control
  - Time-varying systems
---

- Addresses safe adaptive control for uncertain time-varying systems with hard state and input constraints.
- Proposes an identification-based adaptive control framework that explicitly separates adaptive performance from safety assurance.
- Uses an identifier-based estimator and recursive least squares (RLS) for online parameter estimation in a matrix regression form.
- Enforces safety with an offline-synthesized barrier-pair supervisor over a composite safe set defined by the convex hull of invariant ellipsoids.
- Switches to a saturated backup controller at the safe-set boundary, avoiding online optimization and runtime infeasibility via offline LMI synthesis.

<!--more-->
