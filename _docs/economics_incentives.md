---
title: Economics and Incentives
subtitle: It must be easy for advertisers and publishers to transact with individuals, and the Intelligence Stack, while benefiting from the pseudonymity and performance offered by crypto payment rails.
tags: [Experience]
author: Blogger One
---

### <span style="color: #e81313"></span>

OwnYou is stablecoin agnostic. It must be easy for advertisers and publishers to transact with individuals, and the Intelligence Stack, while benefiting from the pseudonymity and performance offered by crypto payment rails.
Every interaction necessitates a new decentralised identifier (DID). That DID is paired with an address on a blockchain; for instance, Ethereum. There are several stablecoins that support ERC-20 addresses.

{% include image.html img="stablecoins.jpg" lightbox="true" alt="Stablecoins" caption="OwnYou uses both stablecoins and tokens." %}

### Stablecoins and tokens both play a role

Advertisers and publishers use stablecoins to compensate individuals for sharing their data, and the Intelligence Stack is compensated for adding value to that data.

Advertisers compensate the Intelligence Stack (IS) for adding value to personal data by creating accurate target audience profiles. Profiles are generated and issued with levels of confidence. Successful interaction, or interactions that result in specific user behaviour, for instance clicking on an ad or requesting information.

Individuals can choose to receive access to publisher content in lieu of payment. This means exchanging their personal advertising profile, including demographic and target audience data, in exchange for access to a publisher’s website. The publisher is then able to share this information in the bid-stream, providing advertisers with reliable and high-resolution information on the user’s demographics and interests. This information is included in the header bidding wrapper.

### Advertisers compensate individuals

Advertisers compensate individuals according to the quantum of information shared, and whether the desired outcome is met; whether the user clicks on the ad that is served, and whether a subsequent action is completed. There are three components to advertiser compensation; a fixed fee, a fee that varies according to the quantum and granularity of information shared, and a fee related to performance (the completion of an action). Fee structure, in order of value to the advertiser:

- Basic demographics (age, country of resistance).
- Advanced demographics (basic + income, region, ethnicity, level of education etc).
- Target audience profile (suggested, confirmed with successful interaction).
- Prior interactions (list of recently visited domains, with time stamps and frequency).
- Prior IDs (list of previously shared DIDs).

Actions are recorded by the individual and by the advertiser. For the advertisers to benefit from attribution, they much confirm and pay for actions. Failure to compensate individuals and the IS will result in censure and the forfeiture of custodied OwnYou tokens.

### Simple "cartoon" model

This is an aspirational cartoon model. Few models on prospective businesses, at this stage of development, are accurate. Rather than focus on the numbers themselves, we recommend a discussion around input trajectories, prior cases studies, and upside/downside factors. We use the model to explore how OwnYou might fit into the current display advertising landscape and how more accurate personal data, that truly reflects user needs and wants, drives higher advertiser ROIs and therefore merits higher CPMs.

{% include image.html img="business_model.jpg" lightbox="true" alt="Business - cartoon - model" caption="Simple -cartoon- model." %}

### Assumptions for user and publisher traction, the number of ads per site and the number of display ads viewed per day

{% include image.html img="user_behaviour.jpg" lightbox="true" alt="User Behaviour" caption="Assumptions for user and publisher traction." %}

Note that:

- TikTok was launched in 2017 and hit more than 1bn users 5 years later.
- Instagram was launched in 2010 and hit 400m daily active users by 2015.
- Facebook was launched in 2004 and hit 1.2bn users by 2009.
- The Brave browser was launched in January 2016, by 2017 they had 1.2m monthly active users. By 2018, 5.9m. That grew to 11.2m in 2019, 24.1m in 2020 and 50m in 2021.

We will provide a publisher specific SDK that makes it easy to implement the OwnYou login button, sets up a digital wallet for publishers to pay for personal data in stablecoins, and receive (and sell) OwnYou tokens. Publishers are an important actor in the OwnYou ecosystem and minimizing adoption hurdles is a priority. Wallets will have multi-sig capabilities, improving security and lowering key person risk.

While we appreciate digital wallet native applications are unfamiliar, the OwnYou’s value propositions and use cases, explored in the prior section on publisher incentives, will drive sustainable adoption. We assume a 1% penetration rate rises to 25% in a steady state.

We assume the average user visits 25 publisher domains a day, with 5 page views per domain. This leads to 125 pages views per day.

### Assumption for CPM, the click-through-rate and CPC.

The cost per thousand impressions (CPM), does not impact OwnYou directly. However, CPM rates are a function of demand and supply. The higher the quality of publisher inventory, the more they can charge for it. And quality is best described by advertiser return on investment (ROI); more effective audience targeting improves engagement and leads to higher sales. As we have already discussed - OwnYou offers real people, genuine demographic profiles, and reliable target audience profiles which makes finding the right target audience easier for advertisers and increases their propensity to spend. CPM only matters because we expect Personal Data CPM to be related to underlier publisher CPM. In other words, the amount of money publishers will be willing to pay for personal data (PD-CPM) will be directly correlated to the value that data generates through higher CPM rates.

