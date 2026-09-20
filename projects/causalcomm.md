# CausalComm · Multi-Agent Communication Efficiency

**Status / role:** AAAI · Under Review · Sole First Author

## Problem

More inter-agent communication does not necessarily improve a multi-agent system. Under limited aggregation capacity, additional messages can increase redundancy and distractor interference, making communication itself a source of error.

## Approach

I built an auditable **capacity × interference × communication-budget** experimental framework and developed a risk-calibrated **PAC Router**. The router selects among nested 25% / 50% / 75% message subsets or the Full communication setting under source-component-disjoint calibration and locked-test protocols.

## Finding / Contribution

The project reframes communication efficiency as **reliability-constrained routing**, rather than simply pruning more messages. The system explicitly falls back to Full communication when risk cannot be certified and separates in-distribution guarantees from out-of-distribution diagnostics.

## Code Availability

The full research repository is private during peer review. Paper-specific method code, formal experiment configurations, data artifacts, checkpoints, and unreleased results are not exposed in this public portfolio. Additional implementation details can be shared privately when appropriate.
