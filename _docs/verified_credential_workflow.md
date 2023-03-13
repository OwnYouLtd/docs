---
title: Verified Credential Workflow
subtitle:
tags: [Experience]
author: Blogger One
---

### <span style="color: #e81313"></span>

#### Verified Credentials

The verified credential data model provides OwnYou with an efficient and secure way to prove to publishers, and ultimately advertisers, they are transacting with real human beings, with authentic credentials. Physical credentials include common forms of identification, like a passport or a driver’s license. We expect both to have digital corollaries that leverage the verified credential data model. Most, if not all, of an individual’s demographic data will be captured in a digital version of passport or driver’s license and while we do expect those to materialize, eventually, we cannot wait for global government execution. In the meantime, we will need to rely on independent commercial issuers who verify physical credentials, capture the credentials and then issue verified credentials. While this will come at a cost, the technology is advancing sufficiently quickly, with a critical mass of competition, suggesting prices will continue fall.

The verified credential data model is a universal format that provides the means for any issuing entity to create a credential for any subject that can then be presented to a verifier, by a holder. In our case, the subject and the holder are the same entity; an individual. The verifier can, without having to contact the issuer directly, confirm the credential has not been tampered with, the credential is authentic, and that it has been issued by the issuer.

### Target audience date might be considered a Verified Credential

In addition to demographic data, we also consider target audience information a credential. The entity creating the target audience profile, as part of the intelligence stack, will release the information as a verified credential, allowing advertisers to verify provenance and allowing the issuer to develop a reputation. Ultimately this is what a verifiable credential does so well; it ties the claim, “this person likes red shoes”, to a specific issuer and a specific subject, cryptographically. This makes it easy for advertiser to assess whether the claim is from a reputable source, that it belongs to the individual presenting it, and that it has not been tampered with.

### Privacy preserving Verified Credentials

Providing publishers and advertisers with authentic, verifiable, information on individuals is not enough. It must be possible for the holder of the verified credential to remain anonymous. The individual’s privacy is sacrosanct. A user may choose to provide personally identifiable information, but it must never be leaked unintentionally. This requires more than pseudonymization. We must make sure publishers and advertisers cannot use the credential as a correlating factor, linking the pseudonymous ID to personally identifying information, thereby revealing the identity of the individual. Equally, we must ensure that the information revealed with an ID cannot be used by a verifier to build a user profile for future use. We must make sure the verified presentation, or proof, conveys no additional knowledge other that what we need to convey; the individual’s demographics, their target audience profile and whatever other information the individual wants to share.

### OwnYou's basic Verified Credential workflow

Verified Credentials are used to authenticate demographic data, ensuring only “real” people share real profiles. There are multiple sources of verified credentials from government issuers to commercial providers. OwnYou will make it easy for users to find a new provider to authenticate their physical documents, thereby creating a new verified credential, and we will make it easy for users to import their existing verified credentials from other digital wallets. The more descriptive the credential, the more valuable it becomes within the advertising workflow. Verified demographics are important to advertisers.

Once the credential has been uploaded to the user’s OwnYou digital wallet, it can be used to authenticate the user in the OwnYou sign-on process. Zero-knowledge proofs are created to facilitate age verification and for privacy preserving authentication. Publishers use the following workflow to check the user is authentic, and their demographics credible. For more information on Verified Credentials, see the W3C/DIF data model.

{% include image.html img="vc_process.jpg" lightbox="true" alt="Verified Credential Process" caption="OwnYou Verified Credential process." %}

<!-- This sounds reasonably close to what Zero Knowledge Proofs offer.

“Zero-knowledge proofs are defined as those proofs that convey no additional knowledge other than the correctness of the proposition in question.”
But before we dig into Zero Knowledge Proofs, of ZKPs, we need to discuss the verified credential data model in a little more detail, including how we construct verified presentations. -->
