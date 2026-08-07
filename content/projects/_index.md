+++
date = '2026-06-05T23:50:33-05:00'
draft = false
title = 'Projects'
+++

These projects form a unified software ecosystem for large-scale atomic structure calculations. The AUTOSTRUCTURE extensions provide scalable computational capabilities, the pipeline automates simulation workflows, and CRISTAL builds upon this framework to optimize configuration interaction calculations.

**CRISTAL**

Status: Published

Configuration interaction calculations often require tens of thousands of electronic configurations to accurately model complex atomic systems, making them computationally expensive. CRISTAL (Complex Resolved Ion Spectroscopy Tree Algorithm) is a decision-tree algorithm designed to identify the smallest configuration set needed to achieve a desired level of accuracy. The set of possible configurations (up to a maximum value of the principal quantum number, $n$) is organized into a tree data structure. The tree is then pruned to find the minimum number of states necessary to reach a given accuracy. The current implementation evaluates candidate models by comparing calculated and experimental energy levels, although future work aims to replace this empirical metric with more fully ab initio selection criteria.

**AUTOSTRUCTURE Extensions**

Status: Ongoing

AUTOSTRUCTURE is a widely used atomic structure code which calculates atomic energies, stationary states, and autoionization and radiative rates using the configuration interaction method. The original implementation was primarily intended for serial calculations involving relatively modest configuration expansions. My collaborators and I have extended this code to perform parallelized calculations on much larger configuration sets. In principle, the upper limit is now only bounded by the available memory.

**Atomic Data Pipelines**

Status: Ongoing

Large-scale atomic structure calculations require the generation of input files, execution of many computational jobs, and post-processing of extensive output data. To streamline this workflow, I have developed a Python-based pipeline that automates these tasks while providing a more intuitive interface to AUTOSTRUCTURE. This pipeline currently serves as the platform on which CRISTAL is implemented and is intended to support additional atomic structure codes in the future. 
