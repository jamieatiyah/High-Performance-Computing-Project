# High-Performance Computing Project

## Overview

This project explores the parallel scalability of provided source codes, focusing on determining the integral of a given function between two points on both ARCHER2 central processing unit (CPU) and graphics processing unit (GPU) hardware. The performance of both the parallel code written in CUDA C and the C code that uses the message passing interface (MPI) on ARCHER2 compute nodes is assessed.

## Table of Contents

- [Introduction](#introduction)
- [Background](#background)
- [CPU](#cpu)
- [GPU Architecture](#gpu-architecture)
- [Methodology](#methodology)
- [Evaluation](#evaluation)
- [Conclusion](#conclusion)
- [References](#references)

## Introduction

The computational power of modern-day technology is increasing rapidly, as observed in Moore's Law. This project investigates the impact of parallelization on CPU and GPU architectures for solving a specific computational problem.

## Background

- Terminology: Provides an overview of high-performance computing (HPC) clusters and parallel programming concepts.
- Amdahl’s Law: Discusses Amdahl’s Law and its implications for parallel computing.

## CPU

- MPI Architecture: Describes the MPI (Message Passing Interface) architecture used in parallel programming on CPUs.

## GPU Architecture

- Overview: Compares CPU and GPU architectures, highlighting the strengths and weaknesses of GPU parallelism.
- CUDA: Provides insights into the CUDA C code used for GPU parallelization.

## Methodology

- Problem Domain: Describes the computational problem of determining the integral of a given function.
- Experimental Setup: Details the setup for running experiments on ARCHER2 and GPU.

## Evaluation

- Value of the Integral: Reports the computed value of the integral for both CPU and GPU solutions.
- MPI Performance: Evaluates the performance of the MPI algorithm for different nodes and cores.
- GPU Performance: Analyzes the performance of the GPU algorithm for various thread configurations.
- Comparison: Compares the performance of GPU and MPI solutions.

## Conclusion

Summarizes the findings of the project and suggests areas for future improvement or exploration.
