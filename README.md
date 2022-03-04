# Cluster-Challenge

## Overview

The cluster challenge is designed to introduce participants to HPC and parallel programming with an overarching aim of encouraging more students to consider HPC as a good career. In order to make the challenge as accessible as possible, the programming language of choice is Python. Although this does not provide as much flexibility and potential for performance tuning as, for example, C++, there are enough parallel features of Python to introduce core parallel programming concepts and to hook participants on "making code run real fast".

Since the goal is to introduce students to parallel programming, part of the event will involve teaching parallel concepts and parallel programming in Python specifically. We hope even students who have done some HPC work previously can find interest in using Python, since it's likely they will have used other, more typical HPC languages. 

The challenges will take the form of accelerating an N-Body simulation of a number of interesting astrophysical problems. The physics is high-school level, requiring some understanding of gravitational forces between two objects, the equations governing the systems are, again, mid-high-school level and the numerical methods used to advance the equations in time will likely be new to participants but are quick to explain and do not require deep mathematical understanding. Since this is not an exercise in computational science, we will provide a fully functional, serial Python code, with a suite of robust tests that the students can use to verify their results. 

## Intended Learning Outcomes

We want the students to leave with answers to the following questions:

- Why do we need parallel codes?
- Why can HPC development be challenging?
- How do we measure performance in HPC?
- What are strong and weak scaling?
- How to vectorise code?
- How to parallelised over multiple cores?
- How to accelerate on a GPU?

This leads us to a list of topics to cover:

- motivation for HPC codes
- pitfalls in parallel programming
- profiling and scaling measurements
- vectorisation
- multi-core parallelisation
- GPU acceleration

What we do *not* want to touch:
- MPI and multi-node HPC (because of node limits on Myriad)
- Communication patterns
- Detailed concurrancy (locks, mutexes, etc) (caveat: races will be covered)

## Schedule

This schedule is extremely approximate and should be adapted as the material develops.

### Day 1

- 10-12 - Introduction to parallel programming in Python (taught)
- 12-1 - Lunch
- 1-5 - CPU challenge

### Day 2

- 10-12 - Introduction to GPU programming in Python (taught)
- 12-1 - Lunch
- 1-5 GPU challenge

## Taught elements

We are using [Timo Betcke's Techniques of High-Performance Computing](https://tbetcke.github.io/hpc_lecture_notes/intro.html) as a basis for the teaching portion of the event.

### Intro to parallel programming in Python
