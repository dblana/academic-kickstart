---
title: "Implicit methods for efficient musculoskeletal simulation and optimal control"
date: 2011-01-01
publishDate: 2020-07-20T14:51:04.637174Z
authors: ["Antonie J van den Bogert", "Dimitra Blana", "Dieter Heinrich"]
publication_types: ["2"]
abstract: "The ordinary differential equations for musculoskeletal dynamics are often numerically stiff and highly nonlinear. Consequently, simulations require small time steps, and optimal control problems are slow to solve and have poor convergence. In this paper, we present an implicit formulation of musculoskeletal dynamics, which leads to new numerical methods for simulation and optimal control, with the expectation that we can mitigate some of these problems. A first order Rosenbrock method was developed for solving forward dynamic problems using the implicit formulation. It was used to perform real-time dynamic simulation of a complex shoulder arm system with extreme dynamic stiffness. Simulations had an RMS error of only 0.11 degrees in joint angles when running at real-time speed. For optimal control of musculoskeletal systems, a direct collocation method was developed for implicitly formulated models. The method was applied to predict gait with a prosthetic foot and ankle. Solutions were obtained in well under one hour of computation time and demonstrated how patients may adapt their gait to compensate for limitations of a specific prosthetic limb design. The optimal control method was also applied to a state estimation problem in sports biomechanics, where forces during skiing were estimated from noisy and incomplete kinematic data. Using a full musculoskeletal dynamics model for state estimation had the additional advantage that forward dynamic simulations, could be done with the same implicitly formulated model to simulate injuries and perturbation responses. While these methods are powerful and allow solution of previously intractable problems, there are still considerable numerical challenges, especially related to the convergence of gradient-based solvers."
featured: false
publication: "*Procedia Iutam*"
doi: "10.1016/j.piutam.2011.04.027"
---

