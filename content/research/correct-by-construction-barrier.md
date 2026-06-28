---
date: '2025-04-10T10:00:00+01:00'
draft: true
title: 'Correct-by-Construction Barrier Certificate Synthesis'
image: '/img/project-placeholder.png'
subsection: 'synthesis'
excerpt: 'Developing a framework for synthesizing correct-by-construction barrier certificates using Gröber bases and semidefinite programming for the real Nullstellensatz.'
---

## Overview

Autonomous driving presents unique challenges for formal verification due to the complexity of the environment, interaction with human drivers, and stringent safety requirements. This project develops domain-specific logical frameworks tailored to autonomous driving scenarios.

## Background

Self-driving cars must navigate complex traffic scenarios while guaranteeing safety. Traditional testing and simulation cannot provide the exhaustive coverage needed for safety certification. Formal methods offer a path to rigorous safety guarantees.

However, existing formalisms struggle with the richness of driving scenarios, including continuous vehicle dynamics, discrete decision-making, and multi-agent interactions.

## Approach

Our framework incorporates:

- **Multi-lane traffic models** with formal safety envelopes
- **Responsibility-sensitive safety (RSS)** formalization
- **Game-theoretic reasoning** for interactive scenarios
- **Perception uncertainty modeling** in the logical framework

## Results

- Formal safety proofs for highway merging maneuvers
- Verified collision avoidance under bounded perception error
- Case studies with industry partners on urban driving scenarios

## Future Work

We aim to scale our methods to full city-scale scenarios and integrate with learning-based perception modules.
