---
layout: page
permalink: /research/
title: Research
description: 
nav: true
nav_order: 5
---

## A numerical self-similar study on singularity formation of the slender-jet model

In this research, we consider the slender-jet model emerging in the fluid dynamics. This model describes an axisymmetric column of fluid that is inherently unstable and spontaneously decays to
a drop. Explicitly, we consider the following equations:

$$
\begin{aligned}
    &\partial_t \rho + \partial_x( u \rho) = 0,\\
    &\partial_t u + u \partial_x u  - \frac 12 \rho^{-\frac 32} \partial_x \rho = \frac{1}{\rho}\partial_x (\rho \partial_x u),
\end{aligned}
$$

on the region $$[0,T^*)\times \mathbb{T} = [0,T^*)\times [a,b)$$ with the periodic boundary condition (that is, $$u(t,a) = u(t,b)$$), where $$\rho$$ is the mass density and $$u$$ is the fluid velocity. Moreover, let $$(\rho, u)$$ be the solution to the above equations. It is shown that if 

 $$\inf_{t\in [0,T^*)} \min_{x\in \mathbb{T}} \rho(t,x) > 0,
 $$

then the solution $$(\rho,t)$$ can be continued past $$T^*.$$ In this research, we aim to answer the following question: Can we construct the initial conditions for the general slender-jet model such that the solution $$(\rho, u)$$ satisfies 

$$\lim_{t\rightarrow T^*}\lim_{x\rightarrow x_0}\rho(t,x) = 0$$

for some finite $$T^*, x_0$$? We developed a numerical scheme for the simulation of the slender-jet model based on the self-similarity assumption of the solution. We speculated that the solution $$(\rho, u)$$ takes the following forms:

$$
\begin{aligned}
    u &= (T^*-t)^\alpha U\left(\frac{x}{(T^*-t)^\beta}\right),\\
    \rho &= (T^*-t)^\delta P\left(\frac{x}{(T^*-t)^\beta}\right).
\end{aligned}
$$

We started with existing numerical methods (forward-time centered-difference and implicit method) that reflects the evolution of the solution to the slender-jet model until the breakdown. In this process, we collected heuristic evidence for numerically calculating the self-similar rates for similarity transformation. We would then compare the rates to the analytic result obtained by dimensional analysis of the self-similar solution to the slender-jet model.

You may see my full report here (will be updated soon).

## A pattern avoidance conjecture for maximal sphericality of type B Coxeter groups

To be updated.

## Exploratory studies
### L-curve and discrete ill-posed prblems

To be updated.