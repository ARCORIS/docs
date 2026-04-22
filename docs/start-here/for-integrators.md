<div align="center">

# For Integrators

**Integration-oriented reading path for understanding how ARCORIS fits into surrounding systems.**

[![Start Here](https://img.shields.io/badge/Start-Start%20Here%20Index-0F766E?style=flat)](index.md)
[![Docs Home](https://img.shields.io/badge/Docs-Documentation%20Index-1D4ED8?style=flat)](../index.md)

System boundaries · Interfaces · Protocols · Flows · Integration fit

**Start with:** [Overview](../overview/index.md) · [Concepts](../concepts/index.md) · [Architecture](../architecture/index.md) · [Reference](../reference/index.md)

</div>

---

## Purpose

This page is the **integration-oriented entry path** for ARCORIS documentation.

Use it when your primary goal is to understand how ARCORIS connects to surrounding systems, where its boundaries are, how requests and workloads move through the platform, and which documentation layers matter before interface-level or deployment-level integration work begins.

This path is designed to help you build a correct integration baseline before you move into detailed configuration, protocol usage, or environment-specific implementation work.

## When to use this path

Choose this path if you are trying to answer questions such as:

- How does ARCORIS fit into a broader technical environment?
- Where are the major system boundaries?
- Which parts of the system matter for external integration?
- How do requests, workloads, and state move through the platform?
- Which documentation layers should I read before touching interfaces, protocols, or integration-specific guides?

If your primary goal is system evaluation, runtime operations, or making changes to the project itself, another path will be more appropriate.

## What this path is for

This path is for readers who need a **system-level integration baseline** before they work with concrete interfaces or deployment-specific material.

A good outcome of this path is that you can explain, in your own words:

- what role ARCORIS plays in a larger system;
- where its major planes and boundaries are;
- how requests, workloads, and state move across those boundaries;
- which concepts are required to understand integration points correctly;
- which later sections are relevant for protocols, reference material, security, and practical integration work.

## What this path is not for

This path is not optimized for:

- detailed configuration instructions;
- deployment recipes or environment-specific setup;
- operational runbooks and incident procedures;
- contribution workflow or engineering process rules;
- full protocol or interface reference consumed in isolation from system context.

Those topics belong in later documentation layers after the integration baseline is clear.

## Recommended reading path

Use the following sequence.

### 1. Establish system fit and scope

Start with [Overview](../overview/index.md).

The overview layer should help you understand:

- what ARCORIS is;
- what problem space it addresses;
- what kinds of use cases it is intended for;
- which assumptions and constraints shape the system boundary.

For integration work, this matters because interface and protocol decisions only make sense once the system scope is clear.

### 2. Build the conceptual model needed for integration

Continue to [Concepts](../concepts/index.md).

The concepts layer should help you understand the language and system behavior that integration work depends on, especially around:

- distributed-system boundaries;
- membership and discovery;
- state propagation;
- execution control;
- workload behavior;
- observability and security models.

Read this layer before deep architecture if you want the architectural material to be easier to interpret in integration terms.

### 3. Understand the structural boundary of the platform

Continue to [Architecture](../architecture/index.md).

The architecture layer should help you evaluate:

- the overall system boundary;
- major planes and components;
- control loops and system coordination;
- request and workload flows;
- where external systems are likely to connect to ARCORIS and where they are not.

For integrators, this is the layer that turns conceptual understanding into structural understanding.

### 4. Use stable technical material as needed

Continue to [Reference](../reference/index.md) when you need stable terminology or technical reference support.

Use reference material to clarify:

- terminology through the [Glossary](../reference/glossary.md);
- interfaces, protocols, configuration, logs, traces, and metrics as those areas become relevant to your integration work.

Reference should support the integration path, not replace the system and architectural baseline that must come first.

### 5. Move to practical material only after the baseline is clear

Once the integration baseline is established, continue to:

- [Guides](../guides/index.md), especially integration- and configuration-oriented material;
- [Security](../security/index.md) for deployment-facing and integration-facing security concerns;
- [Tutorials](../tutorials/index.md) if you need runnable first steps or practical examples before deeper integration work.

## Integration questions this path should answer

By the end of this path, you should be able to answer the following:

- What role does ARCORIS play in a larger technical environment?
- Where are the major system boundaries that matter for integration?
- Which concepts are necessary to interpret integration-relevant architecture correctly?
- How do requests, workloads, and state move through the platform?
- Which later documentation layers matter for interfaces, protocols, configuration, and security?
- What should be understood before beginning concrete integration work?

If these questions are still unclear after finishing this path, the next step is usually not more reference material but a return to the overview, concepts, and architecture layers to confirm the baseline.

## What to read next after integration baseline

Once the integration baseline is clear, continue based on your next goal:

- go to [Guides](../guides/index.md) for task-oriented documentation;
- go to [Reference](../reference/index.md) for interfaces, protocols, and other stable technical material;
- go to [Security](../security/index.md) if integration work depends on transport security, authn/authz, or deployment hardening concerns;
- go to [For Operators](for-operators.md) if your next concern is runtime operation and support in a real environment;
- go to [For Contributors](for-contributors.md) if you plan to make structured changes to the system or its documentation.

## Fast path summary

If you want the shortest serious integration route, use this order:

1. [Overview](../overview/index.md)
2. [Concepts](../concepts/index.md)
3. [Architecture](../architecture/index.md)
4. [Reference](../reference/index.md), as needed
5. [Guides](../guides/index.md) and [Security](../security/index.md), as needed

## Next step

Start with [Overview](../overview/index.md).

If you need a different route instead, return to [Start Here](index.md).
