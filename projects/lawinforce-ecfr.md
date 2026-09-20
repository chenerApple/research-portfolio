# LawInForce-eCFR · Versioned Legal RAG

**Status / role:** AACL-IJCNLP 2026 · Accepted · Sole First Author

**Paper:** *When the Correct Law Still Fails: A Diagnostic Benchmark for Law-in-Force Retrieval in Versioned Legal RAG.*

## Problem

Legal RAG systems can retrieve plausible current law while missing the regulation version that was actually in force on the operative date. This creates a failure mode where the retrieved authority appears legally relevant but is temporally wrong.

## Approach

I built a benchmark pipeline around point-in-time eCFR versions: aligning paragraph versions, extracting high-confidence amendment events, generating paired questions whose answers change across dates, and comparing version-blind retrieval with date-aware, citation-aware, and oracle diagnostics.

## Finding / Contribution

The study identifies **temporal authority retrieval** as a major bottleneck. Current-law or version-blind retrieval can still produce wrong-version evidence, while supplying the correct in-force passage largely closes the downstream answering gap.

## Code Availability

The full research repository is private. This page provides a public project summary; additional implementation details can be shared privately when appropriate.
