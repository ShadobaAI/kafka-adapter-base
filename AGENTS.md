# Repository Agent Instructions

## Workspace Instructions

Read the required [workspace instructions](../../AGENTS.md) before working in this repository. The fixed `KAFKA_PROJECTS_ROOT` layout is required. If the shared file is missing, report a workspace-layout error and stop. The repository-specific rules below supplement and override the shared rules when they conflict.

## Repository Scope

This repository contains the BSP-based host configuration used to develop and test Kafka Adapter. Start with [README.md](README.md). Current local 1C sources and tests are the primary evidence of behavior. Preserve original Russian 1C identifiers.

## Repository-Specific Rules

- Use only the EDT-MCP instance named `kfk-edt` for current-state queries, navigation, platform documentation, diagnostics, and every 1C change under `src/**`.
- Preserve the host configuration's established source and metadata style within valid `v8std` alternatives.
