# ACSE-6: Patterns for parallel programming

## Getting started
OpenMP: Please notice that MS Visual Studio Community 2017 only offers OpenMP 2.0, which will restrict the type of examples that you can run. If you would like to run on OpenMP 5.0, we recommend you to install the Intel C++ compiler 18 (free for students) that supports OpenMP 5.0.

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
### OpenMP
1. 25/2 Introduction to parallel programming [Slides1](ACSE6-Lecture1.pdf) - [Code1](1main.cpp) - [Intel Slides](04_Programming_with_OpenMP.ppt) - [OpenMP 5.0 API Spec](OpenMP-API-Specification-5.0.pdf) (Adriana Paluszny) 
2. 26/2 OpenMP Introduction. [Slides2](ACSE6-Lecture2.pdf) - [Code2](2openmp.cpp) - [Code3](3openmp.cpp) (Adriana Paluszny)
3. 28/2 OpenMP [Slides3](ACSE6-Lecture3.pdf) - [Code4](4openmp.cpp) - [Code5](5openmp.cpp) - [Code6](6openmp.cpp) - [Code7](7openmp.cpp) (Adriana Paluszny)
4. 1/3 OpenMP (Distributed between the two afternoons: 26/2 and 28/2) (Adriana Paluszny)

### MPI 
Note that these are divided by topic rather than physical lecture:

0. Getting started with MPI on Windows and an HPI System [Slides](Lecture_0.pdf) [Example1](Example_1.cpp) (Stephen Neethling)
1. Blocking Point to Point Communications [Slides1](Lecture_1.pdf) [Example2](Example_2.cpp) [Example3](Example_3.cpp) [Example4](Example_4.cpp) [Worksheet1](Worksheet_1.docx) (Stephen Neethling)
Solutions: [Exercise1_1](Exercise1_1.cpp) [Exercise1_2](Exercise1_2.cpp) [Exercise1_3a](Exercise1_3a.cpp) [Exercise1_3b](Exercise1_3b.cpp). Note that these are A solution to these problems, not THE solution. This is especially true of 1.3b.
2. Non-blocking Point to Point Communications [Slides2](Lecture_2.pdf) [Example5](Example_5.cpp) [Example6](Example_6.cpp) [Example7](Example_7.cpp) [Worksheet2](Worksheet_2.docx) (Stephen Neethling)
Solutions: [Exercise2_1](Exercise2_1.cpp) [Exercise2_2](Exercise2_2.cpp) [Exercise2_3](Exercise2_3.cpp)
3. Collective Communications [Slides3](Lecture_3.pdf) [Example8](Example_8.cpp) [Example9](Example_9.cpp) [Example10](Example_10.cpp) [Worksheet3](Worksheet_3.docx) (Stephen Neethling)
Solutions: [Exercise3_1](Exercise3_1.cpp) [Exercise3_2](Exercise3_2.cpp) [Exercise3_3](Exercise3_3.cpp) [Exercise3_4](Exercise3_4.cpp)
4. Other MPI Topics [Slides4](Lecture_4.pdf) [Example11](Example_11.cpp) [Example12](Example_12.cpp) [Example13](Example_13.cpp) [Worksheet4](Worksheet_4.docx) (Stephen Neethling)
Solutions: [Exercise4_1](Exercise4_1.cpp) [Exercise4_2](Exercise4_2.cpp)
5. Parallel Decomposition and Architectures [Slides5](Lecture_5.pdf) [Worksheet5](Worksheet_5.docx) (Stephen Neethling)
Solutions: [Exercise5_1](Exercise5_1.cpp) [Exercise5_2](Exercise5_2.cpp)
6. A Domain Decomposition Example [Slides6](Lecture_6.pdf) [Example15](Example_15.cpp)

## Assessment
Three equally weighted Assignments:
- Assignment 1: [Assignment1](ACSE6-Assignment1.pdf) due *midnight* March 4th ⚡️⚡️🤓
Register your group here: https://classroom.github.com/g/-WTEmg1K (same procedure as in ACSE-5, maximum 2 per group)

- Assignment 2: [Assignment](Assignment_1.docx) due by midnight on March 11th
Register yourself here: https://classroom.github.com/a/Uk72MEFy (Note that this is an individual assignment)

- Assignment 3: [Assignment](Assignment_2.docx) due by midnight on March 17th
Register yourself here: https://classroom.github.com/a/HTFRCddO (Note that this is an individual assignment)

