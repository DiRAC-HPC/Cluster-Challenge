# Cluster-Challenge

## Overview

The cluster challenge was designed to introduce participants to HPC and parallel programming with an overarching aim of encouraging more students to consider HPC as a good career. In order to make the challenge as accessible as possible, the programming language of choice was Python. Although this does not provide as much flexibility and potential for performance tuning as, for example, C++, there are enough parallel features of Python to introduce core parallel programming concepts and to hook participants on "making code run real fast".

Since the goal was to introduce students to parallel programming, part of the event involved teaching parallel concepts and parallel programming in Python specifically. We hoped even students who had done some HPC work previously could find interest in using Python, since it's likely they would have used other, more typical HPC languages. 


## Intended Learning Outcomes

We wanted the students to leave with answers to the following questions:

- Why do we need parallel codes?
- Why can HPC development be challenging?
- How do we measure performance in HPC?
- What are strong and weak scaling?
- How to vectorise code?
- How to parallelise over multiple cores?
- How to accelerate on a GPU?

This lead us to a list of topics to cover:

- motivation for HPC codes
- pitfalls in parallel programming
- profiling and scaling measurements
- vectorisation
- multi-core parallelisation
- GPU acceleration

What we did *not* want to touch:
- MPI and multi-node HPC (because of node limits on Myriad)
- Communication patterns
- Detailed concurrancy (locks, mutexes, etc) (caveat: races will be covered)

## Schedule

This schedule was extremely approximate and should be adapted as the material develops.

### Day 1

- 10-12 - Introduction to parallel programming in Python (taught)
- 12-1 - Lunch
- 1-5 - CPU challenge

### Day 2

- 10-12 - Introduction to GPU programming in Python (taught)
- 12-1 - Lunch
- 1-5 GPU challenge

(Lunch, as well as morning and afternoon tea and coffee was provided).

## Taught elements

We used [Timo Betcke's Techniques of High-Performance Computing](https://tbetcke.github.io/hpc_lecture_notes/intro.html) as a basis for the teaching portion of the event.

### Intro to parallel programming in Python

The non-GPU material from Timo's course:

- [What is HPC](https://tbetcke.github.io/hpc_lecture_notes/what_is_hpc.html)
- [Numexpr](https://tbetcke.github.io/hpc_lecture_notes/numexpr.html)

Plus an intro to profiling using `line_profiler`. This could be taken from [Lorena Barba's course on reproducible research](https://barbagroup.github.io/essential_skills_RRC/numba/1/).

### Intro to GPU accel in Python

Second part of the HPC section of Timo's course.

Introduction to CUDA profiling using nvidia's tooling. See [the Numba CUDA profiling documentation](https://numba.readthedocs.io/en/stable/cuda-reference/host.html#cuda-profiling). 

## Challenges

The challenges took the form of accelerating an N-Body simulation of a number of interesting astrophysical problems. The physics is high-school level, requiring some understanding of gravitational forces between two objects, the equations governing the systems are, again, mid-high-school level and the numerical methods used to advance the equations in time will likely be new to participants but are quick to explain and do not require deep mathematical understanding. Since this was not an exercise in computational science, we provided a fully functional, serial Python code, with a suite of robust tests that the students could use to verify their results. 

### Problems

- 2-body system
- 3-body system
- simple solar system
- formation of gaps in Saturn's rings (requires HPC)
