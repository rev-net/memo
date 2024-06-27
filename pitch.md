## Contents
1. [Thesis](#thesis)
2. [Context](#context)
3. [Problem](#problem)
4. [Big bet](#big-bet)
    - [Revnets](#revnets)
    - [Networked treasuries](#networked-treasuries)
5. [RRG](#rrg)
    - [Pitch to investors](#pitch-to-investors)
    - [Fundraising operations](#fundraising-operations)
    - [Structure](#structure)
    - [Onchain management](#onchain-management)
    - [Offchain management](#offchain-management)
    - [Timing](#timing)
    - [Bottom line](#bottom-line)
    - [Roadmap](#roadmap)
6. [$REV](#rev)
    - [Anatomy of a revnet](#anatomy-of-a-revnet)
    - [$REV stage 1](#rev-stage-1)
    - [$REV stage 2](#rev-stage-2)
    - [$REV stage 3](#rev-stage-3)
7. [Legal](#legal)
8. [Investor FAQ](#investor-faq)
9. [Examples of revnets](#examples-of-revnets)

## Thesis

Major technological breakthroughs force entrepreneurs, capital providers, and regulators to create and use new financial structures. The designs of these structures are informed by the contours of the technological developments they correspond to – it isn't a coincidence that [joint-stock companies](https://en.wikipedia.org/wiki/Joint-stock_company) were the defining structure of the mercantile era, that [limited liability corporations](https://www.jstor.org/stable/764920) defined the Industrial Revolution, or that today's Silicon Valley startups are defined by the use of broad-based equity compensation.[^1]

This decade has seen major developments within a handful of technological domains. Some of these domains, like genomics, are well-served by traditional corporate-stock models. But for many internet-native businesses, and especially cryptocurrency projects, traditional models have clear shortcomings for entrepreneurs, consumers, and capital providers alike. Several major players, like Uniswap, Maker, and Compound have tried to address this by combining standard for-profit companies with experimental structures (often DAOs), often leading to mixed results and dysfunctional governance.[^2]

When these experimental structures fail, it's often due to a lack of transparency, misguided expectations, or misaligned incentives. [Smart contracts](https://ethereum.org/en/smart-contracts/) offer a path forward by:

- Expanding the design space for financial structures, making it possible to express relationships which would be impractical to manage with contractual agreements. This includes designs with better incentive alignment – when ownership and access are always directly proportional to contribution, incentive alignment is a given.
- Providing clear rules which cannot be broken, as opposed to the soft guarantees of legal agreements (which can be difficult to enforce in practice).
- Making it impossible to *not* be transparent, minimizing information asymmetry and simplifying diligence for all participants.

But these positive qualities can be diminished when each project implements its own financial structure uniquely – without standardization, each participant has to trust that there are no bugs or backdoors in the smart contracts being used, and may even have to audit the source code to fully understand what they're receiving in exchange for their support.

In the same way that [Y-Combinator's Safe financing documents](https://www.ycombinator.com/documents/) allow investors to fund startups without auditing new legal agreements each time, a standardized (but configurable) financial structure, encoded by smart contracts, would allow capital providers to confidently fund a wide variety of cryptocurrency projects without the need to separately audit each one's contracts.

The need for a reliable and productive structure to point raised funds and onchain fees (most pressingly for our own projects) led us to create *revnets*. Revnets are a **fully pre-configured** financial structure – although they can evolve over time, they do so according to rules which are set in place at the time of their creation. This means:

- There's no governance. Governance takeovers, one of the most common failure modes for DAOs, are impossible.
- There isn't an ongoing management burden either – revnets operate autonomously, according to their pre-configured rules.
- Trust is maximized. Investors, builders, community, and customers know each revnet's rules will be enforced.
- Transparency and diligence are simple. Once one revnet's workings makes sense, all revnets make sense.

We want to double down on revnets as a vision of how wealth will be most productively created and distributed in our future characterised by digital networks and cryptographic identities, we're after partners to help propel this thesis forward.

## Context

<!--TODO: Make this shorter-->

Juicebox was launched by [Jango](https://jango.eth.sucks) and Peri in July 2021 as an experimental financial model which used smart contracts to allow (TODO...) . As of June 2024, Juicebox has facilitated $185,539,642 in ETH payments to 1,331 projects, 

[Jango](https://jango.eth.sucks) has spent the last 3 years refining smart contracts towards a specialized language for articulating new financial structures, and has spent the last 2 years refining that language in production as [Juicebox](https://juicebox.money). He's done so alongside a group of internet anons, itself organized via this Juicebox language. At its core, the experiment has been to create business models of the future.

## Problem

Over the last few years, we've seen compelling consumer crypto offerings emerge, but few have struck onchain sustainability. Many organizations ironically continue relying only on traditional cap tables, term sheets, payrolls, and rent-seeking fee structures because productive and safe onchain forms haven't been well demonstrated. Others stick to a public goods narrative that sidesteps conversations about risks and incentives altogether.

## Big bet

The next step is to take the now fully-featured Juicebox language and shape it for intentional competitive use. Specifically, we believe organizations oriented around Revnets and other Post-Corporate capital structures that expand to internet scale will prove to be highly productive, and we believe organizations that encourage a broader ecosystem of networked treasuries are also likely to bear fruit.

- **Revnet:** A business framework existing onchain where wealth is exchanged programmatically over time based only on an initial set of rules (like Bitcoin's halving), and where investors and customers are treated as alike participants.

- **Networked treasuries:** Organizations architected with horizontally interconnected treasuries instead of increasingly-bloated hierarchical ones. Revnets work great when they're networked together to automate accounting relationships.

## RRG

We will continue to leverage the open internet to make experimental progress, but we'd also like to begin nurturing a dedicated Revnet Research Group (RRG) corporation to support the ecosystem and extend the benefits of onchain networks to the traditional world while giving revnets access to traditional capital. We want to create a real world studio production environment, and a traditional legal setting to build web tools (like [app.rev.eth.sucks](app.rev.eth.sucks)) that make revnets accessible to browse, participate, and invest in.

### Mission

Tokenize fundraises and revenues to align incentives while reducing risks of growing openly accounted for organizations.

### Pitch to investors
We’re selling 10% of the company Revnet Research Group at a $50m valuation in August 2024.

### Fundraising operations
We will use a SAFE.

### Structure 
RRG is Incorporated in the USA as a Delaware C-Corp. 51% owned by Jango, 39% reserved for staff, 10% sold to investors.

### Onchain management 
Onchain, RRG is managed by a 3/6 multisig at `rrg.rev.eth`. The multisig is controlled by:
- `breadfruit.eth` (jango)
- `filipv.eth`
- `codalabs.eth` (aeolian)
- `kmac.eth`
- `dao.jbx.eth` (JuiceboxDAO)
- `openesquire.eth` (Robert Leonhard)

### Offchain management

Offchain management will be led by Jango, Filip, Aeolian, KMac, Robert, and other members from the Juicebox community:

[Jango](https://jango.eth.sucks) has spent the last 3 years refining smart contracts towards a specialized language for articulating new financial structures, and has spent the last 2 years refining that language in production as [Juicebox](https://juicebox.money). As of June 2024, Juicebox has facilitated $185,539,642 in ETH payments to 1,331 projects. He's done so alongside a group of internet anons, itself organized via this Juicebox language. At its core, the experiment has been to create business models of the future.

[Filip](https://filip.world) has been working on Juicebox since November 2021, contributing to documentation, services, and frontend development, as well as working directly with many of the largest Juicebox projects.

[Aeolian](https://x.com/aeolianeth) has been working on Juicebox since November 2021, and leading the development of [juicebox.money](https://juicebox.money) since 2022. Aeolian has created a number of essential tools within the Juicebox ecosystem: [juicescan.io](https://www.juicescan.io), the [Juicebox SDK](https://github.com/Bananapus/juice-sdk-v4), and the in-progress [revnet.app](https://revnet.app).

[KMac](https://kmacb.eth.limo)

Robert Leonhard is the co-founder of [Open Esquire](https://openesq.tech), a group of legal engineers serving Ethereum projects and many Juicebox projects.

### Ideal partners
The Juicebox community is about to deploy the first handful of revnets alongside Juicebox V4 ($NANA, $REV, $BANNY, $NANCE, $SUCKS, $DEFIFA, $CROPTOP, $SPHINX). They are currently on testnets. We're fundraising as RRG to fund the growth work of extending these revnets to more people, and inviting new revnets to emerge. We're looking for partners that believe in the mission, beleive in the team, and can help make this launch chapter successful.

### Bottom line
 
RRG accumulates $REV and other promising revnet-based tokens, and adds value to them in two ways: by making web tools (like app.rev.eth.sucks) that make revnets accessible to see and participate in, and by onboarding internet projects who would benefit.

The $REV revnet receives a 2.5% network fee whenever someone cashes out from a revnet. RRG will receive a subset of new issuance as fees and other contributions come in (see specs below).

### Roadmap

1. Help revnets accept more money by building great products like revnet.app and offering services to traditional institutions that allow them to participate in revnets.

2. In 5 years once there are hundreds of billion dollar networks running as revnets, IPO to give traditional finance exposure to $REV.

3. In 10 years, start cashing out of $REV positions and offer buybacks – doing so will consolidate the $REV network's value to remaining holders. 

4. Once all positions have been cashed out, the corporation will reach the end of its life and will no longer participate in the networks it has helped build. 

## $REV
$REV runs on its own as a revnet according to the rules below. RRG is a token holder alongside other token holders and has no special powers. Anyone can participate in $REV at any time.

### Anatomy of a revnet

Each revnet is make up of a $TOKEN, and defined in stages. Each stage specifies the following rules:

- **Duration:** How long does the stage last? A revnet’s last stage lasts forever.

- **Starting price:** How much does it cost to buy a $TOKEN at the start of the stage? The paid value stays within the revnet and can only be accessed by $TOKEN holders who cash out.

- **Price increase:** How frequently does the price of $TOKEN increase within the stage?

- **Split:** What percentage of $TOKEN issuance should be withheld to a set of splits, and which address will be the Split Operator that can change the split destinations within the preset percent?

- **Automint:** How many $TOKENs should be automatically mintable to preset destinations at the start of the stage?

- **Cash out tax:** How much does the value reclaimed from cashing out of the revnet increase each time $TOKEN holders leave?

If holders of the $TOKEN add liquidity to an AMM it offers a better price, the revnet will route new incoming payments to the market instead of issuing new $TOKENs. Revnets issue new tokens until the market naturally takes over its supply and demand, helping networks start up without leaking value, and sustain efficient growth over time.

Built using the Juicebox V4 protocol, revnets can grow to accept money on new EVMs as they emerge, and offer cash outs on them too. Holders can move their tokens between chains, which move the revnet’s value alongside to maintain the aggregate value proposition in tact.

### $REV stage 1
_Inaugural 77 day $REV sale ⏩. Your payments are worth 2.5x what they'll be worth in stage 2.  Mint first of two batches of tokens to honor pre-net work._
- **Duration:** 77 days.
- **Initial price:** 1 $REV costs 0.001 ETH.
- **Price increase:** none.
- **Split:** 20% split of issuance and buybacks operated by rrg.rev.eth, 10% routed to rrg.rev.eth, 10% to dao.jbx.eth.
- **Automint:** 70_000 $REV to rrg.rev.eth for pre-net work, split 25_000 to dao.jbx.eth, 10_000 to breadfruit, 10_000 to filipv, 10_000 to codalabs, 4_000 to openesquire, 2_000 to kmac, 2_000 to 0xBa5ed, 2_000 to nowonder, 2_000 to peel,  1_000 to drgorilla, 1_000 to juicecast, 1_000 to peacenode, 1_000 to LJ.
- **Cash out tax:** Medium-high (0.6), the network consolidates when holders cash out.

### $REV stage 2
_The price of issuing new $REV is doubled every 77 days, forever._
- **Duration:** 770 days.
- **Initial price:** 1 $REV costs 0.002 ETH, double the price of stage 1.
- **Price increase:** 100% (double) every 77 days, “halving”.
- **Split:** 38% of issuance and buybacks operated by rrg.rev.eth, 19% routed to rrg.rev.eth, 19% to dao.jbx.eth.
- **Automint:** none.
- **Cash out tax:** No change. Medium-high (0.6).

### $REV stage 3
_Vest more $REV for pre-net work._
- **Duration:** 7777 days. (~22 years)
- **Initial price:** Where stage 2 left off.
- **Price increase:** Continue doubling every 77 days.
- **Split:** No change. 38% of issuance and buybacks operated by rrg.rev.eth, 19% routed to rrg.rev.eth, 19% to dao.jbx.eth.
- **Automint:** 128_000 $REV to rrg.rev.eth for pre-net work, split 35_000 to dao.jbx.eth, 20_000 to breadfruit, 20_000 to filipv, 20_000 to codalabs, 10_000 to openesquire, 5_000 to kmac, 5_000 to 0xBa5ed, 5_000 to nowonder, 5_000 to peel, 1_000 to drgorilla, 1_000 to juicecast, 1_000 to peacenode, 1_000 to LJ.
- **Cash out tax:** No change. Medium-high (0.6).

### $REV stage 4
_End issuance and splits._
- **Duration:** Forever.
- **Initial price:** 0. No more issuance.
- **Price increase:** None, since there's no more issuance.
- **Split:** None.
- **Cash out tax:** No change. Medium-high (0.6).

## Legal

Each revnet’s rules are defined upfront, and all transactions are public. Once a revnet is deployed, no manager has the power to change how it works, no supervisor has special backdoor access, and no authority can stop it. There is no managerial effort attached to an expectation of profit.

The time is now to learn from the legal outcomes of the past few years and bet big on deterministic mechanisms where no entity can change or control the rules once deployed, which also benefit from facilitating fully auditable public data only.

RRG has it's own managerial efforts and thus is selling structured access to a C-Corp via a SAFE, but engages with the $REV economy only as a token holder.

## Examples of revnets

- *[$NANA](https://nana.eth.sucks):* Captures revenues from the omnichain Juicebox V4's 2.5% fee. (very soon)
- *[$BANNY](https://banny.eth.sucks):* Captures revenues from Bannyverse mints. (very soon)
- *[$REV](https://rev.eth.sucks):* Captures revenues from betting on the productivity of the revnet-based projects it builds tools for. (very soon)
- *[$NANCE](https://nance.app):* Supports the building of the open sources Nance governance platform for tokenized communities. (soon)
- *[$SUCKS](https://eth.sucks):* Captures memetic energy from the distribution of .eth.sucks links. (soon)
- *[$DEFIFA](https://defifa.net):* Captures revenues from defifa prediction games. (soon)
- *[$CROPTOP](https://croptop.eth.sucks):* Collects a 2.5% fee from mints made from Croptop templates, a simple IPFS-based peer-to-peer website template with content feeds and revenue streams baked in.
- *[$SPHINX]():* Supports the building of the open source Sphinx multichain devops platform that Juicebox uses to manage deploys. (soon)

Learn more and reach us from RRG at [rev.eth.sucks](rev.eth.sucks).

## Investor FAQ

### Should I invest in RRG, $REV, or...

There are three core entities in play: $REV, RRG Corporation, and Juicebox DAO ($JBX). According to the $REV specs above, RRG and Juicebox DAO are both expected to receive split issuance/buybacks, making them great proxies to build ongoing exposure to $REV's revenue growth -- albeit at the risk of each of their governance processes.

- RRG Corporation is the only way to access the ecosystem for participants who don't want to access tokens directly onchain.
- For those comfortable accessing tokens onchain, $JBX is a fixed-supply governance token that has been on the market for several years now focusing its treasury on contributions to the Juicebox ecosystem -- the revnet project and several others were informally incubated from within Juicebox DAO. You can learn more [here](https://docs.juicebox.money/dao/).
- Also for those onchain, it may be advantageous to build exposure to $REV directly to bet on revenue growth without the burden of proxies.

[^1]: Other recent examples: the gig economy, DAOs, and remote work.
[^2]: [Uniswap](https://docs.uniswap.org/concepts/overview) raises funds and employs developers under the for-profit Uniswap Labs, but the Uniswap protocol is governed by $UNI token voting. The competing interests of token holders and Uniswap Labs have led to a number of controversial decisions over Uniswap's fee switch, source code licensing, and cross-chain deployments. Other projects have faced similar controversies when the interests of token holders and developers have diverged.

