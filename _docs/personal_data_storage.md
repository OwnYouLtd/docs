---
title: Personal Data Storage
subtitle: There is a quiet revolution afoot in the way we think about data storage. Like much of the self-sovereign movement, storage lacks the hype of NFTs and crypto tokens. But underlying every single digital experience lies storage architecture.
tags: [Experience]
author: Blogger One
---

### <span style="color: #e81313"></span>

There are two OwnYou storage requirements:

- Storing intelligent data, including target audience profiles and verified credentials, for the advertising technology stack, and other business use-cases (price comparison, easter-eggs etc).
- Storing large volumes of encrypted data for the Intelligence Stack (IS).

{% include image.html img="personal_data_storage.jpg" lightbox="true" alt="Personal data storage architecture" caption="Personal data storage architecture." %}

### Decentralized Storage

There is a quiet revolution afoot in the way we think about data storage. Like much of the self-sovereign movement, decentralized storage lacks the hype of NFTs and crypto tokens. But underlying every single digital experience lies storage architecture. Like most developments in the Web2 cycle, data storage gravitated towards centrally managed platforms, in concert with the transition toward cloud compute. Emerging with a broader exploration of decentralised ledger technology are various definitions, and implementations, of decentralised storage where access control is managed by the user and their agents.

Various standards are emerging from W3C and DIF (Decentralised Identity Foundation). While these standards are incomplete, and the number of commercial implementations small, what rises from these proposals, as they mature, will revolutionize the way we think about data storage. Fundamental to most decentralised storage is the concept of content addressing. Traditional storage is based on location; a piece of information has an index that tells whatever system needs it, where it exists. Content addressing takes a quite different approach. With content addressing, information is no longer tethered to a specific location but rather by what is in it, or by the content itself. IPFS, or the Inter-Planetary File System, takes a radically different approach to how content is stored across a decentralised distributed system. IPFS (including IPLD) allows us to break away from centrally managed data storage while improving security and censorship resistance. A detailed dive into IPFS, IPLD and emerging decentralised storage standards is out of scope. In any case, rather than an allegiance to any specific standard or technology, most important to the OwnYou is a breakaway from centrally managed control, ownership and censorship.

In keeping with W3C and DIF, we envisage two types of storage, [Decentralised Web Nodes](https://github.com/decentralized-identity/decentralized-web-node/blob/main/spec/spec.md) (DWN) and [Encrypted Data Vaults](https://identity.foundation/edv-spec/) (EDV).

### Decentralized Web Node (DWN)

DWNs are designed to share information with multiple entities and multiple applications, with replication across multiple devices, including on decentralised data storage solutions. User agents will pull target audience, and other advertising related data, from DWNs and, with the necessary encryption, share that information with the ad tech stack, via a publisher and their header bidding wrapper. DWNs are designed to work with DIDs. Typically, DWNs act as service endpoints for DIDs. They can be addressed within a DID document or as a DID-relative URL. See the Advertising Workflow and Technology Stack section for details.

### Encrypted Data Vaults (EDV)

EDVs store structured and unstructured personal data. Controllers (individuals and their agents) may grant access to the intelligence stack, but data must remain encrypted at all times. The normative requirement is for full encryption, at rest and during transport, of all user data. The client controls all encryption and access control. The innovation lies with how the data is indexed, while remaining encrypted, how authorization is managed, and how cryptography is used to manage access control. We will dig into how that data can be used by the intelligence stack without impacting privacy, or diluting user control. Rapidly developing frameworks for machine leaning while maintaining privacy include Federated Learning (FE), secure multiparty computation (SMPC) and homomorphic encryption (HE). We will discuss each technique in more detail in the Intelligence Stack section.

### Brand Zero Party Data (BZPD)

Users may grant businesses/advertisers direct CRUD (Create, Read, Update and Delete) access to EDV resources. The user retains control of which businesses can access their data. Data could be both general (for all businesses) and specific (unique to one business relationship). Brand Zero Party Data (BZPD) describes data created by brands related to a specific user, stored by the user. Rather than store personal data in advertiser databases, we make it easy for brands/advertisers to store all personal data with the consumer’s themselves, in their personal data vaults. It will be easy for brands to integrate with OwnYou encrypted personal data vaults (personal data hubs) and to retrieve that data quickly. Brands will be able to query user data across millions of distributed personal data vaults.
