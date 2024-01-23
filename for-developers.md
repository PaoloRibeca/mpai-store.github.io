---
layout: page
title: For developers
---

# For developers

Are you a developer of AI applications? [MPAI](https://mpai.community) standards allow you to develop modular AI applications and their components in a well-defined, interoperable, and robust way. Applications are defined as _AI workflows_ (AIWs) composed of interconnected _AI modules_ (AIMs); they are run inside standard execution orchestrators called _AI frameworks_ (AIFs).

## The MPAI AI Framework reference model

![The MPAI AIF reference model](https://mpai.store/assets/img/MPAI-AIF V2.png)

## Features

In principle, AI Modules do not need to run on the same hardware/software platform as that of the AI Framework; remote execution hosted by other orchestrators is provided for by communication through specified interfaces. AI Modules are interoperable, i.e., an AI Module with a defined function and interface can be replaced by a different implementation having the same function and interface and possibly different performance. AI Frameworks natively interface with the MPAI Store and its catalogue of AI Workflows and Modules, providing access to validated software components.

The implementation mechanism for AI Modules allows developers to abstract from the development environment and provide interoperable implementations running on a variety of hardware/software platforms. For instance, a module might be implemented as software running on different classes of systems, from MCUs to HPCs, or as a hardware component, or as a hybrid hardware-software solution.

The resulting system offers a range of desirable high-level features. For instance:
1. AI Workflows are executed in local and distributed Zero-Trust architectures, and AI Frameworks can provide access to a number of Trusted Services
2. AI Frameworks can interact with other orchestrators operating in proximity
3. AI Frameworks expose a rich set of APIs, for instance offering direct support for machine learning functionalities and optional support for security services.

## Distributing your applications through the MPAI Store

MPAI has appointed the MPAI Store as the official distributor of MPAI-compliant implementations.

Informally speaking, the MPAI AIF standard envisages for software three possible levels, in increasing order of compliance:
1. Being an application that can be run in an implementation of the AI Framework
2. Being the implementation of an official MPAI application standard
3. Being a level 2 implementation that has passed additional quality tests.

The first step towards distributing your application as an MPAI-compliant AI Workflow or Module is to [request an Implementer ID](https://mpai.store/how-to-register) from the MPAI Store. Once that has been obtained, you will be able to upload your software to the MPAI Store. The MPAI Store will then test the application for conformity with the relevant standard and check its security. After that, your software will be made available according to one among a number of possible distribution models.

## Would you like to know more?

More information and a complete definition of the MPAI AI Framework reference model can be found in the [MPAI AIF standard](https://mpai.community/standards/mpai-aif/https://mpai.community/standards/mpai-aif/).

