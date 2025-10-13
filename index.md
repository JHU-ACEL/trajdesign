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
[Prof. Abhishek Cauligi](https://acauligi.github.io)

## Course Assistants 
Mark Gonzales\\
Arnab Chatterjee

## Meeting Times
Lectures will be held on Tuesdays and Thursdays from  1:30-2:45PM in Hodson 216.

## Office Hours
Office hours will begin from the second week of the semester. Office hours will be held regularly at the following times, but please see the calendar at the bottom of the page for the most up-to-date hours: 
- Monday 3-4PM: Arnab Chatterjee (Hackerman 111)
- Wednesday 1-2PM: Prof. Abhishek Cauligi (Hackerman 117)
- Thursday 11AM-12PM: Mark Gonzales (Hackerman 111)

## Syllabus
The syllabus for the course can be found [here](./assets/pdf/syllabus.pdf).

## Final Project
This class will culminate with a final project that will allow students to explore topics of their interest and pursue potential research applications.
Details on the final project can be found [here](./assets/pdf/final_project.pdf). 


## Schedule

| Week | Date   | Topics Covered                                   | Notes                       | Suggested Readings |
|------|--------|--------------------------------------------------|-----------------------------|--------------------|
| 1    | 08/26  | Intro: linear algebra & differential equations review |                             | [Learn git](https://learngitbranching.js.org/?locale=en_US), [Learn shell](https://www.learnshell.org/), [Docker tutorial](https://docker-curriculum.com/)                   |
|      | 08/28  | Linear systems theory                            | [Lecture 2 Notes](./assets/pdf/lecture_2.pdf)  |  [1](https://ee263.stanford.edu/lectures/lds.pdf), [2](https://ee263.stanford.edu/lectures/expm.pdf)                  |
| 2    | 09/02  | Optimization fundamentals |[Lecture 3 Notes](./assets/pdf/lecture_3.pdf),  [Homework 1 Released](./assets/pdf/HW1.pdf) |                    |
|      | 09/04  | Constrained optimization (Pt. 1)                 | [Lecture 4 Notes](./assets/pdf/lecture_4.pdf)    | [1](https://ee263.stanford.edu/lectures/25q3/original/10_ls.pdf), [2](https://ee263.stanford.edu/lectures/25q3/original/13_min-norm.pdf)                   |
|  3   | 09/09  | Constrained optimization (Pt. 2)                 | [Lecture 5 Notes](./assets/pdf/lecture_5.pdf)| [1](https://www.stat.cmu.edu/~ryantibs/convexopt/lectures/kkt.pdf), [2](https://www.stat.cmu.edu/~ryantibs/convexopt/lectures/newton.pdf)                   |
|      | 09/11 | Constrained optimization (Pt. 3)                 | HW1 Due, [Homework 2 Released](./assets/pdf/HW2.pdf), [Lecture 6 Notes](./assets/pdf/lecture_6.pdf)|     [1](https://www.stat.cmu.edu/~ryantibs/convexopt/lectures/barr-method.pdf), [2](https://www.stat.cmu.edu/~ryantibs/convexopt/lectures/primal-dual.pdf)               |
| 4     | 09/16  | Constrained optimization (Pt. 4) | [Lecture 7 Notes](./assets/pdf/lecture_7.pdf) |                    |
|     | 09/18 | Off-the-shelf trajectory optimization | [Lecture 8 Slides](./assets/pdf/lecture_8.pdf)    | [1](https://epubs.siam.org/doi/10.1137/16M1062569), [2](https://link.springer.com/article/10.1023/A:1021711402723)                   |
| 5     | 09/23 | Powered descent guidance                     |  [Lecture 9 Notes](./assets/pdf/lecture_9.pdf) | [1](https://arc.aiaa.org/doi/10.2514/1.27553), [2](https://arc.aiaa.org/doi/10.2514/1.47202)   |
|     | 09/25 | Rigid bodies and Euler's equations                     |    Final project proposal due |                    |
| 6     | 09/30  | Planning with attitude                         | [Lecture 11 Notes](./assets/pdf/lecture_11.pdf)  | [1](https://rexlab.ri.cmu.edu/papers/planning_with_attitude.pdf)                   |
|    | 10/02 | Pontryagin's maximum principle and indirect methods |                          | [1](https://ocw.mit.edu/courses/16-323-principles-of-optimal-control-spring-2008/60e12b689f23537c9de215aeffab0753_lec6.pdf)                   |
| 7    | 10/07  | Combinatorial planning with integer programs                | HW2 Due, [Homework 3 Released](./assets/pdf/HW3.pdf), [Lecture 14 Notes](./assets/pdf/lecture_14.pdf)  | [1](https://arxiv.org/abs/2107.08143), [2](https://arc.aiaa.org/doi/10.2514/2.4943)                            |
|      | 10/09  | Sampling-based motion planning |                             |                    |
| 8    | 10/14  | Inverse classroom (mid-semester checkpoint) |                             |                    |
|      | 10/16  | **No Lecture (Fall Break)** |  |                    |
| 9    | 10/21  | Surface rover path planning |   HW3 Due, HW4 Released |   [1](https://arxiv.org/pdf/2506.22087v1), [2](https://www.roboticsproceedings.org/rss07/p22.pdf), [3](https://arc.aiaa.org/doi/pdf/10.2514/1.G001921)      |
|      | 10/23  | Long and short range planner hierarchies |                             |                    |
| 10   | 10/28  | Derivative-free methods for trajectory optimization |                             |                    |
|      | 10/30  | Uncertainty propagation |  |                    |
| 11   | 11/04  | Stochastic optimal control                |  HW4 Due, HW5 Released |  [1](https://ieeexplore.ieee.org/document/7740982)                  |
|      | 11/06  | **Midterm Exam**                                 |                             |                    |
| 12   | 11/11  | Guest lecture (Dr. Bobby Braun) |                             | [1](https://arc.aiaa.org/doi/10.2514/1.41161), [2](https://arc.aiaa.org/doi/abs/10.2514/6.2008-6216) |
|      | 11/13  | Differentiable MPC |    |                    |
| 13   | 11/18  | Learning value functions |       HW5 Due     |                    |
|      | 11/20  | Guest lecture (TBD)                              |                             |                    |
| 14   | 11/25  | **No Lecture (Thanksgiving Break)**                          |                             |                    |
|      | 11/27  | **No Lecture (Thanksgiving Break)**                          |                             |                    |
| 15   | 12/02  | Final project presentations                      |                             |                    |
|      | 12/04  | Final project presentations                      |                             |                    | 

## Class Calendar

<iframe src="https://calendar.google.com/calendar/embed?src=d6dad31de5e5051b5a5e5401eb546b4d4afa10b4a0cb2d6f8332d35854175596%40group.calendar.google.com&ctz=America%2FNew_York" style="border: 0" width="800" height="600" frameborder="0" scrolling="no"></iframe>

