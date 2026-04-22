<div align="center">

# For Contributors

**Contribution-oriented reading path for understanding ARCORIS before making changes.**

[![Start Here](https://img.shields.io/badge/Start-Start%20Here%20Index-0F766E?style=flat)](index.md)
[![Docs Home](https://img.shields.io/badge/Docs-Documentation%20Index-1D4ED8?style=flat)](../index.md)

System baseline · Boundaries · Concepts · Architecture · Change readiness

**Start with:** [Overview](../overview/index.md) · [Concepts](../concepts/index.md) · [Architecture](../architecture/index.md) · [Reference](../reference/index.md)

</div>

---

## Purpose

This page is the **contribution-oriented entry path** for ARCORIS documentation.

Use it when your primary goal is to understand the system baseline that should be clear **before** you make changes to code, documentation, design material, or structured technical records.

This path is designed to reduce blind changes. It helps contributors establish a shared understanding of system identity, boundaries, concepts, and architecture before they move into contribution workflow, engineering rules, enhancement processes, or community structures.

## When to use this path

Choose this path if you are trying to answer questions such as:

- What should I understand before changing ARCORIS code or documentation?
- Which documentation layers define the canonical baseline of the system?
- Where are the major boundaries that my change must respect?
- Which conceptual and architectural material should I read before proposing or implementing change?
- Where do I go after the system baseline is clear?

If your primary goal is evaluation, integration, or runtime operation rather than making changes, another path will be more appropriate.

## What this path is for

This path is for readers who need a **pre-change system baseline** before they start implementation, documentation updates, proposals, reviews, or structured technical discussion.

A good outcome of this path is that you can explain, in your own words:

- what ARCORIS is and what it is trying to achieve;
- what its major goals and non-goals are;
- which concepts and terms must be used consistently;
- how the system is divided into major planes, components, and flows;
- where the main architectural boundaries are;
- which repositories and process layers matter after the system baseline is clear.

## What this path is not for

This path is not optimized for:

- contribution mechanics in full detail;
- pull request workflow and review rules in isolation;
- documentation style rules and engineering standards in isolation;
- enhancement lifecycle mechanics in isolation;
- governance and participation structures in isolation;
- protocol reference or deployment instructions consumed without system context.

Those topics matter for contributors, but they should come **after** the system baseline is understood.

## Recommended reading path

Use the following sequence.

### 1. Establish system identity and scope

Start with [Overview](../overview/index.md).

The overview layer should help you understand:

- what ARCORIS is;
- what problem space it addresses;
- which goals and non-goals define system scope;
- which assumptions and constraints shape the platform.

For contributors, this matters because good changes depend on understanding what the system is supposed to be, not only how it is implemented today.

### 2. Build the shared conceptual baseline

Continue to [Concepts](../concepts/index.md).

The concepts layer should help you understand the language used across the rest of the documentation, especially around:

- distributed-system behavior;
- execution control;
- workload management;
- observability;
- security.

Read this layer before deep architecture if you want structural material and later process discussions to be easier to interpret correctly.

### 3. Understand the architectural baseline

Continue to [Architecture](../architecture/index.md).

The architecture layer should help you evaluate:

- the system boundary;
- major planes and components;
- control loops and coordination;
- request and workload flows;
- where structural boundaries should and should not be crossed.

For contributors, this is the layer that turns conceptual understanding into design-aware understanding.

### 4. Use reference material for stable clarification

Continue to [Reference](../reference/index.md) when you need stable support for terminology and technical clarification.

Use reference material to reinforce:

- shared vocabulary through the [Glossary](../reference/glossary.md);
- compatibility, interfaces, configuration, logs, traces, metrics, and generated reference surfaces as needed.

Reference should support the contribution path, not replace the overview, concepts, and architecture baseline that comes first.

### 5. Move to contribution-facing repositories only after the baseline is clear

Once the system baseline is established, continue to the repositories that govern contribution work directly:

- [CONTRIBUTING.md](../../CONTRIBUTING.md) for repository contribution workflow;
- [ARCORIS Handbook](https://github.com/ARCORIS/handbook) for engineering and documentation operating rules;
- [ARCORIS Enhancements](https://github.com/ARCORIS/enhancements) for major proposals, decisions, and change lifecycle records;
- [ARCORIS Community](https://github.com/ARCORIS/community) for governance, participation, and ownership structures.

These repositories should guide **how** changes are made, but this path exists to make sure contributors first understand **what system they are changing**.

## Contributor questions this path should answer

By the end of this path, you should be able to answer the following:

- What kind of platform is ARCORIS?
- What are its primary goals and deliberate non-goals?
- Which concepts and terms matter for discussing it accurately?
- How is the system structured at a high level?
- Where are the main architectural boundaries and flows?
- What should I understand before proposing or implementing change?
- Which repository should I go to next for workflow, standards, governance, or major change tracking?

If these questions are still unclear after finishing this path, the next step is usually not more process material but a return to the overview, concepts, and architecture layers to confirm the baseline.

## What to read next after the contribution baseline

Once the contribution baseline is clear, continue based on your next goal:

- go to [CONTRIBUTING.md](../../CONTRIBUTING.md) for repository contribution workflow;
- go to [ARCORIS Handbook](https://github.com/ARCORIS/handbook) for engineering standards, documentation rules, and review discipline;
- go to [ARCORIS Enhancements](https://github.com/ARCORIS/enhancements) if your change is large enough to require a formal proposal or decision record;
- go to [ARCORIS Community](https://github.com/ARCORIS/community) if you need governance, ownership, or participation guidance;
- go to [Guides](../guides/index.md), [Operations](../operations/index.md), [Security](../security/index.md), or [Reference](../reference/index.md) when your change depends on specific operational or technical layers.

## Fast path summary

If you want the shortest serious contributor route, use this order:

1. [Overview](../overview/index.md)
2. [Concepts](../concepts/index.md)
3. [Architecture](../architecture/index.md)
4. [Reference](../reference/index.md), as needed
5. [CONTRIBUTING.md](../../CONTRIBUTING.md)
6. [ARCORIS Handbook](https://github.com/ARCORIS/handbook)
7. [ARCORIS Enhancements](https://github.com/ARCORIS/enhancements), if needed

## Next step

Start with [Overview](../overview/index.md).

If you need a different route instead, return to [Start Here](index.md).
