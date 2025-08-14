---
layout: default
title: "Trajectory Design for Space Systems"
---

# Trajectory Design for Space Systems (EN.530.626)

## Course Description
This course is an introduction to the techniques and methods used to design and synthesize trajectories for a broad class of space systems.
In particular, we will focus on optimization-based techniques for trajectory generation and study optimal control formulations for solving trajectory optimization and model predictive control problems.
Applications of interest will include interplanetary trajectory optimization, rocket entry-descent-landing, asteroid proximity operations, and planetary rover path planning.
A strong emphasis will be placed on practical applications through coding implementations in Python and evaluation in simple simulation environments.
Finally, a course project will be included to allow students to gain further experience on an algorithm or application of their choice.

## Instructors 
[Prof. Abhishek Cauligi](https://acauligi.github.io)\\
Office: Hackerman 117

## Course Assistants 
Mark Gonzales

## Meeting Times
Lectures will be held on Tuesdays and Thursdays from  1:30-2:45PM.

## Office Hours
Office hours will begin from the second week of the semester.
- Monday 3-4PM: Arnab Chatterjee
- Wednesday 1-2PM: Prof. Abhishek Cauligi
- Thursday 11AM-12PM: Mark Gonzales

## Class Calendar

<iframe src="https://calendar.google.com/calendar/embed?src=d6dad31de5e5051b5a5e5401eb546b4d4afa10b4a0cb2d6f8332d35854175596%40group.calendar.google.com&ctz=America%2FNew_York" style="border: 0" width="800" height="600" frameborder="0" scrolling="no"></iframe>

## Syllabus
The syllabus for the course can be found [here](./assets/pdf/syllabus.pdf).

## Schedule

| Week | Date   | Topics Covered                                   | Notes                       | Suggested Readings |
|------|--------|--------------------------------------------------|-----------------------------|--------------------|
| 1    | 08/26  | Intro: linear algebra & differential equations review |                             | [Learn git](https://learngitbranching.js.org/?locale=en_US), [Learn shell](https://www.learnshell.org/), [Docker tutorial](https://docker-curriculum.com/)                   |
|      | 08/28  | Linear systems theory                            | HW1 Released |  [1](https://ee263.stanford.edu/lectures/lds.pdf), [2](https://ee263.stanford.edu/lectures/expm.pdf)                  |
| 2    | 09/02  | Optimization fundamentals |                             |                    |
|      | 09/04  | Calculus of variations                 | |                    |
| 3    | 09/09  | Pontryagin's maximum principle and indirect methods |                          |                    |
|      | 09/11  | Constrained optimization (Pt. 1)                 |    HW1 Due, HW2 Released                         | [1](https://ee263.stanford.edu/lectures/25q3/original/10_ls.pdf), [2](https://ee263.stanford.edu/lectures/25q3/original/13_min-norm.pdf)                   |
| 4    | 09/16  | Constrained optimization (Pt. 2)                 | Form project groups         | [1](https://www.stat.cmu.edu/~ryantibs/convexopt/lectures/kkt.pdf), [2](https://www.stat.cmu.edu/~ryantibs/convexopt/lectures/newton.pdf)                   |
|      | 09/18  | Constrained optimization (Pt. 3)                 | |     [1](https://www.stat.cmu.edu/~ryantibs/convexopt/lectures/barr-method.pdf), [2](https://www.stat.cmu.edu/~ryantibs/convexopt/lectures/primal-dual.pdf)               |
| 5    | 09/23  | Off-the-shelf trajectory optimization |                             | [1](https://epubs.siam.org/doi/10.1137/16M1062569)                   |
|      | 09/25  | Planetary entry, descent, and landing                     | Final project proposal due  | [1](https://arc.aiaa.org/doi/full/10.2514/1.G001480), [2](https://arc.aiaa.org/doi/10.2514/1.47202)  |
| 6    | 09/30  | Rigid bodies and Euler's equations                     |                             |                    |
|      | 10/02  | Planning with attitude                         | HW2 Due, HW3 Released | [1](https://rexlab.ri.cmu.edu/papers/planning_with_attitude.pdf)                   |
| 7    | 10/07  | Combinatorial planning with integer programs                |  | [1](https://arxiv.org/abs/2107.08143), [2](https://arc.aiaa.org/doi/10.2514/2.4943)                            |
|      | 10/09  | Sampling-based motion planning |                             |                    |
| 8    | 10/14  | Inverse classroom (mid-semester checkpoint) |                             |                    |
|      | 10/16  | **No lecture (Fall Break)** | HW3 Due, HW4 Released |                    |
| 9    | 10/21  | Derivative-free methods for trajectory optimization |                             |   [1](https://arxiv.org/pdf/2506.22087v1), [2](https://www.roboticsproceedings.org/rss07/p22.pdf)      |
|      | 10/23  | Surface rover path planning |                             |                    |
| 10   | 10/28  | Long and short range planner hierarchies |                             |                    |
|      | 10/30  | Uncertainty propagation | HW4 Due, HW5 Released |                    |
| 11   | 11/04  | Stochastic optimal control                |                             |  [1](https://ieeexplore.ieee.org/document/7740982)                  |
|      | 11/06  | **Midterm Exam**                                 |                             |                    |
| 12   | 11/11  | Guest lecture (Dr. Bobby Braun) |                             | [1](https://arc.aiaa.org/doi/10.2514/1.41161) |
|      | 11/13  | Differentiable MPC | HW5 Due                     |                    |
| 13   | 11/18  | Learning value functions |                             |                    |
|      | 11/20  | Guest lecture (TBD)                              |                             |                    |
| 14   | 11/25  | **No Lecture (Thanksgiving Break)**                          |                             |                    |
|      | 11/27  | **No Lecture (Thanksgiving Break)**                          |                             |                    |
| 15   | 12/02  | Final project presentations                      |                             |                    |
|      | 12/04  | Final project presentations                      |                             |                    | 
