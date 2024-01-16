---
layout: page
title: For developers
---

# For developers

Are you a developer of AI applications? [MPAI](https://mpai.community) standards allow you to develop modular AI applications and their components in an well-defined, interoperable, and robust way. Applications are defined as _AI workflows_ (AIWs) composed of interconnected _AI modules_ (AIMs); they are run inside standard execution orchestrators called _AI frameworks_ (AIFs).

![The MPAI AIF reference model](https://mpai.store/assets/img/MPAI-AIF V2.png)
* The MPAI AI Framework reference model. *

In principle, AI Modules do not need to run on the same hardware/software platform as that of the AI Framework; remote execution hosted by other orchestrators is provided for by communication through specified interfaces. AI Modules are interoperable, i.e., an AI Module with a defined function and interface can be replaced by a different implementation having the same function and interface and possibly different performance. AI Frameworks natively interface with the MPAI Store and its catalogue of AI Workflows and Modules, providing access to validated software components.

The implementation mechanism for AI Modules allows developers to abstract from the development environment and provide interoperable implementations running on a variety of hardware/software platforms. For instance, a module might be implemented as software running on different classes of systems, from MCUs to HPCs, or as a hardware component, or as a hybrid hardware-software solution.

The resulting system offers a range of desirable high-level features. For instance:
1. AI Workflows are executed in local and distributed Zero-Trust architectures, and AI Frameworks can provide access to a number of Trusted Services
2. AI Frameworks can interact with other Frameworks operating in proximity
3. AI Frameworks expose a rich set of APIs, for instance offering direct support for machine learning functionalities and optional support for security services.


