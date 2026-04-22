<div align="center">

# For Operators

**Operations-oriented reading path for understanding how ARCORIS behaves in runtime environments.**

[![Start Here](https://img.shields.io/badge/Start-Start%20Here%20Index-0F766E?style=flat)](index.md)
[![Docs Home](https://img.shields.io/badge/Docs-Documentation%20Index-1D4ED8?style=flat)](../index.md)

Runtime shape · Observability · Security surface · Failure handling · Operational fit

**Start with:** [Overview](../overview/index.md) · [Concepts](../concepts/index.md) · [Architecture](../architecture/index.md) · [Operations](../operations/index.md)

</div>

---

## Purpose

This page is the **operations-oriented entry path** for ARCORIS documentation.

Use it when your primary goal is to understand how ARCORIS should be evaluated, run, observed, secured, and supported in a real or production-like environment.

This path is designed to help you build a correct runtime baseline before you move into detailed operational procedures, runbooks, sizing work, or deployment-specific practices.

## When to use this path

Choose this path if you are trying to answer questions such as:

- What does ARCORIS look like as a running system?
- Which parts of the architecture matter most for operation and support?
- What should I understand before reading runbooks, dashboards, or incident material?
- How do observability, security, and failure handling fit into the platform?
- Which documentation layers matter before I make judgments about production readiness or operational fit?

If your primary goal is system evaluation, external integration, or making structured changes to the project itself, another path will be more appropriate.

## What this path is for

This path is for readers who need a **system-level operational baseline** before they work with detailed runtime material.

A good outcome of this path is that you can explain, in your own words:

- what operational shape ARCORIS has as a system;
- which architectural boundaries matter for runtime behavior;
- how observability and security concerns fit into the system model;
- how failure-related behavior should be interpreted at a high level;
- which later documentation layers matter for runbooks, sizing, readiness, and support-facing work.

## What this path is not for

This path is not optimized for:

- exact deployment recipes;
- environment-specific setup instructions;
- line-by-line runbooks;
- incident command procedures in full detail;
- protocol reference or interface documentation consumed in isolation;
- contribution workflow or engineering process rules.

Those topics belong in later documentation layers after the operational baseline is clear.

## Recommended reading path

Use the following sequence.

### 1. Establish system identity and scope

Start with [Overview](../overview/index.md).

The overview layer should help you understand:

- what ARCORIS is;
- what problem space it addresses;
- which goals and non-goals shape the system;
- which assumptions and constraints are relevant before judging operational fit.

For operators, this matters because runtime expectations only make sense once the intended system scope is clear.

### 2. Build the conceptual model needed for operations

Continue to [Concepts](../concepts/index.md).

The concepts layer should help you understand the ideas that shape runtime behavior, especially around:

- distributed-system behavior and failure expectations;
- execution control and overload protection;
- workload behavior, isolation, and backpressure;
- observability and security models.

Read this layer before deep architecture if you want the operational meaning of the architecture to be easier to interpret.

### 3. Understand the runtime structure of the platform

Continue to [Architecture](../architecture/index.md).

The architecture layer should help you evaluate:

- the major planes and components;
- the role of control loops;
- the system boundary and major dependencies;
- how request and workload flows move through the platform;
- how state propagation and failure-handling concerns fit into the runtime model.

For operators, this is the layer that turns conceptual understanding into a usable system picture.

### 4. Move into operational material

Continue to [Operations](../operations/index.md).

The operations layer should help you work with:

- readiness and support-facing material;
- dashboards, sizing, and capacity planning;
- incident response and escalation guidance;
- runbooks and operational procedures.

Use this layer only after the overview, concepts, and architecture baseline is clear enough to interpret operational guidance correctly.

### 5. Use security and reference material as needed

Continue to [Security](../security/index.md) and [Reference](../reference/index.md) when you need stable support for runtime work.

Use these sections to clarify:

- deployment-facing security concerns;
- authn/authz and transport security expectations;
- threat-facing summaries and reporting surfaces;
- terminology, compatibility, logs, traces, metrics, and generated technical reference.

Reference and security material should support the operational path, not replace the system and architectural baseline that comes first.

## Operational questions this path should answer

By the end of this path, you should be able to answer the following:

- What kind of runtime system is ARCORIS?
- Which architectural boundaries matter most for operation and support?
- Which concepts are necessary to interpret runtime behavior correctly?
- How do observability, security, and failure concerns fit into the platform?
- Which later documentation layers matter for sizing, dashboards, runbooks, readiness, and incident handling?
- What should be understood before making judgments about production use or operational support?

If these questions are still unclear after finishing this path, the next step is usually not more operational detail but a return to the overview, concepts, and architecture layers to confirm the baseline.

## What to read next after the operational baseline

Once the operational baseline is clear, continue based on your next goal:

- go to [Operations](../operations/index.md) for runtime procedures, readiness, runbooks, dashboards, sizing, and support-facing material;
- go to [Security](../security/index.md) if deployment hardening, authn/authz, transport security, or threat-facing concerns are central to your work;
- go to [Reference](../reference/index.md) for stable technical clarification around metrics, logs, traces, compatibility, and generated reference surfaces;
- go to [Guides](../guides/index.md) if you need task-oriented deployment or troubleshooting guidance;
- go to [For Integrators](for-integrators.md) if the next concern is external system integration rather than runtime operation.

## Fast path summary

If you want the shortest serious operations route, use this order:

1. [Overview](../overview/index.md)
2. [Concepts](../concepts/index.md)
3. [Architecture](../architecture/index.md)
4. [Operations](../operations/index.md)
5. [Security](../security/index.md) and [Reference](../reference/index.md), as needed

## Next step

Start with [Overview](../overview/index.md).

If you need a different route instead, return to [Start Here](index.md).
