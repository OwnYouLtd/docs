---
title: Design Goals
subtitle: OwnYou has some fundamental design principles that form the bedrock of everything we want to achieve. There is always room for discussion but the bar for change is set high.
tags: [Experience]
author: Blogger colour blue
---

<a id="top"></a>

### Goals and principles

{:.no_toc}

- TOC
{:toc}
<!-- -->

### Always decentralized

We do not want to replace walled gardens, and dominant personal data aggregators, with another centrally managed entity. Everything we do must either start off decentralized, or have clear path towards decentralization. <a href="#"><i class="fas fa-angle-up"></i> </a>

### Always equitable

Interests of all stakeholders must be carefully balanced to ensure long term sustainability. <a href="#"><i class="fas fa-angle-up"></i> </a>

### Control, not just consent

Whether data is volunteered, observed, or inferred, the user must always retain visibility and control over how their data is used and by whom. Both consent and control are mandatory requirements. Consent is nice but ultimately meaningless without control. <a href="#"><i class="fas fa-angle-up"></i> </a>

### Capturing real data, on real people, is important and useful

Traditional programmatic advertising has relied on data harvesting and the stitching together of data points from different sources, resulting in low quality probabilistic models. We want to provide deterministic data points that accurately describe demographic characteristics from verifiable sources (passport, driving license etc). Target audience profiles derived using probabilistic models based on actual consumer data complement factual demographic data. <a href="#"><i class="fas fa-angle-up"></i> </a>

### Personal data must be verifiably authentic

User volunteered data is less useful. Self-labellingis unreliable, prone to fraud and seldom accurate. Verified data is expensive but much higher quality. The current advertising technology stack is beset by fraud. Instead, if an OwnYou user shares their information, the advertiser can be confident the impression is real, and any decision on whether to advertise to the user can be based on facts rather than estimates. OwnYou personal data is always verifiable. <a href="#"><i class="fas fa-angle-up"></i> </a>

### Consumers should have the right to share their data while remaining pseudonymous

The more substantial the consumer advertiser relationship, the more likely the individual user will want to share their personal information. Ultimately, a purchase of a good or service will, in most cases, reveal personally identifiable information (shipping address, payment details etc). We want to provide opportunities for people to share their personal data with advertisers in a way that minimizes the opportunity for third parties to build longer lasting profiles that can be used without their consent. We want to make it possible for users to share their personal profiles without the advertiser learnings more than the individual wants to share. In extremis, it should be possible for individuals to share some personal data (gender, age and broad geolocation) without revealing anything else about themselves. That information is still useful to advertisers and marginally intrusive to the consumer, especially if it can only be used to serve ads over a specific session. <a href="#"><i class="fas fa-angle-up"></i> </a>

### Leverage the existing advertising technology stack

Most alternative approaches to personal data suggest a completely new direction. Whether that be a new decentralised marketplace for connecting advertisers with consumers, or new attention tokens that help compensate publishers more fairly. While we think those are laudable ultimate objectives, embedding a new and novel approach to personal data into the existing advertising technology infrastructure maximizes the probability of early adoption. We want to disrupt, but we also want to minimize the barrier to adoption. <a href="#"><i class="fas fa-angle-up"></i> </a>

### First-party data should not be commingled with OwnYou personal data

Sometimes, personal data is volunteered through a registration or subscription process, but often data is gathered through online and offline customers purchases. First party data is often prized above all other sources, given the relevance to the advertiser’s business and customer privacy waivers. Advertisers will often upload their first-party data onto third-party platforms, in the search for similar audiences. Leveraging personal data that relies on a customer privacy waiver is ultimately unsustainable. Helping advertisers leverage this data in an OwnYou context is challenging. Publishers will not be allowed to store OwnYou data, nor commingle data with their first party data. All OwnYou advertising transactions will need to be discrete, using only data provided by OwnYou. Above all, OwnYou will always prioritise user privacy and user needs. <a href="#"><i class="fas fa-angle-up"></i> </a>

### Minimize correlation risk

Helping users share data their personal data with advertisers necessarily increases data correlation risk. Even with a relatively few data points, advertisers may be able to match their first-party profiles with the profile offered by a pseudonymous OwnYou user. The more data shared, and the more granular the data shared, the higher the risk of correlation. This matters because other than the loss of privacy, we have to consider the loss of value to the consumer. Once the brand has the additional profile data then why should they pay for future interactions? We address this with two approaches; first we use one-time DIDs for each session, define by media interaction; for instance, a new DID for each time a user logs onto a website using OwnYou. Second, we share no personally identifiable information; no email address, IP address, or any other ID that might link the profile to an existing third-party data base. Every share is a unique share, with a unique DID, specific to the user’s engagement with the publisher. Thirdly, no other ID, either first party or third party, can be used in tandem with an OwnYou ID. This is not infallible, we appreciate that. Our goal is not to promise perpetual anonymity, but to help users protect their privacy while monetizing their personal data. Ours in an endeavour to strike a better balance with a more equitable outcome for users. The science is pretty unambiguous; the smallest amount of personal data shared can be correlated with third party personal data stores to build a customer profile. We will need to rely, in part, on legislation to protect human privacy rights. This is true for any system that manages personal data. <a href="#"><i class="fas fa-angle-up"></i> </a>

### Help individuals manage their privacy risk, according to their risk tolerance

By allowing users to customize granularity, and by educating them on the risk vs reward of sharing data, we expect to help users optimise for their preferred mix. At the extreme privacy end of the spectrum, users can share only very high level demographics (gender, year born) and at the extreme monetisation end of the spectrum, they can share their target audience preferences, their geolocation and their verified income bracket. <a href="#"><i class="fas fa-angle-up"></i> </a>

### Minimize leakage

We want to allow users to make the most of their personal data. Granting access to machine learning experts, which we enable through the intelligence stack, can help users mine their own personal data for value that can then either be sold or exchanged for content and services. Privacy preserving machine learning (PPML) is a fundamental requirement but personal data leakage should be contained. Personally identifiable information must not be leaked in training-sets, queries or predictions (i.e. target audience profiles).
<a href="#"><i class="fas fa-angle-up"></i> </a>
