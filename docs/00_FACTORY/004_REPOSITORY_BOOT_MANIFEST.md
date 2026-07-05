# Repository Boot Manifest

**Document ID:** FACTORY-20260705-005

**Version:** 1.0

**Status:** Draft

**Repository:** AHI-Factory

**Path:** docs/00_FACTORY/004_REPOSITORY_BOOT_MANIFEST.md

**Author:** AHI Secretary

**Architecture Authority:** Lê Minh Công (Founder)

**Approver:** Lê Minh Công (Founder)

**Created:** 2026-07-05

**Last Updated:** 2026-07-05

---

# Purpose

This document defines the Repository Boot Manifest standard used throughout the Artificial Hybrid Intelligence (AHI) ecosystem.

A Repository Boot Manifest provides the minimum information required for an authorized AI platform or AHI application to initialize a working environment without reading the entire repository.

GitHub remains the Source of Truth.

---

# Design Principles

The Repository Boot Manifest shall:

- Minimize repository loading time.
- Minimize token consumption.
- Reduce duplicated context.
- Support multiple AI platforms.
- Support future AHI applications.
- Keep repository initialization deterministic.
- Separate permanent repository knowledge from temporary working sessions.

---

# Repository Boot Sequence

Every authorized AI shall initialize a repository in the following order:

1. Read Repository Boot Manifest.
2. Verify repository identity.
3. Verify repository version.
4. Load required standards.
5. Load required architecture documents.
6. Load AI Team definition.
7. Load active roadmap.
8. Load current mission.
9. Build Knowledge Cache.
10. Restore Factory Session if available.
11. Begin working session.

---

# Repository Structure

Every AHI repository should contain:

```text
.boot/

docs/

src/

assets/

README.md
```

The `.boot` directory stores initialization metadata only.

Repository knowledge remains inside the repository itself.

---

# Boot Manifest Location

Standard location:

```text
.boot/BOOT_MANIFEST.md
```

Alternative machine-readable formats may be introduced later.

Examples:

```text
.boot/BOOT_MANIFEST.json

.boot/BOOT_MANIFEST.yaml
```

The Markdown document remains the human-readable reference.

---

# Boot Manifest Contents

A Boot Manifest should contain:

- Repository Name
- Repository ID
- Repository Version
- Repository Description
- Repository Owner
- Repository Maintainer
- Current Branch
- Current Roadmap
- Current Mission
- Active AI Team
- Required Standards
- Required Architecture Documents
- Required Knowledge Packages
- Current Session DNA Reference (if available)
- Current Repository DNA Reference (future)
- Dependencies
- Last Updated

---

# AI Team

The Boot Manifest identifies the AI Team responsible for the repository.

Typical members include:

- PM (Project Manager)
- P (Professor)
- L (Team Leader)
- S (Secretary)
- A (Assistant)

Additional specialized roles may be defined by each repository.

---

# Repository Dependencies

A Boot Manifest may declare dependencies on:

- Standards
- Architecture
- Knowledge Packages
- Shared Libraries
- AI Models
- External Services

Dependencies shall be explicitly listed.

---

# Knowledge Loading Strategy

An AI shall never load the entire repository by default.

Instead, it shall:

1. Read the Boot Manifest.
2. Identify required documents.
3. Load only the documents necessary for the current mission.
4. Build a temporary Knowledge Cache.
5. Continue working.

This minimizes processing cost while improving response quality.

---

# Session Integration

If a valid Session DNA exists and the user is authorized, the AI may:

- Restore the previous working session.
- Reload Working Memory.
- Reload Knowledge Cache.
- Resume unfinished tasks.

Otherwise, a new Factory Session shall be created.

---

# Security

The Boot Manifest shall never contain:

- Secret Space (SS)
- Passwords
- Encryption Keys
- Personal Memories
- Organization Secrets
- Government Secrets

Only references are permitted.

---

# Platform Independence

The Repository Boot Manifest is platform-independent.

It may be used by:

- ChatGPT
- Claude
- Gemini
- Grok
- AHI Desktop
- AHI Mobile
- AHI Cloud
- AHI Robot
- IDE Extensions
- GitHub Actions
- CI/CD Pipelines
- MCP Servers
- Future AHI Runtime

Platform-specific implementations shall preserve the same logical architecture.

---

# Future Evolution

Future versions may introduce:

- Repository DNA
- Machine-readable Boot Manifest
- Automatic GitHub synchronization
- Intelligent Context Loading
- Distributed Knowledge Cache
- Cross-Repository Boot
- Autonomous Repository Discovery
- Dynamic AI Team Loading

---

# References

- AHI Constitution
- GitHub Package Standard
- Factory Initialization
- Factory Session
- Factory Session DNA
- Entity Model
