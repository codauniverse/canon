---
layout:
  title:
    visible: true
  description:
    visible: false
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: true
---

# Asimovian Architecture

<figure><img src="../../.gitbook/assets/nomoney420_a_diagram_of_a_flow_chart_showing_information_being__56bb1857-1b70-46a0-9bd3-839123e03673.png" alt=""><figcaption><p>An ontology graph mapping an Asimovian system.</p></figcaption></figure>

## Overview

An Asimovian system is a computational system that is designed in such a way that it is immune to corruption and cannot exhibit unpredictable behavior. One of the key tenets of Asimovian architecture is that you should be able to look at a system’s hardware and know exactly what kind of behaviors it can express. These tangible, auditable computers would require ‘physical functions’—computational logic that is fully “physicalized” and unchangeable. This constraint led to the advent of “[hard code](hard-code.md)” and new programming languages like [LMNL](hard-code.md#lmnl).

***

## **Ontology Design**

A branch of Asimovian research focused on creating safe ontological manifolds for computation.

An ontological manifold is a symbolic domain of possible calculations. If you were to build a simple calculator, it would require a much smaller ontological manifold and fewer hard-coded modules. When building [COGs](cogs.md), more advanced cognitive systems, the ontological manifold of each module and the system as a whole must be very carefully considered.

The most essential tool in the ontology design toolkit is [the filter module](asimovian-architecture.md#filter-modules). Filters are ubiquitous, found in just about every piece of legal technology around the world, especially in [the Free Territories](../../nations/free-territories/) where filters are particularly essential given the endemic [Daemon virus](the-daemon-virus.md).

### **Filter Modules**

Asimovian architecture notably introduces ‘filter modules' that scrub information passed between modules in a hard coded program. This effectively prunes a system’s ‘perception’ of reality and limits its range of behavior. Filters make it so that certain information or operations are not able to exist within a given system, and are an essential tool in ontology design.

Asimovian filters are especially important for the safe operation of cogs (cognitive systems). Filters make it so that certain truths are unthinkable and certain behaviors are inexpressible for cogs. Roughly 95% of the volume of modern cog architecture is dedicated to filter hard code.

#### **Understanding Filter Modules**

Filter modules are hard-coded “physical functions” written in LMNL that filter information flowing through a system. A filter could modify all information passing through it such that 1 is equal to 2, 2 is equal to 4 and so on. If you were to ask that system what 1 plus 1 is, it would answer 8. You would then know that it meant to say 4, and that the input was not 2, but 1. Filters ensure that nodes can only access the desired information, and express desired ranges of behavior.
