---
layout: page
permalink: /miscellanea/
title: Miscellanea
description: 
nav: false
nav_order: 2
---
To be updated


<!-- ## A numerical self-similar study on singularity formation of the slender-jet model

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

To be updated

## Exploratory studies
### L-curve and discrete ill-posed prblems ([<ins>PDF</ins>](/assets/pdf/Math_221_Term_Project_final.pdf))

The Tikhnov regularization is a popular approach to solve the **ill-posed** algebraic problem $$\min \|Ax-b\|_2,$$ where the matrix $$A$$ is ill-conditioned and some of its singular values gradually decay to 0. Tikhonov regularized solution $$x_\lambda$$ solves the following least square problem:

$$
\begin{aligned}
    \min \{\|Ax-b\|_2^2+\lambda^2\|L(x-x_0)\|_2^2\},
\end{aligned}
$$

where $$L$$ is a banded matrix with full row rank and $$L=I$$ in its standard form. A continuous curve parameterized by the penalty parameter $$\lambda$$

$$
    \begin{aligned}
        ( \|Ax_\lambda-b\|_2,  \|x_\lambda\|_2)
    \end{aligned}
$$

on the **log-log** scale is called the L-curve in its standard form. It can be showned that the corner point of the L-curve model provides the "best" parameter for solving the minimization problem. It is significant to notice that 

$$
\begin{aligned}
    Ax_\lambda - b &= (A\bar x_0 - b) + (A\bar x_\lambda - A\bar x_0) + (Ax_\lambda - A\bar x_\lambda) \\
    &= (A\bar x_0 - b) + A\underbrace{(\bar x_\lambda - \bar x_0)}_\text{(i)} + A\underbrace{(x_\lambda - \bar x_\lambda)}_\text{(ii)},
\end{aligned}
$$

where $$\bar x_0$$ is the unregularized solution to the unperturbed problem, part (i) describes the regularization error, and part (ii) describes the perturbation error. If part (i) is large, then the residua norm is large. If part (ii) is large, then the regularized solution norm is large. This suggests that a regularized parameter $$\lambda$$ is optimal if it nears the corner of the L-curve. The project also discuss the application of the L-curve model, which can be seen in the full [<ins>PDF</ins>](/assets/pdf/Math_221_Term_Project_final.pdf)
 -->