{% include image.html img="cpc.jpg" lightbox="true" alt="User CPC" caption="Online Advertising Costs in 2021 - Topdraw Digital Marketing, June 2020" %}

<!-- Platform Average CPC Average CPM
Google Search Ads $2.32 $38.40
Google Display Ads $0.67 $3.12
Facebook Ads $1.35 $8.60
Instagram Ads $3.56 $8.96
Twitter Ads $0.38 $6.46
LinkedIn Ads $5.26 $6.59
Pinterest Ads $1.50 $30 -->

While the model assumes PD-CPM is 10% of CPM, that relationship is a placeholder for a more complex pricing mechanism that reflects the value of effective personal data to different publishers. A hedge fund manager’s target audience profile will be more valuable to a publisher because of the matched value of underlying goods and services. BMW will pay more to advertise their latest electric car to Mr Bateman the investment banker than Kraft Heinz is willing to pay to advertise ketchup to Mrs Miggins ahead of her weekly shop. Publishers create content and curate audiences. The more valuable the audience, the more valuable the inventory. OwnYou allows a publisher to prove that to an advertiser and, as such, we expect the publisher to pay their audience more for their data, contingent on it being valuable; it is important the publisher is in fact paying Mr Bateman for their data rather than Mrs Miggins. We have nothing against Mrs Miggins but Bloomberg publishing is not going to be able to sell the right inventory, at the right cost, to pay for the content that attracts BWM, if their audience consists of Mrs Miggins and her pie making friends.

As such, OwnYou’s PD-CPM pricing mechanism will include the following components:

- A reserve price.
- A market driven price, in addition to the reserve price, allowing publishers to either pay or exchange services with the right audience, in exchange for their data.
- A price for privacy forgone, allowing publisher to offer a price for more granular demographics and more granular location data. The user will need to approve the release of more granular information as it substantially increases the correlation risk.

### Attribution assumptions.

While sharing personal data is important, it will take time to demonstrate the relationship between higher CPMs and higher quality OwnYou data. However, as all web2 platforms pivot toward cohort-based attribution, OwnYou’s attribution architecture is both unique and valuable. Personal data fuels Web2 business models. As privacy concerns escalate, cohort driven architecture offers a compromise; Web2 platforms will continue to harvest personal data, but they will prevent the advertiser from knowing your specific interests, or which ads you, specifically, responded to. Web2 platforms will continue to collect, store and use your personal data but, like a Victorian surgeon using a bone saw to amputate the gangrenous leg, Web2 platform providers will apply ever more layers of obfuscation in an effort to protect you, the user, from predatorial pesky privacy destroying advertisers.

Wait a minute. Is the advertiser responsible for your lack of privacy or the web2 platform? Shouldn’t the web2 platform simply compensate users and provide them with control over their own data? Can they be trusted to do that? We don’t think so. In fact, by now, you know that OwnYou will rely on cryptography and a decentralised architecture to allow its users to directly engage with advertisers. Advertisers care less about Mrs Miggins’ actual name and personally identifiable information. Instead, they do care about whether a $30,000 budget spent on Pie Weekly’s website translated into actual clicks and sales. Advertisers rely on real time attribution data, in a privacy preserving manner, to manage scarce advertising budgets. Because OwnYou is owned by the individual, and because the attribution transactions are with the individual directly, pseudonymously in a privacy preserving manner, attribution data does not require further obfuscation.

Attribution income is both a function a fee and the click-through rate. The average click through rates for display are 0.46%. We expect that more relevant advertising and the attribution incentive will lead to substantially higher click-through-rates.
The $0.25 attribution fee per click (APC) is a function of the overall cost-per-click fee. Because we expect a higher click through rate, the initial cost per click (CPC) drops (more click-throughs, for the same budget). Since CPC typically range between $1-2 per click , we reason a lower CPC makes room for an additional $0.25 APC. Brushing that food salad aside; as advertisers see a higher level of engagement (i.e., more clicks) for the same budget, we expect them to want to spend on high quality attribution data to help them further improve their ROIs.

{% include image.html img="ctr.jpg" lightbox="true" alt="Average Click Through Rate (CTR) - Google Ads Benchmarks, WordStream, October 2022" caption="Average Click Through Rate (CTR) - Google Ads Benchmarks, WordStream, October 2022" %}

<!-- Industry Average CTR (Search) Average CTR (GDN )
Advocacy 4.41% 0.59%
Auto 4.00% 0.60%
B2B 2.41% 0.46%
Consumer Services 2.41% 0.51%
Dating & Personals 6.05% 0.72%
E-Commerce 2.69% 0.51%
Education 3.78% 0.53%
Employment Services 2.42% 0.59%
Finance & Insurance 2.91% 0.52%
Health & Medical 3.27% 0.59%
Home Goods 2.44% 0.49%
Industrial Services 2.61% 0.50%
Legal 2.93% 0.59%
Real Estate 3.71% 1.08%
Technology 2.09% 0.39%
Travel & Hospitality 4.68% 0.47% -->

