# Legal-RAG Diagnostics

**Role:** First Author · Challenge Cup

## Problem

Retrieval, hallucination, and reasoning failures are often entangled in legal LLM systems. Subtle semantic drift among confusable legal terms can further reduce retriever separation, making aggregate answer accuracy difficult to interpret.

## Approach

I built a legal-domain hallucination benchmark over **7 mainstream LLMs**, added review and detection stages to an agent workflow, mapped step-wise CoT into analyzable state trajectories, and designed word-, sentence-, and system-level paired evaluations for Legal-RAG drift.

## Finding / Contribution

The project unifies answer-level evaluation, reasoning-state analysis, and retrieval-drift diagnostics. Initial experiments show that drift samples substantially weaken retrieval performance, motivating embedding-separation threshold analysis and targeted drift-suppression modules.

## Code Availability

The full research code is not exposed in this public portfolio. Additional implementation details can be shared privately when appropriate.
