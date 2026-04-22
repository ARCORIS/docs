<div align="center">

# ARCORIS Docs

**Public documentation root for the ARCORIS ecosystem.**

[![Start Here](https://img.shields.io/badge/Start-Docs%20Index-0F766E?style=flat)](docs/index.md)
[![Docs as Code](https://img.shields.io/badge/Approach-Docs%20as%20Code-1D4ED8?style=flat)](https://github.com/ARCORIS/docs)

[Core Platform](https://github.com/ARCORIS/arcoris) · [Handbook](https://github.com/ARCORIS/handbook) · [Community](https://github.com/ARCORIS/community) · [Enhancements](https://github.com/ARCORIS/enhancements) · [Examples](https://github.com/ARCORIS/examples)

Canonical system explanation · Architecture · Concepts · Guides · Operations · Security · Reference

**Overview:** [Purpose](#purpose) · [Start here](#start-here) · [Intended audiences](#intended-audiences)

**Scope:** [What belongs here](#what-belongs-here) · [What does not belong here](#what-does-not-belong-here) · [Source of truth](#source-of-truth-policy)

**Structure:** [Repository map](#repository-map) · [Documentation principles](#documentation-principles)

**Repository:** [Contributing](#contribution-expectations) · [Repository status](#repository-status)

</div>

---

## Purpose

This repository is the **public documentation entry point** for ARCORIS.

It exists to explain the system at a stable level:

- what ARCORIS is;
- how its planes, components, and control loops are structured;
- how the major parts interact;
- how users, evaluators, operators, integrators, and contributors should read the platform.

This repository is not a generic markdown store. It is the canonical home for **stable, public-facing system documentation**.

## Start here

Use the [Docs Index](docs/index.md) as the primary entry point for documentation navigation, reading order, and topic-based access paths.

The index defines how the documentation set is structured and how it should be explored across concepts, architecture, operations, security, and reference material.

## What belongs here

Use this repository for documentation that should remain valid beyond a single proposal, experiment, or implementation detail.

Typical content includes:

- orientation and onboarding for new readers;
- concepts, terminology, and mental models;
- canonical architecture explanations and diagrams;
- subsystem responsibilities, contracts, and interaction flows;
- evaluation, integration, deployment, and operations guidance;
- security model and security operations guidance;
- stable reference material for public behavior, interfaces, and configuration.

## What does not belong here

This repository must not absorb responsibilities that belong elsewhere.

The following should live outside this repository:

- engineering process, documentation policy, writing standards, review rules, and release discipline;
- governance, ownership, roles, meetings, and coordination;
- proposal-specific design alternatives, change lifecycle tracking, and superseded decisions;
- runnable examples, baseline environments, demos, observability bundles, and failure scenarios;
- implementation-near documentation that belongs next to source code.

If a topic becomes accepted and stable, its canonical explanation should be promoted here. Until then, it should remain in the repository that owns that stage of the lifecycle.

## Repository map

ARCORIS uses multiple repositories with different responsibilities. This repository is only one layer of that system.

### Core platform

| Repository | Role |
| --- | --- |
| [Core Platform](https://github.com/ARCORIS/arcoris/blob/main/README.md) | Main code repository for the platform |

### Documentation ecosystem

| Repository | Role |
| --- | --- |
| Docs (this repository) | Public documentation and canonical system explanation |
| [Handbook](https://github.com/ARCORIS/handbook/blob/main/README.md) | Engineering and documentation operating rules |
| [Community](https://github.com/ARCORIS/community/blob/main/README.md) | Governance, roles, coordination, and contributor growth |
| [Enhancements](https://github.com/ARCORIS/enhancements/blob/main/README.md) | Major proposals, accepted changes, and decision history |
| [Examples](https://github.com/ARCORIS/examples/blob/main/README.md) | Runnable examples, baselines, demos, and scenario material |

This repository should **link to these repositories where appropriate without taking over their responsibilities**.

## Intended audiences

This repository serves several audiences:

- **new readers** who need a reliable entry point;
- **evaluators** who need a coherent system explanation;
- **operators** who need deployment and runtime guidance;
- **integrators** who need contracts, interfaces, and behavior documentation;
- **contributors** who need an accurate picture of the current stable architecture.

Because these audiences differ, the documentation should follow **progressive disclosure**:

1. overview first;
2. concepts second;
3. architecture and subsystem flows next;
4. operations and reference after that.

## Source-of-truth policy

This repository should hold the canonical explanation of the **current stable system**.

That means:

- stable architecture must be documented here;
- canonical architecture diagrams must live here;
- accepted behavior must not remain documented only in proposal records;
- public system explanation must not be outsourced to internal process repositories.

If a topic exists in multiple forms, the boundary is simple:

- **stable baseline** -> [Docs](https://github.com/ARCORIS/docs)
- **proposed change** -> [Enhancements](https://github.com/ARCORIS/enhancements)
- **process and review policy** -> [Handbook](https://github.com/ARCORIS/handbook)
- **governance and coordination** -> [Community](https://github.com/ARCORIS/community)
- **runnable and demonstrative material** -> [Examples](https://github.com/ARCORIS/examples)
- **implementation-near technical detail** -> [Core Platform](https://github.com/ARCORIS/arcoris)

## Documentation principles

Documentation in this repository should follow a small set of strict principles:

- **One clear source of truth per topic.**
- **Audience-first navigation.** Organize by reader need, not by author convenience.
- **Stable information architecture.** Prefer durable sections over ad hoc pages.
- **Boundary discipline.** Do not mix public system explanation with governance, proposal tracking, or internal policy.
- **Diagram locality.** Diagrams should live next to the documents they explain.
- **Promotion of accepted knowledge.** Once a proposal becomes product reality, its canonical explanation moves here.
- **Docs-as-code rigor.** Documentation should be reviewable, versioned, and maintainable like source code.

Detailed navigation and documentation structure should be defined in the [Docs Index](docs/index.md) and in the documentation pages themselves, not in this root README.

## Contribution expectations

A good change in this repository usually does one or more of the following:

- clarifies a system concept, boundary, or responsibility;
- explains a subsystem or flow more precisely;
- improves onboarding for a specific audience;
- documents operational or integration behavior more accurately;
- promotes accepted design knowledge into stable documentation;
- removes ambiguity, duplication, or stale content.

Changes should not place proposal-only material, governance content, or internal process rules here unless that content is explicitly part of the public documentation surface.

## Repository status

This repository currently defines the documentation boundary, source-of-truth policy, and public documentation scope for ARCORIS.

The documentation toolchain, local preview workflow, and validation commands are intentionally deferred until the site generator and repository automation model are finalized.

Until then, this README serves as the repository’s boundary and role definition rather than a tooling guide.
