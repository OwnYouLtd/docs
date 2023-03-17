---
title: What
subtitle: There are five main technology components to OwnYou. Viewed slightly differently, there are four layers to the technology stack. The sections on Experiences and Workflows, and Building Blocks, digs into each component in more detail.
tags: [Experience]
author: Nick
---

From an technology perspective, there are five main components to OwnYou:

1. The [Intelligence Stack](/docs/intelligence_stack/), which includes [personal data capture](/docs/personal_data_capture) and [storage](/docs/personal_data_storage). This suite of technologies allow individual users to store and control their raw data, while running third party machine learning algorithms to convert that data into intelligent profiles they can monetize.
2. [Verified credential protocols and workflows](/docs/verified_credential_workflow). OwnYou will not create identity Verified Credentials but instead it will interoperate with [Verified Credential Issuers](https://verifiablecredentials.dev/), making it easy for Individual users to store and present their credentials in a privacy preserving manner, as part of various business application workflows. OwnYou may use verified credential workflows to store and present attribution data for advertisers, which we describe in the section on [Advertising Workflows](/docs/advertising_workflow).
3. A [digital wallet](/docs/digital_wallet) connecting different entities and applications. The digital wallet stores all the user's DIDs, blockchain addresses, cryptographic material (keys) and provides the backbone for the [individual user experience](/docs/individual_user_experience). All business entity applications will also use digital wallets, albeit with different user experiences.
4. Applications that enable the [Advertising Workflow](/docs/advertising_workflow), [Dynamic Price Comparison](/docs/price_comparison_integration) and [Easter Egg Marketing](/docs/easter_eggs_marketing)
5. Infrastructure Service which support compute, storage and transaction validation.

### OwnYou's architecture

{% include image.html img="architecture_workflow_1.jpg" lightbox="true" alt="Architecture" caption="OwnYou high-level architecture." %}

### OwnYou's principle components

It might help to think about OwnYou as a number of layers.

- At the bottom, layer 1, lies the engine room - where data is stored, and where computing resources are deployed to convert raw data into valuable information, and where transactions are recorded on-chain.
- Layer 2 facilitates pseudonymous peer to peer communication, leveraging decentralized identifiers.
- Layer 3 is the protocol layer, which handles credential issuance and verification, payment, messaging and premissioning protocols for the Intelligence Stack.
- Layer 4 is the application layer, facilitating advertising workflows, dynamic price comparison and other applications.

{% include image.html img="ownyou_modules.png" lightbox="true" alt="Modules" caption="OwnYou architecture, leveraging components from Blockchains, Cryptography, Zero Knowledge Proofs and SSI." %}
