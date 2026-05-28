# MPC Finally Explained
### An Interactive Visual Guide to Model Predictive Control

**Parastoo Semnani** · Imperial College London · TU Berlin · BIFOLD  
**Live →** https://PSemnani.github.io/mpc-finally-explained

---

MPC is everywhere in process control, robotics, and autonomous systems —
yet most learning resources either skip the theory or skip the intuition.
This guide does neither.

It starts with a single question — *why can't you just plan once and execute?* —
and builds up through the optimal control problem, receding horizon execution,
data-driven surrogate modelling, and Gaussian process regression, using a
four-tank nonlinear benchmark as a running example throughout.

**Nine sections. Two modes. One file.**

The *serious* mode reads like an engineering reference — dense, typeset,
precise. The *Grug* mode covers the same ideas as a caveman Reddit post.
The interactive figures are shared between both.

---

## Sections

`§01` What MPC is and why feedback beats open-loop planning  
`§02` The optimal control problem — cost, constraints, horizon  
`§03` Receding horizon — why you plan five steps but only do one  
`§04` The four-tank process — a nonlinear ODE benchmark  
`§05` Surrogate models — linear, quadratic, and neural network regression  
`§06` Gaussian processes — uncertainty-aware prediction, interactive demo  
`§07` Nonlinear programming — SLSQP, CasADi, do-mpc  
`§08` Robustness — what happens when the model is wrong  
`§09` What to read and try next  

---

## Built with

Single HTML file · Vanilla JS · SVG · Canvas · No frameworks · No build step  
GP posterior computed in-browser (SE kernel + Gaussian elimination)

---

## Cite

Semnani, P. (2026). *MPC Finally Explained: An Interactive Visual Guide
to Model Predictive Control.*
https://PSemnani.github.io/mpc-finally-explained

---

[LinkedIn](https://www.linkedin.com/in/psemnani/) ·
[Google Scholar](https://scholar.google.com/citations?user=rWFoXBYAAAAJ&hl=en) ·
p.semnani@tu-berlin.de
