# ACSE-6: Patterns for parallel programming

## Getting started
Please notice that MS Visual Studio Community 2017 only offers OpenMP 2.0, which will restrict the type of examples that you can run. If you would like to run on OpenMP 5.0, we recommend you to install the Intel C++ compiler 18 (free for students) that supports OpenMP 5.0.

## Description
The module will introduce the basic concepts of parallel programming to students with experience in higher-level programming languages, such as C++. Students will be taught how to identify different types of concurrency in various problem domains and map it to the appropriate parallelisation strategy, as well as how to reason about scalability and parallel efficiency. Students will learn the basic concepts of task parallelism and data parallelism, as well as common concepts such as the master-worker paradigm, domain-decomposition, and load-balancing strategies.

The module will teach students basic implementation strategies based on shared-memory parallelism and the message-passing paradigm. Particular attention will be paid to the design of parallel data structures and their use in the context of scientific programming. Students will thus gain a basic understanding of scalable parallel solvers and the different parallelisation paradigms involved in complex inversion and optimisation algorithms.

The teaching activities will be complemented with a set of individual mini-projects, each teaching the implementation of a particular parallel programming paradigm in an applied scientific context. The exercises in OpenMP threading will primarily based on C++.

## Learning Objectives
On successful completion of this module, students will be able to:
1.	Identify different concurrency design spaces.
2.	Create software to implement a number of different parallel algorithms and parallel data structures.
3.	Apply a range of parallel programming models. 

## Team
- Dr Adriana Paluszny - Royal Society Research Fellow - computational scientist and C++ devotee (Introduction to parallel programming and OpenMP, C++) - Four classes
- Prof Stephen Neethling - Professor of Minerals Processing - Remaining classes, focused on MPI

## Lectures
1. 25/2 Introduction to parallel programming [Slides1](ACSE6-Lecture1.pdf) - [Code1](1main.cpp) - [Intel Slides](04_Programming_with_OpenMP.ppt) - [OpenMP 5.0 API Spec](OpenMP-API-Specification-5.0.pdf) (Adriana Paluszny) 
2. 26/2 OpenMP Introduction. [Slides2](ACSE6-Lecture2.pdf) - [Code2](2openmp.cpp) - [Code3](3openmp.cpp) (Adriana Paluszny)
3. 28/2 OpenMP [Slides3](ACSE6-Lecture3.pdf) - [Code4](4openmp.cpp) - [Code5](5openmp.cpp) - [Code6](6openmp.cpp) - [Code7](7openmp.cpp) (Adriana Paluszny)
4. 1/3 OpenMP (Distributed between the two afternoons: 26/2 and 28/2) (Adriana Paluszny)
5. MPI (Stephen Neethling)
6. MPI (Stephen Neethling)
7. MPI (Stephen Neethling)
8. MPI (Stephen Neethling)
9. MPI (Stephen Neethling)
10. MPI (Stephen Neethling)
11. MPI (Stephen Neethling)
12. MPI (Stephen Neethling)

## Assessment
Three equally weighted Assignments:
- Assignment 1: [Assignment1](ACSE6-Assignment1.pdf) due *midnight* March 4th ⚡️⚡️🤓
Register your group here: https://classroom.github.com/g/-WTEmg1K (same procedure as in ACSE-5, maximum 2 per group)

- Assignment 2: due March 11th
- Assignment 3: due March 18th

