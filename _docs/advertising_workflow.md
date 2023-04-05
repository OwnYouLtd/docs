---
title: Advertising Workflow
subtitle: Advertisers want to display their ads to the most relevant audience, for the best price. They need to know when advertising has been effective, and whether one creative is more engaging than another. Ultimately, advertisers want to know how to invest most effectively across all their campaigns.
tags: [Experience]
author: ""
---

{% include image.html img="ad_cycle.jpg" lightbox="true" alt="Advertising Cycle" caption="The OwnYou advertising cycle." %}

OwnYou provides advertisers with authentic demographic data and detailed target audience profiles, helping them access the right audiences. OwnYou provides the means for attribution and retargeting, with privacy preserving technologies that maintain resolution while minimizing correlation factors. Most important, OwnYou compensates stakeholders fairly and securely.

Every user login includes an automatic verification, to prove the traffic is authentic, and a Personal Data Payloads (PDPs) share. PDPs contain all the information the consumer is willing to share with the advertiser as well as a one-time identifier to facilitate payment and attribution. PDPs can, at the individual’s request, include information around recent domains visited as well as recent campaigns served, to facilitate remarketing and retargeting. The PDP is included in JSON web token (JWT), which is cryptographically signed to help prove authenticity.

<span style="color: #e81313">The following sections walk-through the advertising workflow, from user onboarding to ad rendering.</span>

### User signs up to OwnYou

The OwnYou onboarding process includes uploading unstructured data to their encrypted data vault and downloading an OwnYou digital wallet. For more details on the personal data capture, making data available to the intelligence stack, and creating new personal data storage, see the respective sections. Once the user has created a new account, they need to create, or download, their verified credentials.

### User sets up verified credentials

Verified Credentials are used to authenticate demographic data, ensuring only “real” people share real profiles. There are multiple sources of verified credentials from government issuers to commercial providers. OwnYou will make it easy for users to find a new provider to authenticate their physical documents, thereby creating a new verified credential, and we will make it easy for users to import their existing verified credentials from other digital wallets. The more descriptive the credential, the more valuable it becomes within the advertising workflow. Verified demographics are important to advertisers.

Once the credential has been uploaded to the user’s OwnYou digital wallet, it can be used to authenticate the user in the OwnYou sign-on process. Zero-knowledge proofs are created to facilitate age verification and for privacy preserving authentication. Publishers use the following workflow to check the user is authentic, and their demographics credible. For more information on Verified Credentials, see the W3C/DIF data model.

{% include image.html img="vc_process.jpg" lightbox="true" alt="Verified Credential Process" caption="OwnYou Verified Credential process." %}

### User signs-on to the publisher’s website

On visiting a publisher website, the user selects the OwnYou sign-in option. The user’s Wallet Agent pops up requesting the user’s permission to share a new pseudonymous identifier. At this point, the website operator can present terms and conditions for access to their domain, including any minimum personal data request (still anonymous), a request for micropayment, or subscription options. This is a bargain between the publisher and the user. A publisher will require the user share a minimum amount of data, without which the publisher cannot monetise the interaction. Publisher are encouraged to provide a minimum access tier.

Personal Data Payloads (PDPs) contain all the information the consumer is willing to share with the advertiser as well as a one-time identifier to facilitate payment and attribution. PDPs can, at the individuals request, include information around recent domains visited as well as recent campaigns served, to facilitate remarketing and retargeting.

{% include image.html img="pdp.jpg" lightbox="true" alt="Personal Data Payload" caption="Sharing Personal Data Payload." %}

### Using header bidding and integrating with the existing technology stack

Pseudonymous DIDs are always shared between users and publishers. DIDs form the basis for all capability-based access control to personal data, and they facilitate attribution and payment. Users can not share personally identifiable information (PII). The sharing of personal identifiers (name, email, telephone number etc) puts the user’s privacy at risk, will lead to correlation and personal data leakage, and should always be discouraged.
Users will be able to share pseudonymous personal data, with the following options:

- Key demographics, including verified credentials. Verified credentials are much more valuable to publishers or app developers, where advertising revenues are fundamental to their revenue-generating model. Verifying credential helps reduce fraud.
- Target audience data - any information derived from personal data that describes the user in terms of the IAB Tech Lab Audience Taxonomy. The IAB Tech Lab Audience Taxonomy provides a standardised way to describe segmented audiences across demographic, interest, and purchase intent attributes.
- Location flags - location data will not be shared but the user will invite media and application developers to leave location-based offers and services that only unlock on the user’s device when certain geolocation requirements are met.

### How does the user share data?

Structured personal data, including demographic information, verified credentials and target audience data, is stored in the user’s DWN. The user’s digital wallet includes an agent, permissioned with CRUD access. The agent handles publisher website logins and authentication. That process includes sharing personal data pseudonymously in exchange for access using ephemeral decentralised identifiers and JASON Web Tokens.

A JSON Web Token (JWT) is an open standard that defines a compact and self-contained way for parties to securely transmit information as a JSON object. The object is digitally signed allowing the receiver to verify the integrity of the claims within the token. In other words, it allows the publisher to share information with the advertisers, and for the advertiser to verify the information has not been tampered with. Furthermore, advertisers will be able to audit and verify any shared user credentials.

### How much personal data does the user share?

That is entirely up to the user, however different publishers will have differing minimum requirement, reflecting how the value their content. Our goal is to develop infrastructure that rewards users for sharing more detailed information with publishers, safely and securely, while ensuring data is authentic and reliable.

### Decentralized Identifiers

We use decentralised identifiers (DIDs) for pseudonymous identification, tying individuals to their data, creating the means for privacy preserving attribution and payment. Every publisher interaction leads requires a new DID. Only the user has access to their DID history and only the user can access their data sharing and income history in its entirety.

### Sharing Personal Data Payloads

- Individual sign-in with the OwnYou option, on the publisher website.
- The publisher requests a JTW, with the individual’s personal data payload.
- The individual’s wallet creates a new DID, registers the address on the blockchain, and shares the DID in the JTW personal data payload.
- The publisher includes the payload in the header bidder wrapper.
- The wrapper is is shared with multiple Ad Exchanges/SSP.
- The payload is encrypted with each Ad Exchanges public key.
- The Ad exchange decrypts the payload, sharing the information with advertisers
- Advertisers, or their DSPs, bid.
- Each bid results in an Attribution Hash.
- Winning bids result in ad server notifications, and the relevant ad is served and displayed.
- The user’s wallet registers the attribution hash, which is stored in the user decentralised web node.
- An Attribution Hash includes, as described in the figure below:
  - the user DID,
  - campaign ID,
  - the publisher ID,
  - the and a timestamp.

{% include image.html img="attribution_hash.jpg" lightbox="true" alt="The Composition of an Attribution Hash" caption="The composition of an attribution hash." %}
