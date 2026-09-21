# Graph Report - rust_repository  (2026-09-21)

## Corpus Check
- Corpus is ~11,136 words - fits in a single context window. You may not need a graph.

## Summary
- 21 nodes · 18 edges · 3 communities (2 shown, 1 thin omitted)
- Extraction: 100% EXTRACTED · 0% INFERRED · 0% AMBIGUOUS
- Token cost: 0 input · 0 output

## Community Hubs (Navigation)
- graphify_pipeline.py
- main.rs
- rust_wasi_markdown_parser

## God Nodes (most connected - your core abstractions)
1. `Self-contained graphify pipeline for CI. Builds a knowledge graph over this…` - 1 edges
2. `rust_wasi_markdown_parser` - 0 edges

## Surprising Connections (you probably didn't know these)
- None detected - all connections are within the same source files.

## Import Cycles
- None detected.

## Communities (3 total, 1 thin omitted)

### Community 0 - "graphify_pipeline.py"
Cohesion: 0.13
Nodes (13): graphify_analyze, graphify_build, graphify_cluster, graphify_detect, graphify_export, graphify_extract, graphify_llm, graphify_report (+5 more)

### Community 1 - "main.rs"
Cohesion: 0.40
Nodes (3): io, ordering, rng

## Knowledge Gaps
- **1 isolated node(s):** `rust_wasi_markdown_parser`
  These have ≤1 connection - possible missing edges or undocumented components. (Counts symbols only; 19 node(s) total have ≤1 connection when file, concept and rationale nodes are included.)
- **1 thin communities (<3 nodes) omitted from report** — run `graphify query` to explore isolated nodes.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **What connects `rust_wasi_markdown_parser` to the rest of the system?**
  _1 weakly-connected nodes found - possible documentation gaps or missing edges._
- **Should `graphify_pipeline.py` be split into smaller, more focused modules?**
  _Cohesion score 0.13333333333333333 - nodes in this community are weakly interconnected._