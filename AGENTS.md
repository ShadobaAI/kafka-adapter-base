# Repository Agent Instructions

Apply the required [workspace instructions](../../AGENTS.md). The rules below are this repository's delta and override shared rules on conflict.

## Repository Scope

This repository contains the BSP-based host configuration used to develop and test Kafka Adapter. Use current 1C sources and tests as primary evidence of behavior. Preserve Russian 1C identifiers and the established source and metadata style within valid 1C standards.

- Use `kfk-edt` on port `8765` for authoritative live state, platform documentation, diagnostics, and every persistent 1C mutation.
- Use the canonical `kfk-base` alias only for supplementary read-only code-index analysis of this checkout.
