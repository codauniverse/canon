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

# The System

The System is a decentralized, [hard-coded](../../../overview/science-and-tech/hard-code.md) infrastructure that handles power, economic transactions, communication, and coordination within and between [districts](districts.md).

After [GATA](../) began transitioning its districts to The System, there was a significant decrease in violence, political instability, mental and physical disease, and other social issues.

This transformation led to operational efficiencies that produced surpluses called [Yield](yield.md), which could be distributed to citizens, marking what is now called "The First Light of the New Dawn." The System is responsible for calculating and distributing Yield to GATA’s citizens.

The System’s concerns are sometimes referred to as the 3 R’s: Resources, Risk, and Rights.

### Technical Description

Under the hood, The System is an advanced, distributed state machine operating on a network of [hardcode](../../../overview/science-and-tech/hard-code.md) nodes and clients designed by [Systema](../enterprise/systema.md) using the [Asimov-complete](../../../overview/science-and-tech/asimovian-architecture.md) programming language, [LMNL](../../../overview/science-and-tech/hard-code.md#lmnl). [System Nodes](the-system.md#system-nodes) are large, facility-sized computers that house extremely secure, purpose-built [COGs](../../../overview/science-and-tech/cogs.md), capable of managing and enforcing the operation of GATA.

Most interaction with The System is done through the [System Terminals](the-system.md#system-terminals) that can be found throughout GATA's [districts](districts.md).

***

<figure><img src="../../../.gitbook/assets/system.png" alt="" width="563"><figcaption><p>Control terminals inside of a System Node.</p></figcaption></figure>

## System Terminals

System Terminals can be found ubiquitously across GATA’s districts. System Terminals are used by citizens to do things like send messages, search the [General Record](the-general-record.md), download information, withdraw and deposit funds, perform legal transactions, collect Yield, alert local authorities, and vote in the [Third Quorum](governance.md#the-third-quorum). Use of System Terminals requires valid [citizenship keys](keys.md#citizenship-keys).

System Terminals are not themselves computers; they are merely windows into The System’s distributed virtual computer. Personal interfaces like [slates](../../../overview/science-and-tech/slates.md) and [links](../../../overview/science-and-tech/links.md) can be synchronized with terminals allowing for remote access while within close range.

***

<figure><img src="../../../.gitbook/assets/districts.png" alt="" width="563"><figcaption></figcaption></figure>

## **System Nodes**

The System is secured by System Nodes, which are large, [Asimovian](../../../overview/science-and-tech/asimovian-architecture.md) compute facilities that maintain the state for GATA’s global operations.

System Nodes are heavily restricted COGs ([hard-coded](../../../overview/science-and-tech/hard-code.md) cognitive platforms) that handle power, economic transactions, communication, and coordination within and between districts.

Each district has at least two “full nodes”, which are owned and maintained by the district’s local government. The [System Terminals](the-system.md#system-terminals) found across GATA’s districts are all connected to public [endpoints](../../../overview/science-and-tech/endpoints.md) that connect to their local full nodes.

### Enterprise Nodes

Additionally, large [enterprises](../enterprise/) with a significant share of traffic on the network are required to build and maintain their own full nodes.

All licensed enterprises have their own private System endpoints that allow them to coordinate their operations globally and report their activity in real-time, in accordance with the [NDA](the-new-dawn-accords.md).

***

## **System Sensors**

The System also utilizes an array of sensors developed by WILD and installed by [Systema](../enterprise/systema.md)'s [Infrastructure & Maintenance department](../enterprise/systema.md#departments). These sensors are installed in districts, as well as in discrete remote locations around the world.&#x20;

These arrays provide real-time insight into things like climate, microbial health, biodiversity, migratory patterns, and other signals that can be factored into The System’s calculations.

It has been claimed by some that the [Angelis](../military-and-defense/angelis.md) [Intelligence Division](../military-and-defense/angelis.md#watchers) has direct access to this sensor information, however no evidence of this exists. This would be a direct contravention of [NDA](the-new-dawn-accords.md) and [WPP](../institutions/atlan-information-control-aic.md#whole-privacy-protection-act) law.

\