### Cost-per-completion assumptions.

Cost-per-completion (or cost-per-action, CPA) advertising campaigns typically only pay the publisher, for their inventory, if the individual completes an action; signs up to a subscription, registers their email, requests a call-back or makes a purchase. Our cost-per-completion model provides a rebate to the individual as well as compensating publishers. We want to incentivise publishers for curating valuable audiences and we want to make it possible for advertisers to reward individuals who engage through their adverts. Only the OwnYou infrastructure makes that possible. Completion fees will vary enormously, typically varying with advertiser customer acquisition costs. It cost more that $500 to acquire new insurance customers in the US. Not all advertising will include a CPA element. Individual users will be able to opt-in to CPA but they won’t know which ads have a CPA element until they are compensated.

### Easter egg income.

Easter eggs allow advertisers to link specific offers to specific locations. Users opt to share their location with the app and the app will display which easter-egg offers are available in each location. For instance, P&G might choose to release 1,000 discount coupons for their new washing powder, across 100 different locations. The first 1,000 purchases will entitle users to a $1 discount.
Users can opt-in to easter-eggs via their wallets. Advertisers broadcast the offers to user wallets. Each offer is encrypted with a location key. The location key can only be unlocked by a wallet in that specific location, and only if the offer remains valid. The user doesn’t have to share their personal details to claim the coupon, only their pseudonymous demographics and target audience data. Sharing personal identifiable information is strictly prohibited.
Easter eggs allow marketers to engage local customers with localised marketing while respecting individual privacy.

### Auto price comparison.

Auto prices comparison scans user personal data for upcoming service renewals, automatically connecting to price comparison sites, pseudonymously, to check for the latest competitive offers. The user can elect to be alerted when more competitive services are available. The user can modify their personal details while remaining anonymous until the final point of transaction. Pseudonymous data is immediately hobbled and removed from third-party price comparison partner sites, as per contractual agreements with the OwnYou foundation.
Fees are high because we expect the service to be dominated by financial services and healthcare providers, where customer acquisitions costs are high, and knowing when a potential customer is up for renewal merits special compensation.

### Compensating the intelligence stack

The intelligence stack benefits from scale. We expect the OwnYou foundation will need to kick start early algorithm development, as it builds out key infrastructure. However, an open-source model with visible, instant rewards, will attract contributions. As the population grows, we expect Easter Egg and Price Comparison adoption to increase, and revenue per user to rise. Ultimately, given the fixed cost nature of algorithm development, we expect a growing number of users to attract an increasing number of profession machine learning experts.

### Compensating Publishers

First and foremost, publisher benefit from user personal data without having to wear the increasingly complex burden of managing first party data across multiple jurisdictions. Higher quality demographic data, combined with reliable targeted audience data, substantially increases the value of publisher inventory. How they exchange access to content in exchange for user data, is up to the publisher. During the OwnYou enabled one-click sign-in, the user shares their pseudonymous personal details with the publisher. With that information, the publisher can choose to grant full access, selective access, or no access. We recommend against providing no access, and suggest a simple landing page, with a smaller selection of content.
Publishers have two sources of revenue in the OwnYou ecosystem; advertising revenues and completion revenues. Advertising revenues are not accounted for in our model since publishers already sell their inventory and we lay no claim to that existing revenue. We argue that higher quality personal data, with no personal data management burden, is a net positive, and we reflect that in the higher CPM rates. We also suggest higher click-through rates, from a more engaged consumer, makes room for attribution revenues, benefiting and attracting individuals.
Publisher completion revenues are very much a function of audience curation. If publishers create valuable content, attracting consumers with a higher propensity to spend, when presented with relevant ads, they should stand to benefit. Publishers take the highest cut from completion income, reflecting the importance of audience curation.

### Compensating infrastructure and service providers

OwnYou relies on a network of helper nodes that provide storage and compute services.
Service providers are compensated with a 10% share of personal data provision and a 10% share of attribution income.
Whether OwnYou creates and manages the development of its own network of service providers, or taps into one or more of the many developing networks, has yet to be decided. The decentralised web node and secure data vault specifications is still under development. We will either innovate around those requirements, or development infrastructure that allows us to leverage providers specialising in the development of those systems. Ultimately, we think decentralised storage and compute service will become commodities.
Most important to OwnYou is the development of a secure entitlement system that helps the Intelligence stack run their algorithms on user data, in a privacy preserving manner, without the data leaving the user’s control.
Also important to OwnYou is the development of a systematic payment and reward system that allows users to automatically compensate the intelligence stack, and each key service provider.
