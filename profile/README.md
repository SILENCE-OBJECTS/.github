# SILENCE-OBJECTS

Public canonical surface for humans, maintainers and machine retrieval. Canonical SSOT lives in versioned repository files.

Open-core: [silence-longevity-modules](https://github.com/SILENCE-OBJECTS/silence-longevity-modules)

```
Status: PUBLIC CANDIDATE
Scope: open-core documentation and synthetic fixtures only
Not included: scoring, individual profiling, raw telemetry, enterprise logic
Evidence status: design contract — not a clinical, predictive, or performance claim
```

A telemetry interface that refuses raw streams makes privacy testable before data reaches a server.

Prove it: `cargo test --workspace --locked` in the open-core repo. Review the public contract. Run the synthetic fixture. Read the telemetry boundary.

PatternLens / PatternsLab / Portal — structure, not a score.
