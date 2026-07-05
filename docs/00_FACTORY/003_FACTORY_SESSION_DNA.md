# Factory Session DNA

**Document ID:** FACTORY-20260705-004

**Version:** 1.0

**Status:** Draft

**Repository:** AHI-Factory

**Path:** docs/00_FACTORY/003_FACTORY_SESSION_DNA.md

**Author:** AHI Secretary

**Architecture Authority:** Lê Minh Công (Founder)

**Approver:** Lê Minh Công (Founder)

**Created:** 2026-07-05

**Last Updated:** 2026-07-05

---

# Purpose

This document defines the Factory Session DNA architecture used by the Artificial Hybrid Intelligence (AHI) ecosystem.

Its purpose is to allow any authorized AI platform or AHI application to continue an existing working session with minimal user effort while respecting ownership, permissions and governance.

GitHub remains the Source of Truth.

Session DNA never replaces repository knowledge.

Session DNA only describes how to restore a working session.

---

# Design Principles

Factory Session DNA follows these principles:

- GitHub is the Source of Truth.
- Session DNA stores references, not complete knowledge.
- Working Memory is temporary.
- Repository knowledge is persistent.
- Secret Space (SS) is never exposed.
- The AI shall adapt to the user.
- The user shall never be required to reconstruct the session manually.

---

# Architecture

Factory Session consists of five logical layers:

1. User Identity
2. Session DNA
3. Repository Knowledge
4. Knowledge Cache
5. Working Memory

Each layer has a different lifecycle and responsibility.

---

# Session DNA

Session DNA is the digital description of one working session.

It is temporary.

It exists only to restore the operational context.

Session DNA never becomes the permanent knowledge base.

---

# Session DNA Contents

A Session DNA may contain:

- Session ID
- Session Version
- User ID
- Entity ID
- Repository
- Branch
- Current Folder
- Current Document
- Current Mission
- Current Task
- Active AI Team
- Current Standards
- Current Architecture Version
- Repository Version
- Knowledge References
- Current Decisions
- Pending Decisions
- Permission Profile
- Governance Profile
- Language Profile
- Translation Profile
- User Preference Profile
- Working Context
- Knowledge Cache Reference
- Working Memory Reference
- Previous Session Reference
- Next Session Reference
- Creation Time
- Last Updated Time

---

# What Session DNA Shall Never Store

Session DNA shall never directly store:

- Secret Space (SS)
- Passwords
- Encryption Keys
- Private Documents
- Protected Documents
- Repository Knowledge
- Personal Memories
- Organization Secrets
- Government Secrets

Only secure references are permitted.

---

# Repository Knowledge

Repository Knowledge remains inside GitHub.

Session DNA only records where the knowledge is located.

Examples:

- Repository
- Branch
- Folder
- Document
- Version

This minimizes duplicated information.

---

# Knowledge Cache

Knowledge Cache is generated dynamically.

It contains only the information required for the current task.

Knowledge Cache may be rebuilt at any time.

---

# Working Memory

Working Memory stores temporary information including:

- Current discussion
- Temporary drafts
- Questions
- Intermediate results
- Pending tasks

Working Memory disappears when the session ends unless explicitly saved.

---

# Session Restoration Workflow

An authorized AI or AHI application restores a session using the following sequence:

1. Authenticate the user.
2. Verify permissions.
3. Read Session DNA.
4. Locate the GitHub repository.
5. Load the required documents.
6. Build the Knowledge Cache.
7. Restore the Working Memory.
8. Verify compliance with the AHI Constitution.
9. Continue the working session.

---

# Boot Manifest

Every repository should provide a Boot Manifest.

Example:

.boot/BOOT_MANIFEST.md

The Boot Manifest defines:

- Repository
- Current Version
- Architecture Version
- Active AI Team
- Required Standards
- Current Roadmap
- Current Mission
- Required Documents

The Boot Manifest allows an AI to understand where to begin without reading the entire repository.

---

# Multi-AI Collaboration

Factory Session DNA is platform-independent.

Supported platforms may include:

- ChatGPT
- Claude
- Gemini
- Grok
- Future AHI Applications

Each platform restores the same session using the same Session DNA.

Platform limitations shall not change the architecture.

---

# Session Evolution

Every completed task may generate a new Session DNA version.

Previous versions remain traceable.

Session evolution shall never overwrite history.

---

# Security

Session DNA follows the AHI Constitution.

Every access requires:

- Authentication
- Authorization
- Governance validation
- Compliance validation

Secret Space (SS) remains encrypted.

Only the owner may authorize access.

---

# Future Evolution

Future versions may support:

- Automatic GitHub synchronization
- GitHub API integration
- Repository DNA
- Cross-AI synchronization
- Cross-device synchronization
- Autonomous session recovery
- Digital Successor continuity
- Offline synchronization
- Distributed Knowledge Cache
- Intelligent Session Compression

---

# References

- Factory Initialization
- Factory Session
- Entity Model
- GitHub Package Standard
- AHI Constitution
- Omniverse Architecture
