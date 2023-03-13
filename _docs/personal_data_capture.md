---
title: Personal Data Capture
subtitle: Personal data is the life-blood of OwnYou. Personal data never leaves the individual's control, always stored safely, and only ever shared in a privacy preserving manner.
tags: [Experience]
author: Blogger One
---

### <span style="color: #e81313"></span>

{% include image.html img="connectors.jpg" lightbox="true" alt="Connectors" caption="Connectors help individual users consolidate their personal data. (Excerpt from section on the Individual User Experience, under experiences and workflows)." %}

### Types of personal data

Personal data is everywhere. Over the last thirty years, we have become used to sharing our email address for wifi access, our personal home address for access to digital content, and our telephone number for access to news. Pretty much any form of access requires some level of personal data. This will change. OwnYou hopes to be part of the change. We want to help individuals consolidate their data, super-charge it with [intelligence](/docs/docs/intelligence_stack), allowing them to harness its value. Broadly speaking, there are four different types of personal data:

#### Volunteered data (PII, Social Networks, emails, images etc)

- Volunteered data includes names, email address, date of birth, declared interest, social media content, photos, emails, bank records, credit score etc.
- All data remains under the sole control of the user. Only the user has access control.
- There is no centrally managed database.
- There is no co-ordinating party.
- Unverified structured data, for instance demographic data, cannot be used for advertising purposes. It is important we prevent fraud at the source. Allowing users to register and share un-verified demographic data is likely to lead to abuse and fraud.
- Unverified unstructured data, for instance emails or social media posts, has value but only when paired with verified structured data. It must be possible for the user’s agent to confirm unstructured data is related to verified data. This helps improve the data quality which benefits the overall ecosystem. Low quality data effects all stakeholders.

#### Verified Credentials

The World-Wide-Web Consortium (W3C) defines a Verified Credential (VC) as a “tamper-evident credential that has authorship that can be cryptographically verified”. A physical driver’s license is a credential issued by a trusted government body (for instance, in the UK, the DVLA). When we present our driver’s license, we can be confident the physical format will be recognisable. A verifier, for instance a police officer, can plug the details into a centrally managed system to verify the license’s authenticity. Verified Credentials use cryptography to prove authenticity to a verifier, without the verifier needing to either check a centrally managed system or check with the issuer. For instance, a policeman can verify the authenticity of a digital VC driver’s license by simply checking the digital signature is authentic. Cryptography is used to substantially improve both efficiency and security. OwnYou will use VCs for the following:

- Advertisers will be able to confirm volunteered user data comes from a human and is authentic.
- Verified Credentials will be used to help advertisers understand data provenance. This is especially important for Intelligent Data.
- Verified Credential can capture demographic information from credible sources.

#### Observed data

Observed Data includes historical browsing history, including behaviour on first-party domains but also historical browsing history on third-party domains, typically recorded by third-party cookies. Advertisers want to evaluate whether an individual fits into a particular target audience. Understanding which websites they have most recently visited, helps the advertiser build a profile. Understanding whether the user has been shown an ad, and the context (channel and time) also helps with retargeting. Generally speaking, as we have already discussed, this type of surveillance advertising is frowned upon. But what if the information was volunteered? Should an individual have an opportunity to share this information with potential advertisers, while maintaining pseudonymity, and with appropriate compensation, we expect individuals to share this information willingly. After all, if a consumer is interested in a brand, they may have visited the store, they may have visited various related website, would they not be more amenable to relevant advertising?

Apple and Firefox have banned third party cookies. Google will soon follow. This suggest that tracking user behaviour, with or without consent, will not be possible using third-party cookies. Facebook, and others, are using first-party cookies and pixels to circumvent tracking restrictions. We are now in a privacy arms race of sorts. How OwnYou allows users to track themselves is going to depend on whether first-party work around will persist. We suspect they won’t. Ultimately it is the intent of Apple’s anti-tracking policy that matters to Apple, not the letter. With this in mind, OwnYou will need to consider it’s own browser solution and how we navigate Apple’s increasingly restrictive WebKit browser engine.

#### Intelligent data

Intelligent Data results from an individual sharing structured and unstructured data with the intelligence stack. We will discuss the intelligence stack in more detail in the intelligence stack section. Intelligent data seeks to emulate sophisticated Google and Facebook user profiles that results from analysing unstructured data. The main difference is users do not have much choice with google and Facebook. If they want to enjoy the full service, then they need to share their data. And perhaps that is an equitable arrangement. OwnYou thinks that high quality insights on user needs and wants is valuable to appropriately matched brands and advertisers. Especially when the preference and time dimension are optimised. I am most willing to buy an umbrella when walking home from the train station. While I do not like the idea of Google tracking my every move and, when combined with my other user attributes and the local weather information, suggesting nearby umbrella deals, I might be more open to sharing that information myself. A change of power and control has a meaningful impact on what we are willing to share and with whom. Choosing to share your secret with someone is not the same as someone else sharing your secret, for their profit.

### Connectors

OwnYou will develop easy to use connectors that plug the user's [personal data vaults](/docs/docs/personal_data_storage) into the users personal data.
