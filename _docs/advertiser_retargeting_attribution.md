---
title: Advertiser Retargeting and Attribution
subtitle: Retargeting and attribution are fundamental components of any advertiser campaign life-cycle. Advertisers know when and how to retarget individuals with the same campaign, balancing exposure with exhaustion. Advertisers must be able to measure whether, and how, advertising campaigns have resulted in purchases. Attribution is critical component of any successful advertising campaign.
tags: [Experience]
author: Blogger colour blue
---

### <span style="color: #e81313"></span>

### Retargeting and Attribution

Every interaction requires a new DID, helping to maintain user pseudonymity. But advertisers need to be able to identify whether the inventory they are bidding for offers an opportunity for retargeting, where they serve an add to an individual who has recently seen one of their ads. Retargeting is an important tool. It helps advertisers strike the right balance between re-enforcing a message and irritating consumers.

By allowing advertisers to pay for attribution, each impression will result in a hash of the user DID and the campaign ID. The attribution ID is stored on chain, as an immutable record, and in the user’s and advertiser’s DWNs. To access the attribution ID, advertisers must deposit both attribution and completion deposits via an on chain smart contract. Different attribution periods are available, up to a maximum of 30 days. This process can be automated with deposits paid as soon as the advertiser bid has been accepted (via whatever advertising exchange has processed and won the ad).

For a maximum of 30 days, every user online interaction, using OwnYou, will include the attribution hash in the JWT. Advertisers can delegate attribution subscriptions to their DSPs, as well as the storage of attribution hashes, for performance benefits.

{% include image.html img="attribution_hash_multiple.jpg" lightbox="true" alt="Attribution Hashes" caption="Attribution hashes resulting from multiple impressions of the same campaign." %}

### Sharing personal data should be transactional

Within the OwnYou ecosystem, personal data and any related attribution and completion data is transactional. This is a subtle but important point. Every existing advertising technology platform is trying to figure out how to protect user privacy. Let us deconstruct what that means. User data is harvested by advertising technology platforms. That data drives which ads the user is served. Advertisers need to understand which campaigns are successful but, to do that effectively, they need to track the user’s behaviour. In summary, data is harvested, users are served, users need to be tracked. Compare that to the OwnYou’s advertising cycle; individuals sell their pseudonymous data in exchange for access to publisher content. If they want to earn money, they can sell their attribution and completion data to advertisers, while remaining pseudonymous. This is transactional. They are willingly, in exchange for compensation, and with full visibility and control, to exchange their attribution and completion data for compensation.

With the deprecation of third-party cookies, advertisers can no longer track users. Advertising platforms are innovating, with various combinations of differential privacy and multi-party computation, to provide some level of reporting so that advertisers can measure ROAS. The digital advertising industry cannot agree on any single path forward. Apple is using privacy to forge a new role for themselves, in the online advertising space, with considerably revenue opportunities. Regulators have a spotlight on Google to make sure they do not abuse their dominant market position. Meta is having to navigate increasingly restrictive platforms. It is very messy. OwnYou’s approach is simple. Pay the individual. Make the entire advertising cycle one of user control rather than consent. Stop harvesting people. Stop trying to plug the privacy dam with complicated, and often inferior, work arounds.

There is a risk that DSPs, or any other delegated third party, could link an initial DID-JWT attribution hash to every subsequent new DID that includes that attribution ID. Every time the attribution ID is shared, a third party will be able to link that information back to the original DID and the related user demographics and target audience profile. While that might be true, there is not much a third party can do with that information outside of the OwnYou ecosystem. In other words, the original DID is ephemeral. It will never be used twice. A curious but honest actor might be able see what an individual DID was interested in, but they won’t be able to forecast the associate individual turns up next, and with what DID. They can’t monetise the future without paying the individual and all other stakeholders.

There are several other considerations; the terms and agreement for using OwnYou will make it clear that the storage of DIDs, and any associate personal data, is strictly prohibited and prosecutable by law. Also, while the demographic details might be more permanent, target audience profiles will change over time and the information has a limited shelf life.

### Retargeting and attribution workflows

- Attribution Hashes are created by all DSPs/Advertisers and passed back with the winning bids.
- This allows advertisers to track both successful bids, and unsuccessful bids.
- It also allows individuals to Monetise both successful bids and unsuccessful bids.
- Advertisers must deposit attribution payments using the user’s one-time blockchain address (created at the same time the ephemeral DID is created).
- Attribution Hashes are paired with the advertiser’s public key. Only attribution hashes with payment reconciliation are release in subsequent interactions.

{% include image.html img="retargeting.jpg" lightbox="true" alt="Retargeting Workflow" caption="Retargeting Workflow." %}

{% include image.html img="attribution.jpg" lightbox="true" alt="Attribution Workflow" caption="Attribution Workflow." %}
