<div align="center">

# For Evaluators

**Evaluation-oriented reading path for understanding ARCORIS as a system.**

[![Start Here](https://img.shields.io/badge/Start-Start%20Here%20Index-0F766E?style=flat)](index.md)
[![Docs Home](https://img.shields.io/badge/Docs-Documentation%20Index-1D4ED8?style=flat)](../index.md)

System fit · Problem space · Scope · Operating model · Architecture baseline

**Start with:** [Overview](../overview/index.md) · [Concepts](../concepts/index.md) · [Architecture](../architecture/index.md)

</div>

---

## Purpose

This page is the **evaluation-oriented entry path** for ARCORIS documentation.

Use it when your primary goal is to understand what ARCORIS is, what class of problem it addresses, where its boundaries are, and whether its system model is relevant to your environment or use case.

This path is designed to help you reach a grounded system-level understanding before you invest in integration, operations, or contribution work.

## When to use this path

Choose this path if you are trying to answer questions such as:

- What is ARCORIS?
- What problem space is it designed for?
- What are its goals and non-goals?
- What kind of system is it, conceptually and architecturally?
- Where are its major boundaries?
- Is it likely to fit my intended use case?

If your primary goal is integration, runtime operations, or making changes to the project itself, another path will be more appropriate.

## What this path is for

This path is for readers who need a **coherent evaluation baseline**, not deep implementation detail.

A good outcome of this path is that you can explain, in your own words:

- what ARCORIS is;
- what it is trying to achieve;
- what it is explicitly not trying to be;
- how it thinks about workloads, control, isolation, and observability;
- how its main planes, components, and flows are organized at a high level.

## What this path is not for

This path is not optimized for:

- implementation-near technical detail;
- configuration specifics;
- deployment recipes;
- runbooks and operational procedures;
- protocol- or interface-level reference;
- contribution workflow or engineering process rules.

Those topics belong in later documentation layers once the system baseline is clear.

## Recommended reading path

Use the following sequence.

### 1. Understand the system at the highest level

Start with [Overview](../overview/index.md).

The overview layer should give you the shortest path to:

- what ARCORIS is;
- what problem space it addresses;
- what its goals and non-goals are;
- what kinds of use cases it is intended for;
- which assumptions and constraints shape the system.

### 2. Build the conceptual baseline

Continue to [Concepts](../concepts/index.md).

The concepts layer should help you understand the language used throughout the rest of the documentation, especially around:

- distributed-system concerns;
- execution control;
- workload management;
- observability;
- security.

Read this layer before deep architecture if you want the architectural material to be easier to interpret and compare.

### 3. Understand the system structure

Continue to [Architecture](../architecture/index.md).

The architecture layer should help you evaluate:

- the system boundary;
- the major planes and components;
- the role of control loops;
- how request and workload flows move through the system;
- whether the architectural model matches the needs of your environment.

### 4. Use reference material only as needed

Use [Reference](../reference/index.md), especially the [Glossary](../reference/glossary.md), when you need stable terminology or technical clarification while evaluating the system.

Reference should support the evaluation path, not replace it.

## Evaluation questions this path should answer

By the end of this path, you should be able to answer the following:

- What kind of platform is ARCORIS?
- Which problem space does it address well?
- What are its intended goals and deliberate non-goals?
- What are the major concepts required to understand it accurately?
- How is the system divided at a high level?
- What are the major flows and control concerns?
- Is the system model compatible with the environment or use case I care about?

If these questions are still unclear after finishing this path, the next step is usually not more detail but a return to the overview and concepts layers to confirm the baseline.

## What to read next after evaluation

Once the evaluation baseline is clear, continue based on your next goal:

- go to [For Integrators](for-integrators.md) if you want to understand how ARCORIS fits into external systems and interfaces;
- go to [For Operators](for-operators.md) if you want to understand runtime shape, observability, and operational concerns;
- go to [For Contributors](for-contributors.md) if you want to prepare for structured changes to code or documentation;
- go to [Tutorials](../tutorials/index.md) if you want practical first steps after the conceptual baseline is established.

## Fast path summary

If you want the shortest serious evaluation route, use this order:

1. [Overview](../overview/index.md)
2. [Concepts](../concepts/index.md)
3. [Architecture](../architecture/index.md)
4. [Reference](../reference/index.md), only as needed

## Next step

Start with [Overview](../overview/index.md).

If you need a different route instead, return to [Start Here](index.md).
