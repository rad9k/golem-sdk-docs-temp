---
description: The provider actor in the Golem
---

# Provider

## What is a provider?

Technically speaking, a provider agent is a specific piece of code running on an Internet-connected device. The code implements the Golem network protocol, thus the machine running it acts as an actor in Golem. 

The characteristic that describes the provider agent is the fact of sharing hardware resources to the Golem network. In practice, almost any computer might act as a provider. It can be a laptop, desktop, or a server machine. The particular resource details \(for example, the number of CPUs or its memory limit\) that are subject to sharing can be configured by the hardware owner.

{% hint style="info" %}
We make the provider binaries available as a pre-built Linux installation package. You do not need to perform any development or extensive configuration to have a Golem provider up and running on your Linux machine.
{% endhint %}

## What does a provider do?

1. The provider announces the availability of its resources in the decentralized market. This announcement is called an offer.
2. The decentralized market performs the matching between provider side offers and requestor side demands.
3. If there is a requestor willing to use the provider's resources, the transaction is arranged.
4. The resources are used by the requestor \(for example by transferring input/output files and running a particular docker container on the provider's hardware\).
5. The provider bills the requestor.
6. The requestor performs an [ethereum](https://ethereum.org/) payment for resource usage.

## How can I benefit from running the provider on my machine?

After installing and running the Golem provider you will benefit in the following way:

* serving other actors in the Golem network that are in need of IT resources with your hardware that is currently not in use
* receiving payments for the resources you share

{% hint style="info" %}
The payments are performed through [Ethereum](https://ethereum.org/), so the whole process is very simple!
{% endhint %}

The typical resource usage scenario is as follows: after receiving the input data, the processing is performed by your machine. Next, the output data is sent back to the requestor and the payment is executed through [Ethereum](https://ethereum.org/). 

It is that simple.

![](../.gitbook/assets/tnm-docs-infographics-02.jpg)

## How I can become a Golem provider?

Becoming a Golem network provider is open to anyone. The installation and configuration are simple and straightforward. The details are described in the:

{% page-ref page="../provider-tutorials/provider-tutorial.md" %}



