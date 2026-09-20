# Persistent Decision-State Agent Simulation

**Research experience:** SUTD iNLP · Prof. Wenxuan Zhang · Summer 2026

## Problem

In long-horizon character agents, near-perfect factual recall does not guarantee correct character-specific decisions after repeated preference or policy updates.

## Approach

I built controlled synthetic trajectories and an evaluation suite across **11 models** to separate factual recall, next-action prediction, and policy change. I then investigated **Persistent Decision State (PDS)** and a Decision-State Layer with reset / freeze / swap interventions.

## Finding / Contribution

At horizon 200, PDS reached **94.5% vs. 52.6% for GRU** on opposite-update and **73.4% vs. 11.6%** on hidden-conflict. The intervention experiments support the causal role of an explicit decision state while also exposing selective-update weaknesses.

## Code Availability

The full research repository is private. This page provides a public project summary; additional implementation details can be shared privately when appropriate.
