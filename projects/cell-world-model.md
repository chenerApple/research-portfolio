# Cell World Model · Single-Cell Population Dynamics

## Problem

Destructive single-cell snapshots reveal marginal population states at observed conditions, but they do not uniquely determine the latent dynamics or intervention sequence that generated those states.

## Approach

I developed a distributional world-model pipeline with set encoders, latent SDE / ODE dynamics, stochastic population decoding, well-level distribution supervision, sequential intervention rollout, and explicit identifiability and evidence audits.

## Finding / Contribution

The project shows that strong endpoint fit alone is not sufficient evidence that underlying dynamics are identified. Different models can match observed marginals while disagreeing on intermediate trajectories or intervention behavior. Extensive static and simple baselines, transfer controls, and negative results are used to delineate where dynamic modeling gains do and do not hold.

## Code Availability

The full research repository is private while the work is ongoing. Unpublished model code, data artifacts, formal experiment configurations, and checkpoints are not exposed here. Additional implementation details can be shared privately when appropriate.
