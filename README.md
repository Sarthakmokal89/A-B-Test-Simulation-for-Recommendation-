# A/B Test Simulation for Recommendation 

## Summary
A professional, self-contained simulation that demonstrates how to design and analyze an A/B test for a recommendation experiment.  
This repository contains a notebook/script that (1) generates synthetic user-level binary conversion data, (2) computes conversion rates, standard errors, and 95% confidence intervals, (3) runs a two-proportion z-test, and (4) produces a compact visualization of results.



---

## Purpose & Use Cases
**Purpose:** Provide a reproducible example for learning, demoing, or prototyping A/B testing analysis in the context of recommender systems.

**Use cases:**
- Teaching basic A/B testing concepts (conversion rate, lift, SE, z-test, CI).
- Quickly prototyping experiment analysis pipelines before applying to real data.
- Generating synthetic datasets for CI demos, slides, or interview exercises.
- Verifying analysis code (sanity checks) when preparing to analyze live experiment data.

---

## Features
- Self-contained synthetic data generation (no external dataset required).
- Per-arm and pooled statistics: conversion counts, conversion rates, absolute & relative lift.
- Two-proportion z-test (two-sided) with p-value.
- 95% Wald confidence intervals for each arm.
- Simple bar plot showing conversion rates with 95% error bars.
- Clear, notebook-style structure with separated Markdown and code blocks for easy copy/paste.

---

## Requirements
- Python 3.8+
- Python packages:
  - `numpy`
  - `pandas`
  - `scipy`
  - `matplotlib`


