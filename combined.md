# Introduction

> Welcome to Story

<Frame>
  <img src="https://mintcdn.com/story/KwuxPVrS3UIa7CU1/images/story-banner.png?fit=max&auto=format&n=KwuxPVrS3UIa7CU1&q=85&s=da78d677a3f4739cbd1694854be2157b" alt="Hero" data-og-width="3000" width="3000" data-og-height="1000" height="1000" data-path="images/story-banner.png" data-optimize="true" data-opv="3" srcset="https://mintcdn.com/story/KwuxPVrS3UIa7CU1/images/story-banner.png?w=280&fit=max&auto=format&n=KwuxPVrS3UIa7CU1&q=85&s=2bd93e8784cf1b90e9cd1c3c35b6c3bc 280w, https://mintcdn.com/story/KwuxPVrS3UIa7CU1/images/story-banner.png?w=560&fit=max&auto=format&n=KwuxPVrS3UIa7CU1&q=85&s=b6244e6e4ebc729159e605f1733383d9 560w, https://mintcdn.com/story/KwuxPVrS3UIa7CU1/images/story-banner.png?w=840&fit=max&auto=format&n=KwuxPVrS3UIa7CU1&q=85&s=48ef5fbe868de6811a06a301c4f5a4d5 840w, https://mintcdn.com/story/KwuxPVrS3UIa7CU1/images/story-banner.png?w=1100&fit=max&auto=format&n=KwuxPVrS3UIa7CU1&q=85&s=a21e7c2c3fdd3c103e4d6c75ff8b9d5e 1100w, https://mintcdn.com/story/KwuxPVrS3UIa7CU1/images/story-banner.png?w=1650&fit=max&auto=format&n=KwuxPVrS3UIa7CU1&q=85&s=30232e9907451464acc4095b10d15510 1650w, https://mintcdn.com/story/KwuxPVrS3UIa7CU1/images/story-banner.png?w=2500&fit=max&auto=format&n=KwuxPVrS3UIa7CU1&q=85&s=4f871e6529349187b29e0388f81a1559 2500w" />
</Frame>

## Introducing the World's IP Blockchain

Story is a purpose-built layer 1 blockchain designed specifically for intellectual property.

You can register your IP on-chain and add usage terms to it in seconds, massively lowering the barrier to the currently complex & antiquated legal system for IP. For example, enforcing "you owe me 50% of your commercial revenue if you use my IP" without needing time, money, or lawyers.

<Note>
  IP could be an image, a song, an RWA, AI training data, or anything
  in-between.
</Note>

By making IP programmable on the blockchain, it becomes this transparent & decentralized global IP repository where AI agents (or any other software) and humans alike can transact on & monetize IP with a simple API call.

<CardGroup cols={2}>
  <Card title="Explain Like I'm 5" icon="house" href="/explain-like-im-five">
    Read a 1 minute summary.
  </Card>

  <Card title="Read the Whitepaper" href="https://www.story.foundation/whitepaper.pdf" icon="file">
    Read the Story whitepaper.
  </Card>
</CardGroup>

<Accordion title="Why did we build Story?" icon="face-thinking">
  When IP owners share their work online, it’s easy for others to use or change it without crediting them, and they often don't get paid fairly if their work becomes popular or valuable. This can be discouraging for people who want to share their ideas and creations but don’t want to lose control over them.

  Additionally, the sheer speed and superabundance of AI-generated media is outpacing the current IP system that was designed for physical replication. In many cases, [AI is trained on and is producing copyrighted data](https://twitter.com/BriannaWu/status/1823833723764084846).

  Story fixes this by providing a way for creators to share their work with built-in protection. When someone (including an AI model) uses a song, image, or any creative work that’s registered on Story, the system automatically tracks who the original owner is and makes sure they get credited. Plus, if that work generates revenue—say someone remixes a song and it earns money—the original owner automatically receives their fair share based on license terms that were set on-chain.
</Accordion>

## Quick FAQs

<AccordionGroup>
  <Accordion title="What's the gas token?">\$IP</Accordion>

  <Accordion title="What wallet should I use?">
    Your preference obviously, since you can use any EVM-based wallet. But we
    recommend [MetaMask](https://metamask.io/) for [OKX](https://www.okx.com/web3). You can add Story's L1 below:

    <CardGroup cols={2}>
      <Card title="Add Story Mainnet" icon="globe" href="https://chainid.network/chain/1514/">
        Connect your wallet to Story's mainnet.
      </Card>

      <Card title="Add Story 'Aeneid' Testnet" icon="globe" href="https://chainid.network/chain/1315/">
        Connect your wallet to Story's 'Aeneid' testnet.
      </Card>
    </CardGroup>
  </Accordion>

  <Accordion title="Where can I see the ecosystem?">
    Check out our [Ecosystem - Getting Started](https://storyprotocol.notion.site/Story-Ecosystem-Getting-Started-169051299a5480cc9b3dcac7c3ec82da) page.
  </Accordion>

  <Accordion title="What are my stablecoin options?">
    You can use bridged USDC.e powered by [Stargate](https://stargate.finance/bridge).
  </Accordion>

  <Accordion title="How do I bridge and what's the best method?">
    Use [Stargate](https://stargate.finance/bridge), [deBridge](https://app.debridge.finance/?inputChain=1\&outputChain=1514\&inputCurrency=\&outputCurrency=0xf1815bd50389c46847f0bda824ec8da914045d14\&dlnMode=simple\&address=\&amount=1), or [Orbiter Finance](https://www.orbiter.finance/en?tgt_chain=1514\&src_chain=1\&src_token=ETH).
  </Accordion>
</AccordionGroup>

## Brief Architecture Overview

There are several elements that make up Story as a whole. Below we will cover the most important components.

<Frame>
  <img src="https://mintcdn.com/story/KwuxPVrS3UIa7CU1/images/story-stack.png?fit=max&auto=format&n=KwuxPVrS3UIa7CU1&q=85&s=d376323d8ad7c8f844c6b45a880d601a" alt="Story Diagram" data-og-width="1200" width="1200" data-og-height="675" height="675" data-path="images/story-stack.png" data-optimize="true" data-opv="3" srcset="https://mintcdn.com/story/KwuxPVrS3UIa7CU1/images/story-stack.png?w=280&fit=max&auto=format&n=KwuxPVrS3UIa7CU1&q=85&s=92336f34b3a903cc18f0a9ad41284be9 280w, https://mintcdn.com/story/KwuxPVrS3UIa7CU1/images/story-stack.png?w=560&fit=max&auto=format&n=KwuxPVrS3UIa7CU1&q=85&s=60b867d369ef6f61afe92cc61dd8a236 560w, https://mintcdn.com/story/KwuxPVrS3UIa7CU1/images/story-stack.png?w=840&fit=max&auto=format&n=KwuxPVrS3UIa7CU1&q=85&s=77dcddd3f132a8ad4cc154a99f01aaae 840w, https://mintcdn.com/story/KwuxPVrS3UIa7CU1/images/story-stack.png?w=1100&fit=max&auto=format&n=KwuxPVrS3UIa7CU1&q=85&s=399f551213e9c84f80a0dae22a446a82 1100w, https://mintcdn.com/story/KwuxPVrS3UIa7CU1/images/story-stack.png?w=1650&fit=max&auto=format&n=KwuxPVrS3UIa7CU1&q=85&s=9556bdbca289195a7ba45f5b7e4ddf57 1650w, https://mintcdn.com/story/KwuxPVrS3UIa7CU1/images/story-stack.png?w=2500&fit=max&auto=format&n=KwuxPVrS3UIa7CU1&q=85&s=2c913714a57ce66636a03245acfc67be 2500w" />
</Frame>

### Story Network: "The World's IP Blockchain"

Story Network is a purpose-built layer 1 blockchain achieving the best of EVM and Cosmos SDK. It is 100% EVM-compatible alongside deep execution layer optimizations to support graph data structures, purpose-built for handling complex data structures like IP quickly and cost-efficiently. It does this by:

* using precompiled primitives to traverse complex data structures like IP graphs within seconds at marginal costs
* a consensus layer based on the mature CometBFT stack to ensure fast finality and cheap transactions

### "Proof-of-Creativity" Protocol

Our "Proof-of-Creativity" Protocol, made up of smart contracts written in Solidity, are natively deployed on Story Network and allow anyone to onramp IP to Story. Most of our documentation focuses on the protocol.

Creators register their IP as [🧩 IP Assets](/concepts/ip-asset) on Story. You use [🧱 Modules](/concepts/modules) to interact with IP Assets. For example, enforcing proper usage of your IP via the [Licensing Module](/concepts/licensing-module), paying & claiming revenue via the [Royalty Module](/concepts/royalty-module), and disputing infringing IP via the [Dispute Module](/concepts/dispute-module).

Each IP Asset has an associated ERC721 NFT, which represents *ownership* over the IP. This means IP ownership can be bought & sold. Additionally, the licenses minted from an IP are also ERC721 NFTs, meaning you can buy & sell the rights to use an IP under certain terms. Together, this unlocks a new realm of **IPFi**.

### Programmable IP License

Although on-chain, an IP's usage terms and minted licenses are enforced by an off-chain legal contract called the [Programmable IP License (PIL💊)](/concepts/programmable-ip-license).

The PIL allows anyone to offramp tokenized IP on Story into the "real world" legal system and outlines real legal terms for how creators can remix, monetize, and create derivatives of their IP. *The protocol, or more specifically the IP Assets and modules described above, are what automate and enforce those terms on-chain*, creating a mapping between the legal world (PIL) and the blockchain.

<Note>
  Like USDC enables redemption for fiat, the PIL enables redemption for IP.
</Note>

## Examples

<Accordion title="Example #1" icon="circle-info">
  Imagine you're an artist who creates digital paintings, or a musician who makes original songs. You want to share your work online, but you want to ensure that if others use or change your work, they give you credit and—if they make money from it—you get a share. That’s where Story comes in. It's a platform that uses technology to give IP owners like you control over how your work is used, tracked, and shared, so it’s both protected and fairly rewarded.

  Think of it like this: Suppose you upload a song to Story. Now, anyone can see that you’re the original creator, and if someone wants to remix it, they can do so through Story. The system then automatically tracks the remix as a "derivative" of your song and notes you as the original artist. This way, if the remix becomes popular and earns money, Story can help you earn a portion of those earnings, just like the remixer.
</Accordion>

<Accordion title="Example #2" icon="circle-info">
  Let’s say a scientist uploads an image dataset to be used by artificial intelligence (AI) models for research. Through Story, that dataset is registered, so if any company uses it to train their AI, the original scientist is credited. If that dataset then contributes to a profitable AI application, Story ensures a fair share goes to the original contributor.

  With Story, you can share your work freely, knowing that wherever it goes, it’s tracked and fairly credited back to you. The idea is to create a fair environment for sharing, building upon, and growing creative work.
</Accordion>
# 💊 Programmable IP License (PIL)

> Story Programmable IP License - A legal framework for IP licensing on-chain

The PIL is a legal off-chain document based on US copyright law created by the Story team.

The parameters outlined in the PIL (ex. "Commercial Use", "Derivatives Allowed", etc) have been mapped on-chain, which means they can be enforced on-chain via our protocol, bridging code and law and unlocking the benefit of transparent, autonomous, and permission-less smart contracts for the world of intellectual property.

<CardGroup cols={1}>
  <Card title="PIL Legal Text" href="https://github.com/piplabs/pil-document/blob/main/Story%20Foundation%20-%20Programmable%20IP%20License%20(1.31.25).pdf" icon="scroll" color="#ccb092">
    Check out the actual PIL legal text. It is very human-readable for a legal
    text!
  </Card>
</CardGroup>

The PIL is the first and currently only example of a [License Template](/concepts/licensing-module/license-template). A License Template is simply a traditional legal document that has been brought on-chain and contains a set of pre-defined terms that people must set, like:

* `commercialUse` - can someone use my work commercially?
* `mintingFee` - the cost of minting a license to use my work in your own works.
* `derivativesAttribution` - does someone have to credit me in their derivative works?

In code, these terms form a struct that represent their legal off-chain counterparts. To see all of the terms defined by the PIL and their associated explanations in code, see [PIL Terms](/concepts/programmable-ip-license/pil-terms).

To see example configurations ("flavors") of the PIL, see [PIL Flavors (examples)](/concepts/programmable-ip-license/pil-flavors).

## The Background Story

<Note>
  If you just want to get started developing with the PIL, you can skip this section.
</Note>

We designed Story's [📜 Licensing Module](/concepts/licensing-module/overview) to power the expansion of emerging forms of creativity, such as authorized remixes and co-creation. Our protocol can support any media format or project, ranging from user-generated social videos & images to Hollywood-grade collaborative storytelling.

Intellectual property owners can permit other parties to use, or build on, their work by granting rights in a license, which can be for profit or for the common good. In the media world, these licenses are generally highly tailored contracts, which vary by media formats and the unique needs of licensors - often requiring unique expertise (via lawyers) and significant resources to create.

We searched for a form of a "universal license" that could support these emerging activities at scale. Hat tip to [Creative Commons](https://creativecommons.org/mission/), [Arweave](https://mirror.xyz/0x64eA438bd2784F2C52a9095Ec0F6158f847182d9/AjNBmiD4A4Sw-ouV9YtCO6RCq0uXXcGwVJMB5cdfbhE), A16Z / [Can't Be Evil,](https://a16zcrypto.com/posts/article/introducing-nft-licenses/) The [Token-Bound NFT License](https://james.grimmelmann.net/files/articles/token-bound-nft-license.pdf) and music rights organizations, among others. But we simply couldn't find one framework or agreement robust enough - so with our expert legal counsel (with special thanks to Ghaith Mahmood and Heather Liu) we created one ourselves! **Introducing the Programmable IP License (PIL:pill:)**, the first example of a [License Template](/concepts/licensing-module/license-template) on the protocol.

## Feedback

We are excited to collect feedback and collaborate with IP owners to unlock the potential of their works - please let us know what you think! We can be reached at `legal@storyprotocol.xyz`.

<CardGroup cols={1}>
  <Card title="PIL Legal Text" href="https://github.com/piplabs/pil-document/blob/main/Story%20Foundation%20-%20Programmable%20IP%20License%20(1.31.25).pdf" icon="scroll" color="#ccb092">
    Check out the actual PIL legal text. It is very human-readable for a legal
    text!
  </Card>
</CardGroup>
# How does Story protect IP?

> Okay... how does Story *actually* protect IP?

<Frame>
  <img src="https://mintcdn.com/story/Ci-RgMKFKns3XzFq/images/concepts/hdspip.png?fit=max&auto=format&n=Ci-RgMKFKns3XzFq&q=85&s=966a75f9366d19b771031059b62764fc" alt="How Does Story Protect IP?" data-og-width="2284" width="2284" data-og-height="1298" height="1298" data-path="images/concepts/hdspip.png" data-optimize="true" data-opv="3" srcset="https://mintcdn.com/story/Ci-RgMKFKns3XzFq/images/concepts/hdspip.png?w=280&fit=max&auto=format&n=Ci-RgMKFKns3XzFq&q=85&s=7985b727656f6b3f744ac09ebbe3e9dc 280w, https://mintcdn.com/story/Ci-RgMKFKns3XzFq/images/concepts/hdspip.png?w=560&fit=max&auto=format&n=Ci-RgMKFKns3XzFq&q=85&s=bd74fc935eab62668deaab25d792f241 560w, https://mintcdn.com/story/Ci-RgMKFKns3XzFq/images/concepts/hdspip.png?w=840&fit=max&auto=format&n=Ci-RgMKFKns3XzFq&q=85&s=3fb3828753ad2aad535c8c17081db974 840w, https://mintcdn.com/story/Ci-RgMKFKns3XzFq/images/concepts/hdspip.png?w=1100&fit=max&auto=format&n=Ci-RgMKFKns3XzFq&q=85&s=376549c40a56a1bb91bb2ea9ac3873d8 1100w, https://mintcdn.com/story/Ci-RgMKFKns3XzFq/images/concepts/hdspip.png?w=1650&fit=max&auto=format&n=Ci-RgMKFKns3XzFq&q=85&s=91501c1485dd5a6104bb04925c974bce 1650w, https://mintcdn.com/story/Ci-RgMKFKns3XzFq/images/concepts/hdspip.png?w=2500&fit=max&auto=format&n=Ci-RgMKFKns3XzFq&q=85&s=12e35bda35166f3cb0225ab2c6ca148b 2500w" />
</Frame>

<Tip>Every license created on Story is a real, enforceable legal contract.</Tip>

## The Programmable IP License (PIL): The Foundation of Legal Enforcement

At its core, every [IP Asset](/concepts/ip-asset) registered on Story is wrapped by a **legally binding document called the [Programmable IP License (PIL)](/concepts/programmable-ip-license)**. Based on US copyright law, the PIL acts as a universal license agreement template that allows IP owners to attach customizable terms to their assets.

**Licensing on Story means making a genuine legal commitment.** The parameters defined in the PIL—commercial use, derivative allowances, attribution requirements, and royalty structures—represent legally enforceable terms between the IP owner (licensor) and anyone who licenses the IP (licensee).

### How does the PIL enable enforcement?

* **Clear Legal Terms:** The PIL provides a standardized way for IP owners to define usage rules.
* **On-Chain Record as Evidence:** PIL terms attached to an IP Asset are recorded immutably on Story's purpose-built blockchain, serving as *irrefutable evidence* of the agreed-upon terms.
* **Off-Chain Legal Recourse:** If IP is misused in violation of PIL terms, the IP owner can leverage on-chain evidence in **off-chain legal proceedings** such as arbitration or court actions.
* **License Tokens as Proof of Rights:** Licensees receive a [**License Token**](/concepts/licensing-module/license-token) (NFT) representing specific usage rights granted under the PIL terms, providing further evidence of authorization status.

## The Story Attestation Service (SAS): Proactive Infringement Monitoring

Beyond the legal framework, we are building the [**Story Attestation Service (SAS)**](/concepts/story-attestation-service) to help IP owners monitor for potential copyright infringement using a multi-layered decentralized approach.

<Note>
  SAS is a signal layer, not a judgment layer—it flags potential issues for the
  IP owner to act upon, rather than taking automated enforcement actions.
</Note>

### How the SAS Helps with Infringement Detection:

* **Network of Specialized Providers:** SAS coordinates with service providers like Yakoa and Pex that use AI and machine learning to detect copyright violations across different media types on the internet and other blockchains.
* **Transparent Signals:** SAS provides publicly accessible signals regarding the legitimacy of an IP Asset based on provider findings.
* **Focus on Commercial IP:** Currently, SAS primarily runs infringement checks on commercial IP Assets—those with at least one License Terms where `commercialUse = true`.
* **Metadata-Driven Checks:** SAS relies on IP-specific metadata provided during registration to perform checks against existing online content.

### Important Considerations:

* **Detection, Not Prevention:** SAS primarily flags potential infringements after IP registration rather than preventing them.
* **Internet-Based Checks:** Currently, SAS primarily detects infringement based on content already existing online, not offline uses.
* **No Guarantee of Perfection:** No system can guarantee 100% detection of all copyright infringement.

## The Role of the Dispute Module

We have also built a [**Dispute Module**](/concepts/dispute-module) that allows anyone to raise on-chain disputes against IP Assets for reasons such as improper registration or potential plagiarism. This can lead to on-chain flagging of disputed IP, potentially affecting its ability to generate licenses or earn revenue.

## The Hybrid Enforcement Model

<Note>
  Story doesn't replace courts or lawyers—it gives IP holders tools that work
  with traditional enforcement systems while benefiting from on-chain
  automation, transparency, and interoperability.
</Note>

### What Story Can Do:

* Provide a legally sound framework for IP licensing through the PIL
* Create an immutable on-chain record of IP ownership and license terms
* Offer monitoring tools through the SAS to detect potential online infringement
* Facilitate on-chain dispute resolution through the Dispute Module
* Provide evidence usable for off-chain legal enforcement

### What Story Cannot Do:

* Act as a global police force for IP infringement
* Guarantee prevention of all unauthorized IP uses
* Directly enforce legal judgments in the physical world
* Monitor every digital and physical interaction with registered IP

```
+--------------------------+      +-----------------------------+
| IP Owner Registers IP on |----->| IP Asset Created on Story   |
| Story                    |      | (with associated metadata)  |
+--------------------------+      +-----------------------------+
                                          |
                                          v
+---------------------------------------+   +-------------------------+
| Programmable IP License (PIL)         |<--| IP Owner Attaches Legal |
| (Legal wrapper defining usage terms)  |   | Terms via PIL           |
+---------------------------------------+   +-------------------------+
                                          |
                                          v
                                  +-------------------------+
                                  | IP Asset with PIL Terms |
                                  | (Commercial Use = true) |
                                  +-------------------------+
                                          |
                                          v
+--------------------------+      +-------------------------------------+
| Story Attestation        |----->| SAS Providers Scan Internet & Other |
| Service (SAS) Coordinates|      | Sources for Infringement (using IP  |
+--------------------------+      | Metadata)                           |
                                  +-------------------------------------+
                                          |
                                          v
+----------------------------------------------------------------------+
| SAS Providers Report Potential Infringement Signals for the IP Asset |
| (e.g., "Potential copy found on website X")                          |
+----------------------------------------------------------------------+
                                          |
                                          v
+---------------------------------------------------------------------+
| IP Owner Reviews SAS Signals on IP Portal (Coming Soon)             |
+---------------------------------------------------------------------+
                                          |
                                          v
+---------------------------------------------------------------------+
| IP Owner Can Use SAS Signals & PIL Terms as Evidence for:           |
| - On-Chain Dispute via Dispute Module                               |
| - Off-Chain Legal Action (e.g., Cease & Desist, Lawsuit)            |
+---------------------------------------------------------------------+

```
# PIL Flavors (examples)

> Pre-configured License Terms for ease of use

The [💊 Programmable IP License (PIL)](/concepts/programmable-ip-license/overview) is very configurable, but we support popular pre-configured License Terms (also known as "flavors") for ease of use. We expect these to be the most popular options:

<Frame>
  <img src="https://mintcdn.com/story/Ci-RgMKFKns3XzFq/images/concepts/pil-flavor-compare.png?fit=max&auto=format&n=Ci-RgMKFKns3XzFq&q=85&s=b5b2f3912aabe9f3b684b6cb3acadd12" alt="PIL Flavor Comparison" data-og-width="3702" width="3702" data-og-height="1017" height="1017" data-path="images/concepts/pil-flavor-compare.png" data-optimize="true" data-opv="3" srcset="https://mintcdn.com/story/Ci-RgMKFKns3XzFq/images/concepts/pil-flavor-compare.png?w=280&fit=max&auto=format&n=Ci-RgMKFKns3XzFq&q=85&s=6b0a5630648234b045ccf2e914be5c9b 280w, https://mintcdn.com/story/Ci-RgMKFKns3XzFq/images/concepts/pil-flavor-compare.png?w=560&fit=max&auto=format&n=Ci-RgMKFKns3XzFq&q=85&s=27b5db9861fa19c975304c910f760490 560w, https://mintcdn.com/story/Ci-RgMKFKns3XzFq/images/concepts/pil-flavor-compare.png?w=840&fit=max&auto=format&n=Ci-RgMKFKns3XzFq&q=85&s=b91a20112c5374757a1b053e9c7760a1 840w, https://mintcdn.com/story/Ci-RgMKFKns3XzFq/images/concepts/pil-flavor-compare.png?w=1100&fit=max&auto=format&n=Ci-RgMKFKns3XzFq&q=85&s=0e0e2f84ac6e94fbe8e4752d6ee75087 1100w, https://mintcdn.com/story/Ci-RgMKFKns3XzFq/images/concepts/pil-flavor-compare.png?w=1650&fit=max&auto=format&n=Ci-RgMKFKns3XzFq&q=85&s=7c6ad196a1f52302cd1f6057fc12c4d4 1650w, https://mintcdn.com/story/Ci-RgMKFKns3XzFq/images/concepts/pil-flavor-compare.png?w=2500&fit=max&auto=format&n=Ci-RgMKFKns3XzFq&q=85&s=d2b82fc5f6a5e734616748e35c90f808 2500w" />
</Frame>

## Non-Commercial Social Remixing

<Note>
  This flavor is already registered as `licenseTermsId = 1` on our protocol. This is because it doesn't take any inputs, so we registered it ahead of time.
</Note>

Let the world build on and play with your creation. This license allows for endless free remixing while tracking all uses of your work while giving you full credit. Similar to: TikTok plus attribution.

### What others can do?

| Others can                                            | Others cannot                                                                       |
| ----------------------------------------------------- | ----------------------------------------------------------------------------------- |
| ✅ Remix this work (`derivativesAllowed == true`)      | ❌ Commercialize the original and derivative works (`commercialUse == false`)        |
| ✅ Distribute their remix anywhere                     | ❌ Claim credit for any derivative works (`derivativesAttribution == true`)          |
| ✅ Get the license for free (`defaultMintingFee == 0`) | ❌ Claim credit for the original work ("Attribution" is true in the off-chain terms) |

### PIL Term Values

* **On-chain**:

<CodeGroup>
  ```solidity Solidity theme={null}
  PILTerms({
    transferable: true,
    royaltyPolicy: address(0),
    defaultMintingFee: 0,
    expiration: 0,
    commercialUse: false,
    commercialAttribution: false,
    commercializerChecker: address(0),
    commercializerCheckerData: EMPTY_BYTES,
    commercialRevShare: 0,
    commercialRevCeiling: 0,
    derivativesAllowed: true,
    derivativesAttribution: true,
    derivativesApproval: false,
    derivativesReciprocal: true,
    derivativeRevCeiling: 0,
    currency: address(0),
    uri: "https://github.com/piplabs/pil-document/blob/998c13e6ee1d04eb817aefd1fe16dfe8be3cd7a2/off-chain-terms/NCSR.json"
  });
  ```

  ```typescript TypeScript theme={null}
  import { zeroAddress } from "viem";
  import { LicenseTerms } from "@story-protocol/core-sdk";

  const nonCommercialSocialRemix: LicenseTerms = {
    transferable: true,
    royaltyPolicy: zeroAddress,
    defaultMintingFee: 0n,
    expiration: 0n,
    commercialUse: false,
    commercialAttribution: false,
    commercializerChecker: zeroAddress,
    commercializerCheckerData: "0x",
    commercialRevShare: 0,
    commercialRevCeiling: 0n,
    derivativesAllowed: true,
    derivativesAttribution: true,
    derivativesApproval: false,
    derivativesReciprocal: true,
    derivativeRevCeiling: 0n,
    currency: zeroAddress,
    uri: "https://github.com/piplabs/pil-document/blob/998c13e6ee1d04eb817aefd1fe16dfe8be3cd7a2/off-chain-terms/NCSR.json",
  };
  ```
</CodeGroup>

* **Off-chain:**

| Parameter                         | Options / Tags                                                              |
| --------------------------------- | --------------------------------------------------------------------------- |
| Territory                         | No restrictions                                                             |
| Channels of Distribution          | No Restriction                                                              |
| Attribution                       | True                                                                        |
| Content Standards                 | No-Hate, Suitable-for-All-Ages, No-Drugs-or-Weapons, No-Pornography         |
| Sublicensable                     | False                                                                       |
| AI Learning Models                | False                                                                       |
| Restriction on Cross-Platform Use | False                                                                       |
| Governing Law                     | California, USA                                                             |
| Alternative Dispute Resolution    | Tag: Alternative-Dispute-Resolution Ledger-Authoritative-Dispute-Resolution |
| Additional License Parameters     | None                                                                        |

## Commercial Use

Retain control over reuse of your work, while allowing anyone to appropriately use the work in exchange for the economic terms you set. This is similar to Shutterstock with creator-set rules.

### What others can do?

| Others can                                                  | Others cannot                                                                                             |
| ----------------------------------------------------------- | --------------------------------------------------------------------------------------------------------- |
| ✅ Commercialize the original work (`commercialUse == true`) | ❌ Remix this work (`derivativesAllowed == false`)                                                         |
| ✅ Keep all revenue (`commercialRevShare == 0`)              | ❌ Claim credit for the original work (`commercialAttribution == true`)                                    |
|                                                             | ❌ Get the license for free (`defaultMintingFee` is set)                                                   |
|                                                             | ❌ Claim credit for the original work even non-commercially ("Attribution" is true in the off-chain terms) |

### PIL Term Values

* **On-chain**:

<CodeGroup>
  ```solidity Solidity theme={null}
  PILTerms({
    transferable: true,
    royaltyPolicy: ROYALTY_POLICY, // ex. RoyaltyPolicyLAP address
    defaultMintingFee: MINTING_FEE, // ex. 1000000000000000000 (which means it costs 1 $WIP to mint)
    expiration: 0,
    commercialUse: true,
    commercialAttribution: true,
    commercializerChecker: address(0),
    commercializerCheckerData: EMPTY_BYTES,
    commercialRevShare: 0,
    commercialRevCeiling: 0,
    derivativesAllowed: false,
    derivativesAttribution: false,
    derivativesApproval: false,
    derivativesReciprocal: false,
    derivativeRevCeiling: 0,
    currency: CURRENCY, // ex. $WIP address
    uri: "https://github.com/piplabs/pil-document/blob/9a1f803fcf8101a8a78f1dcc929e6014e144ab56/off-chain-terms/CommercialUse.json"
  })
  ```

  ```typescript TypeScript theme={null}
  import { zeroAddress, parseEther } from "viem";
  import { LicenseTerms } from "@story-protocol/core-sdk";

  const commercialUse: LicenseTerms = {
    transferable: true,
    royaltyPolicy: ROYALTY_POLICY, // ex. RoyaltyPolicyLAP address
    defaultMintingFee: MINTING_FEE, // ex. parseEther("1") (which means it costs 1 $WIP to mint)
    expiration: 0n,
    commercialUse: true,
    commercialAttribution: true,
    commercializerChecker: zeroAddress,
    commercializerCheckerData: "0x",
    commercialRevShare: 0,
    commercialRevCeiling: 0n,
    derivativesAllowed: false,
    derivativesAttribution: false,
    derivativesApproval: false,
    derivativesReciprocal: false,
    derivativeRevCeiling: 0n,
    currency: CURRENCY, // ex. $WIP address
    uri: "https://github.com/piplabs/pil-document/blob/9a1f803fcf8101a8a78f1dcc929e6014e144ab56/off-chain-terms/CommercialUse.json",
  };
  ```
</CodeGroup>

* **Off-chain**

| Parameter                         | Options / Tags                                                              |
| --------------------------------- | --------------------------------------------------------------------------- |
| Territory                         | No restrictions                                                             |
| Channels of Distribution          | No Restriction                                                              |
| Attribution                       | True                                                                        |
| Content Standards                 | No-Hate, Suitable-for-All-Ages, No-Drugs-or-Weapons, No-Pornography         |
| Sublicensable                     | False                                                                       |
| AI Learning Models                | False                                                                       |
| Restriction on Cross-Platform Use | False                                                                       |
| Governing Law                     | California, USA                                                             |
| Alternative Dispute Resolution    | Tag: Alternative-Dispute-Resolution Ledger-Authoritative-Dispute-Resolution |
| Additional License Parameters     | None                                                                        |

## Commercial Remix

Let the world build on and play with your creation... and earn money together from it! This license allows for endless free remixing while tracking all uses of your work while giving you full credit, with each derivative paying a percentage of revenue to its "parent" IP.

### Example

Check out Story's official mascot **Ippy**, which we have registered with commercial remix terms on both [Mainnet](https://explorer.story.foundation/ipa/0xB1D831271A68Db5c18c8F0B69327446f7C8D0A42) and [Aeneid Testnet](https://aeneid.explorer.story.foundation/ipa/0x641E638e8FCA4d4844F509630B34c9D524d40BE5).

### What others can do?

| Others can                                                                  | Others cannot                                                                                             |
| --------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------- |
| ✅ Remix this work (`derivativesAllowed == true`)                            | ❌ Claim credit for the original work (`commercialAttribution == true`)                                    |
| ✅ Commercialize the original and derivative works (`commercialUse == true`) | ❌ Claim credit for any derivative works (`derivativesAttribution == true`)                                |
| ✅ Distribute their remix anywhere                                           | ❌ Keep all revenue (`commercialRevShare` is set)                                                          |
|                                                                             | ❌ Get the license for free (`defaultMintingFee` is set)                                                   |
|                                                                             | ❌ Claim credit for the original work even non-commercially ("Attribution" is true in the off-chain terms) |

### PIL Term Values

* **On-chain**:

<CodeGroup>
  ```solidity Solidity theme={null}
  PILTerms({
    transferable: true,
    royaltyPolicy: ROYALTY_POLICY, // ex. RoyaltyPolicyLAP address
    defaultMintingFee: MINTING_FEE, // ex. 1000000000000000000 (which means it costs 1 $WIP to mint)
    expiration: 0,
    commercialUse: true,
    commercialAttribution: true,
    commercializerChecker: address(0),
    commercializerCheckerData: EMPTY_BYTES,
    commercialRevShare: COMMERCIAL_REV_SHARE, // ex. 50 * 10 ** 6 (which means 50% of derivative revenue)
    commercialRevCeiling: 0,
    derivativesAllowed: true,
    derivativesAttribution: true,
    derivativesApproval: false,
    derivativesReciprocal: true,
    derivativeRevCeiling: 0,
    currency: CURRENCY, // ex. $WIP address
    uri: "https://github.com/piplabs/pil-document/blob/ad67bb632a310d2557f8abcccd428e4c9c798db1/off-chain-terms/CommercialRemix.json"
  });
  ```

  ```typescript TypeScript theme={null}
  import { zeroAddress, parseEther } from "viem";
  import { LicenseTerms } from "@story-protocol/core-sdk";

  const commercialRemix: LicenseTerms = {
    transferable: true,
    royaltyPolicy: ROYALTY_POLICY, // ex. RoyaltyPolicyLAP address
    defaultMintingFee: MINTING_FEE, // ex. parseEther("1") (which means it costs 1 $WIP to mint)
    expiration: 0n,
    commercialUse: true,
    commercialAttribution: true,
    commercializerChecker: zeroAddress,
    commercializerCheckerData: "0x",
    commercialRevShare: COMMERCIAL_REV_SHARE, // ex. 50 (which means 50% of derivative revenue)
    commercialRevCeiling: 0n,
    derivativesAllowed: true,
    derivativesAttribution: true,
    derivativesApproval: false,
    derivativesReciprocal: true,
    derivativeRevCeiling: 0n,
    currency: CURRENCY, // ex. $WIP address
    uri: "https://github.com/piplabs/pil-document/blob/ad67bb632a310d2557f8abcccd428e4c9c798db1/off-chain-terms/CommercialRemix.json",
  };
  ```
</CodeGroup>

* **Off-chain**

| Parameter                         | Options / Tags                                                              |
| --------------------------------- | --------------------------------------------------------------------------- |
| Territory                         | No restrictions                                                             |
| Channels of Distribution          | No Restriction                                                              |
| Attribution                       | True                                                                        |
| Content Standards                 | No-Hate, Suitable-for-All-Ages, No-Drugs-or-Weapons, No-Pornography         |
| Sublicensable                     | False                                                                       |
| AI Learning Models                | False                                                                       |
| Restriction on Cross-Platform Use | False                                                                       |
| Governing Law                     | California, USA                                                             |
| Alternative Dispute Resolution    | Tag: Alternative-Dispute-Resolution Ledger-Authoritative-Dispute-Resolution |
| Additional License Parameters     | None                                                                        |

## Creative Commons Attribution

Let the world build on and play with your creation - including making money.

### What others can do?

| Others can                                                                  | Others cannot                                                                                             |
| --------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------- |
| ✅ Remix this work (`derivativesAllowed == true`)                            | ❌ Claim credit for the original work (`commercialAttribution == true`)                                    |
| ✅ Commercialize the original and derivative works (`commercialUse == true`) | ❌ Claim credit for any derivative works (`derivativesAttribution == true`)                                |
| ✅ Distribute their remix anywhere                                           | ❌ Claim credit for the original work even non-commercially ("Attribution" is true in the off-chain terms) |
| ✅ Get the license for free (`defaultMintingFee == 0`)                       |                                                                                                           |
| ✅ Keep all revenue (`commercialRevShare == 0`)                              |                                                                                                           |

### PIL Term Values

* **On-chain**:

<CodeGroup>
  ```solidity Solidity theme={null}
  PILTerms({
    transferable: true,
    royaltyPolicy: ROYALTY_POLICY, // ex. RoyaltyPolicyLAP address
    defaultMintingFee: 0,
    expiration: 0,
    commercialUse: true,
    commercialAttribution: true,
    commercializerChecker: address(0),
    commercializerCheckerData: EMPTY_BYTES,
    commercialRevShare: 0,
    commercialRevCeiling: 0,
    derivativesAllowed: true,
    derivativesAttribution: true,
    derivativesApproval: false,
    derivativesReciprocal: true,
    derivativeRevCelling: 0,
    currency: CURRENCY, // ex. $WIP address
    uri: 'https://github.com/piplabs/pil-document/blob/998c13e6ee1d04eb817aefd1fe16dfe8be3cd7a2/off-chain-terms/CC-BY.json'
  });
  ```

  ```typescript TypeScript theme={null}
  import { zeroAddress } from "viem";
  import { LicenseTerms } from "@story-protocol/core-sdk";

  const creativeCommonsAttribution: LicenseTerms = {
    transferable: true,
    royaltyPolicy: ROYALTY_POLICY, // ex. RoyaltyPolicyLAP address
    defaultMintingFee: 0n,
    expiration: 0n,
    commercialUse: true,
    commercialAttribution: true,
    commercializerChecker: zeroAddress,
    commercializerCheckerData: "0x",
    commercialRevShare: 0,
    commercialRevCeiling: 0n,
    derivativesAllowed: true,
    derivativesAttribution: true,
    derivativesApproval: false,
    derivativesReciprocal: true,
    derivativeRevCelling: 0n,
    currency: CURRENCY, // ex. $WIP address
    uri: "https://github.com/piplabs/pil-document/blob/998c13e6ee1d04eb817aefd1fe16dfe8be3cd7a2/off-chain-terms/CC-BY.json",
  };
  ```
</CodeGroup>

* **Off-chain**

| Parameter                         | Options / Tags                                                              |
| --------------------------------- | --------------------------------------------------------------------------- |
| Territory                         | No restrictions                                                             |
| Channels of Distribution          | No Restriction                                                              |
| Attribution                       | True                                                                        |
| Content Standards                 | No-Hate, Suitable-for-All-Ages, No-Drugs-or-Weapons, No-Pornography         |
| Sublicensable                     | False                                                                       |
| AI Learning Models                | True                                                                        |
| Restriction on Cross-Platform Use | False                                                                       |
| Governing Law                     | California, USA                                                             |
| Alternative Dispute Resolution    | Tag: Alternative-Dispute-Resolution Ledger-Authoritative-Dispute-Resolution |
| Additional License Parameters     | None                                                                        |

# Examples

Here are some common examples of royalty flow. *More coming soon!*

## Example 1

<Frame>
  <img src="https://mintcdn.com/story/Ci-RgMKFKns3XzFq/images/concepts/flavor-1.png?fit=max&auto=format&n=Ci-RgMKFKns3XzFq&q=85&s=6a0633e9dc2a7be138715ab9056737bb" alt="Example 1 Royalty Flow" data-og-width="1628" width="1628" data-og-height="1252" height="1252" data-path="images/concepts/flavor-1.png" data-optimize="true" data-opv="3" srcset="https://mintcdn.com/story/Ci-RgMKFKns3XzFq/images/concepts/flavor-1.png?w=280&fit=max&auto=format&n=Ci-RgMKFKns3XzFq&q=85&s=8a1326c28be0c69f84a34c9d8cd86e88 280w, https://mintcdn.com/story/Ci-RgMKFKns3XzFq/images/concepts/flavor-1.png?w=560&fit=max&auto=format&n=Ci-RgMKFKns3XzFq&q=85&s=8519893fcdb9b07f9f64464854cf0586 560w, https://mintcdn.com/story/Ci-RgMKFKns3XzFq/images/concepts/flavor-1.png?w=840&fit=max&auto=format&n=Ci-RgMKFKns3XzFq&q=85&s=5356049f6857d540d84cc4876b0d668a 840w, https://mintcdn.com/story/Ci-RgMKFKns3XzFq/images/concepts/flavor-1.png?w=1100&fit=max&auto=format&n=Ci-RgMKFKns3XzFq&q=85&s=0b24c22bf84e9490bfda20fd28f4695f 1100w, https://mintcdn.com/story/Ci-RgMKFKns3XzFq/images/concepts/flavor-1.png?w=1650&fit=max&auto=format&n=Ci-RgMKFKns3XzFq&q=85&s=5dd4c34a1f2fb8eb56c549f726b36f1f 1650w, https://mintcdn.com/story/Ci-RgMKFKns3XzFq/images/concepts/flavor-1.png?w=2500&fit=max&auto=format&n=Ci-RgMKFKns3XzFq&q=85&s=377390651fa242d0e599b6ab007531f3 2500w" />
</Frame>

### Explanation

Someone registers their Azuki on Story. By default, that IP Asset has Non-Commercial Social Remixing Terms, which specify that anyone can create derivatives of that work but cannot commercialize them. So, someone else creates & registers a remix of that work (IPA2) which inherits those same terms. Someone else then does the same to IPA2, creating & registering IPA3.

The owner of IPA1 then decides that others can commercialize the work, but they cannot create derivatives to do so, they must pay a 10 \$WIP minting fee, and they must share 10% of all revenue earned. So, someone wants to commercialize IPA1 by putting it on a t-shirt. They pay the 10 \$WIP minting fee to get a License Token, which represents the license to commercialize IPA1. They then put the image on a t-shirt and sell it. 10% of revenue earned by that t-shirt must be sent on-chain to IPA1.

## Example 2

<Frame>
  <img src="https://mintcdn.com/story/Ci-RgMKFKns3XzFq/images/concepts/flavor-2.png?fit=max&auto=format&n=Ci-RgMKFKns3XzFq&q=85&s=e2318fab1d0620738f4b5a7a0300be2c" alt="Example 2 Royalty Flow" data-og-width="1642" width="1642" data-og-height="1150" height="1150" data-path="images/concepts/flavor-2.png" data-optimize="true" data-opv="3" srcset="https://mintcdn.com/story/Ci-RgMKFKns3XzFq/images/concepts/flavor-2.png?w=280&fit=max&auto=format&n=Ci-RgMKFKns3XzFq&q=85&s=c61215f27eb4f2f37b22c53087880ae7 280w, https://mintcdn.com/story/Ci-RgMKFKns3XzFq/images/concepts/flavor-2.png?w=560&fit=max&auto=format&n=Ci-RgMKFKns3XzFq&q=85&s=95fbeebc8563ff7fb03cbf25fe5dd699 560w, https://mintcdn.com/story/Ci-RgMKFKns3XzFq/images/concepts/flavor-2.png?w=840&fit=max&auto=format&n=Ci-RgMKFKns3XzFq&q=85&s=c24fe1c1330d29b6a292514579e84ea4 840w, https://mintcdn.com/story/Ci-RgMKFKns3XzFq/images/concepts/flavor-2.png?w=1100&fit=max&auto=format&n=Ci-RgMKFKns3XzFq&q=85&s=4361dabcdf76acdcf0dbf111b19914a1 1100w, https://mintcdn.com/story/Ci-RgMKFKns3XzFq/images/concepts/flavor-2.png?w=1650&fit=max&auto=format&n=Ci-RgMKFKns3XzFq&q=85&s=d2ebc89df976282243f6e14d16ba8f65 1650w, https://mintcdn.com/story/Ci-RgMKFKns3XzFq/images/concepts/flavor-2.png?w=2500&fit=max&auto=format&n=Ci-RgMKFKns3XzFq&q=85&s=d9b5c6557b35e3ffb8caa76c79d3acb9 2500w" />
</Frame>

### Explanation

Someone registers their Azuki on Story. By default, that IP Asset has Non-Commercial Social Remixing Terms, which specify that anyone can create derivatives of that work but cannot commercialize them. So, someone else creates & registers a remix of that work (IPA2) which inherits those same terms. Someone else then does the same to IPA2, creating & registering IPA3.

The owner of IPA1 then decides that others can create derivatives of their work and commercialize them, but they must pay a 10 \$WIP minting fee and share 10% of all revenue earned. So, someone wants to commercialize IPA1 by putting it on a t-shirt. They pay the 10 \$WIP minting fee to get a License Token and burn it to create their own derivative, which changes the background color to red. They then put the remixed image on a t-shirt and sell it. 10% of revenue earned by that t-shirt must be sent on-chain to IPA1.

A third person wants to commercialize the remix by putting it in a TV advertisement, but they want to change the hair color to white. So, they pay a 10 \$WIP minting fee (of which, 1 \$WIP gets sent back to IPA1) to create their own derivative. They then put the remixed image in a TV ad. 10% of TV advertising revenue earned must be sent on-chain to IPA4, of which 10% will be distributed back to IPA1.
# PIL Terms

> Detailed explanation of all terms available in the Programmable IP License

<CardGroup cols={3}>
  <Card title="Read the Overview" href="/concepts/programmable-ip-license/overview" icon="pills" color="yellow">
    If you haven't already, read the Programmable IP License (PIL💊) overview.
  </Card>

  <Card title="Preset PIL Terms" href="/concepts/programmable-ip-license/pil-flavors" icon="thumbs-up" color="#51af51">
    Since there are so many possible combinations of the PIL, we have created
    preset "flavors" for you to use while developing.
  </Card>

  <Card title="PIL Legal Text" href="https://github.com/piplabs/pil-document/blob/main/Story%20Foundation%20-%20Programmable%20IP%20License%20(1.31.25).pdf" icon="scroll" color="#ccb092">
    Check out the actual PIL legal text. It is very human-readable for a legal
    text!
  </Card>
</CardGroup>

# On-chain terms

Most PIL terms are on-chain. They are implemented in the `IPILicenseTemplate.sol` contract as a `PILTerms` struct [here](https://github.com/storyprotocol/protocol-core-v1/blob/main/contracts/interfaces/modules/licensing/IPILicenseTemplate.sol).

```solidity IPILicenseTemplate.sol theme={null}
/// @notice This struct defines the terms for a Programmable IP License (PIL).
/// These terms can be attached to IP Assets.
struct PILTerms {
  bool transferable;
  address royaltyPolicy;
  uint256 defaultMintingFee;
  uint256 expiration;
  bool commercialUse;
  bool commercialAttribution;
  address commercializerChecker;
  bytes commercializerCheckerData;
  uint32 commercialRevShare;
  uint256 commercialRevCeiling;
  bool derivativesAllowed;
  bool derivativesAttribution;
  bool derivativesApproval;
  bool derivativesReciprocal;
  uint256 derivativeRevCeiling;
  address currency;
  string uri;
}
```

## Descriptions

| Parameter                   | Values           | Description                                                                                                                                                                                                                                                                                                                                                                                            |
| --------------------------- | ---------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| `transferable`              | True/False       | If false, the License Token cannot be transferred once it is minted to a recipient address.                                                                                                                                                                                                                                                                                                            |
| `royaltyPolicy`             | Address          | The address of the royalty policy contract.                                                                                                                                                                                                                                                                                                                                                            |
| `defaultMintingFee`         | #                | The fee to be paid when minting a license.                                                                                                                                                                                                                                                                                                                                                             |
| `expiration`                | #                | The expiration period of the license.                                                                                                                                                                                                                                                                                                                                                                  |
| `commercialUse`             | True/False       | You can make money from using the original IP Asset, subject to limitations below.                                                                                                                                                                                                                                                                                                                     |
| `commercialAttribution`     | True/False       | If true, people must give credit to the original work in their commercial application (eg. merch)                                                                                                                                                                                                                                                                                                      |
| `commercializerChecker`     | Address          | Commercializers that are allowed to commercially exploit the original work. If zero address, then no restrictions are enforced.                                                                                                                                                                                                                                                                        |
| `commercializerCheckerData` | Bytes            | The data to be passed to the commercializer checker contract.                                                                                                                                                                                                                                                                                                                                          |
| `commercialRevShare`        | \[0-100,000,000] | Amount of revenue (from any source, original & derivative) that must be shared with the licensor (a value of 10,000,000 == 10% of revenue share). This will collect all revenue from tokens that are whitelisted in the [RoyaltyModule.sol contract](https://github.com/storyprotocol/protocol-core-v1/blob/e339f0671c9172a6699537285e32aa45d4c1b57b/contracts/modules/royalty/RoyaltyModule.sol#L50). |
| `commercialRevCeiling`      | #                | If `commercialUse` is set to true, this value determines the maximum revenue you can earn from the original work.                                                                                                                                                                                                                                                                                      |
| `derivativesAllowed`        | True/False       | Indicates whether the licensee can create derivatives of his work or not.                                                                                                                                                                                                                                                                                                                              |
| `derivativesAttribution`    | True/False       | If true, derivatives that are made must give credit to the original work.                                                                                                                                                                                                                                                                                                                              |
| `derivativesApproval`       | True/False       | If true, the licensor must approve derivatives of the work.                                                                                                                                                                                                                                                                                                                                            |
| `derivativesReciprocal`     | True/False       | If false, you cannot create a derivative of a derivative. Set this to true to allow indefinite remixing.                                                                                                                                                                                                                                                                                               |
| `derivativeRevCeiling`      | #                | If `commercialUse` is set to true, this value determines the maximum revenue you can earn from derivative works.                                                                                                                                                                                                                                                                                       |
| `currency`                  | Address          | The ERC20 token to be used to pay the minting fee. The token must be registered on Story.                                                                                                                                                                                                                                                                                                              |
| `uri`                       | String           | The URI of the license terms, which can be used to fetch [off-chain license terms](/concepts/programmable-ip-license/pil-terms#off-chain-terms-to-be-included-in-uri-field).                                                                                                                                                                                                                           |

# Off-chain terms to be included in `uri` field

Some PIL terms must be stored off-chain and passed in the `uri` field above. This is because these terms are often more lengthy and/or descriptive, so it would not make sense to store them on-chain.

| Parameter                       | Description                                                                                                                                                                                                                                           |
| ------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `territory`                     | Limit usage of the IP to certain regions and/or countries. By default, the IP can be used globally.                                                                                                                                                   |
| `channelsOfDistribution`        | Restrict usage of the IP to certain media formats and use in certain channels of distribution. By default, the IP can be used across all possible channels of distribution. Examples: "television", "physical consumer products", "video games", etc. |
| `attribution`                   | If the original author should be credited for usage of the IP. By default, you do not need to provide credit to the original author.                                                                                                                  |
| `contentStandards`              | Set content standards around use of the IP. By default, no standards apply. Examples: "No-Hate", "Suitable-for-All-Ages", "No-Drugs-or-Weapons", "No-Pornography".                                                                                    |
| `sublicensable`                 | Derivative works can grant the same rights they received under this license to a 3rd party, without approval from the original licensor. By default, derivatives may not do so.                                                                       |
| `aiLearningModels`              | Whether or not the IP can be used to develop AI learning models. By default, the IP **cannot** be used for such development.                                                                                                                          |
| `restrictionOnCrossPlatformUse` | Limit licensing and creation of derivative works solely on the app on which the IP is made available. By default, the IP can be used anywhere.                                                                                                        |
| `governingLaw`                  | The laws of a certain jurisdiction by which this license abides. By default, this is California, USA.                                                                                                                                                 |
| `alternativeDisputeResolution`  | Please see section 3.1 (s) [here](https://github.com/piplabs/pil-document/blob/main/Story%20Foundation%20-%20Programmable%20IP%20License%20\(1.31.25\).pdf).                                                                                          |
| `PILUri`                        | The URI to the PIL legal terms.                                                                                                                                                                                                                       |
| `additionalParameters`          | There may be other terms the licensor would like to add and they can do so in this tag.                                                                                                                                                               |
# Mainnet

> Information and Resources for the Story's Mainnet

<CardGroup cols={1}>
  <Card title="Connet to Mainnet" href="https://chainid.network/chain/1514/" icon="house">
    Connect your wallet to Story's Mainnet.
  </Card>
</CardGroup>

# Resources

**Network Name**: Story Mainnet

**Chain ID**: 1514

**Chainlist Link**: [https://chainlist.org/chain/1514](https://chainlist.org/chain/1514)

## RPCs

| RPC Name           | RPC URL                                                     | Official |
| :----------------- | :---------------------------------------------------------- | :------: |
| Story              | `https://mainnet.storyrpc.io`                               |     ✅    |
| Story by Ankr      | `https://rpc.ankr.com/story_mainnet`                        |          |
| Story by QuickNode | `https://www.quicknode.com/chains/story`                    |          |
| Story by Alchemy   | `https://story-mainnet.g.alchemy.com/v2/${ALCHEMY_API_KEY}` |          |
| Story by Tenderly  | `https://tenderly.co/`                                      |          |

## Block Explorers

| Explorer                                                                                                                | URL                                 | Official |
| :---------------------------------------------------------------------------------------------------------------------- | :---------------------------------- | :------: |
| [BlockScout Explorer ↗️](https://www.storyscan.io/)                                                                     | `https://www.storyscan.io/`         |     ✅    |
| [IP Explorer ↗️](https://explorer.story.foundation) (only for IP-related actions like licensing, minting licenses, etc) | `https://explorer.story.foundation` |     ✅    |
| [Stakeme Explorer ↗️](https://storyscan.app/)                                                                           | `https://storyscan.app/`            |          |

## Staking Dashboard

| Dashboard URL                                        | Official |
| :--------------------------------------------------- | :------: |
| [Story Dashboard](https://staking.story.foundation/) |     ✅    |
| [Origin Stake](https://ipworld.io/)                  |          |
| [Node.Guru](https://story.explorers.guru/)           |          |

## Contract deployment addresses

* [Proof of Creativity](/developers/deployed-smart-contracts)
# Testnet - Aeneid

> Information and resources for the Story Testnet (Aeneid)

<CardGroup cols={1}>
  <Card title="Connect to 'Aeneid' Testnet" href="https://chainid.network/chain/1315/" icon="house">
    Connect your wallet to Story's 'Aeneid' testnet.
  </Card>
</CardGroup>

# Resources

**Network Name**: Story Aeneid Testnet

**Chain ID**: 1315

**Chainlist Link**: [https://chainlist.org/chain/1315](https://chainlist.org/chain/1315)

## RPCs

| RPC Name           | RPC URL                                                    | Official |
| :----------------- | :--------------------------------------------------------- | :------: |
| Story              | `https://aeneid.storyrpc.io`                               |     ✅    |
| Story by Ankr      | `https://rpc.ankr.com/story_aeneid_testnet`                |          |
| Story by QuickNode | `https://www.quicknode.com/chains/story`                   |          |
| Story by Alchemy   | `https://story-aeneid.g.alchemy.com/v2/${ALCHEMY_API_KEY}` |          |
| Story by Tenderly  | `https://tenderly.co/`                                     |          |

## Explorers

| Explorer                                                                                                                       | URL                                        | Official |
| :----------------------------------------------------------------------------------------------------------------------------- | :----------------------------------------- | :------: |
| [Blockscout Explorer ↗️](https://aeneid.storyscan.io)                                                                          | `https://aeneid.storyscan.io`              |     ✅    |
| [IP Explorer ↗️](https://aeneid.explorer.story.foundation) (only for IP-related actions like licensing, minting licenses, etc) | `https://aeneid.explorer.story.foundation` |     ✅    |
| [Stakeme Explorer ↗️](https://aeneid.storyscan.app/)                                                                           | `https://aeneid.storyscan.app/`            |          |

## Faucet

| Faucet                                                                                  | Amount |
| :-------------------------------------------------------------------------------------- | :----- |
| [Google Cloud Faucet ↗️](https://cloud.google.com/application/web3/faucet/story/aeneid) | 10 IP  |
| [Official Faucet ↗️](https://aeneid.faucet.story.foundation/)                           | 10 IP  |

## Staking Dashboard

| Dashboard URL                                               | Official |
| :---------------------------------------------------------- | :------: |
| [Story Dashboard](https://aeneid.staking.story.foundation/) |     ✅    |

## Contract deployment addresses

* [Proof of Creativity](/developers/deployed-smart-contracts)
# Deployed Smart Contracts

> A list of all deployed protocol addresses

## Core Protocol Contracts

* View contracts on our GitHub [here](https://github.com/storyprotocol/protocol-core-v1/tree/main)

<CodeGroup>
  ```json Aeneid Testnet theme={null}
  {
    "AccessController": "0xcCF37d0a503Ee1D4C11208672e622ed3DFB2275a",
    "ArbitrationPolicyUMA": "0xfFD98c3877B8789124f02C7E8239A4b0Ef11E936",
    "CoreMetadataModule": "0x6E81a25C99C6e8430aeC7353325EB138aFE5DC16",
    "CoreMetadataViewModule": "0xB3F88038A983CeA5753E11D144228Ebb5eACdE20",
    "DisputeModule": "0x9b7A9c70AFF961C799110954fc06F3093aeb94C5",
    "EvenSplitGroupPool": "0xf96f2c30b41Cb6e0290de43C8528ae83d4f33F89",
    "GroupNFT": "0x4709798FeA84C84ae2475fF0c25344115eE1529f",
    "GroupingModule": "0x69D3a7aa9edb72Bc226E745A7cCdd50D947b69Ac",
    "IPAccountImplBeacon": "0x9825cc7A398D9C3dDD66232A8Ec76d5b05422581",
    "IPAccountImplBeaconProxy": "0x00b800138e4D82D1eea48b414d2a2A8Aee9A33b1",
    "IPAccountImpl": "0xdeC03e0c63f800efD7C9d04A16e01E80cF57Bf79",
    "IPAssetRegistry": "0x77319B4031e6eF1250907aa00018B8B1c67a244b",
    "IPGraphACL": "0x1640A22a8A086747cD377b73954545e2Dfcc9Cad",
    "IpRoyaltyVaultBeacon": "0x6928ba25Aa5c410dd855dFE7e95713d83e402AA6",
    "IpRoyaltyVaultImpl": "0xbd0f3c59B6f0035f55C58893fA0b1Ac4aDEa50Dc",
    "LicenseRegistry": "0x529a750E02d8E2f15649c13D69a465286a780e24",
    "LicenseToken": "0xFe3838BFb30B34170F00030B52eA4893d8aAC6bC",
    "LicensingModule": "0x04fbd8a2e56dd85CFD5500A4A4DfA955B9f1dE6f",
    "ModuleRegistry": "0x022DBAAeA5D8fB31a0Ad793335e39Ced5D631fa5",
    "PILicenseTemplate": "0x2E896b0b2Fdb7457499B56AAaA4AE55BCB4Cd316",
    "ProtocolAccessManager": "0xFdece7b8a2f55ceC33b53fd28936B4B1e3153d53",
    "ProtocolPauseAdmin": "0xdd661f55128A80437A0c0BDA6E13F214A3B2EB24",
    "RoyaltyModule": "0xD2f60c40fEbccf6311f8B47c4f2Ec6b040400086",
    "RoyaltyPolicyLAP": "0xBe54FB168b3c982b7AaE60dB6CF75Bd8447b390E",
    "RoyaltyPolicyLRP": "0x9156e603C949481883B1d3355c6f1132D191fC41"
  }
  ```

  ```json Mainnet theme={null}
  {
    "AccessController": "0xcCF37d0a503Ee1D4C11208672e622ed3DFB2275a",
    "ArbitrationPolicyUMA": "0xfFD98c3877B8789124f02C7E8239A4b0Ef11E936",
    "CoreMetadataModule": "0x6E81a25C99C6e8430aeC7353325EB138aFE5DC16",
    "CoreMetadataViewModule": "0xB3F88038A983CeA5753E11D144228Ebb5eACdE20",
    "DisputeModule": "0x9b7A9c70AFF961C799110954fc06F3093aeb94C5",
    "EvenSplitGroupPool": "0xf96f2c30b41Cb6e0290de43C8528ae83d4f33F89",
    "GroupNFT": "0x4709798FeA84C84ae2475fF0c25344115eE1529f",
    "GroupingModule": "0x69D3a7aa9edb72Bc226E745A7cCdd50D947b69Ac",
    "IPAccountImplBeacon": "0x9825cc7A398D9C3dDD66232A8Ec76d5b05422581",
    "IPAccountImplBeaconProxy": "0x00b800138e4D82D1eea48b414d2a2A8Aee9A33b1",
    "IPAccountImpl": "0x7343646585443F1c3F64E4F08b708788527e1C77",
    "IPAssetRegistry": "0x77319B4031e6eF1250907aa00018B8B1c67a244b",
    "IPGraphACL": "0x1640A22a8A086747cD377b73954545e2Dfcc9Cad",
    "IpRoyaltyVaultBeacon": "0x6928ba25Aa5c410dd855dFE7e95713d83e402AA6",
    "IpRoyaltyVaultImpl": "0x63cC7611316880213f3A4Ba9bD72b0EaA2010298",
    "LicenseRegistry": "0x529a750E02d8E2f15649c13D69a465286a780e24",
    "LicenseToken": "0xFe3838BFb30B34170F00030B52eA4893d8aAC6bC",
    "LicensingModule": "0x04fbd8a2e56dd85CFD5500A4A4DfA955B9f1dE6f",
    "ModuleRegistry": "0x022DBAAeA5D8fB31a0Ad793335e39Ced5D631fa5",
    "PILicenseTemplate": "0x2E896b0b2Fdb7457499B56AAaA4AE55BCB4Cd316",
    "ProtocolAccessManager": "0xFdece7b8a2f55ceC33b53fd28936B4B1e3153d53",
    "ProtocolPauseAdmin": "0xdd661f55128A80437A0c0BDA6E13F214A3B2EB24",
    "RoyaltyModule": "0xD2f60c40fEbccf6311f8B47c4f2Ec6b040400086",
    "RoyaltyPolicyLAP": "0xBe54FB168b3c982b7AaE60dB6CF75Bd8447b390E",
    "RoyaltyPolicyLRP": "0x9156e603C949481883B1d3355c6f1132D191fC41"
  }
  ```
</CodeGroup>

## Periphery Contracts

* View contracts on our GitHub [here](https://github.com/storyprotocol/protocol-periphery-v1)

<CodeGroup>
  ```json Aeneid Testnet theme={null}
  {
    "DerivativeWorkflows": "0x9e2d496f72C547C2C535B167e06ED8729B374a4f",
    "GroupingWorkflows": "0xD7c0beb3aa4DCD4723465f1ecAd045676c24CDCd",
    "LicenseAttachmentWorkflows": "0xcC2E862bCee5B6036Db0de6E06Ae87e524a79fd8",
    "OwnableERC20Beacon": "0xB83639aF55F03108091020b7c75a46e2eaAb4FfA",
    "OwnableERC20Template": "0xf8D299af9CBEd49f50D7844DDD1371157251d0A7",
    "RegistrationWorkflows": "0xbe39E1C756e921BD25DF86e7AAa31106d1eb0424",
    "RoyaltyTokenDistributionWorkflows": "0xa38f42B8d33809917f23997B8423054aAB97322C",
    "RoyaltyWorkflows": "0x9515faE61E0c0447C6AC6dEe5628A2097aFE1890",
    "SPGNFTBeacon": "0xD2926B9ecaE85fF59B6FB0ff02f568a680c01218",
    "SPGNFTImpl": "0x5266215a00c31AaA2f2BB7b951Ea0028Ea8b4e37",
    "TokenizerModule": "0xAC937CeEf893986A026f701580144D9289adAC4C"
  }
  ```

  ```json Mainnet theme={null}
  {
    "DerivativeWorkflows": "0x9e2d496f72C547C2C535B167e06ED8729B374a4f",
    "GroupingWorkflows": "0xD7c0beb3aa4DCD4723465f1ecAd045676c24CDCd",
    "LicenseAttachmentWorkflows": "0xcC2E862bCee5B6036Db0de6E06Ae87e524a79fd8",
    "OwnableERC20Beacon": "0x9a81C447C0b4C47d41d94177AEea3511965d3Bc9",
    "OwnableERC20Template": "0xE6505ffc5A7C19B68cEc2311Cc35BC02d8f7e0B1",
    "RegistrationWorkflows": "0xbe39E1C756e921BD25DF86e7AAa31106d1eb0424",
    "RoyaltyTokenDistributionWorkflows": "0xa38f42B8d33809917f23997B8423054aAB97322C",
    "RoyaltyWorkflows": "0x9515faE61E0c0447C6AC6dEe5628A2097aFE1890",
    "SPGNFTBeacon": "0xD2926B9ecaE85fF59B6FB0ff02f568a680c01218",
    "SPGNFTImpl": "0x6Cfa03Bc64B1a76206d0Ea10baDed31D520449F5",
    "TokenizerModule": "0xAC937CeEf893986A026f701580144D9289adAC4C"
  }
  ```
</CodeGroup>

## License Hooks

* View contracts on our GitHub [here](https://github.com/storyprotocol/protocol-periphery-v1/tree/main/contracts/hooks)

<CodeGroup>
  ```json Aeneid Testnet theme={null}
  {
    "LockLicenseHook": "0x54C52990dA304643E7412a3e13d8E8923cD5bfF2",
    "TotalLicenseTokenLimitHook": "0xaBAD364Bfa41230272b08f171E0Ca939bD600478"
  }
  ```

  ```json Mainnet theme={null}
  {
    "LockLicenseHook": "0x5D874d4813c4A8A9FB2AB55F30cED9720AEC0222",
    "TotalLicenseTokenLimitHook": "0xB72C9812114a0Fc74D49e01385bd266A75960Cda"
  }
  ```
</CodeGroup>

## Whitelisted Revenue Tokens

The below list contains the whitelisted revenue tokens that can be used in the Royalty Module. Learn more about Revenue Tokens [here](/concepts/royalty-module/ip-royalty-vault).

<Tabs>
  <Tab title="Aeneid Testnet">
    | Token  | Contract Address                             | Explorer                                                                                       | Mint                                                                                                                    |
    | :----- | :------------------------------------------- | :--------------------------------------------------------------------------------------------- | :---------------------------------------------------------------------------------------------------------------------- |
    | WIP    | `0x1514000000000000000000000000000000000000` | [View here ↗️](https://aeneid.storyscan.io/address/0x1514000000000000000000000000000000000000) | N/A                                                                                                                     |
    | MERC20 | `0xF2104833d386a2734a4eB3B8ad6FC6812F29E38E` | [View here ↗️](https://aeneid.storyscan.io/address/0xF2104833d386a2734a4eB3B8ad6FC6812F29E38E) | [Mint ↗️](https://aeneid.storyscan.io/address/0xF2104833d386a2734a4eB3B8ad6FC6812F29E38E?tab=write_contract#0x40c10f19) |
  </Tab>

  <Tab title="Mainnet">
    | Token | Contract Address                             | Explorer                                                                                    | Mint |
    | :---- | :------------------------------------------- | :------------------------------------------------------------------------------------------ | :--- |
    | WIP   | `0x1514000000000000000000000000000000000000` | [View here ↗️](https://www.storyscan.io/address/0x1514000000000000000000000000000000000000) | N/A  |
  </Tab>
</Tabs>

## Misc

* **Multicall3**: 0xcA11bde05977b3631167028862bE2a173976CA11
* **Default License Terms ID** (Non-Commercial Social Remixing): 1
* **Bridged USDC (Stargate)**: 0xF1815bd50389c46847f0Bda824eC8da914045D14

<Note>
  We only support the above USDC on Story's mainnet.
</Note>

## Ecosystem Official Contracts

The below is a list of official ecosystem contracts.

### Story ENS

<CodeGroup>
  ```json Aeneid Testnet theme={null}
  {
    "SidRegistry": "0x5dC881dDA4e4a8d312be3544AD13118D1a04Cb17",
    "PublicResolver": "0x6D3B3F99177FB2A5de7F9E928a9BD807bF7b5BAD"
  }
  ```

  ```json Mainnet theme={null}
  {
    "SidRegistry": "0x5dC881dDA4e4a8d312be3544AD13118D1a04Cb17",
    "PublicResolver": "0x6D3B3F99177FB2A5de7F9E928a9BD807bF7b5BAD"
  }
  ```
</CodeGroup>
# Dynamic Setup

> Learn how to setup Dynamic Wallet in your Story DApp.

<Note>
  **Optional: Official Dynamic Docs**

  Check out the official Wagmi + Dynamic installation docs [here](https://docs.dynamic.xyz/react-sdk/using-wagmi).
</Note>

## Install the Dependencies

<CodeGroup>
  ```bash npm theme={null}
  npm install --save @story-protocol/core-sdk viem wagmi @dynamic-labs/sdk-react-core @dynamic-labs/wagmi-connector @dynamic-labs/ethereum @tanstack/react-query
  ```

  ```bash pnpm theme={null}
  pnpm install @story-protocol/core-sdk viem
  ```

  ```bash yarn theme={null}
  yarn add @story-protocol/core-sdk viem
  ```
</CodeGroup>

## Setup

Before diving into the example, make sure you have two things setup:

1. Make sure to have `NEXT_PUBLIC_RPC_PROVIDER_URL` set up in your `.env` file.
   * You can use the public default one (`https://aeneid.storyrpc.io`) or any other RPC [here](/network/network-info/aeneid#rpcs).
2. Make sure to have `NEXT_PUBLIC_DYNAMIC_ENV_ID` set up in your `.env` file. Do this by logging into [Dynamic](https://app.dynamic.xyz/) and creating a project.

<CodeGroup>
  ```jsx Web3Providers.tsx theme={null}
  "use client";
  import { createConfig, WagmiProvider } from "wagmi";
  import { http } from 'viem';
  import { QueryClient, QueryClientProvider } from "@tanstack/react-query";
  import { DynamicContextProvider } from "@dynamic-labs/sdk-react-core";
  import { DynamicWagmiConnector } from "@dynamic-labs/wagmi-connector";
  import { EthereumWalletConnectors } from "@dynamic-labs/ethereum";
  import { PropsWithChildren } from "react";
  import { aeneid } from "@story-protocol/core-sdk";

  // setup wagmi
  const config = createConfig({
    chains: [aeneid],
    multiInjectedProviderDiscovery: false,
    transports: {
      [aeneid.id]: http(),
    },
  });
  const queryClient = new QueryClient();

  export default function Web3Providers({ children }: PropsWithChildren) {
    return (
      // setup dynamic
      <DynamicContextProvider
        settings={{
          // Find your environment id at https://app.dynamic.xyz/dashboard/developer
          environmentId: process.env.NEXT_PUBLIC_DYNAMIC_ENV_ID as string,
          walletConnectors: [EthereumWalletConnectors],
        }}
      >
        <WagmiProvider config={config}>
          <QueryClientProvider client={queryClient}>
            <DynamicWagmiConnector>
              {children}
            </DynamicWagmiConnector>
          </QueryClientProvider>
        </WagmiProvider>
      </DynamicContextProvider>
    );
  }
  ```

  ```jsx layout.tsx theme={null}
  import type { Metadata } from "next";
  import { Inter } from "next/font/google";
  import "./globals.css";
  import { PropsWithChildren } from "react";
  import Web3Providers from "./Web3Providers";
  import { DynamicWidget } from "@dynamic-labs/sdk-react-core";

  const inter = Inter({ subsets: ["latin"] });

  export const metadata: Metadata = {
    title: "Example",
    description: "This is an Example DApp",
  };

  export default function RootLayout({ children }: PropsWithChildren) {
    return (
      <html lang="en">
        <body>
          <Web3Providers>
            <DynamicWidget />
            {children}
          </Web3Providers>
        </body>
      </html>
    );
  }
  ```

  ```jsx TestComponent.tsx theme={null}
  import { custom, toHex } from 'viem';
  import { useWalletClient } from "wagmi";
  import { StoryClient, StoryConfig } from "@story-protocol/core-sdk";

  // example of how you would now use the fully setup sdk

  export default function TestComponent() {
    const { data: wallet } = useWalletClient();

    async function setupStoryClient(): Promise<StoryClient> {
      const config: StoryConfig = {
        wallet: wallet,
        transport: custom(wallet!.transport),
        chainId: "aeneid",
      };
      const client = StoryClient.newClient(config);
      return client;
    }

    async function registerIp() {
      const client = await setupStoryClient();
      const response = await client.ipAsset.registerIpAsset({
        nft: {
          type: 'minted',
          nftContract: '0x01...',
          tokenId: '1',
        }
        ipMetadata: {
          ipMetadataURI: "test-metadata-uri",
          ipMetadataHash: toHex("test-metadata-hash", { size: 32 }),
          nftMetadataURI: "test-nft-metadata-uri",
          nftMetadataHash: toHex("test-nft-metadata-hash", { size: 32 }),
        }
      });
      console.log(
        `Root IPA created at tx hash ${response.txHash}, IPA ID: ${response.ipId}`
      );
    }

    return (
      {/* */}
    )
  }
  ```
</CodeGroup>
# Setup Client

> Learn how to setup the TypeScript SDK.

### Prerequisites

We require node version 18 or later version and npm version 8 to be installed in your environment. To install node and npm, we recommend you go to the [Node.js official website](https://nodejs.org) and download the latest LTS (Long Term Support) version.

### Install the Dependencies

Install the [Story SDK](https://www.npmjs.com/package/@story-protocol/core-sdk) node package, as well as [viem](https://www.npmjs.com/package/viem).

<CodeGroup>
  ```bash npm theme={null}
  npm install --save @story-protocol/core-sdk viem
  ```

  ```bash pnpm theme={null}
  pnpm install @story-protocol/core-sdk viem
  ```

  ```bash yarn theme={null}
  yarn add @story-protocol/core-sdk viem
  ```
</CodeGroup>

## Initiate SDK Client

Next we can initiate the SDK Client. There are two ways to do this:

1. Using a private key (preferable for some backend admin)
2. JSON-RPC account like Metamask where users sign their own transactions

### Set Up Private Key Account

<CardGroup cols={1}>
  <Card title="Working Example" href="https://github.com/storyprotocol/typescript-tutorial/blob/main/utils/config.ts" icon="thumbs-up">
    Check out the TypeScript Tutorial for a working example of how to set up the
    Story SDK Client.
  </Card>
</CardGroup>

Before continuing with the code below:

1. Make sure to have `WALLET_PRIVATE_KEY` set up in your `.env` file.
   * Don’t forget to fund the wallet with some testnet tokens from a [Faucet](/network/network-info/aeneid#faucet)
2. Make sure to have `RPC_PROVIDER_URL` set up in your `.env` file.
   * You can use the public default one (`https://aeneid.storyrpc.io`) or check out the other RPCs [here](/network/network-info/aeneid#rpcs).

```typescript utils.ts theme={null}
import { http } from "viem";
import { Account, privateKeyToAccount, Address } from "viem/accounts";
import { StoryClient, StoryConfig } from "@story-protocol/core-sdk";

const privateKey: Address = `0x${process.env.WALLET_PRIVATE_KEY}`;
const account: Account = privateKeyToAccount(privateKey);

const config: StoryConfig = {
  account: account, // the account object from above
  transport: http(process.env.RPC_PROVIDER_URL),
  chainId: "aeneid",
};
export const client = StoryClient.newClient(config);
```

### Setup for React (ex. Metamask)

The [React Setup Guide](/developers/react-guide/setup/overview) shows how we can also use the TypeScript SDK to delay signing & sending transactions to a JSON-RPC account like Metamask.
# Register an IP Asset

> Learn how to Register an NFT as an IP Asset in TypeScript.

<CardGroup cols={1}>
  <Card title="Completed Code" href="https://github.com/storyprotocol/typescript-tutorial/blob/main/scripts/registration/register.ts" icon="thumbs-up">
    Follow the completed code all the way through.
  </Card>
</CardGroup>

Let's say you have some off-chain IP (ex. a book, a character, a drawing, etc). In order to register that IP on Story, you first need to mint an NFT. This NFT is the **ownership** over the IP. Then you **register** that NFT on Story, turning it into an [IP Asset](/concepts/ip-asset). The below tutorial will walk you through how to do this.

### Prerequisites

There are a few steps you have to complete before you can start the tutorial.

1. Complete the [TypeScript SDK Setup](/developers/typescript-sdk/setup)
2. \[OPTIONAL] Go to [Pinata](https://pinata.cloud/) and create a new API key. Add the JWT to your `.env` file:

```text .env theme={null}
PINATA_JWT=<YOUR_PINATA_JWT>
```

3. \[OPTIONAL] Install the `pinata-web3` dependency:

```bash Terminal theme={null}
npm install pinata-web3
```

## 1. Set up your IP Metadata

We can set metadata on our NFT & IP, *but you don't have to*. To do this, view the [IPA Metadata Standard](/concepts/ip-asset/ipa-metadata-standard) and construct your metadata for both your NFT & IP.

```typescript main.ts theme={null}
// you should already have a client set up (prerequisite)
import { client } from "./utils";

async function main() {
  const ipMetadata = {
    title: "Ippy",
    description: "Official mascot of Story.",
    image:
      "https://ipfs.io/ipfs/QmSamy4zqP91X42k6wS7kLJQVzuYJuW2EN94couPaq82A8",
    imageHash:
      "0x21937ba9d821cb0306c7f1a1a2cc5a257509f228ea6abccc9af1a67dd754af6e",
    mediaUrl:
      "https://ipfs.io/ipfs/QmSamy4zqP91X42k6wS7kLJQVzuYJuW2EN94couPaq82A8",
    mediaHash:
      "0x21937ba9d821cb0306c7f1a1a2cc5a257509f228ea6abccc9af1a67dd754af6e",
    mediaType: "image/png",
    creators: [
      {
        name: "Story Foundation",
        address: "0x67ee74EE04A0E6d14Ca6C27428B27F3EFd5CD084",
        description: "The World's IP Blockchain",
        contributionPercent: 100,
        socialMedia: [
          {
            platform: "Twitter",
            url: "https://twitter.com/storyprotocol",
          },
          {
            platform: "Website",
            url: "https://story.foundation",
          },
        ],
      },
    ],
  };
}

main();
```

## 2. Set up your NFT Metadata

The NFT Metadata follows the [ERC-721 Metadata Standard](https://eips.ethereum.org/EIPS/eip-721).

```typescript main.ts theme={null}
import { IpMetadata } from "@story-protocol/core-sdk";
import { client } from "./utils";

async function main() {
  // previous code here ...

  const nftMetadata = {
    name: "Ownership NFT",
    description: "This is an NFT representing owernship of our IP Asset.",
    image: "https://picsum.photos/200",
  };
}

main();
```

## 3. Upload your IP and NFT Metadata to IPFS

In a separate `uploadToIpfs` file, create a function to upload your IP & NFT Metadata objects to IPFS:

```typescript uploadToIpfs.ts theme={null}
import { PinataSDK } from "pinata-web3";

const pinata = new PinataSDK({
  pinataJwt: process.env.PINATA_JWT,
});

export async function uploadJSONToIPFS(jsonMetadata: any): Promise<string> {
  const { IpfsHash } = await pinata.upload.json(jsonMetadata);
  return IpfsHash;
}
```

You can then use that function to upload your metadata, as shown below:

```typescript main.ts theme={null}
import { IpMetadata } from "@story-protocol/core-sdk";
import { client } from "./utils";
import { uploadJSONToIPFS } from "./uploadToIpfs";
import { createHash } from "crypto";

async function main() {
  // previous code here ...

  const ipIpfsHash = await uploadJSONToIPFS(ipMetadata);
  const ipHash = createHash("sha256")
    .update(JSON.stringify(ipMetadata))
    .digest("hex");
  const nftIpfsHash = await uploadJSONToIPFS(nftMetadata);
  const nftHash = createHash("sha256")
    .update(JSON.stringify(nftMetadata))
    .digest("hex");
}

main();
```

## 4. Register an NFT as an IP Asset

Remember that in order to register a new IP, we first have to mint an NFT, which will represent the underlying ownership of the IP. This NFT then gets "registered" and becomes an [IP Asset](/concepts/ip-asset).

Luckily, we can use the `registerIpAsset` function to mint an NFT and register it as an IP Asset in the same transaction.

This function needs an SPG NFT Contract to mint from.

### 4a. What SPG NFT contract address should I use?

For simplicity, you can use a public collection we have created for you on Aeneid testnet: `0xc32A8a0FF3beDDDa58393d022aF433e78739FAbc`. On Mainnet, or even when testing a real scenario on Aeneid, you should **create your own** contract as described in the "Using a custom ERC-721 contract" section below.

<Accordion title="Using a custom ERC-721 contract" icon="info">
  Using a public collection we provide for you is fine, but when you do this for real, you should make your own NFT Collection for your IPs. You can do this in 2 ways:

  1. Deploy a contract that implements the [ISPGNFT](https://github.com/storyprotocol/protocol-periphery-v1/blob/main/contracts/interfaces/ISPGNFT.sol) interface, or use the SDK's [createNFTCollection](/sdk-reference/nftclient#createnftcollection) function (shown below) to do it for you. This will give you your own SPG NFT Collection that only you can mint from.

  ```typescript createSpgNftCollection.ts theme={null}
  import { zeroAddress } from "viem";
  import { client } from "./utils";

  async function createSpgNftCollection() {
    const newCollection = await client.nftClient.createNFTCollection({
      name: "Test NFTs",
      symbol: "TEST",
      isPublicMinting: false,
      mintOpen: true,
      mintFeeRecipient: zeroAddress,
      contractURI: "",
    });

    console.log("New collection created:", {
      "SPG NFT Contract Address": newCollection.spgNftContract,
      "Transaction Hash": newCollection.txHash,
    });
  }

  createSpgNftCollection();
  ```

  2. Create a custom ERC-721 NFT collection on your own. See a working code example [here](https://github.com/storyprotocol/typescript-tutorial/blob/main/scripts/registration/registerCustom.ts). This is helpful if you **already have a custom NFT contract that has your own custom logic, or if your IPs themselves are NFTs.**
</Accordion>

Here is the code to register an IP:

<Info>
  Associated Docs:
  [ipAsset.registerIpAsset](/sdk-reference/ipasset#registeripasset)
</Info>

```typescript main.ts theme={null}
import { IpMetadata } from "@story-protocol/core-sdk";
import { client } from "./utils";
import { uploadJSONToIPFS } from "./uploadToIpfs";
import { createHash } from "crypto";
import { Address } from "viem";

async function main() {
  // previous code here ...

  const response = await client.ipAsset.registerIpAsset({
    nft: {
      type: "mint",
      spgNftContract: "0xc32A8a0FF3beDDDa58393d022aF433e78739FAbc",
    },
    ipMetadata: {
      ipMetadataURI: `https://ipfs.io/ipfs/${ipIpfsHash}`,
      ipMetadataHash: `0x${ipHash}`,
      nftMetadataURI: `https://ipfs.io/ipfs/${nftIpfsHash}`,
      nftMetadataHash: `0x${nftHash}`,
    },
  });

  console.log(
    `Root IPA created at transaction hash ${response.txHash}, IPA ID: ${response.ipId}`
  );
  console.log(
    `View on the explorer: https://aeneid.explorer.story.foundation/ipa/${response.ipId}`
  );
}

main();
```

## 5. Add License Terms to IP

During the registration process, you can attach [License Terms](/concepts/licensing-module/license-terms) to the IP. This will allow others to mint a license and use your IP, restricted by the terms.

```typescript main.ts theme={null}
import {
  IpMetadata,
  PILFlavor,
  WIP_TOKEN_ADDRESS,
} from "@story-protocol/core-sdk";
import { client } from "./utils";
import { uploadJSONToIPFS } from "./uploadToIpfs";
import { createHash } from "crypto";
import { Address, parseEther } from "viem";

async function main() {
  // previous code here ...

  const response = await client.ipAsset.registerIpAsset({
    nft: {
      type: "mint",
      spgNftContract: "0xc32A8a0FF3beDDDa58393d022aF433e78739FAbc",
    },
    // [!code ++:9]
    licenseTermsData: [
      {
        terms: PILFlavor.commercialRemix({
          commercialRevShare: 5,
          defaultMintingFee: parseEther("1"), // 1 $IP
          currency: WIP_TOKEN_ADDRESS,
        }),
      },
    ],
    ipMetadata: {
      ipMetadataURI: `https://ipfs.io/ipfs/${ipIpfsHash}`,
      ipMetadataHash: `0x${ipHash}`,
      nftMetadataURI: `https://ipfs.io/ipfs/${nftIpfsHash}`,
      nftMetadataHash: `0x${nftHash}`,
    },
  });

  console.log(
    `Root IPA created at transaction hash ${response.txHash}, IPA ID: ${response.ipId}`
  );
  console.log(
    `View on the explorer: https://aeneid.explorer.story.foundation/ipa/${response.ipId}`
  );
}

main();
```

## 6. View Completed Code

Congratulations, you registered an IP and attached license terms to it!

<CardGroup cols={1}>
  <Card title="Completed Code" href="https://github.com/storyprotocol/typescript-tutorial/blob/main/scripts/registration/register.ts" icon="thumbs-up">
    Follow the completed code all the way through.
  </Card>
</CardGroup>
# Register a Derivative

> Learn how to register a derivative/remix IP Asset as a child of another in TypeScript.

<CardGroup cols={1}>
  <Card title="Completed Code" href="https://github.com/storyprotocol/typescript-tutorial/blob/main/scripts/derivative/registerDerivativeCommercial.ts" icon="thumbs-up">
    All of this page is covered in this working code example.
  </Card>
</CardGroup>

This section demonstrates how to register an IP Asset as a derivative of another.

### Prerequisites

There are a few steps you have to complete before you can start the tutorial.

1. Complete the [TypeScript SDK Setup](/developers/typescript-sdk/setup)

## 1. Before We Start

Registering a derivative IP Asset requires you have a License Token from the parent IP Assets you plan to be a derivative of. If you don't, the SDK will handle it for you.

### 1a. Why would I ever use a License Token if it's not needed?

There are a few times when **you would need** a License Token to register a derivative:

* The License Token contains private license terms, so you would only be able to register as a derivative if you had the License Token that was manually minted by the owner. More on that [here](/concepts/licensing-module/license-token#private-licenses).
* The License Token (which is an NFT) costs a `mintingFee` to mint, and you were able to buy it on a marketplace for a cheaper price. Then it makes more sense to simply register with the License Token then have to pay the more expensive `defaultMintingFee`.

## 2. Register Derivative

In this example we're going to assume you have no license tokens, the child IP is not yet registered, and you don't have your own NFT contract or an already minted NFT.

<Info>
  Associated Docs:
  [ipAsset.registerDerivativeIpAsset](/sdk-reference/ipasset#registerderivativeipasset)
</Info>

```typescript main.ts theme={null}
import { IpMetadata, DerivativeData } from "@story-protocol/core-sdk";
import { client } from "./utils";
import { uploadJSONToIPFS } from "./uploadToIpfs";
import { createHash } from "crypto";
import { Address } from "viem";

async function main() {
  // previous code here ...

  const derivData = {
    // TODO: insert the parent's ipId
    parentIpIds: [PARENT_IP_ID],
    // TODO: insert the licenseTermsId attached to parent IpId
    licenseTermsIds: [LICENSE_TERMS_ID],
  };

  const response = await client.ipAsset.registerDerivativeIpAsset({
    nft: {
      type: "mint",
      spgNftContract: "0xc32A8a0FF3beDDDa58393d022aF433e78739FAbc",
    },
    derivData,
    ipMetadata: {
      ipMetadataURI: `https://ipfs.io/ipfs/${ipIpfsHash}`,
      ipMetadataHash: `0x${ipHash}`,
      nftMetadataURI: `https://ipfs.io/ipfs/${nftIpfsHash}`,
      nftMetadataHash: `0x${nftHash}`,
    },
  });

  console.log(
    `Completed at transaction hash ${response.txHash}, IPA ID: ${response.ipId}, Token ID: ${response.tokenId}`
  );
}
```

## 3. View Completed Code

Congratulations, you registered a derivative IP Asset!

<CardGroup cols={1}>
  <Card title="Completed Code" href="https://github.com/storyprotocol/typescript-tutorial/blob/main/scripts/derivative/registerDerivativeCommercial.ts" icon="thumbs-up">
    All of this page is covered in this working code example.
  </Card>
</CardGroup>

## 4. Paying and Claiming Revenue

Now that we have established parent-child IP relationships, we can begin to explore payments and automated revenue share based on the license terms. We'll cover that in the upcoming pages.
# Attach Terms to an IPA

> Learn how to Attach License Terms to an IP Asset in TypeScript.

This section demonstrates how to attach [License Terms](/concepts/licensing-module/license-terms) to an [IP Asset](/concepts/ip-asset). By attaching terms, users can publicly mint [License Tokens](/concepts/licensing-module/license-token) (the on-chain "license") with those terms from the IP.

### Prerequisites

There are a few steps you have to complete before you can start the tutorial.

1. Complete the [TypeScript SDK Setup](/developers/typescript-sdk/setup)

## 1. Before We Start

We should mention that you do not need an existing IP Asset to attach terms to it. As we saw in the previous section, you can register an IP Asset and attach terms to it in the same transaction.

## 2. Register License Terms

In order to attach terms to an IP Asset, let's first create them!

[License Terms](/concepts/licensing-module/license-terms) are a configurable set of values that define restrictions on licenses minted from your IP that have those terms. For example, "If you mint this license, you must share 50% of your revenue with me." You can view the full set of terms in [PIL Terms](/concepts/programmable-ip-license/pil-terms).

<Note>
  If License Terms already exist on our protocol for the identical set of parameters you intend to create, it is unnecessary to create it again and the function will simply return the existing `licenseTermsId` and an undefined `txHash`. License Terms are protocol-wide, so you can use existing License Terms by its `licenseTermsId`.
</Note>

Below is a code example showing how to create new terms:

<Info>
  Associated Docs:
  [license.registerPILTerms](/sdk-reference/license#registerpilterms)
</Info>

```typescript main.ts theme={null}
import { LicenseTerms } from "@story-protocol/core-sdk";
import { zeroAddress } from "viem";
// you should already have a client set up (prerequisite)
import { client } from "./utils";

async function main() {
  const licenseTerms: LicenseTerms = {
    defaultMintingFee: 0n,
    // must be a whitelisted revenue token from https://docs.story.foundation/developers/deployed-smart-contracts
    // in this case, we use $WIP
    currency: "0x1514000000000000000000000000000000000000",
    // RoyaltyPolicyLAP address from https://docs.story.foundation/developers/deployed-smart-contracts
    royaltyPolicy: "0xBe54FB168b3c982b7AaE60dB6CF75Bd8447b390E",
    transferable: false,
    expiration: 0n,
    commercialUse: false,
    commercialAttribution: false,
    commercializerChecker: zeroAddress,
    commercializerCheckerData: "0x",
    commercialRevShare: 0,
    commercialRevCeiling: 0n,
    derivativesAllowed: false,
    derivativesAttribution: false,
    derivativesApproval: false,
    derivativesReciprocal: false,
    derivativeRevCeiling: 0n,
    uri: "",
  };

  const response = await client.license.registerPILTerms({
    ...licenseTerms,
  });

  console.log(
    `PIL Terms registered at transaction hash ${response.txHash}, License Terms ID: ${response.licenseTermsId}`
  );
}

main();
```

### 2a. PIL Flavors

As you see above, you have to choose between a lot of terms.

We have convenience functions to help you register new terms. We have created [PIL Flavors](/concepts/programmable-ip-license/pil-flavors), which are pre-configured popular combinations of License Terms to help you decide what terms to use. You can view those PIL Flavors and then register terms using the following convenience functions:

<CardGroup cols={4}>
  <Card title="Non-Commercial Social Remixing" href="/concepts/programmable-ip-license/pil-flavors#non-commercial-social-remixing" icon="file">
    Free remixing with attribution. No commercialization.
  </Card>

  {" "}

  <Card title="Commercial Use" href="/concepts/programmable-ip-license/pil-flavors#commercial-use" icon="file">
    Pay to use the license with attribution, but don't have to share revenue.
  </Card>

  {" "}

  <Card title="Commercial Remix" href="/concepts/programmable-ip-license/pil-flavors#commercial-remix" icon="file">
    Pay to use the license with attribution and pay % of revenue earned.
  </Card>

  <Card title="Creative Commons Attribution" href="/concepts/programmable-ip-license/pil-flavors#creative-commons-attribution" icon="file">
    Free remixing and commercial use with attribution.
  </Card>
</CardGroup>

You can easily register a flavor of terms like so:

```typescript main.ts theme={null}
import { PILFlavor, WIP_TOKEN_ADDRESS } from "@story-protocol/core-sdk";
import { parseEther } from "viem";
// you should already have a client set up (prerequisite)
import { client } from "./utils";

async function main() {
  const response = await client.license.registerPILTerms(
    PILFlavor.commercialRemix({
      commercialRevShare: 5,
      defaultMintingFee: parseEther("1"), // 1 $IP
      currency: WIP_TOKEN_ADDRESS,
    })
  );

  console.log(
    `PIL Terms registered at transaction hash ${response.txHash}, License Terms ID: ${response.licenseTermsId}`
  );
}

main();
```

## 3. Attach License Terms

Now that we have created terms and have the associated `licenseTermsId`, we can attach them to an existing IP Asset like so:

<Info>
  Associated Docs:
  [license.attachLicenseTerms](/sdk-reference/license#attachlicenseterms)
</Info>

```typescript main.ts theme={null}
import { LicenseTerms } from "@story-protocol/core-sdk";
import { zeroAddress } from "viem";
// you should already have a client set up (prerequisite)
import { client } from "./utils";

async function main() {
  // previous code here ...

  const response = await client.license.attachLicenseTerms({
    // insert your newly created license terms id here
    licenseTermsId: LICENSE_TERMS_ID,
    // insert the ipId you want to attach terms to here
    ipId: "0x4c1f8c1035a8cE379dd4ed666758Fb29696CF721",
  });

  if (response.success) {
    console.log(
      `Attached License Terms to IPA at transaction hash ${response.txHash}.`
    );
  } else {
    console.log(`License Terms already attached to this IPA.`);
  }
}

main();
```

## 3. Mint a License

Now that we have attached License Terms to our IP, the next step is minting a License Token, which we'll go over on the next page.
# Mint a License Token

> Learn how to mint a License Token from an IP Asset in TypeScript.

This section demonstrates how to mint a [License Token](/concepts/licensing-module/license-token) from an [IP Asset](/concepts/ip-asset). You can only mint a License Token from an IP Asset if the IP Asset has [License Terms](/concepts/licensing-module/license-terms) attached to it. A License Token is minted as an ERC-721.

There are two reasons you'd mint a License Token:

1. To hold the license and be able to use the underlying IP Asset as the license described (for ex. "Can use commercially as long as you provide proper attribution and share 5% of your revenue)
2. Use the license token to link another IP Asset as a derivative of it. *Note though that, as you'll see later, some SDK functions don't require you to explicitly mint a license token first in order to register a derivative, and will actually handle it for you behind the scenes.*

### Prerequisites

There are a few steps you have to complete before you can start the tutorial.

1. Complete the [TypeScript SDK Setup](/developers/typescript-sdk/setup)
2. An IP Asset that has License Terms added. Learn how to add License Terms to an IPA [here](/developers/typescript-sdk/attach-terms).

## 1. Mint License

Let's say that IP Asset (`ipId = 0x01`) has License Terms (`licenseTermdId = 10`) attached to it. We want to mint 2 License Tokens with those terms to a specific wallet address (`0x02`).

<Warning>
  Be mindful that some IP Assets may have license terms attached that require the user minting the license to pay a `defaultMintingFee`. You can see an example of that in the [TypeScript Tutorial](https://github.com/storyprotocol/typescript-tutorial/blob/main/scripts/derivative/registerDerivativeCommercial.ts).
</Warning>

<Note>
  Note that a license token can only be minted if the `licenseTermsId` are already attached to the IP Asset, making it a publicly available license. The IP owner can, however, mint a [private license](/concepts/licensing-module/license-token#private-licenses) by minting a license token with a `licenseTermsId` that is not attached to the IP Asset.
</Note>

<Info>
  Associated Docs:
  [license.mintLicenseTokens](/sdk-reference/license#mintlicensetokens)
</Info>

```typescript main.ts theme={null}
// you should already have a client set up (prerequisite)
import { client } from "./client";

async function main() {
  const response = await client.license.mintLicenseTokens({
    licenseTermsId: "10",
    licensorIpId: "0x641E638e8FCA4d4844F509630B34c9D524d40BE5",
    receiver: "0x641E638e8FCA4d4844F509630B34c9D524d40BE5", // optional. if not provided, it will go to the tx sender
    amount: 2,
    maxMintingFee: BigInt(0), // disabled
    maxRevenueShare: 100, // default
  });

  console.log(
    `License Token minted at transaction hash ${response.txHash}, License IDs: ${response.licenseTokenIds}`
  );
}

main();
```

### 1a. Setting Restrictions on Minting License Token

This is a note for owners of an IP Asset who want to set restrictions on who or how their license tokens are minted. You can:

* Set a max number of licenses that can be minted
* Charge dynamic fees based on who / how many are minted
* Whitelisted certain wallets to mint the tokens

... and more. Learn more by checking out the [License Config](/concepts/licensing-module/license-config) section of our documentation.

## 2. Register a Derivative

Now that we have minted a License Token, we can hold it or use it to link an IP Asset as a derivative. We will go over that on the next page.

*Note though that, as you'll see later, some SDK functions don't require you to explicitly mint a license token first in order to register a derivative, and will actually handle it for you behind the scenes.*

### 2a. Why would I ever use a License Token if it's not needed?

There are a few times when **you would need** a License Token to register a derivative:

* The License Token contains private license terms, so you would only be able to register as a derivative if you had the License Token that was manually minted by the owner. More on that [here](/concepts/licensing-module/license-token#private-licenses).
* The License Token (which is an NFT) costs a `mintingFee` to mint, and you were able to buy it on a marketplace for a cheaper price. Then it makes more sense to simply register with the License Token then have to pay the more expensive `defaultMintingFee`.
# Claim Revenue

> Learn how to claim due revenue from a child IP Asset in TypeScript.

<CardGroup cols={1}>
  <Card title="Completed Code" href="https://github.com/storyprotocol/typescript-tutorial/blob/main/scripts/royalty/payRevenue.ts" icon="thumbs-up">
    All of this page is covered in this working code example.
  </Card>
</CardGroup>

This section demonstrates how to claim due revenue from an IP Asset.

There are two main ways revenue can be claimed:

1. **Scenario #1**: Someone pays my IP Asset directly, and I claim that revenue.
2. **Scenario #2**: Someone pays a derivative IP Asset of my IP, and I have the right to a % of their revenue based on the `commercialRevShare` in the license terms.

### Prerequisites

There are a few steps you have to complete before you can start the tutorial.

1. Complete the [TypeScript SDK Setup](/developers/typescript-sdk/setup)
2. Have a basic understanding of the [Royalty Module](/concepts/royalty-module)
3. Obviously, there must be a payment to be claimed. Read [Pay an IPA](/developers/typescript-sdk/pay-ipa)

## Before We Start

When payments are made, they eventually end up in an IP Asset's [IP Royalty Vault](/concepts/royalty-module/ip-royalty-vault). From here, they are claimed/transferred to whoever owns the Royalty Tokens associated with it, which represent a % of revenue share for a given IP Asset's IP Royalty Vault.

The IP Account (the smart contract that represents the [IP Asset](/concepts/ip-asset)) is what holds 100% of the Royalty Tokens when it's first registered. So usually, it indeed holds most of the Royalty Tokens.

<Note>
  **Quick Note**. The below scenarios and examples use a [Liquid Absolute Percentage](/concepts/royalty-module/liquid-absolute-percentage) royalty policy. This is currently one of two royalty policies you can use.
</Note>

## Scenario #1

In this scenario, I own IP Asset 3. Someone pays my IP Asset 3 directly, and I claim that revenue. Let's view this in steps:

1. As we can see in the below diagram, when someone pays IP Asset 3 100 \$WIP, 85 \$WIP automatically gets deposited into IP Royalty Vault 3 (based on the license terms, which specifiies a LAP royalty policy and the resulting royalty stack).

   <Frame>
     <img src="https://mintcdn.com/story/KwuxPVrS3UIa7CU1/images/concepts/royalty-module/royalty-module-split-lap.png?fit=max&auto=format&n=KwuxPVrS3UIa7CU1&q=85&s=c24fbc48c17c96574628a8eac087f7d9" alt="Payment flow to IP Royalty Vault" data-og-width="2164" width="2164" data-og-height="1218" height="1218" data-path="images/concepts/royalty-module/royalty-module-split-lap.png" data-optimize="true" data-opv="3" srcset="https://mintcdn.com/story/KwuxPVrS3UIa7CU1/images/concepts/royalty-module/royalty-module-split-lap.png?w=280&fit=max&auto=format&n=KwuxPVrS3UIa7CU1&q=85&s=b98c029fa2bfedb5cfe1dc984005e147 280w, https://mintcdn.com/story/KwuxPVrS3UIa7CU1/images/concepts/royalty-module/royalty-module-split-lap.png?w=560&fit=max&auto=format&n=KwuxPVrS3UIa7CU1&q=85&s=d0ef29971541358d75cb6171b52fc090 560w, https://mintcdn.com/story/KwuxPVrS3UIa7CU1/images/concepts/royalty-module/royalty-module-split-lap.png?w=840&fit=max&auto=format&n=KwuxPVrS3UIa7CU1&q=85&s=3d20d2ec307fed750437d944c20444c6 840w, https://mintcdn.com/story/KwuxPVrS3UIa7CU1/images/concepts/royalty-module/royalty-module-split-lap.png?w=1100&fit=max&auto=format&n=KwuxPVrS3UIa7CU1&q=85&s=a8e4f23a10ed304f84332085a7c2a056 1100w, https://mintcdn.com/story/KwuxPVrS3UIa7CU1/images/concepts/royalty-module/royalty-module-split-lap.png?w=1650&fit=max&auto=format&n=KwuxPVrS3UIa7CU1&q=85&s=1c5cb6309ba6345f3e9345f374b14cd6 1650w, https://mintcdn.com/story/KwuxPVrS3UIa7CU1/images/concepts/royalty-module/royalty-module-split-lap.png?w=2500&fit=max&auto=format&n=KwuxPVrS3UIa7CU1&q=85&s=00b9dcda1f3ce02159d8ee3bc17d8d1c 2500w" />
   </Frame>

2. Now, IP Asset 3 wants to claim its revenue sitting in the IP Royalty Vault 3. It will look like this:

   <Frame>
     <img src="https://mintcdn.com/story/KwuxPVrS3UIa7CU1/images/concepts/royalty-module/ipa3-claims.png?fit=max&auto=format&n=KwuxPVrS3UIa7CU1&q=85&s=1ff2c5d8750ab747782cbeae050af512" alt="Claiming revenue from IP Royalty Vault" data-og-width="2196" width="2196" data-og-height="1272" height="1272" data-path="images/concepts/royalty-module/ipa3-claims.png" data-optimize="true" data-opv="3" srcset="https://mintcdn.com/story/KwuxPVrS3UIa7CU1/images/concepts/royalty-module/ipa3-claims.png?w=280&fit=max&auto=format&n=KwuxPVrS3UIa7CU1&q=85&s=bd6b011fcdcd978ea17e9c23bc994a27 280w, https://mintcdn.com/story/KwuxPVrS3UIa7CU1/images/concepts/royalty-module/ipa3-claims.png?w=560&fit=max&auto=format&n=KwuxPVrS3UIa7CU1&q=85&s=a94f369984ad2dede20cdd38a3a3b02e 560w, https://mintcdn.com/story/KwuxPVrS3UIa7CU1/images/concepts/royalty-module/ipa3-claims.png?w=840&fit=max&auto=format&n=KwuxPVrS3UIa7CU1&q=85&s=2da9892c1fd2950c15fa30e2f6f3f7b3 840w, https://mintcdn.com/story/KwuxPVrS3UIa7CU1/images/concepts/royalty-module/ipa3-claims.png?w=1100&fit=max&auto=format&n=KwuxPVrS3UIa7CU1&q=85&s=83cfb67ad31776fca24e37ace72d299f 1100w, https://mintcdn.com/story/KwuxPVrS3UIa7CU1/images/concepts/royalty-module/ipa3-claims.png?w=1650&fit=max&auto=format&n=KwuxPVrS3UIa7CU1&q=85&s=1163ff7c239e0ca3c1fffd229d7c7b3b 1650w, https://mintcdn.com/story/KwuxPVrS3UIa7CU1/images/concepts/royalty-module/ipa3-claims.png?w=2500&fit=max&auto=format&n=KwuxPVrS3UIa7CU1&q=85&s=1497fa8cb0cb0fa73553c4c094a4346a 2500w" />
   </Frame>

Below is how IP Asset 3 would claim their revenue, as shown in the image above, with the SDK:

<Info>
  Associated Docs:
  [royalty.claimAllRevenue](/sdk-reference/royalty#claimallrevenue)
</Info>

<Note>
  Claiming revenue is permissionless. Any wallet can run the claim revenue transaction for an IP.
</Note>

```typescript main.ts theme={null}
import { WIP_TOKEN_ADDRESS } from "@story-protocol/core-sdk";
// you should already have a client set up (prerequisite)
import { client } from "./client";

async function main() {
  const claimRevenue = await client.royalty.claimAllRevenue({
    // IP Asset 3's ipId
    ancestorIpId: "0x03",
    // the address that owns the royalty tokens,
    // which is the IP Account in this case
    claimer: "0x03",
    currencyTokens: [WIP_TOKEN_ADDRESS],
    childIpIds: [],
    royaltyPolicies: [],
    claimOptions: {
      // If the wallet claiming the revenue is the owner of the
      // IP Account/IP Asset (in other words, the owner of the
      // IP's underlying NFT), `claimAllRevenue` will transfer all
      // earnings to the user's external wallet holding the NFT
      // instead of the IP Account, for convenience. You can disable it here.
      autoTransferAllClaimedTokensFromIp: true,
      // Unwraps the claimed $WIP to $IP for you
      autoUnwrapIpTokens: true,
    },
  });

  console.log(`Claimed revenue: ${claimRevenue.claimedTokens}`);
}

main();
```

## Scenario #2

In this scenario, I own IP Asset 1. Someone pays a derivative IP Asset 3, and I have the right to a % of their revenue based on the `commercialRevShare` in the license terms. This is exactly the same as Scenario #1, except one extra step is added. Let's view this in steps:

1. As we can see in the below diagram, when someone pays IP Asset 3 100 \$WIP, 15 \$WIP automatically gets deposited to the LAP royalty policy contract to be distributed to ancestors.

   <Frame>
     <img src="https://mintcdn.com/story/KwuxPVrS3UIa7CU1/images/concepts/royalty-module/royalty-module-split-lap.png?fit=max&auto=format&n=KwuxPVrS3UIa7CU1&q=85&s=c24fbc48c17c96574628a8eac087f7d9" alt="Revenue distribution to royalty policy contract" data-og-width="2164" width="2164" data-og-height="1218" height="1218" data-path="images/concepts/royalty-module/royalty-module-split-lap.png" data-optimize="true" data-opv="3" srcset="https://mintcdn.com/story/KwuxPVrS3UIa7CU1/images/concepts/royalty-module/royalty-module-split-lap.png?w=280&fit=max&auto=format&n=KwuxPVrS3UIa7CU1&q=85&s=b98c029fa2bfedb5cfe1dc984005e147 280w, https://mintcdn.com/story/KwuxPVrS3UIa7CU1/images/concepts/royalty-module/royalty-module-split-lap.png?w=560&fit=max&auto=format&n=KwuxPVrS3UIa7CU1&q=85&s=d0ef29971541358d75cb6171b52fc090 560w, https://mintcdn.com/story/KwuxPVrS3UIa7CU1/images/concepts/royalty-module/royalty-module-split-lap.png?w=840&fit=max&auto=format&n=KwuxPVrS3UIa7CU1&q=85&s=3d20d2ec307fed750437d944c20444c6 840w, https://mintcdn.com/story/KwuxPVrS3UIa7CU1/images/concepts/royalty-module/royalty-module-split-lap.png?w=1100&fit=max&auto=format&n=KwuxPVrS3UIa7CU1&q=85&s=a8e4f23a10ed304f84332085a7c2a056 1100w, https://mintcdn.com/story/KwuxPVrS3UIa7CU1/images/concepts/royalty-module/royalty-module-split-lap.png?w=1650&fit=max&auto=format&n=KwuxPVrS3UIa7CU1&q=85&s=1c5cb6309ba6345f3e9345f374b14cd6 1650w, https://mintcdn.com/story/KwuxPVrS3UIa7CU1/images/concepts/royalty-module/royalty-module-split-lap.png?w=2500&fit=max&auto=format&n=KwuxPVrS3UIa7CU1&q=85&s=00b9dcda1f3ce02159d8ee3bc17d8d1c 2500w" />
   </Frame>

2. Then, in a second step, the tokens are transferred to the ancestors' [IP Royalty Vault](/concepts/royalty-module/ip-royalty-vault) based on the negotiated `commercialRevShare` in the license terms.

   <Frame>
     <img src="https://mintcdn.com/story/Ci-RgMKFKns3XzFq/images/concepts/royalty-module/claim-to-ip1.png?fit=max&auto=format&n=Ci-RgMKFKns3XzFq&q=85&s=eda4d640fd26720785e91a9968fb416c" alt="Revenue distribution to ancestors" data-og-width="2186" width="2186" data-og-height="1270" height="1270" data-path="images/concepts/royalty-module/claim-to-ip1.png" data-optimize="true" data-opv="3" srcset="https://mintcdn.com/story/Ci-RgMKFKns3XzFq/images/concepts/royalty-module/claim-to-ip1.png?w=280&fit=max&auto=format&n=Ci-RgMKFKns3XzFq&q=85&s=5bd9495e60b0a4a6c2650f0a659a91de 280w, https://mintcdn.com/story/Ci-RgMKFKns3XzFq/images/concepts/royalty-module/claim-to-ip1.png?w=560&fit=max&auto=format&n=Ci-RgMKFKns3XzFq&q=85&s=c182fc64645f2da2470f65461eee477d 560w, https://mintcdn.com/story/Ci-RgMKFKns3XzFq/images/concepts/royalty-module/claim-to-ip1.png?w=840&fit=max&auto=format&n=Ci-RgMKFKns3XzFq&q=85&s=e2e1338a7e6afca0a73020b284dfb04e 840w, https://mintcdn.com/story/Ci-RgMKFKns3XzFq/images/concepts/royalty-module/claim-to-ip1.png?w=1100&fit=max&auto=format&n=Ci-RgMKFKns3XzFq&q=85&s=1caaf7f281677951cf84a6e95e98b35c 1100w, https://mintcdn.com/story/Ci-RgMKFKns3XzFq/images/concepts/royalty-module/claim-to-ip1.png?w=1650&fit=max&auto=format&n=Ci-RgMKFKns3XzFq&q=85&s=c8631e0b0ba3f89146c4ee1692fc9527 1650w, https://mintcdn.com/story/Ci-RgMKFKns3XzFq/images/concepts/royalty-module/claim-to-ip1.png?w=2500&fit=max&auto=format&n=Ci-RgMKFKns3XzFq&q=85&s=232174ddecf30af46151a9038f259037 2500w" />
   </Frame>

3. Lastly, IP Asset 1 wants to claim their revenue sitting in its associated IP Royalty Vault. It will look like this:

   <Frame>
     <img src="https://mintcdn.com/story/Ci-RgMKFKns3XzFq/images/concepts/royalty-module/claim-to-ip1-account.png?fit=max&auto=format&n=Ci-RgMKFKns3XzFq&q=85&s=084d29d3231f6d30449b4d8e1f249840" alt="Claiming revenue from ancestor IP Royalty Vaults" data-og-width="2192" width="2192" data-og-height="1304" height="1304" data-path="images/concepts/royalty-module/claim-to-ip1-account.png" data-optimize="true" data-opv="3" srcset="https://mintcdn.com/story/Ci-RgMKFKns3XzFq/images/concepts/royalty-module/claim-to-ip1-account.png?w=280&fit=max&auto=format&n=Ci-RgMKFKns3XzFq&q=85&s=eedb17d4beb74520bfc2e449048b0e15 280w, https://mintcdn.com/story/Ci-RgMKFKns3XzFq/images/concepts/royalty-module/claim-to-ip1-account.png?w=560&fit=max&auto=format&n=Ci-RgMKFKns3XzFq&q=85&s=930bf358d914070d2147bc5e9334d7f9 560w, https://mintcdn.com/story/Ci-RgMKFKns3XzFq/images/concepts/royalty-module/claim-to-ip1-account.png?w=840&fit=max&auto=format&n=Ci-RgMKFKns3XzFq&q=85&s=2ccb2f4e13d8ba22a9f93abe20a41703 840w, https://mintcdn.com/story/Ci-RgMKFKns3XzFq/images/concepts/royalty-module/claim-to-ip1-account.png?w=1100&fit=max&auto=format&n=Ci-RgMKFKns3XzFq&q=85&s=2869fa3ceffba0602a996d536bb32623 1100w, https://mintcdn.com/story/Ci-RgMKFKns3XzFq/images/concepts/royalty-module/claim-to-ip1-account.png?w=1650&fit=max&auto=format&n=Ci-RgMKFKns3XzFq&q=85&s=fc73788ed1bbbe8c6a39a6958f377133 1650w, https://mintcdn.com/story/Ci-RgMKFKns3XzFq/images/concepts/royalty-module/claim-to-ip1-account.png?w=2500&fit=max&auto=format&n=Ci-RgMKFKns3XzFq&q=85&s=501c819a795d7fd016dd980e28d5b403 2500w" />
   </Frame>

Below is how IP Asset 1 (or 2) would claim their revenue, as shown in the image above, with the SDK:

<Info>
  Associated Docs:
  [royalty.claimAllRevenue](/sdk-reference/royalty#claimallrevenue)
</Info>

<Note>
  Claiming revenue is permissionless. Any wallet can run the claim revenue transaction for an IP.
</Note>

```typescript main.ts theme={null}
import { WIP_TOKEN_ADDRESS } from "@story-protocol/core-sdk";
// you should already have a client set up (prerequisite)
import { client } from "./client";

async function main() {
  const claimRevenue = await client.royalty.claimAllRevenue({
    // IP Asset 1's ipId
    ancestorIpId: "0x01",
    // the address that owns the royalty tokens,
    // which is the IP Account in this case
    claimer: "0x01",
    currencyTokens: [WIP_TOKEN_ADDRESS],
    // IP Asset 3's ipId
    childIpIds: ["0x03"],
    // Aeneid testnet address of RoyaltyPolicyLAP
    royaltyPolicies: ["0xBe54FB168b3c982b7AaE60dB6CF75Bd8447b390E"],
    claimOptions: {
      // If the wallet claiming the revenue is the owner of the
      // IP Account/IP Asset (in other words, the owner of the
      // IP's underlying NFT), `claimAllRevenue` will transfer all
      // earnings to the user's external wallet holding the NFT
      // instead of the IP Account, for convenience. You can disable it here.
      autoTransferAllClaimedTokensFromIp: true,
      // Unwraps the claimed $WIP to $IP for you
      autoUnwrapIpTokens: true,
    },
  });

  console.log(`Claimed revenue: ${claimRevenue.claimedTokens}`);
}

main();
```

## Scenario #3

In this scenario, I own IP Asset 1. Someone pays a derivative IP Asset 3, and I have the right to a % of their revenue based on the `commercialRevShare` in the license terms. The difference here is that I have previously transferred the royalty tokens in the IP Account to an external wallet, most commonly the wallet that owns the IP. This is exactly the same as Scenario #2, except royalty is being claimed to an external wallet instead of the IP Account. Let's view this in steps:

1. As we can see in the below diagram, when someone pays IP Asset 3 100 \$WIP, 15 \$WIP automatically gets deposited to the LAP royalty policy contract to be distributed to ancestors.

   <Frame>
     <img src="https://mintcdn.com/story/KwuxPVrS3UIa7CU1/images/concepts/royalty-module/royalty-module-split-lap.png?fit=max&auto=format&n=KwuxPVrS3UIa7CU1&q=85&s=c24fbc48c17c96574628a8eac087f7d9" alt="Revenue distribution to royalty policy contract" data-og-width="2164" width="2164" data-og-height="1218" height="1218" data-path="images/concepts/royalty-module/royalty-module-split-lap.png" data-optimize="true" data-opv="3" srcset="https://mintcdn.com/story/KwuxPVrS3UIa7CU1/images/concepts/royalty-module/royalty-module-split-lap.png?w=280&fit=max&auto=format&n=KwuxPVrS3UIa7CU1&q=85&s=b98c029fa2bfedb5cfe1dc984005e147 280w, https://mintcdn.com/story/KwuxPVrS3UIa7CU1/images/concepts/royalty-module/royalty-module-split-lap.png?w=560&fit=max&auto=format&n=KwuxPVrS3UIa7CU1&q=85&s=d0ef29971541358d75cb6171b52fc090 560w, https://mintcdn.com/story/KwuxPVrS3UIa7CU1/images/concepts/royalty-module/royalty-module-split-lap.png?w=840&fit=max&auto=format&n=KwuxPVrS3UIa7CU1&q=85&s=3d20d2ec307fed750437d944c20444c6 840w, https://mintcdn.com/story/KwuxPVrS3UIa7CU1/images/concepts/royalty-module/royalty-module-split-lap.png?w=1100&fit=max&auto=format&n=KwuxPVrS3UIa7CU1&q=85&s=a8e4f23a10ed304f84332085a7c2a056 1100w, https://mintcdn.com/story/KwuxPVrS3UIa7CU1/images/concepts/royalty-module/royalty-module-split-lap.png?w=1650&fit=max&auto=format&n=KwuxPVrS3UIa7CU1&q=85&s=1c5cb6309ba6345f3e9345f374b14cd6 1650w, https://mintcdn.com/story/KwuxPVrS3UIa7CU1/images/concepts/royalty-module/royalty-module-split-lap.png?w=2500&fit=max&auto=format&n=KwuxPVrS3UIa7CU1&q=85&s=00b9dcda1f3ce02159d8ee3bc17d8d1c 2500w" />
   </Frame>

2. Then, in a second step, the tokens are transferred to the ancestors' [IP Royalty Vault](/concepts/royalty-module/ip-royalty-vault) based on the negotiated `commercialRevShare` in the license terms.

   <Frame>
     <img src="https://mintcdn.com/story/Ci-RgMKFKns3XzFq/images/concepts/royalty-module/claim-to-ip1.png?fit=max&auto=format&n=Ci-RgMKFKns3XzFq&q=85&s=eda4d640fd26720785e91a9968fb416c" alt="Revenue distribution to ancestors" data-og-width="2186" width="2186" data-og-height="1270" height="1270" data-path="images/concepts/royalty-module/claim-to-ip1.png" data-optimize="true" data-opv="3" srcset="https://mintcdn.com/story/Ci-RgMKFKns3XzFq/images/concepts/royalty-module/claim-to-ip1.png?w=280&fit=max&auto=format&n=Ci-RgMKFKns3XzFq&q=85&s=5bd9495e60b0a4a6c2650f0a659a91de 280w, https://mintcdn.com/story/Ci-RgMKFKns3XzFq/images/concepts/royalty-module/claim-to-ip1.png?w=560&fit=max&auto=format&n=Ci-RgMKFKns3XzFq&q=85&s=c182fc64645f2da2470f65461eee477d 560w, https://mintcdn.com/story/Ci-RgMKFKns3XzFq/images/concepts/royalty-module/claim-to-ip1.png?w=840&fit=max&auto=format&n=Ci-RgMKFKns3XzFq&q=85&s=e2e1338a7e6afca0a73020b284dfb04e 840w, https://mintcdn.com/story/Ci-RgMKFKns3XzFq/images/concepts/royalty-module/claim-to-ip1.png?w=1100&fit=max&auto=format&n=Ci-RgMKFKns3XzFq&q=85&s=1caaf7f281677951cf84a6e95e98b35c 1100w, https://mintcdn.com/story/Ci-RgMKFKns3XzFq/images/concepts/royalty-module/claim-to-ip1.png?w=1650&fit=max&auto=format&n=Ci-RgMKFKns3XzFq&q=85&s=c8631e0b0ba3f89146c4ee1692fc9527 1650w, https://mintcdn.com/story/Ci-RgMKFKns3XzFq/images/concepts/royalty-module/claim-to-ip1.png?w=2500&fit=max&auto=format&n=Ci-RgMKFKns3XzFq&q=85&s=232174ddecf30af46151a9038f259037 2500w" />
   </Frame>

3. Lastly, IP Asset 1 wants to claim their revenue sitting in its associated IP Royalty Vault. It will look like this:

   <Frame>
     <img src="https://mintcdn.com/story/Ci-RgMKFKns3XzFq/images/concepts/royalty-module/claim-to-ip1-owner.png?fit=max&auto=format&n=Ci-RgMKFKns3XzFq&q=85&s=61dcedfdebb7170e07572641a5e752e9" alt="Claiming revenue from ancestor IP Royalty Vaults" data-og-width="1756" width="1756" data-og-height="1164" height="1164" data-path="images/concepts/royalty-module/claim-to-ip1-owner.png" data-optimize="true" data-opv="3" srcset="https://mintcdn.com/story/Ci-RgMKFKns3XzFq/images/concepts/royalty-module/claim-to-ip1-owner.png?w=280&fit=max&auto=format&n=Ci-RgMKFKns3XzFq&q=85&s=e0675ccc0e686c2e9d0132d6daae7a0c 280w, https://mintcdn.com/story/Ci-RgMKFKns3XzFq/images/concepts/royalty-module/claim-to-ip1-owner.png?w=560&fit=max&auto=format&n=Ci-RgMKFKns3XzFq&q=85&s=1897bdc6f2eec4f1d5235ec0f3ac0ea0 560w, https://mintcdn.com/story/Ci-RgMKFKns3XzFq/images/concepts/royalty-module/claim-to-ip1-owner.png?w=840&fit=max&auto=format&n=Ci-RgMKFKns3XzFq&q=85&s=48d2146329cc949b430b85b59253c860 840w, https://mintcdn.com/story/Ci-RgMKFKns3XzFq/images/concepts/royalty-module/claim-to-ip1-owner.png?w=1100&fit=max&auto=format&n=Ci-RgMKFKns3XzFq&q=85&s=b78d9fe8dfac57262ffad991f11bd297 1100w, https://mintcdn.com/story/Ci-RgMKFKns3XzFq/images/concepts/royalty-module/claim-to-ip1-owner.png?w=1650&fit=max&auto=format&n=Ci-RgMKFKns3XzFq&q=85&s=e43b91e8f165340957ae0b7ccf4578f0 1650w, https://mintcdn.com/story/Ci-RgMKFKns3XzFq/images/concepts/royalty-module/claim-to-ip1-owner.png?w=2500&fit=max&auto=format&n=Ci-RgMKFKns3XzFq&q=85&s=ee8d96c00f8099aca75cce3ed324241a 2500w" />
   </Frame>

Below is how IP Asset 1 (or 2) would claim their revenue, as shown in the image above, with the SDK:

<Info>
  Associated Docs:
  [royalty.claimAllRevenue](/sdk-reference/royalty#claimallrevenue)
</Info>

<Note>
  Claiming revenue is permissionless. Any wallet can run the claim revenue transaction for an IP.
</Note>

```typescript main.ts theme={null}
import { WIP_TOKEN_ADDRESS } from "@story-protocol/core-sdk";
// you should already have a client set up (prerequisite)
import { client } from "./client";

async function main() {
  // transfer the royalty tokens from the
  // ip account to the external wallet
  // NOTE: this can only be called by the IP owner
  // and only needs to be called once. Any future
  // claims will be to this external wallet
  const royaltyVaultAddress = await client.royalty.getRoyaltyVaultAddress("0x01");
  const transferRoyaltyTokens = await client.ipAccount.transferErc20({
    ipId: "0x01",
    tokens: [
      {
        address: royaltyVaultAddress,
        amount: 100_000_000, // 100% of the royalty tokens
        target: "0x04", // the external wallet
      },
    ],
  });

  // claim the revenue to the external wallet
  const claimRevenue = await client.royalty.claimAllRevenue({
    // IP Asset 1's ipId
    ancestorIpId: "0x01",
    // the address that owns the royalty tokens,
    // which is the external wallet in this case
    claimer: "0x04",
    currencyTokens: [WIP_TOKEN_ADDRESS],
    // IP Asset 3's ipId
    childIpIds: ["0x03"],
    // Aeneid testnet address of RoyaltyPolicyLAP
    royaltyPolicies: ["0xBe54FB168b3c982b7AaE60dB6CF75Bd8447b390E"],
    claimOptions: {
      // If the wallet claiming the revenue is the owner of the
      // IP Account/IP Asset (in other words, the owner of the
      // IP's underlying NFT), `claimAllRevenue` will transfer all
      // earnings to the user's external wallet holding the NFT
      // instead of the IP Account, for convenience. You can disable it here.
      autoTransferAllClaimedTokensFromIp: true,
      // Unwraps the claimed $WIP to $IP for you
      autoUnwrapIpTokens: true,
    },
  });

  console.log(`Claimed revenue: ${claimRevenue.claimedTokens}`);
}

main();
```

## View Completed Code

Congratulations, you claimed revenue using the [Royalty Module](/concepts/royalty-module)!

<CardGroup cols={1}>
  <Card title="Completed Code" href="https://github.com/storyprotocol/typescript-tutorial/blob/main/scripts/royalty/payRevenue.ts" icon="thumbs-up">
    All of this page is covered in this working code example.
  </Card>
</CardGroup>

## Dispute an IP

Now what happens if an IP Asset doesn't pay their due share? We can dispute the IP on-chain, which we will cover on the next page.
# Pay an IPA

> Learn how to pay an IP Asset in TypeScript.

<CardGroup cols={1}>
  <Card title="Completed Code" href="https://github.com/storyprotocol/typescript-tutorial/blob/main/scripts/royalty/payRevenue.ts" icon="thumbs-up">
    All of this page is covered in this working code example.
  </Card>
</CardGroup>

This section demonstrates how to pay an IP Asset. There are a few reasons you would do this:

1. You simply want to "tip" an IP
2. You have to because your license terms with an ancestor IP require you to forward a certain % of payment

In either scenario, you would use the below `payRoyaltyOnBehalf` function. When this happens, the [Royalty Module](/concepts/royalty-module) automatically handles the different payment flows such that parent IP Assets who have negotiated a certain `commercialRevShare` with the IPA being paid can claim their due share.

### Prerequisites

There are a few steps you have to complete before you can start the tutorial.

1. Complete the [TypeScript SDK Setup](/developers/typescript-sdk/setup)
2. Have a basic understanding of the [Royalty Module](/concepts/royalty-module)

## Before We Start

You can pay an IP Asset using the `payRoyaltyOnBehalf` function.

You will be paying the IP Asset with [\$WIP](https://aeneid.storyscan.io/address/0x1514000000000000000000000000000000000000). **Note that if you don't have enough \$WIP, the function will auto wrap an equivalent amount of \$IP into \$WIP for you.** If you don't have enough of either, it will fail.

To help with the following scenarios, let's say we have a parent IP Asset that has negotiated a 50% `commercialRevShare` with its child IP Asset.

### Whitelisted Revenue Tokens

Only tokens that are whitelisted by our protocol can be used as payment ("revenue") tokens. \$WIP is one of those tokens. To see that list, go [here](/developers/deployed-smart-contracts#whitelisted-revenue-tokens).

<Tip>
  If you want to test paying IP Assets, you'll probably want a whitelisted revenue token you can mint freely for testing. We have provided [MockERC20](https://aeneid.storyscan.io/address/0xF2104833d386a2734a4eB3B8ad6FC6812F29E38E?tab=write_contract#0x40c10f19) on Aeneid testnet which you can mint and pay with. Then when you're ready, you should use \$WIP.
</Tip>

## Scenario #1: Tipping an IP Asset

In this scenario, you're an external 3rd-party user who wants to pay an IP Asset 2 \$WIP for being cool. When you call the function below, you should make `payerIpId` a zero address because you are not paying on behalf of an IP Asset. Additionally, you would set `amount` to 2.

<Info>
  Associated Docs:
  [royalty.payRoyaltyOnBehalf](/sdk-reference/royalty#payroyaltyonbehalf)
</Info>

```typescript main.ts theme={null}
import { WIP_TOKEN_ADDRESS } from "@story-protocol/core-sdk";
// you should already have a client set up (prerequisite)
import { client } from "./utils";
import { zeroAddress, parseEther } from "viem";

async function main() {
  const payRoyalty = await client.royalty.payRoyaltyOnBehalf({
    receiverIpId: "0x0b825D9E5FA196e6B563C0a446e8D9885057f9B1", // the ip you're paying
    payerIpId: zeroAddress,
    token: WIP_TOKEN_ADDRESS,
    amount: parseEther("2"), // 2 $WIP
  });

  console.log(`Paid royalty at transaction hash ${payRoyalty.txHash}`);
}

main();
```

Let's say the IP Asset you're paying is a derivative. And due to existing license terms with a parent that specify 50% `commercialRevShare`, 50% of the revenue (2\*0.5 = 1) would automatically be claimable by the parent thanks to the [Royalty Module](/concepts/royalty-module), such that both the parent and child IP Assets earn 1 \$WIP. We'll go over this on the next page.

## Scenario #2: Paying Due Share

In this scenario, lets say a derivative IP Asset earned 2 USD off-chain. Because the derivative owes the parent IP Asset 50% of its revenue, it could give the parent 1 USD off-chain and be ok. Or, it can send 1 \$USD equivalent to the parent on-chain *(for this example, let's just assume 1 \$WIP = 1 USD)*.

<Info>
  Associated Docs:
  [royalty.payRoyaltyOnBehalf](/sdk-reference/royalty#payroyaltyonbehalf)
</Info>

```typescript main.ts theme={null}
import { WIP_TOKEN_ADDRESS } from "@story-protocol/core-sdk";
// you should already have a client set up (prerequisite)
import { client } from "./utils";
import { parseEther } from "viem";

async function main() {
  const payRoyalty = await client.royalty.payRoyaltyOnBehalf({
    receiverIpId: "0xDa03c4B278AD44f5a669e9b73580F91AeDE0E3B2", // parentIpId
    payerIpId: "0x0b825D9E5FA196e6B563C0a446e8D9885057f9B1", // childIpId
    token: WIP_TOKEN_ADDRESS,
    amount: parseEther("1"), // 1 $WIP
  });

  console.log(`Paid royalty at transaction hash ${payRoyalty.txHash}`);
}

main();
```

### Complex Royalty Graphs

Let's say the child earned 1,000 USD off-chain, and is linked to a huge ancestor tree where each parent has a different set of complex license terms. In this scenario, you won't be able to individually calculate each payment to each parent. Instead, you would just pay *yourself* the amount you earned, and the [Royalty Module](/concepts/royalty-module) will automate the payment, such that each ancestor gets their due share.

## View Completed Code

Congratulations, you paid an IP Asset on-chain!

<CardGroup cols={1}>
  <Card title="Completed Code" href="https://github.com/storyprotocol/typescript-tutorial/blob/main/scripts/royalty/payRevenue.ts" icon="thumbs-up">
    All of this page is covered in this working code example.
  </Card>
</CardGroup>

## Claiming Revenue

Now that we have paid revenue, we need to learn how to claim it! We will cover that on the next page.
# Raise a Dispute

> Learn how to create an on-chain dispute in TypeScript.

<CardGroup cols={1}>
  <Card title="Completed Code" href="https://github.com/storyprotocol/typescript-tutorial/blob/main/scripts/dispute/disputeIp.ts" icon="thumbs-up">
    All of this page is covered in this working code example.
  </Card>
</CardGroup>

This section demonstrates how to dispute an IP on Story. There are many instances where you may want to dispute an IP - whether that IP is or is not owned by you. Disputing IP on Story is easy thanks to our [Dispute Module](/concepts/dispute-module) and the [UMA Arbitration Policy](/concepts/dispute-module/uma-arbitration-policy).

Let's say you register a drawing, and then someone else registers that drawing with 1 pixel off. You can dispute it along a `IMPROPER_REGISTRATION` tag, which communicates potential plagiarism.

In this tutorial, you will simply learn how to flag an IP as being disputed.

### Prerequisites

There are a few steps you have to complete before you can start the tutorial.

1. Complete the [TypeScript SDK Setup](/developers/typescript-sdk/setup)
2. Have a basic understanding of the [Dispute Module](/concepts/dispute-module)

## 1. Dispute an IP

To dispute an IP Asset, you will need:

* The `targetIpId` of the IP Asset you are disputing (we use a test one below)
* The `targetTag` that you are applying to the dispute. Only [whitelisted tags](/concepts/dispute-module/overview#dispute-tags) can be applied.
* A `cid` (Content Identifier) is a unique identifier in IPFS that represents the dispute evidence you must provide, as described [here](/concepts/dispute-module/uma-arbitration-policy#dispute-evidence-submission-guidelines) (we use a test one below).

<Warning>
  **Note you can only provide a CID one time.** After it is used, it can't be
  used as evidence again.
</Warning>

Create a `main.ts` file and add the code below:

```typescript main.ts theme={null}
import { client } from "./utils";
import { parseEther } from "viem";
import { DisputeTargetTag } from "@story-protocol/core-sdk";

async function main() {
  const disputeResponse = await client.dispute.raiseDispute({
    targetIpId: "0x6b42d065aDCDA6fA83B59ad731841360dC5321fB",
    // NOTE: you must use your own CID here, because every time it is used,
    // the protocol does not allow you to use it again
    cid: "QmbWqxBEKC3P8tqsKc98xmWNzrzDtRLMiMPL8wBuTGsMnR",
    // you must pick from one of the whitelisted tags here: https://docs.story.foundation/concepts/dispute-module#dispute-tags
    targetTag: DisputeTargetTag.IMPROPER_REGISTRATION,
    bond: parseEther("0.1"), // minimum of 0.1
    liveness: 2592000,
  });
  console.log(
    `Dispute raised at transaction hash ${disputeResponse.txHash}, Dispute ID: ${disputeResponse.disputeId}`
  );
}

main();
```

## 2. View Completed Code

<CardGroup cols={1}>
  <Card title="Completed Code" href="https://github.com/storyprotocol/typescript-tutorial/blob/main/scripts/dispute/disputeIp.ts" icon="thumbs-up">
    See a completed, working example disputing an IP.
  </Card>
</CardGroup>
# Setup

> Set up your development environment for Story smart contracts.

In this guide, we will show you how to setup the Story smart contract development environment in just a few minutes.

## Prerequisites

* [Install Foundry](https://book.getfoundry.sh/getting-started/installation)
* [Install yarn](https://classic.yarnpkg.com/lang/en/docs/install/)

## Creating a Project

1. Run `foundryup` to automatically install the latest stable version of the precompiled binaries: forge, cast, anvil, and chisel
2. Run the following command in a new directory: `forge init`. This will create a `foundry.toml` and example project files in the project root. By default, forge init will also initialize a new git repository.
3. Initialize a new yarn project: `yarn init`. (⚠️ Note: Only Yarn is compatible with the packages used in this project. Using `npm` or `pnpm` may result in dependency conflicts.)
4. Open up your root-level `foundry.toml` file (located in the top directory of your project) and replace it with this:

```toml  theme={null}
[profile.default]
out = 'out'
libs = ['node_modules', 'lib']
cache_path  = 'forge-cache'
gas_reports = ["*"]
optimizer = true
optimizer_runs = 20000
test = 'test'
solc = '0.8.26'
fs_permissions = [{ access = 'read', path = './out' }, { access = 'read-write', path = './deploy-out' }]
evm_version = 'cancun'
remappings = [
    '@openzeppelin/=node_modules/@openzeppelin/',
    '@storyprotocol/core/=node_modules/@story-protocol/protocol-core/contracts/',
    '@storyprotocol/periphery/=node_modules/@story-protocol/protocol-periphery/contracts/',
    'erc6551/=node_modules/erc6551/',
    'forge-std/=node_modules/forge-std/src/',
    'ds-test/=node_modules/ds-test/src/',
    '@storyprotocol/test/=node_modules/@story-protocol/protocol-core/test/foundry/',
    '@solady/=node_modules/solady/'
]
```

5. Remove the example contract files: `rm src/Counter.sol script/Counter.s.sol test/Counter.t.sol`

## Installing Dependencies

Now, we are ready to start installing our dependencies. To incorporate the Story Protocol core and periphery modules, run the following to have them added to your `package.json`. We will also install `openzeppelin` and `erc6551` as a dependency for the contract and test.

```bash  theme={null}
# note: you can run them one-by-one, or all at once
yarn add @story-protocol/protocol-core@https://github.com/storyprotocol/protocol-core-v1
yarn add @story-protocol/protocol-periphery@https://github.com/storyprotocol/protocol-periphery-v1
yarn add @openzeppelin/contracts
yarn add @openzeppelin/contracts-upgradeable
yarn add erc6551
yarn add solady
```

Additionally, for working with Foundry's test kit, we also recommend adding the following `devDependencies`:

```bash  theme={null}
yarn add -D https://github.com/dapphub/ds-test
yarn add -D github:foundry-rs/forge-std#v1.7.6
```

Now we are ready to build a simple test registration contract!
# Using an Example

> Combine all of our tutorials together in a practical example.

<CardGroup cols={2}>
  <Card title="Completed Code" href="https://github.com/storyprotocol/story-protocol-boilerplate/blob/main/src/Example.sol" icon="thumbs-up">
    See the completed code.
  </Card>

  <Card title="Video Walkthrough" href="https://www.youtube.com/watch?v=X421IuZENqM" icon="video">
    Check out a video walkthrough of this tutorial!
  </Card>
</CardGroup>

# Writing the Smart Contract

Now that we have walked through each of the individual steps, let's try to write, deploy, and verify our own smart contract.

## Register IPA, Register License Terms, and Attach to IPA

In this first section, we will combine a few of the tutorials into one. We will create a function named `mintAndRegisterAndCreateTermsAndAttach` that allows you to mint & register a new IP Asset, register new License Terms, and attach those terms to an IP Asset. It will also accept a `receiver` field to be the owner of the new IP Asset.

### Prerequisites

* Complete [Register an IP Asset](/developers/smart-contracts-guide/register-ip-asset)
* Complete [Register License Terms](/developers/smart-contracts-guide/register-terms)
* Complete [Attach Terms to an IPA](/developers/smart-contracts-guide/attach-terms)

### Writing our Contract

Create a new file under `./src/Example.sol` and paste the following:

<Note>
  **Contract Addresses**

  In order to get the contract addresses to pass in the constructor, go to [Deployed Smart Contracts](/developers/deployed-smart-contracts).
</Note>

```solidity src/Example.sol theme={null}
// SPDX-License-Identifier: UNLICENSED
pragma solidity ^0.8.26;

import { IIPAssetRegistry } from "@storyprotocol/core/interfaces/registries/IIPAssetRegistry.sol";
import { ILicensingModule } from "@storyprotocol/core/interfaces/modules/licensing/ILicensingModule.sol";
import { IPILicenseTemplate } from "@storyprotocol/core/interfaces/modules/licensing/IPILicenseTemplate.sol";
import { PILFlavors } from "@storyprotocol/core/lib/PILFlavors.sol";

import { SimpleNFT } from "./mocks/SimpleNFT.sol";

import { ERC721Holder } from "@openzeppelin/contracts/token/ERC721/utils/ERC721Holder.sol";

/// @notice An example contract that demonstrates how to mint an NFT, register it as an IP Asset,
/// attach license terms to it, mint a license token from it, and register it as a derivative of the parent.
contract Example is ERC721Holder {
  IIPAssetRegistry public immutable IP_ASSET_REGISTRY;
  ILicensingModule public immutable LICENSING_MODULE;
  IPILicenseTemplate public immutable PIL_TEMPLATE;
  address public immutable ROYALTY_POLICY_LAP;
  address public immutable WIP;
  SimpleNFT public immutable SIMPLE_NFT;

  constructor(
    address ipAssetRegistry,
    address licensingModule,
    address pilTemplate,
    address royaltyPolicyLAP,
    address wip
  ) {
    IP_ASSET_REGISTRY = IIPAssetRegistry(ipAssetRegistry);
    LICENSING_MODULE = ILicensingModule(licensingModule);
    PIL_TEMPLATE = IPILicenseTemplate(pilTemplate);
    ROYALTY_POLICY_LAP = royaltyPolicyLAP;
    WIP = wip;
    // Create a new Simple NFT collection
    SIMPLE_NFT = new SimpleNFT("Simple IP NFT", "SIM");
  }

  /// @notice Mint an NFT, register it as an IP Asset, and attach License Terms to it.
  /// @param receiver The address that will receive the NFT/IPA.
  /// @return tokenId The token ID of the NFT representing ownership of the IPA.
  /// @return ipId The address of the IP Account.
  /// @return licenseTermsId The ID of the license terms.
  function mintAndRegisterAndCreateTermsAndAttach(
    address receiver
  ) external returns (uint256 tokenId, address ipId, uint256 licenseTermsId) {
    // We mint to this contract so that it has permissions
    // to attach license terms to the IP Asset.
    // We will later transfer it to the intended `receiver`
    tokenId = SIMPLE_NFT.mint(address(this));
    ipId = IP_ASSET_REGISTRY.register(block.chainid, address(SIMPLE_NFT), tokenId);

    // register license terms so we can attach them later
    licenseTermsId = PIL_TEMPLATE.registerLicenseTerms(
      PILFlavors.commercialRemix({
        mintingFee: 0,
        commercialRevShare: 10 * 10 ** 6, // 10%
        royaltyPolicy: ROYALTY_POLICY_LAP,
        currencyToken: WIP
      })
    );

    // attach the license terms to the IP Asset
    LICENSING_MODULE.attachLicenseTerms(ipId, address(PIL_TEMPLATE), licenseTermsId);

    // transfer the NFT to the receiver so it owns the IPA
    SIMPLE_NFT.transferFrom(address(this), receiver, tokenId);
  }
}
```

## Mint a License Token and Register as Derivative

In this next section, we will combine a few of the later tutorials into one. We will create a function named `mintLicenseTokenAndRegisterDerivative` that allows a potentially different user to register their own "child" (derivative) IP Asset, mint a License Token from the "parent" (root) IP Asset, and register their child IPA as a derivative of the parent IPA. It will accept a few parameters:

1. `parentIpId`: the `ipId` of the parent IPA
2. `licenseTermsId`: the id of the License Terms you want to mint a License Token for
3. `receiver`: the owner of the child IPA

### Prerequisites

* Complete [Mint a License Token](/developers/smart-contracts-guide/mint-license)
* Complete [Register a Derivative](/developers/smart-contracts-guide/register-derivative)

### Writing our Contract

In your `Example.sol` contract, add the following function at the bottom:

```solidity src/Example.sol theme={null}
/// @notice Mint and register a new child IPA, mint a License Token
/// from the parent, and register it as a derivative of the parent.
/// @param parentIpId The ipId of the parent IPA.
/// @param licenseTermsId The ID of the license terms you will
/// mint a license token from.
/// @param receiver The address that will receive the NFT/IPA.
/// @return childTokenId The token ID of the NFT representing ownership of the child IPA.
/// @return childIpId The address of the child IPA.
function mintLicenseTokenAndRegisterDerivative(
  address parentIpId,
  uint256 licenseTermsId,
  address receiver
) external returns (uint256 childTokenId, address childIpId) {
  // We mint to this contract so that it has permissions
  // to register itself as a derivative of another
  // IP Asset.
  // We will later transfer it to the intended `receiver`
  childTokenId = SIMPLE_NFT.mint(address(this));
  childIpId = IP_ASSET_REGISTRY.register(block.chainid, address(SIMPLE_NFT), childTokenId);

  // mint a license token from the parent
  uint256 licenseTokenId = LICENSING_MODULE.mintLicenseTokens({
    licensorIpId: parentIpId,
    licenseTemplate: address(PIL_TEMPLATE),
    licenseTermsId: licenseTermsId,
    amount: 1,
    // mint the license token to this contract so it can
    // use it to register as a derivative of the parent
    receiver: address(this),
    royaltyContext: "", // for PIL, royaltyContext is empty string
    maxMintingFee: 0,
    maxRevenueShare: 0
  });

  uint256[] memory licenseTokenIds = new uint256[](1);
  licenseTokenIds[0] = licenseTokenId;

  // register the new child IPA as a derivative
  // of the parent
  LICENSING_MODULE.registerDerivativeWithLicenseTokens({
    childIpId: childIpId,
    licenseTokenIds: licenseTokenIds,
    royaltyContext: "", // empty for PIL
    maxRts: 0
  });

  // transfer the NFT to the receiver so it owns the child IPA
  SIMPLE_NFT.transferFrom(address(this), receiver, childTokenId);
}
```

# Testing our Contract

Create another new file under `test/Example.t.sol` and paste the following:

```solidity test/Example.t.sol theme={null}
// SPDX-License-Identifier: UNLICENSED
pragma solidity ^0.8.26;

import { Test } from "forge-std/Test.sol";
// for testing purposes only
import { MockIPGraph } from "@storyprotocol/test/mocks/MockIPGraph.sol";
import { IIPAssetRegistry } from "@storyprotocol/core/interfaces/registries/IIPAssetRegistry.sol";
import { ILicenseRegistry } from "@storyprotocol/core/interfaces/registries/ILicenseRegistry.sol";

import { Example } from "../src/Example.sol";
import { SimpleNFT } from "../src/mocks/SimpleNFT.sol";

// Run this test:
// forge test --fork-url https://aeneid.storyrpc.io/ --match-path test/Example.t.sol
contract ExampleTest is Test {
  address internal alice = address(0xa11ce);
  address internal bob = address(0xb0b);

  // For addresses, see https://docs.story.foundation/developers/deployed-smart-contracts
  // Protocol Core - IPAssetRegistry
  address internal ipAssetRegistry = 0x77319B4031e6eF1250907aa00018B8B1c67a244b;
  // Protocol Core - LicenseRegistry
  address internal licenseRegistry = 0x529a750E02d8E2f15649c13D69a465286a780e24;
  // Protocol Core - LicensingModule
  address internal licensingModule = 0x04fbd8a2e56dd85CFD5500A4A4DfA955B9f1dE6f;
  // Protocol Core - PILicenseTemplate
  address internal pilTemplate = 0x2E896b0b2Fdb7457499B56AAaA4AE55BCB4Cd316;
  // Protocol Core - RoyaltyPolicyLAP
  address internal royaltyPolicyLAP = 0xBe54FB168b3c982b7AaE60dB6CF75Bd8447b390E;
  // Revenue Token - WIP
  address internal wip = 0x1514000000000000000000000000000000000000;

  SimpleNFT public SIMPLE_NFT;
  Example public EXAMPLE;

  function setUp() public {
    // this is only for testing purposes
    // due to our IPGraph precompile not being
    // deployed on the fork
    vm.etch(address(0x0101), address(new MockIPGraph()).code);

    EXAMPLE = new Example(ipAssetRegistry, licensingModule, pilTemplate, royaltyPolicyLAP, wip);
    SIMPLE_NFT = SimpleNFT(EXAMPLE.SIMPLE_NFT());
  }

  function test_mintAndRegisterAndCreateTermsAndAttach() public {
    ILicenseRegistry LICENSE_REGISTRY = ILicenseRegistry(licenseRegistry);
    IIPAssetRegistry IP_ASSET_REGISTRY = IIPAssetRegistry(ipAssetRegistry);

    uint256 expectedTokenId = SIMPLE_NFT.nextTokenId();
    address expectedIpId = IP_ASSET_REGISTRY.ipId(block.chainid, address(SIMPLE_NFT), expectedTokenId);

    (uint256 tokenId, address ipId, uint256 licenseTermsId) = EXAMPLE.mintAndRegisterAndCreateTermsAndAttach(alice);

    assertEq(tokenId, expectedTokenId);
    assertEq(ipId, expectedIpId);
    assertEq(SIMPLE_NFT.ownerOf(tokenId), alice);

    assertTrue(LICENSE_REGISTRY.hasIpAttachedLicenseTerms(ipId, pilTemplate, licenseTermsId));
    assertEq(LICENSE_REGISTRY.getAttachedLicenseTermsCount(ipId), 1);
    (address licenseTemplate, uint256 attachedLicenseTermsId) = LICENSE_REGISTRY.getAttachedLicenseTerms({
      ipId: ipId,
      index: 0
    });
    assertEq(licenseTemplate, pilTemplate);
    assertEq(attachedLicenseTermsId, licenseTermsId);
  }

  function test_mintLicenseTokenAndRegisterDerivative() public {
    ILicenseRegistry LICENSE_REGISTRY = ILicenseRegistry(licenseRegistry);
    IIPAssetRegistry IP_ASSET_REGISTRY = IIPAssetRegistry(ipAssetRegistry);

    (uint256 parentTokenId, address parentIpId, uint256 licenseTermsId) = EXAMPLE
    .mintAndRegisterAndCreateTermsAndAttach(alice);

    (uint256 childTokenId, address childIpId) = EXAMPLE.mintLicenseTokenAndRegisterDerivative(
      parentIpId,
      licenseTermsId,
      bob
    );

    assertTrue(LICENSE_REGISTRY.hasDerivativeIps(parentIpId));
    assertTrue(LICENSE_REGISTRY.isParentIp(parentIpId, childIpId));
    assertTrue(LICENSE_REGISTRY.isDerivativeIp(childIpId));
    assertEq(LICENSE_REGISTRY.getDerivativeIpCount(parentIpId), 1);
    assertEq(LICENSE_REGISTRY.getParentIpCount(childIpId), 1);
    assertEq(LICENSE_REGISTRY.getParentIp({ childIpId: childIpId, index: 0 }), parentIpId);
    assertEq(LICENSE_REGISTRY.getDerivativeIp({ parentIpId: parentIpId, index: 0 }), childIpId);
  }
}
```

Run `forge build`. If everything is successful, the command should successfully compile.

To test this out, simply run the following command:

```bash  theme={null}
forge test --fork-url https://aeneid.storyrpc.io/ --match-path test/Example.t.sol
```

# Deploy & Verify the Example Contract

The `--constructor-args` come from [Deployed Smart Contracts](/developers/deployed-smart-contracts).

```bash  theme={null}
forge create \
  --rpc-url https://aeneid.storyrpc.io/ \
  --private-key $PRIVATE_KEY \
  ./src/Example.sol:Example \
  --legacy \
  --verify \
  --verifier blockscout \
  --verifier-url https://aeneid.storyscan.io/api/ \
  --constructor-args 0x77319B4031e6eF1250907aa00018B8B1c67a244b 0x04fbd8a2e56dd85CFD5500A4A4DfA955B9f1dE6f 0x2E896b0b2Fdb7457499B56AAaA4AE55BCB4Cd316 0xBe54FB168b3c982b7AaE60dB6CF75Bd8447b390E 0xF2104833d386a2734a4eB3B8ad6FC6812F29E38E
```

If everything worked correctly, you should see something like `Deployed to: 0xfb0923D531C1ca54AB9ee10CB8364b23d0C7F47d` in the console. Paste that address into [the explorer](https://aeneid.storyscan.io/) and see your verified contract!

# Great job! :)

<CardGroup cols={2}>
  <Card title="Completed Code" href="https://github.com/storyprotocol/story-protocol-boilerplate/blob/main/src/Example.sol" icon="thumbs-up">
    See the completed code.
  </Card>

  <Card title="Video Walkthrough" href="https://www.youtube.com/watch?v=X421IuZENqM" icon="video">
    Check out a video walkthrough of this tutorial!
  </Card>
</CardGroup>
# Register an IP Asset

> Learn how to Register an NFT as an IP Asset in Solidity.

<Card title="Completed Code" href="https://github.com/storyprotocol/story-protocol-boilerplate/blob/main/test/0_IPARegistrar.t.sol" icon="thumbs-up">
  Follow the completed code all the way through.
</Card>

Let's say you have some off-chain IP (ex. a book, a character, a drawing, etc). In order to register that IP on Story, you first need to mint an NFT. This NFT is the **ownership** over the IP. Then you **register** that NFT on Story, turning it into an [IP Asset](/concepts/ip-asset/overview). The below tutorial will walk you through how to do this.

## Prerequisites

There are a few steps you have to complete before you can start the tutorial.

1. Complete the [Setup Your Own Project](/developers/smart-contracts-guide/setup)

## Before We Start

There are two scenarios:

1. You already have a **custom** ERC-721 NFT contract and can mint from it
2. You want to create an [SPG (Periphery)](/concepts/spg/overview) NFT contract to do minting for you

## Scenario #1: You already have a custom ERC-721 NFT contract and can mint from it

If you already have an NFT minted, or you want to register IP using a custom-built ERC-721 contract, this is the section for you.

As you can see below, the registration process is relatively straightforward. We use `SimpleNFT` as an example, but you can replace it with your own ERC-721 contract.

All you have to do is call `register` on the [IP Asset Registry](/concepts/registry/ip-asset-registry) with:

* `chainid` - you can simply use `block.chainid`
* `tokenContract` - the address of your NFT collection
* `tokenId` - your NFT's ID

Let's create a test file under `test/0_IPARegistrar.t.sol` to see it work and verify the results:

<Note>
  **Contract Addresses**

  We have filled in the addresses from the Story contracts for you. However you can also find the addresses for them here: [Deployed Smart Contracts](/developers/deployed-smart-contracts)

  You can view the `SimpleNFT` contract we're using to test [here](https://github.com/storyprotocol/story-protocol-boilerplate/blob/main/src/mocks/SimpleNFT.sol).
</Note>

<Info>
  You can view the `SimpleNFT` contract we're using to test [here](https://github.com/storyprotocol/story-protocol-boilerplate/blob/main/src/mocks/SimpleNFT.sol).
</Info>

```solidity test/0_IPARegistrar.t.sol theme={null}
// SPDX-License-Identifier: UNLICENSED
pragma solidity ^0.8.26;

import { Test } from "forge-std/Test.sol";
import { IIPAssetRegistry } from "@storyprotocol/core/interfaces/registries/IIPAssetRegistry.sol";

// your own ERC-721 NFT contract
import { SimpleNFT } from "../src/mocks/SimpleNFT.sol";

// Run this test:
// forge test --fork-url https://aeneid.storyrpc.io/ --match-path test/0_IPARegistrar.t.sol
contract IPARegistrarTest is Test {
    address internal alice = address(0xa11ce);

    // For addresses, see https://docs.story.foundation/developers/deployed-smart-contracts
    // Protocol Core - IPAssetRegistry
    IIPAssetRegistry internal IP_ASSET_REGISTRY = IIPAssetRegistry(0x77319B4031e6eF1250907aa00018B8B1c67a244b);

    SimpleNFT public SIMPLE_NFT;

    function setUp() public {
        // Create a new Simple NFT collection
        SIMPLE_NFT = new SimpleNFT("Simple IP NFT", "SIM");
    }

    /// @notice Mint an NFT and then register it as an IP Asset.
    function test_register() public {
        uint256 expectedTokenId = SIMPLE_NFT.nextTokenId();
        address expectedIpId = IP_ASSET_REGISTRY.ipId(block.chainid, address(SIMPLE_NFT), expectedTokenId);

        uint256 tokenId = SIMPLE_NFT.mint(alice);
        address ipId = IP_ASSET_REGISTRY.register(block.chainid, address(SIMPLE_NFT), tokenId);

        assertEq(tokenId, expectedTokenId);
        assertEq(ipId, expectedIpId);
        assertEq(SIMPLE_NFT.ownerOf(tokenId), alice);
    }
}
```

## Scenario #2: You want to create an SPG NFT contract to do minting for you

If you don't have your own custom NFT contract, this is the section for you.

To achieve this, we will be using the [SPG](/concepts/spg/overview), which is a utility contract that allows us to combine multiple transactions into one. In this case, we'll be using the SPG's `mintAndRegisterIp` function which combines both minting an NFT and registering it as an IP Asset.

In order to use `mintAndRegisterIp`, we first have to create a new `SPGNFT` collection. We can do this simply by calling `createCollection` on the `StoryProtocolGateway` contract. Or, if you want to create your own `SPGNFT` for some reason, you can implement the [ISPGNFT](https://github.com/storyprotocol/protocol-periphery-v1/blob/main/contracts/interfaces/ISPGNFT.sol) contract interface. Follow the example below to see example parameters you can use to initialize a new SPGNFT.

Once you have your own SPGNFT, all you have to do is call `mintAndRegisterIp` with:

* `spgNftContract` - the address of your SPGNFT contract
* `recipient` - the address of who will receive the NFT and thus be the owner of the newly registered IP. *Note: remember that registering IP on Story is permissionless, so you can register an IP for someone else (by paying for the transaction) yet they can still be the owner of that IP Asset.*
* `ipMetadata` - the metadata associated with your NFT & IP. See [this](/concepts/ip-asset/overview#nft-vs-ip-metadata) section to better understand setting NFT & IP metadata.

1. Run `touch test/0_IPARegistrar.t.sol` to create a test file under `test/0_IPARegistrar.t.sol`. Then, paste in the following code:

<Note>
  **Contract Addresses**

  We have filled in the addresses from the Story contracts for you. However you can also find the addresses for them here: [Deployed Smart Contracts](/developers/deployed-smart-contracts)
</Note>

```solidity test/0_IPARegistrar.t.sol theme={null}
// SPDX-License-Identifier: UNLICENSED
pragma solidity ^0.8.26;

import { Test } from "forge-std/Test.sol";
import { IIPAssetRegistry } from "@storyprotocol/core/interfaces/registries/IIPAssetRegistry.sol";
import { ISPGNFT } from "@storyprotocol/periphery/interfaces/ISPGNFT.sol";
import { IRegistrationWorkflows } from "@storyprotocol/periphery/interfaces/workflows/IRegistrationWorkflows.sol";
import { WorkflowStructs } from "@storyprotocol/periphery/lib/WorkflowStructs.sol";

// Run this test:
// forge test --fork-url https://aeneid.storyrpc.io/ --match-path test/0_IPARegistrar.t.sol
contract IPARegistrarTest is Test {
    address internal alice = address(0xa11ce);

    // For addresses, see https://docs.story.foundation/developers/deployed-smart-contracts
    // Protocol Core - IPAssetRegistry
    IIPAssetRegistry internal IP_ASSET_REGISTRY = IIPAssetRegistry(0x77319B4031e6eF1250907aa00018B8B1c67a244b);
    // Protocol Periphery - RegistrationWorkflows
    IRegistrationWorkflows internal REGISTRATION_WORKFLOWS =
        IRegistrationWorkflows(0xbe39E1C756e921BD25DF86e7AAa31106d1eb0424);

    ISPGNFT public SPG_NFT;

    function setUp() public {
        // Create a new NFT collection via SPG
        SPG_NFT = ISPGNFT(
            REGISTRATION_WORKFLOWS.createCollection(
                ISPGNFT.InitParams({
                    name: "Test Collection",
                    symbol: "TEST",
                    baseURI: "",
                    contractURI: "",
                    maxSupply: 100,
                    mintFee: 0,
                    mintFeeToken: address(0),
                    mintFeeRecipient: address(this),
                    owner: address(this),
                    mintOpen: true,
                    isPublicMinting: false
                })
            )
        );
    }

    /// @notice Mint an NFT and register it in the same call via the Story Protocol Gateway.
    /// @dev Requires the collection address that is passed into the `mintAndRegisterIp` function
    /// to be created via SPG (createCollection), as done above. Or, a contract that
    /// implements the `ISPGNFT` interface.
    function test_mintAndRegisterIp() public {
        uint256 expectedTokenId = SPG_NFT.totalSupply() + 1;
        address expectedIpId = IP_ASSET_REGISTRY.ipId(block.chainid, address(SPG_NFT), expectedTokenId);

        // Note: The caller of this function must be the owner of the SPG NFT Collection.
        // In this case, the owner of the SPG NFT Collection is the contract itself
        // because it deployed it in the `setup` function.
        // We can make `alice` the recipient of the NFT though, which makes her the
        // owner of not only the NFT, but therefore the IP Asset.
        (address ipId, uint256 tokenId) = REGISTRATION_WORKFLOWS.mintAndRegisterIp(
            address(SPG_NFT),
            alice,
            WorkflowStructs.IPMetadata({
                ipMetadataURI: "https://ipfs.io/ipfs/QmZHfQdFA2cb3ASdmeGS5K6rZjz65osUddYMURDx21bT73",
                ipMetadataHash: keccak256(
                    abi.encodePacked(
                        "{'title':'My IP Asset','description':'This is a test IP asset','createdAt':'','creators':[]}"
                    )
                ),
                nftMetadataURI: "https://ipfs.io/ipfs/QmRL5PcK66J1mbtTZSw1nwVqrGxt98onStx6LgeHTDbEey",
                nftMetadataHash: keccak256(
                    abi.encodePacked(
                        "{'name':'Test NFT','description':'This is a test NFT','image':'https://picsum.photos/200'}"
                    )
                )
            }),
            true
        );

        assertEq(ipId, expectedIpId);
        assertEq(tokenId, expectedTokenId);
        assertEq(SPG_NFT.ownerOf(tokenId), alice);
    }
}
```

## Run the Test and Verify the Results

2. Run `forge build`. If everything is successful, the command should successfully compile.

3. Now run the test by executing the following command:

```bash  theme={null}
forge test --fork-url https://aeneid.storyrpc.io/ --match-path test/0_IPARegistrar.t.sol
```

## Add License Terms to IP

Congratulations, you registered an IP!

<Card title="Completed Code" href="https://github.com/storyprotocol/story-protocol-boilerplate/blob/main/test/0_IPARegistrar.t.sol" icon="thumbs-up">
  Follow the completed code all the way through.
</Card>

Now that your IP is registered, you can create and attach [License Terms](/concepts/licensing-module/license-terms) to it. This will allow others to mint a license and use your IP, restricted by the terms.

We will go over this on the next page.
# Register License Terms

> Learn how to create new License Terms in Solidity.

<Card title="Completed Code" href="https://github.com/storyprotocol/story-protocol-boilerplate/blob/main/test/1_LicenseTerms.t.sol" icon="thumbs-up">
  Follow the completed code all the way through.
</Card>

[License Terms](/concepts/licensing-module/license-terms) are a configurable set of values that define restrictions on licenses minted from your IP that have those terms. For example, "If you mint this license, you must share 50% of your revenue with me." You can view the full set of terms in [PIL Terms](/concepts/programmable-ip-license/pil-terms).

## Prerequisites

There are a few steps you have to complete before you can start the tutorial.

1. Complete the [Setup Your Own Project](/developers/smart-contracts-guide/setup)

## Before We Start

It's important to know that if **License Terms already exist for the identical set of parameters you intend to create, it is unnecessary to create it again**. License Terms are protocol-wide, so you can use existing License Terms by its `licenseTermsId`.

## Register License Terms

You can view the full set of terms in [PIL Terms](/concepts/programmable-ip-license/pil-terms).

Let's create a test file under `test/1_LicenseTerms.t.sol` to see it work and verify the results:

<Note>
  **Contract Addresses**

  We have filled in the addresses from the Story contracts for you. However you can also find the addresses for them here: [Deployed Smart Contracts](/developers/deployed-smart-contracts)
</Note>

```solidity test/1_LicenseTerms.t.sol theme={null}
// SPDX-License-Identifier: UNLICENSED
pragma solidity ^0.8.26;

import { Test } from "forge-std/Test.sol";
import { IPILicenseTemplate } from "@storyprotocol/core/interfaces/modules/licensing/IPILicenseTemplate.sol";
import { PILTerms } from "@storyprotocol/core/interfaces/modules/licensing/IPILicenseTemplate.sol";

// Run this test:
// forge test --fork-url https://aeneid.storyrpc.io/ --match-path test/1_LicenseTerms.t.sol
contract LicenseTermsTest is Test {
    address internal alice = address(0xa11ce);

    // For addresses, see https://docs.story.foundation/developers/deployed-smart-contracts
    // Protocol Core - PILicenseTemplate
    IPILicenseTemplate internal PIL_TEMPLATE = IPILicenseTemplate(0x2E896b0b2Fdb7457499B56AAaA4AE55BCB4Cd316);
    // Protocol Core - RoyaltyPolicyLAP
    address internal ROYALTY_POLICY_LAP = 0xBe54FB168b3c982b7AaE60dB6CF75Bd8447b390E;
    // Revenue Token - MERC20
    address internal MERC20 = 0xF2104833d386a2734a4eB3B8ad6FC6812F29E38E;

    function setUp() public {}

    /// @notice Registers new PIL Terms. Anyone can register PIL Terms.
    function test_registerPILTerms() public {
        PILTerms memory pilTerms = PILTerms({
            transferable: true,
            royaltyPolicy: ROYALTY_POLICY_LAP,
            defaultMintingFee: 0,
            expiration: 0,
            commercialUse: true,
            commercialAttribution: true,
            commercializerChecker: address(0),
            commercializerCheckerData: "",
            commercialRevShare: 0,
            commercialRevCeiling: 0,
            derivativesAllowed: true,
            derivativesAttribution: true,
            derivativesApproval: true,
            derivativesReciprocal: true,
            derivativeRevCeiling: 0,
            currency: MERC20,
            uri: ""
        });
        uint256 licenseTermsId = PIL_TEMPLATE.registerLicenseTerms(pilTerms);

        uint256 selectedLicenseTermsId = PIL_TEMPLATE.getLicenseTermsId(pilTerms);
        assertEq(licenseTermsId, selectedLicenseTermsId);
    }
}
```

### PIL Flavors

As you see above, you have to choose between a lot of terms.

We have convenience functions to help you register new terms. We have created [PIL Flavors](/concepts/programmable-ip-license/pil-flavors), which are pre-configured popular combinations of License Terms to help you decide what terms to use. You can view those PIL Flavors and then register terms using the following convenience functions:

<CardGroup cols={2}>
  <Card title="Non-Commercial Social Remixing" href="/concepts/programmable-ip-license/pil-flavors#non-commercial-social-remixing" icon="file">
    Free remixing with attribution. No commercialization.
  </Card>

  <Card title="Commercial Use" href="/concepts/programmable-ip-license/pil-flavors#commercial-use" icon="file">
    Pay to use the license with attribution, but don't have to share revenue.
  </Card>

  <Card title="Commercial Remix" href="/concepts/programmable-ip-license/pil-flavors#commercial-remix" icon="file">
    Pay to use the license with attribution and pay % of revenue earned.
  </Card>

  <Card title="Creative Commons Attribution" href="/concepts/programmable-ip-license/pil-flavors#creative-commons-attribution" icon="file">
    Free remixing and commercial use with attribution.
  </Card>
</CardGroup>

For example:

```solidity Solidity theme={null}
import { PILFlavors } from "@storyprotocol/core/lib/PILFlavors.sol";

PILTerms memory pilTerms = PILFlavors.commercialRemix({
  mintingFee: 0,
  commercialRevShare: 5 * 10 ** 6, // 5% rev share
  royaltyPolicy: ROYALTY_POLICY_LAP,
  currencyToken: MERC20
});
```

## Test Your Code!

Run `forge build`. If everything is successful, the command should successfully compile.

Now run the test by executing the following command:

```bash  theme={null}
forge test --fork-url https://aeneid.storyrpc.io/ --match-path test/1_LicenseTerms.t.sol
```

## Attach Terms to Your IP

Congratulations, you created new license terms!

<Card title="Completed Code" href="https://github.com/storyprotocol/story-protocol-boilerplate/blob/main/test/1_LicenseTerms.t.sol" icon="thumbs-up">
  Follow the completed code all the way through.
</Card>

Now that you have registered new license terms, we can attach them to an IP Asset. This will allow others to mint a license and use your IP, restricted by the terms.

We will go over this on the next page.
# Attach Terms to an IPA

> Learn how to attach License Terms to an IP Asset in Solidity.

<Card title="Completed Code" href="https://github.com/storyprotocol/story-protocol-boilerplate/blob/main/test/2_AttachTerms.t.sol" icon="thumbs-up">
  Follow the completed code all the way through.
</Card>

This section demonstrates how to attach [License Terms](/concepts/licensing-module/license-terms) to an [IP Asset](/concepts/ip-asset/overview). By attaching terms, users can publicly mint [License Tokens](/concepts/licensing-module/license-token) (the on-chain "license") with those terms from the IP.

## Prerequisites

There are a few steps you have to complete before you can start the tutorial.

1. Complete the [Setup Your Own Project](/developers/smart-contracts-guide/setup)
2. Create License Terms and have a `licenseTermsId`. You can do that by following the [previous page](/developers/smart-contracts-guide/register-terms).

## Attach License Terms

Now that we have created terms and have the associated `licenseTermsId`, we can attach them to an existing IP Asset.

Let's create a test file under `test/2_AttachTerms.t.sol` to see it work and verify the results:

<Note>
  **Contract Addresses**

  We have filled in the addresses from the Story contracts for you. However you can also find the addresses for them here: [Deployed Smart Contracts](/developers/deployed-smart-contracts)
</Note>

```solidity test/2_AttachTerms.t.sol theme={null}
// SPDX-License-Identifier: UNLICENSED
pragma solidity ^0.8.26;

import { Test } from "forge-std/Test.sol";
// for testing purposes only
import { MockIPGraph } from "@storyprotocol/test/mocks/MockIPGraph.sol";
import { IIPAssetRegistry } from "@storyprotocol/core/interfaces/registries/IIPAssetRegistry.sol";
import { ILicenseRegistry } from "@storyprotocol/core/interfaces/registries/ILicenseRegistry.sol";
import { IPILicenseTemplate } from "@storyprotocol/core/interfaces/modules/licensing/IPILicenseTemplate.sol";
import { ILicensingModule } from "@storyprotocol/core/interfaces/modules/licensing/ILicensingModule.sol";
import { PILFlavors } from "@storyprotocol/core/lib/PILFlavors.sol";
import { PILTerms } from "@storyprotocol/core/interfaces/modules/licensing/IPILicenseTemplate.sol";

import { SimpleNFT } from "../src/mocks/SimpleNFT.sol";

// Run this test:
// forge test --fork-url https://aeneid.storyrpc.io/ --match-path test/2_AttachTerms.t.sol
contract AttachTermsTest is Test {
    address internal alice = address(0xa11ce);

    // For addresses, see https://docs.story.foundation/developers/deployed-smart-contracts
    // Protocol Core - IPAssetRegistry
    IIPAssetRegistry internal IP_ASSET_REGISTRY = IIPAssetRegistry(0x77319B4031e6eF1250907aa00018B8B1c67a244b);
    // Protocol Core - LicenseRegistry
    ILicenseRegistry internal LICENSE_REGISTRY = ILicenseRegistry(0x529a750E02d8E2f15649c13D69a465286a780e24);
    // Protocol Core - LicensingModule
    ILicensingModule internal LICENSING_MODULE = ILicensingModule(0x04fbd8a2e56dd85CFD5500A4A4DfA955B9f1dE6f);
    // Protocol Core - PILicenseTemplate
    IPILicenseTemplate internal PIL_TEMPLATE = IPILicenseTemplate(0x2E896b0b2Fdb7457499B56AAaA4AE55BCB4Cd316);
    // Protocol Core - RoyaltyPolicyLAP
    address internal ROYALTY_POLICY_LAP = 0xBe54FB168b3c982b7AaE60dB6CF75Bd8447b390E;
    // Revenue Token - MERC20
    address internal MERC20 = 0xF2104833d386a2734a4eB3B8ad6FC6812F29E38E;

    SimpleNFT public SIMPLE_NFT;
    uint256 public tokenId;
    address public ipId;
    uint256 public licenseTermsId;

    function setUp() public {
        // this is only for testing purposes
        // due to our IPGraph precompile not being
        // deployed on the fork
        vm.etch(address(0x0101), address(new MockIPGraph()).code);

        SIMPLE_NFT = new SimpleNFT("Simple IP NFT", "SIM");
        tokenId = SIMPLE_NFT.mint(alice);
        ipId = IP_ASSET_REGISTRY.register(block.chainid, address(SIMPLE_NFT), tokenId);

        // Register random Commercial Remix terms so we can attach them later
        licenseTermsId = PIL_TEMPLATE.registerLicenseTerms(
            PILFlavors.commercialRemix({
                mintingFee: 0,
                commercialRevShare: 10 * 10 ** 6, // 10%
                royaltyPolicy: ROYALTY_POLICY_LAP,
                currencyToken: MERC20
            })
        );
    }

    /// @notice Attaches license terms to an IP Asset.
    /// @dev Only the owner of an IP Asset can attach license terms to it.
    /// So in this case, alice has to be the caller of the function because
    /// she owns the NFT associated with the IP Asset.
    function test_attachLicenseTerms() public {
        vm.prank(alice);
        LICENSING_MODULE.attachLicenseTerms(ipId, address(PIL_TEMPLATE), licenseTermsId);

        assertTrue(LICENSE_REGISTRY.hasIpAttachedLicenseTerms(ipId, address(PIL_TEMPLATE), licenseTermsId));
        assertEq(LICENSE_REGISTRY.getAttachedLicenseTermsCount(ipId), 1);
        (address licenseTemplate, uint256 attachedLicenseTermsId) = LICENSE_REGISTRY.getAttachedLicenseTerms({
            ipId: ipId,
            index: 0
        });
        assertEq(licenseTemplate, address(PIL_TEMPLATE));
        assertEq(attachedLicenseTermsId, licenseTermsId);
    }
}
```

## Test Your Code!

Run `forge build`. If everything is successful, the command should successfully compile.

Now run the test by executing the following command:

```bash  theme={null}
forge test --fork-url https://aeneid.storyrpc.io/ --match-path test/2_AttachTerms.t.sol
```

## Mint a License

Congratulations, you attached terms to an IPA!

<Card title="Completed Code" href="https://github.com/storyprotocol/story-protocol-boilerplate/blob/main/test/2_AttachTerms.t.sol" icon="thumbs-up">
  Follow the completed code all the way through.
</Card>

Now that we have attached License Terms to our IP, the next step is minting a License Token, which we'll go over on the next page.
# Mint a License Token

> Learn how to mint a License Token from an IPA in Solidity.

<Card title="Completed Code" href="https://github.com/storyprotocol/story-protocol-boilerplate/blob/main/test/3_LicenseToken.t.sol" icon="thumbs-up">
  Follow the completed code all the way through.
</Card>

This section demonstrates how to mint a [License Token](/concepts/licensing-module/license-token) from an [IP Asset](/concepts/ip-asset/overview). You can only mint a License Token from an IP Asset if the IP Asset has [License Terms](/concepts/licensing-module/license-terms) attached to it. A License Token is minted as an ERC-721.

There are two reasons you'd mint a License Token:

1. To hold the license and be able to use the underlying IP Asset as the license described (for ex. "Can use commercially as long as you provide proper attribution and share 5% of your revenue)
2. Use the license token to link another IP Asset as a derivative of it. *Note though that, as you'll see later, some SDK functions don't require you to explicitly mint a license token first in order to register a derivative, and will actually handle it for you behind the scenes.*

## Prerequisites

There are a few steps you have to complete before you can start the tutorial.

1. Complete the [Setup Your Own Project](/developers/smart-contracts-guide/setup)
2. An IP Asset has License Terms attached to it. You can learn how to do that [here](/developers/smart-contracts-guide/attach-terms)

## Mint License

Let's say that IP Asset (`ipId = 0x01`) has License Terms (`licenseTermdId = 10`) attached to it. We want to mint 2 License Tokens with those terms to a specific wallet address (`0x02`).

<Warning>
  **Paid Licenses**

  Be mindful that some IP Assets may have license terms attached that require the user minting the license to pay a `mintingFee`.
</Warning>

Let's create a test file under `test/3_LicenseToken.t.sol` to see it work and verify the results:

<Note>
  **Contract Addresses**

  We have filled in the addresses from the Story contracts for you. However you can also find the addresses for them here: [Deployed Smart Contracts](/developers/deployed-smart-contracts)
</Note>

```solidity test/3_LicenseToken.t.sol theme={null}
// SPDX-License-Identifier: UNLICENSED
pragma solidity ^0.8.26;

import { Test } from "forge-std/Test.sol";
// for testing purposes only
import { MockIPGraph } from "@storyprotocol/test/mocks/MockIPGraph.sol";
import { IIPAssetRegistry } from "@storyprotocol/core/interfaces/registries/IIPAssetRegistry.sol";
import { IPILicenseTemplate } from "@storyprotocol/core/interfaces/modules/licensing/IPILicenseTemplate.sol";
import { ILicensingModule } from "@storyprotocol/core/interfaces/modules/licensing/ILicensingModule.sol";
import { ILicenseToken } from "@storyprotocol/core/interfaces/ILicenseToken.sol";
import { RoyaltyPolicyLAP } from "@storyprotocol/core/modules/royalty/policies/LAP/RoyaltyPolicyLAP.sol";
import { PILFlavors } from "@storyprotocol/core/lib/PILFlavors.sol";
import { PILTerms } from "@storyprotocol/core/interfaces/modules/licensing/IPILicenseTemplate.sol";

import { SimpleNFT } from "../src/mocks/SimpleNFT.sol";

// Run this test:
// forge test --fork-url https://aeneid.storyrpc.io/ --match-path test/3_LicenseToken.t.sol
contract LicenseTokenTest is Test {
    address internal alice = address(0xa11ce);
    address internal bob = address(0xb0b);

    // For addresses, see https://docs.story.foundation/developers/deployed-smart-contracts
    // Protocol Core - IPAssetRegistry
    IIPAssetRegistry internal IP_ASSET_REGISTRY = IIPAssetRegistry(0x77319B4031e6eF1250907aa00018B8B1c67a244b);
    // Protocol Core - LicensingModule
    ILicensingModule internal LICENSING_MODULE = ILicensingModule(0x04fbd8a2e56dd85CFD5500A4A4DfA955B9f1dE6f);
    // Protocol Core - PILicenseTemplate
    IPILicenseTemplate internal PIL_TEMPLATE = IPILicenseTemplate(0x2E896b0b2Fdb7457499B56AAaA4AE55BCB4Cd316);
    // Protocol Core - RoyaltyPolicyLAP
    address internal ROYALTY_POLICY_LAP = 0xBe54FB168b3c982b7AaE60dB6CF75Bd8447b390E;
    // Protocol Core - LicenseToken
    ILicenseToken internal LICENSE_TOKEN = ILicenseToken(0xFe3838BFb30B34170F00030B52eA4893d8aAC6bC);
    // Revenue Token - MERC20
    address internal MERC20 = 0xF2104833d386a2734a4eB3B8ad6FC6812F29E38E;

    SimpleNFT public SIMPLE_NFT;
    uint256 public tokenId;
    address public ipId;
    uint256 public licenseTermsId;

    function setUp() public {
        // this is only for testing purposes
        // due to our IPGraph precompile not being
        // deployed on the fork
        vm.etch(address(0x0101), address(new MockIPGraph()).code);

        SIMPLE_NFT = new SimpleNFT("Simple IP NFT", "SIM");
        tokenId = SIMPLE_NFT.mint(alice);
        ipId = IP_ASSET_REGISTRY.register(block.chainid, address(SIMPLE_NFT), tokenId);

        licenseTermsId = PIL_TEMPLATE.registerLicenseTerms(
            PILFlavors.commercialRemix({
                mintingFee: 0,
                commercialRevShare: 10 * 10 ** 6, // 10%
                royaltyPolicy: ROYALTY_POLICY_LAP,
                currencyToken: MERC20
            })
        );

        vm.prank(alice);
        LICENSING_MODULE.attachLicenseTerms(ipId, address(PIL_TEMPLATE), licenseTermsId);
    }

    /// @notice Mints license tokens for an IP Asset.
    /// Anyone can mint a license token.
    function test_mintLicenseToken() public {
        uint256 startLicenseTokenId = LICENSING_MODULE.mintLicenseTokens({
            licensorIpId: ipId,
            licenseTemplate: address(PIL_TEMPLATE),
            licenseTermsId: licenseTermsId,
            amount: 2,
            receiver: bob,
            royaltyContext: "", // for PIL, royaltyContext is empty string
            maxMintingFee: 0,
            maxRevenueShare: 0
        });

        assertEq(LICENSE_TOKEN.ownerOf(startLicenseTokenId), bob);
        assertEq(LICENSE_TOKEN.ownerOf(startLicenseTokenId + 1), bob);
    }
}
```

## Test Your Code!

Run `forge build`. If everything is successful, the command should successfully compile.

Now run the test by executing the following command:

```bash  theme={null}
forge test --fork-url https://aeneid.storyrpc.io/ --match-path test/3_LicenseToken.t.sol
```

## Register a Derivative

<Card title="Completed Code" href="https://github.com/storyprotocol/story-protocol-boilerplate/blob/main/test/3_LicenseToken.t.sol" icon="thumbs-up">
  Follow the completed code all the way through.
</Card>

Now that we have minted a License Token, we can hold it or use it to link an IP Asset as a derivative. We will go over that on the next page.
# Register a Derivative

> Learn how to register a derivative/remix IP Asset as a child of another in Solidity.

<Card title="Completed Code" href="https://github.com/storyprotocol/story-protocol-boilerplate/blob/main/test/4_IPARemix.t.sol" icon="thumbs-up">
  All of this page is covered in this working code example.
</Card>

Once a [License Token](/concepts/licensing-module/license-token) has been minted from an IP Asset, the owner of that token (an ERC-721 NFT) can burn it to register their own IP Asset as a derivative of the IP Asset associated with the License Token.

## Prerequisites

There are a few steps you have to complete before you can start the tutorial.

1. Complete the [Setup Your Own Project](/developers/smart-contracts-guide/setup)
2. Have a minted License Token. You can learn how to do that [here](/developers/smart-contracts-guide/mint-license)

## Register as Derivative

Let's create a test file under `test/4_IPARemix.t.sol` to see it work and verify the results:

<Note>
  **Contract Addresses**

  We have filled in the addresses from the Story contracts for you. However you can also find the addresses for them here: [Deployed Smart Contracts](/developers/deployed-smart-contracts)
</Note>

```solidity test/4_IPARemix.t.sol theme={null}
// SPDX-License-Identifier: UNLICENSED
pragma solidity ^0.8.26;

import { Test } from "forge-std/Test.sol";
// for testing purposes only
import { MockIPGraph } from "@storyprotocol/test/mocks/MockIPGraph.sol";
import { IIPAssetRegistry } from "@storyprotocol/core/interfaces/registries/IIPAssetRegistry.sol";
import { ILicenseRegistry } from "@storyprotocol/core/interfaces/registries/ILicenseRegistry.sol";
import { IPILicenseTemplate } from "@storyprotocol/core/interfaces/modules/licensing/IPILicenseTemplate.sol";
import { ILicensingModule } from "@storyprotocol/core/interfaces/modules/licensing/ILicensingModule.sol";
import { PILFlavors } from "@storyprotocol/core/lib/PILFlavors.sol";
import { PILTerms } from "@storyprotocol/core/interfaces/modules/licensing/IPILicenseTemplate.sol";

import { SimpleNFT } from "../src/mocks/SimpleNFT.sol";

// Run this test:
// forge test --fork-url https://aeneid.storyrpc.io/ --match-path test/4_IPARemix.t.sol
contract IPARemixTest is Test {
    address internal alice = address(0xa11ce);
    address internal bob = address(0xb0b);

    // For addresses, see https://docs.story.foundation/developers/deployed-smart-contracts
    // Protocol Core - IPAssetRegistry
    IIPAssetRegistry internal IP_ASSET_REGISTRY = IIPAssetRegistry(0x77319B4031e6eF1250907aa00018B8B1c67a244b);
    // Protocol Core - LicenseRegistry
    ILicenseRegistry internal LICENSE_REGISTRY = ILicenseRegistry(0x529a750E02d8E2f15649c13D69a465286a780e24);
    // Protocol Core - LicensingModule
    ILicensingModule internal LICENSING_MODULE = ILicensingModule(0x04fbd8a2e56dd85CFD5500A4A4DfA955B9f1dE6f);
    // Protocol Core - PILicenseTemplate
    IPILicenseTemplate internal PIL_TEMPLATE = IPILicenseTemplate(0x2E896b0b2Fdb7457499B56AAaA4AE55BCB4Cd316);
    // Protocol Core - RoyaltyPolicyLAP
    address internal ROYALTY_POLICY_LAP = 0xBe54FB168b3c982b7AaE60dB6CF75Bd8447b390E;
    // Revenue Token - MERC20
    address internal MERC20 = 0xF2104833d386a2734a4eB3B8ad6FC6812F29E38E;

    SimpleNFT public SIMPLE_NFT;
    uint256 public tokenId;
    address public ipId;
    uint256 public licenseTermsId;
    uint256 public startLicenseTokenId;

    function setUp() public {
        // this is only for testing purposes
        // due to our IPGraph precompile not being
        // deployed on the fork
        vm.etch(address(0x0101), address(new MockIPGraph()).code);

        SIMPLE_NFT = new SimpleNFT("Simple IP NFT", "SIM");
        tokenId = SIMPLE_NFT.mint(alice);
        ipId = IP_ASSET_REGISTRY.register(block.chainid, address(SIMPLE_NFT), tokenId);

        licenseTermsId = PIL_TEMPLATE.registerLicenseTerms(
            PILFlavors.commercialRemix({
                mintingFee: 0,
                commercialRevShare: 10 * 10 ** 6, // 10%
                royaltyPolicy: ROYALTY_POLICY_LAP,
                currencyToken: MERC20
            })
        );

        vm.prank(alice);
        LICENSING_MODULE.attachLicenseTerms(ipId, address(PIL_TEMPLATE), licenseTermsId);
        startLicenseTokenId = LICENSING_MODULE.mintLicenseTokens({
            licensorIpId: ipId,
            licenseTemplate: address(PIL_TEMPLATE),
            licenseTermsId: licenseTermsId,
            amount: 2,
            receiver: bob,
            royaltyContext: "", // for PIL, royaltyContext is empty string
            maxMintingFee: 0,
            maxRevenueShare: 0
        });
    }

    /// @notice Mints an NFT to be registered as IP, and then
    /// linked as a derivative of alice's asset using the
    /// minted license token.
    function test_registerDerivativeWithLicenseTokens() public {
        // First we mint an NFT and register it as an IP Asset,
        // owned by Bob.
        uint256 childTokenId = SIMPLE_NFT.mint(bob);
        address childIpId = IP_ASSET_REGISTRY.register(block.chainid, address(SIMPLE_NFT), childTokenId);

        uint256[] memory licenseTokenIds = new uint256[](1);
        licenseTokenIds[0] = startLicenseTokenId;

        // Bob uses the License Token he has from Alice's IP
        // to register his IP as a derivative of Alice's IP.
        vm.prank(bob);
        LICENSING_MODULE.registerDerivativeWithLicenseTokens({
            childIpId: childIpId,
            licenseTokenIds: licenseTokenIds,
            royaltyContext: "", // empty for PIL
            maxRts: 0
        });

        assertTrue(LICENSE_REGISTRY.hasDerivativeIps(ipId));
        assertTrue(LICENSE_REGISTRY.isParentIp(ipId, childIpId));
        assertTrue(LICENSE_REGISTRY.isDerivativeIp(childIpId));
        assertEq(LICENSE_REGISTRY.getParentIpCount(childIpId), 1);
        assertEq(LICENSE_REGISTRY.getDerivativeIpCount(ipId), 1);
        assertEq(LICENSE_REGISTRY.getParentIp({ childIpId: childIpId, index: 0 }), ipId);
        assertEq(LICENSE_REGISTRY.getDerivativeIp({ parentIpId: ipId, index: 0 }), childIpId);
    }
}
```

## Test Your Code!

Run `forge build`. If everything is successful, the command should successfully compile.

Now run the test by executing the following command:

```bash  theme={null}
forge test --fork-url https://aeneid.storyrpc.io/ --match-path test/4_IPARemix.t.sol
```

## Paying and Claiming Revenue

Congratulations, you registered a derivative IP Asset!

<Card title="Completed Code" href="https://github.com/storyprotocol/story-protocol-boilerplate/blob/main/test/4_IPARemix.t.sol" icon="thumbs-up">
  All of this page is covered in this working code example.
</Card>

Now that we have established parent-child IP relationships, we can begin to explore payments and automated revenue share based on the license terms. We'll cover that in the upcoming pages.
# Pay & Claim Revenue

> Learn how to pay an IP Asset and claim revenue in Solidity.

<Card title="Completed Code" href="https://github.com/storyprotocol/story-protocol-boilerplate/blob/main/test/5_Royalty.t.sol" icon="thumbs-up">
  Follow the completed code all the way through.
</Card>

This section demonstrates how to pay an IP Asset. There are a few reasons you would do this:

1. You simply want to "tip" an IP
2. You have to because your license terms with an ancestor IP require you to forward a certain % of payment

In either scenario, you would use the below `payRoyaltyOnBehalf` function. When this happens, the [Royalty Module](/concepts/royalty-module/overview) automatically handles the different payment flows such that parent IP Assets who have negotiated a certain `commercialRevShare` with the IPA being paid can claim their due share.

## Prerequisites

There are a few steps you have to complete before you can start the tutorial.

1. Complete the [Setup Your Own Project](/developers/smart-contracts-guide/setup)
2. Have a basic understanding of the [Royalty Module](/concepts/royalty-module/overview)
3. A child IPA and a parent IPA, for which their license terms have a commercial revenue share to make this example work

## Before We Start

You can pay an IP Asset using the `payRoyaltyOnBehalf` function from the [Royalty Module](/concepts/royalty-module/overview).

You will be paying the IP Asset with [MockERC20](https://aeneid.storyscan.io/address/0xF2104833d386a2734a4eB3B8ad6FC6812F29E38E). Usually you would pay with \$WIP, but because we need to mint some tokens to test, we will use MockERC20.

To help with the following scenarios, let's say we have a parent IP Asset that has negotiated a 50% `commercialRevShare` with its child IP Asset.

### Whitelisted Revenue Tokens

Only tokens that are whitelisted by our protocol can be used as payment ("revenue") tokens. MockERC20 is one of those tokens. To see that list, go [here](/developers/deployed-smart-contracts#whitelisted-revenue-tokens).

## Paying an IP Asset

We can pay an IP Asset like so:

```solidity Solidity theme={null}
ROYALTY_MODULE.payRoyaltyOnBehalf(childIpId, address(0), address(MERC20), 10);
```

This will send 10 \$MERC20 to the `childIpId`'s [IP Royalty Vault](/concepts/royalty-module/ip-royalty-vault). From there, the child can claim revenue. In the next section, you'll see a working version of this.

<Warning>
  **Important: Approving the Royalty Module**

  Before you call `payRoyaltyOnBehalf`, you have to approve the royalty module to spend the tokens for you. In the section below, you will see that we call `MERC20.approve(address(ROYALTY_MODULE), 10);` or else it will not work.
</Warning>

## Claim Revenue

When payments are made, they eventually end up in an IP Asset's [IP Royalty Vault](/concepts/royalty-module/ip-royalty-vault). From here, they are claimed/transferred to whoever owns the Royalty Tokens associated with it, which represent a % of revenue share for a given IP Asset's IP Royalty Vault.

The IP Account (the smart contract that represents the [IP Asset](/concepts/ip-asset/overview)) is what holds 100% of the Royalty Tokens when it's first registered. So usually, it indeed holds most of the Royalty Tokens.

Let's create a test file under `test/5_Royalty.t.sol` to see it work and verify the results:

<Note>
  **Contract Addresses**

  We have filled in the addresses from the Story contracts for you. However you can also find the addresses for them here: [Deployed Smart Contracts](/developers/deployed-smart-contracts)
</Note>

```solidity test/5_Royalty.t.sol theme={null}
// SPDX-License-Identifier: UNLICENSED
pragma solidity ^0.8.26;

import { Test } from "forge-std/Test.sol";
// for testing purposes only
import { MockIPGraph } from "@storyprotocol/test/mocks/MockIPGraph.sol";
import { IPAssetRegistry } from "@storyprotocol/core/registries/IPAssetRegistry.sol";
import { LicenseRegistry } from "@storyprotocol/core/registries/LicenseRegistry.sol";
import { PILicenseTemplate } from "@storyprotocol/core/modules/licensing/PILicenseTemplate.sol";
import { RoyaltyPolicyLAP } from "@storyprotocol/core/modules/royalty/policies/LAP/RoyaltyPolicyLAP.sol";
import { PILFlavors } from "@storyprotocol/core/lib/PILFlavors.sol";
import { PILTerms } from "@storyprotocol/core/interfaces/modules/licensing/IPILicenseTemplate.sol";
import { LicensingModule } from "@storyprotocol/core/modules/licensing/LicensingModule.sol";
import { LicenseToken } from "@storyprotocol/core/LicenseToken.sol";
import { RoyaltyWorkflows } from "@storyprotocol/periphery/workflows/RoyaltyWorkflows.sol";
import { RoyaltyModule } from "@storyprotocol/core/modules/royalty/RoyaltyModule.sol";
import { MockERC20 } from "@storyprotocol/test/mocks/token/MockERC20.sol";

import { SimpleNFT } from "../src/mocks/SimpleNFT.sol";

// Run this test:
// forge test --fork-url https://aeneid.storyrpc.io/ --match-path test/5_Royalty.t.sol
contract RoyaltyTest is Test {
    address internal alice = address(0xa11ce);
    address internal bob = address(0xb0b);

    // For addresses, see https://docs.story.foundation/developers/deployed-smart-contracts
    // Protocol Core - IPAssetRegistry
    IPAssetRegistry internal IP_ASSET_REGISTRY = IPAssetRegistry(0x77319B4031e6eF1250907aa00018B8B1c67a244b);
    // Protocol Core - LicenseRegistry
    LicenseRegistry internal LICENSE_REGISTRY = LicenseRegistry(0x529a750E02d8E2f15649c13D69a465286a780e24);
    // Protocol Core - LicensingModule
    LicensingModule internal LICENSING_MODULE = LicensingModule(0x04fbd8a2e56dd85CFD5500A4A4DfA955B9f1dE6f);
    // Protocol Core - PILicenseTemplate
    PILicenseTemplate internal PIL_TEMPLATE = PILicenseTemplate(0x2E896b0b2Fdb7457499B56AAaA4AE55BCB4Cd316);
    // Protocol Core - RoyaltyPolicyLAP
    RoyaltyPolicyLAP internal ROYALTY_POLICY_LAP = RoyaltyPolicyLAP(0xBe54FB168b3c982b7AaE60dB6CF75Bd8447b390E);
    // Protocol Core - LicenseToken
    LicenseToken internal LICENSE_TOKEN = LicenseToken(0xFe3838BFb30B34170F00030B52eA4893d8aAC6bC);
    // Protocol Core - RoyaltyModule
    RoyaltyModule internal ROYALTY_MODULE = RoyaltyModule(0xD2f60c40fEbccf6311f8B47c4f2Ec6b040400086);
    // Protocol Periphery - RoyaltyWorkflows
    RoyaltyWorkflows internal ROYALTY_WORKFLOWS = RoyaltyWorkflows(0x9515faE61E0c0447C6AC6dEe5628A2097aFE1890);
    // Mock - MERC20
    MockERC20 internal MERC20 = MockERC20(0xF2104833d386a2734a4eB3B8ad6FC6812F29E38E);

    SimpleNFT public SIMPLE_NFT;
    uint256 public tokenId;
    address public ipId;
    uint256 public licenseTermsId;
    uint256 public startLicenseTokenId;
    address public childIpId;

    function setUp() public {
        // this is only for testing purposes
        // due to our IPGraph precompile not being
        // deployed on the fork
        vm.etch(address(0x0101), address(new MockIPGraph()).code);

        SIMPLE_NFT = new SimpleNFT("Simple IP NFT", "SIM");
        tokenId = SIMPLE_NFT.mint(alice);
        ipId = IP_ASSET_REGISTRY.register(block.chainid, address(SIMPLE_NFT), tokenId);

        licenseTermsId = PIL_TEMPLATE.registerLicenseTerms(
            PILFlavors.commercialRemix({
                mintingFee: 0,
                commercialRevShare: 10 * 10 ** 6, // 10%
                royaltyPolicy: address(ROYALTY_POLICY_LAP),
                currencyToken: address(MERC20)
            })
        );

        vm.prank(alice);
        LICENSING_MODULE.attachLicenseTerms(ipId, address(PIL_TEMPLATE), licenseTermsId);
        startLicenseTokenId = LICENSING_MODULE.mintLicenseTokens({
            licensorIpId: ipId,
            licenseTemplate: address(PIL_TEMPLATE),
            licenseTermsId: licenseTermsId,
            amount: 2,
            receiver: bob,
            royaltyContext: "", // for PIL, royaltyContext is empty string
            maxMintingFee: 0,
            maxRevenueShare: 0
        });

        // Registers a child IP (owned by Bob) as a derivative of Alice's IP.
        uint256 childTokenId = SIMPLE_NFT.mint(bob);
        childIpId = IP_ASSET_REGISTRY.register(block.chainid, address(SIMPLE_NFT), childTokenId);

        uint256[] memory licenseTokenIds = new uint256[](1);
        licenseTokenIds[0] = startLicenseTokenId;

        vm.prank(bob);
        LICENSING_MODULE.registerDerivativeWithLicenseTokens({
            childIpId: childIpId,
            licenseTokenIds: licenseTokenIds,
            royaltyContext: "", // empty for PIL
            maxRts: 0
        });
    }

    /// @notice Pays MERC20 to Bob's IP. Some of this MERC20 is then claimable
    /// by Alice's IP.
    /// @dev In this case, this contract will act as the 3rd party paying MERC20
    /// to Bob (the child IP).
    function test_claimAllRevenue() public {
        // ADMIN SETUP
        // We mint 100 MERC20 to this contract so it has some money to pay.
        MERC20.mint(address(this), 100);
        // We have to approve the Royalty Module to spend MERC20 on our behalf, which
        // it will do using `payRoyaltyOnBehalf`.
        MERC20.approve(address(ROYALTY_MODULE), 10);

        // This contract pays 10 MERC20 to Bob's IP.
        ROYALTY_MODULE.payRoyaltyOnBehalf(childIpId, address(0), address(MERC20), 10);

        // Now that Bob's IP has been paid, Alice can claim her share (1 MERC20, which
        // is 10% as specified in the license terms)
        address[] memory childIpIds = new address[](1);
        address[] memory royaltyPolicies = new address[](1);
        address[] memory currencyTokens = new address[](1);
        childIpIds[0] = childIpId;
        royaltyPolicies[0] = address(ROYALTY_POLICY_LAP);
        currencyTokens[0] = address(MERC20);

        uint256[] memory amountsClaimed = ROYALTY_WORKFLOWS.claimAllRevenue({
            ancestorIpId: ipId,
            claimer: ipId,
            childIpIds: childIpIds,
            royaltyPolicies: royaltyPolicies,
            currencyTokens: currencyTokens
        });

        // Check that 1 MERC20 was claimed by Alice's IP Account
        assertEq(amountsClaimed[0], 1);
        // Check that Alice's IP Account now has 1 MERC20 in its balance.
        assertEq(MERC20.balanceOf(ipId), 1);
        // Check that Bob's IP now has 9 MERC20 in its Royalty Vault, which it
        // can claim to its IP Account at a later point if he wants.
        assertEq(MERC20.balanceOf(ROYALTY_MODULE.ipRoyaltyVaults(childIpId)), 9);
    }
}
```

## Test Your Code!

Run `forge build`. If everything is successful, the command should successfully compile.

Now run the test by executing the following command:

```bash  theme={null}
forge test --fork-url https://aeneid.storyrpc.io/ --match-path test/5_Royalty.t.sol
```

## Dispute an IP

Congratulations, you claimed revenue using the [Royalty Module](/concepts/royalty-module/overview)!

<Card title="Completed Code" href="https://github.com/storyprotocol/story-protocol-boilerplate/blob/main/test/5_Royalty.t.sol" icon="thumbs-up">
  Follow the completed code all the way through.
</Card>

Now what happens if an IP Asset doesn't pay their due share? We can dispute the IP on-chain, which we will cover on the next page.

<Warning>Coming soon!</Warning>
# Cross-Chain License Minting

> A guide on how to set up cross-chain license minting using deBridge.

In this tutorial, we will explore how to use [deBridge](https://docs.debridge.finance/) to perform cross-chain license minting. For this tutorial specifically, we'll be using Base \$ETH to mint a license on Story.

<CardGroup>
  <Card title="Base Example" icon="computer" color="#0000fe" href="https://github.com/jacob-tucker/base-story-quickstart">
    A working code example of minting a license on Story using Base \$ETH.
  </Card>

  <Card title="Abstract Chain Example" icon="computer" color="#2cdb84" href="https://github.com/jacob-tucker/abs-story-quickstart">
    A working code example of minting a license on Story using Abstract \$ETH.
  </Card>
</CardGroup>

From a high level, it involves:

1. Constructing a deBridge API call that will return tx data to swap tokens across chains and perform some action (e.g. mint a license on Story)
2. Executing the API call to receive that tx data
3. Executing the transaction (using the returned tx data) on the source chain

<Frame>
  <img src="https://mintcdn.com/story/VqUVNnzVygnCxrbT/images/tutorials/cross-chain-license-minting.jpeg?fit=max&auto=format&n=VqUVNnzVygnCxrbT&q=85&s=3c9b5876cae6a215c90caf7c96248f9f" alt="Cross-Chain License Minting" data-og-width="1878" width="1878" data-og-height="1036" height="1036" data-path="images/tutorials/cross-chain-license-minting.jpeg" data-optimize="true" data-opv="3" srcset="https://mintcdn.com/story/VqUVNnzVygnCxrbT/images/tutorials/cross-chain-license-minting.jpeg?w=280&fit=max&auto=format&n=VqUVNnzVygnCxrbT&q=85&s=f6e9df616d86c733826b830ad1109b62 280w, https://mintcdn.com/story/VqUVNnzVygnCxrbT/images/tutorials/cross-chain-license-minting.jpeg?w=560&fit=max&auto=format&n=VqUVNnzVygnCxrbT&q=85&s=c2c14e38457b21595d4b2f40bd08a12d 560w, https://mintcdn.com/story/VqUVNnzVygnCxrbT/images/tutorials/cross-chain-license-minting.jpeg?w=840&fit=max&auto=format&n=VqUVNnzVygnCxrbT&q=85&s=0a749bd38075c79e56289eca7a560241 840w, https://mintcdn.com/story/VqUVNnzVygnCxrbT/images/tutorials/cross-chain-license-minting.jpeg?w=1100&fit=max&auto=format&n=VqUVNnzVygnCxrbT&q=85&s=d1280d9ac01adce3f8e692902443b6fa 1100w, https://mintcdn.com/story/VqUVNnzVygnCxrbT/images/tutorials/cross-chain-license-minting.jpeg?w=1650&fit=max&auto=format&n=VqUVNnzVygnCxrbT&q=85&s=c608c2872a4f0ac1f7d7c121568e70fb 1650w, https://mintcdn.com/story/VqUVNnzVygnCxrbT/images/tutorials/cross-chain-license-minting.jpeg?w=2500&fit=max&auto=format&n=VqUVNnzVygnCxrbT&q=85&s=60efe93e604658e43c71937709ae28d9 2500w" />
</Frame>

## Step 1: Constructing the deBridge API Call

The first step is to construct a deBridge API call. The purpose of this API call is to receive back a response that will contain transaction data so we can then execute it on the source chain.

This deBridge order swaps tokens from one chain to another. We can also optionally attach a `dlnHook` that will execute an arbitrary action upon order completion (ex. after \$ETH has been swapped for \$IP). This is where the magic happens.

<Note>
  You can learn more about dlnHooks [here](https://docs.debridge.finance/dln-the-debridge-liquidity-network-protocol/integration-guidelines/interacting-with-the-api).
</Note>

In this case, the `dlnHook` will be a call to `mintLicenseTokensCrossChain`, which is a function [in this contract](https://www.storyscan.io/address/0x6429A616F76a8958e918145d64bf7681C3936D6A?tab=contract) that wraps the received \$IP to \$WIP and then mints a license token on Story.

You can see that `mintLicenseTokensCrossChain` looks like this:

```solidity DebridgeLicenseTokenMinter.sol expandable theme={null}
function mintLicenseTokensCrossChain(
    address licensorIpId,
    uint256 licenseTermsId,
    uint256 tokenAmount,
    address receiver
) external payable {
  uint256 amount = msg.value;
  require(amount > 0, "DebridgeLicenseTokenMinter: zero amount");

  // Create multicall data - using memory array directly to avoid stack issues
  IMulticall.Call3Value[] memory calls = new IMulticall.Call3Value[](2);

  // First call: deposit IP to get WIP tokens
  calls[0] = IMulticall.Call3Value({
      target: WIP,
      allowFailure: false,
      value: amount,
      callData: abi.encodeWithSelector(IWrappedIP.deposit.selector)
  });

  // Second call: mint license tokens
  calls[1] = IMulticall.Call3Value({
      target: LICENSING_MODULE,
      allowFailure: false,
      value: 0,
      callData: abi.encodeWithSelector(
          ILicensingModule.mintLicenseTokens.selector,
          licensorIpId,
          PIL_TEMPLATE,
          licenseTermsId,
          tokenAmount,
          receiver,
          "",
          0,
          100_000_000
      )
  });

  // Execute multicall and emit event
  IMulticall.Result[] memory returnData = IMulticall(MULTICALL).aggregate3Value{ value: amount }(calls);
  bytes memory raw = returnData[1].returnData;
  uint256 startLicenseTokenId = abi.decode(raw, (uint256)); // if mintLicenseTokens returns uint256
  emit LicenseTokensMinted(licensorIpId, receiver, startLicenseTokenId, tokenAmount);
}
```

You may be wondering, *"where does it `approve` the Royalty Module (what pays for the license minting fee) to spend the \$WIP?"* This is already done for you, since the Royalty Module is already approved to spend on behalf of Multicall.

The reason we had to make a Multicall contract in the first place, instead of simply bridging directly to \$WIP and calling `mintLicenseTokens` in the Licensing Module, is because the Royalty Module wouldn't be approved to spend the \$WIP. So we utilize the Multicall contract to take care of that for us instead.

<Tip>
  To summarize, we will construct a deBridge API call that says *"we want to swap \$ETH for \$IP, then use a dlnHook to call a smart contract on Story that wraps \$IP to \$WIP and mints a license on Story".*
</Tip>

### Step 1a. Constructing the `dlnHook`

The `dlnHook` is a JSON object that will be attached to the deBridge API call. It will contain the following information:

* The type of action to execute (`evm_transaction_call`)
* The address of the contract to call (`DebridgeLicenseTokenMinter.sol`)
* The calldata to execute (`mintLicenseTokensCrossChain`)

```typescript main.ts theme={null}
const STORY_WRAP_THEN_LICENSE_MULTICALL =
  "0x6429a616f76a8958e918145d64bf7681c3936d6a";

// Build the dlnHook for Story royalty payment
const buildRoyaltyPaymentHook = ({ ipId: `0x${string}`, licenseTermsId: bigint, receiverAddress: `0x${string}` }): string => {
  // Encode the mintLicenseTokensCrossChain function call
  const calldata = encodeFunctionData({
    abi: [
      {
        name: "mintLicenseTokensCrossChain",
        type: "function",
        inputs: [
          { name: "licensorIpId", type: "address" },
          { name: "licenseTermsId", type: "uint256" },
          { name: "tokenAmount", type: "uint256" },
          { name: "receiver", type: "address" },
        ],
      },
    ],
    functionName: "mintLicenseTokensCrossChain",
    args: [
      ipId,
      licenseTermsId,
      BigInt(1),
      receiverAddress,
    ],
  });

  // Build the dlnHook JSON
  const dlnHook = {
    type: "evm_transaction_call",
    data: {
      to: STORY_WRAP_THEN_LICENSE_MULTICALL,
      calldata: calldata,
      gas: 0,
    },
  };

  return JSON.stringify(dlnHook);
};
```

### Step 1b. Constructing the deBridge API Call

Now that we have the `dlnHook`, we can construct the whole deBridge API call, including the `dlnHook`.

<Note>
  You can view deBridge's documentation on the `create-tx` endpoint [here](https://docs.debridge.finance/dln-the-debridge-liquidity-network-protocol/integration-guidelines/interacting-with-the-api/creating-an-order). I also highly recommend checking out the [Swagger UI](https://dln.debridge.finance/v1.0#/DLN/DlnOrderControllerV10_createOrder) for the `create-tx` endpoint as well.
</Note>

| Attribute                       | Description                                                                                                                          |
| ------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------ |
| `srcChainId`                    | The ID of the source blockchain (e.g., Ethereum mainnet is 1).                                                                       |
| `srcChainTokenIn`               | The address of the token being swapped on the source chain (ETH in this case).                                                       |
| `srcChainTokenInAmount`         | The amount of the source token to swap, set to `auto` for automatic calculation.                                                     |
| `dstChainId`                    | The ID of the destination blockchain (e.g., Story mainnet is 100000013).                                                             |
| `dstChainTokenOut`              | The address of the token to receive on the destination chain (WIP token).                                                            |
| `dstChainTokenOutAmount`        | The amount of the destination token to receive. It should be the same as the amount we're paying in `payRoyaltyOnBehalf` in step 1a. |
| `dstChainTokenOutRecipient`     | This can just be the same as `senderAddress`.                                                                                        |
| `senderAddress`                 | The address initiating the transaction.                                                                                              |
| `srcChainOrderAuthorityAddress` | The address authorized to manage the order on the source chain. This can just be the same as `senderAddress`.                        |
| `dstChainOrderAuthorityAddress` | The address authorized to manage the order on the destination chain. This can just be the same as `senderAddress`.                   |
| `enableEstimate`                | A flag to enable transaction simulation and estimation.                                                                              |
| `prependOperatingExpenses`      | A flag to include operating expenses in the transaction.                                                                             |
| `dlnHook`                       | The URL-encoded hook that specifies additional actions to execute post-swap.                                                         |

```typescript main.ts theme={null}
import { base } from "viem/chains";

// ... previous code here ...

// Build deBridge API URL for cross-chain royalty payment
const buildDeBridgeApiUrl = ({
  ipId: `0x${string}`,
  licenseTermsId: bigint,
  receiverAddress: `0x${string}`,
  senderAddress: `0x${string}`,
  paymentAmount: string // should be in wei
}): string => {
  const dlnHook = buildRoyaltyPaymentHook({ ipId, licenseTermsId, receiverAddress });
  const encodedHook = encodeURIComponent(dlnHook);
  const url =
    `https://dln.debridge.finance/v1.0/dln/order/create-tx?` +
    `srcChainId=${base.id}` +
    // we make this zero address which represents the native token ($ETH)
    `&srcChainTokenIn=0x0000000000000000000000000000000000000000` +
    // we set this to auto which will automatically calculate the amount of $ETH to swap
    `&srcChainTokenInAmount=auto` +
    // Story's mainnet chain ID
    `&dstChainId=100000013` +
    // we make this zero address which represents the native token ($IP)
    `&dstChainTokenOut=0x0000000000000000000000000000000000000000` +
    // we set the amount of $IP to pay for the license on Story
    `&dstChainTokenOutAmount=${paymentAmount}` +
    // the address of the contract that will wrap the $IP and mint the license on Story
    `&dstChainTokenOutRecipient=${senderAddress}` +
    // the address of the user initiating the transaction
    `&senderAddress=${senderAddress}` +
    // the address authorized to manage the order on the source chain
    `&srcChainOrderAuthorityAddress=${senderAddress}` +
    // the address authorized to manage the order on the destination chain
    `&dstChainOrderAuthorityAddress=${senderAddress}` +
    // we set this to true to enable transaction simulation and estimation
    `&enableEstimate=true` +
    // we set this to true to include operating expenses in the transaction
    `&prependOperatingExpenses=true` +
    `&dlnHook=${encodedHook}`;

  return url;
};
```

## Step 2: Executing the API Call

Once the API call is constructed, execute it to receive a response. This response includes transaction data and an estimate for running the transaction on the source swap chain (e.g., Ethereum, Solana).

<CodeGroup>
  ```typescript main.ts theme={null}
  // ... previous code here ...

  const getDeBridgeTransactionData = async ({
    ipId: `0x${string}`,
    licenseTermsId: bigint,
    receiverAddress: `0x${string}`,
    senderAddress: `0x${string}`,
    paymentAmount: string // should be in wei
  }): Promise<DeBridgeApiResponse> => {
    try {
      const apiUrl = buildDeBridgeApiUrl({ ipId, licenseTermsId, receiverAddress, senderAddress, paymentAmount });

      const response = await fetch(apiUrl, {
        method: "GET",
        headers: {
          Accept: "application/json",
        },
      });

      if (!response.ok) {
        throw new Error(
          `deBridge API error: ${response.status} ${response.statusText}`
        );
      }

      const data = (await response.json()) as DeBridgeApiResponse;

      // Validate the response
      if (!data.tx || !data.estimation || !data.orderId) {
        throw new Error("Invalid deBridge API response: missing required fields");
      }

      return data;
    } catch (error) {
      console.error("Error calling deBridge API:", error);
      throw error;
    }
  };
  ```

  ```typescript DeBridgeApiResponse theme={null}
  export interface DeBridgeApiResponse {
    estimation: {
      srcChainTokenIn: {
        amount: string;
        approximateOperatingExpense: string;
      };
      dstChainTokenOut: {
        amount: string;
        maxTheoreticalAmount: string;
      };
    };
    tx: {
      to: string;
      data: string;
      value: string;
    };
    orderId: string;
  }
  ```
</CodeGroup>

## Step 3: Executing the Transaction on the Source Chain

Next, you would take the API response and execute the transaction on the source chain.

<Note>
  View [the docs here](https://docs.debridge.finance/dln-the-debridge-liquidity-network-protocol/integration-guidelines/interacting-with-the-api/submitting-an-order-creation-transaction) on submitting the transaction, including how this would be done differently on Solana.
</Note>

```typescript TypeScript theme={null}
import { base } from "viem/chains";
import { createWalletClient, http, WalletClient, parseEther } from "viem";
import { privateKeyToAccount, Address, Account } from "viem/accounts";
import dotenv from "dotenv";

dotenv.config();

// Validate environment variables
if (!process.env.WALLET_PRIVATE_KEY) {
  throw new Error("WALLET_PRIVATE_KEY is required in .env file");
}

// Create account from private key
const account: Account = privateKeyToAccount(
  `0x${process.env.WALLET_PRIVATE_KEY}` as Address
);

// Initialize the wallet client
const walletClient = createWalletClient({
  chain: base,
  transport: http("https://mainnet.infura.io/v3/YOUR_INFURA_PROJECT_ID"), // Use Infura or another Ethereum provider
  account,
}) as WalletClient;

// ... previous code here ...

// Function to send a transaction
const executeLicenseMint = async (params: {
  ipId: `0x${string}`;
  licenseTermsId: bigint;
  receiverAddress: `0x${string}`;
  senderAddress: `0x${string}`;
  paymentAmount: string; // should be in wei
}) => {
  // Get transaction data from deBridge
  const deBridgeResponse = await getDeBridgeTransactionData(params);

  try {
    // Execute the transaction using the user's wallet
    const txHash = await walletClient.sendTransaction({
      to: deBridgeResponse.tx.to as Address,
      data: deBridgeResponse.tx.data as Address,
      value: BigInt(deBridgeResponse.tx.value),
      account: account as Account,
      chain: base,
    });
    console.log("Transaction sent:", txHash);

    // Wait for the transaction to be mined
    const receipt = await walletClient.waitForTransactionReceipt(txHash);
    console.log("Transaction mined:", receipt.transactionHash);
  } catch (error) {
    console.error("Error sending transaction:", error);
  }
};

// Example usage with a mock API response
const params = {
  ipId: "0xcb6B9CCae4108A103097B30cFc25e1E257D4b5Fe",
  licenseTermsId: BigInt(27910),
  receiverAddress: "0x01", // replace with the address that should receive the license on Story
  senderAddress: account.address,
  paymentAmount: parseEther("0.00001"), // 0.00001 $WIP since the license on Story costs 0.00001 $WIP
};

// Execute the function to send the transaction
executeLicenseMint(params);
```

## Conclusion

Congratulations! You have successfully set up cross-chain license minting using deBridge.

<CardGroup>
  <Card title="Base Example" icon="computer" color="#0000fe" href="https://github.com/jacob-tucker/base-story-quickstart">
    A working code example of minting a license on Story using Base \$ETH.
  </Card>

  <Card title="Abstract Chain Example" icon="computer" color="#2cdb84" href="https://github.com/jacob-tucker/abs-story-quickstart">
    A working code example of minting a license on Story using Abstract \$ETH.
  </Card>
</CardGroup>
# Cross-Chain Royalty Payments

> A guide on how to set up cross-chain royalty payments using deBridge.

In this tutorial, we will explore how to use [deBridge](https://docs.debridge.finance/) to perform cross-chain royalty payments. For this tutorial specifically, we'll pay an IP Asset on Story using Base \$ETH.

From a high level, it involves:

1. Constructing a deBridge API call that will return tx data to swap tokens across chains and perform some action (e.g. pay royalty to an IP Asset on Story)
2. Executing the API call to receive that tx data
3. Executing the transaction (using the returned tx data) on the source chain

<Frame>
  <img src="https://mintcdn.com/story/ifOO5dfZ0pPInpZO/images/tutorials/cross-chain-royalty-payments.png?fit=max&auto=format&n=ifOO5dfZ0pPInpZO&q=85&s=fb17b9d4d78dee940eaf1087e5ef7c90" alt="Cross-Chain Royalty Payments" data-og-width="1344" width="1344" data-og-height="800" height="800" data-path="images/tutorials/cross-chain-royalty-payments.png" data-optimize="true" data-opv="3" srcset="https://mintcdn.com/story/ifOO5dfZ0pPInpZO/images/tutorials/cross-chain-royalty-payments.png?w=280&fit=max&auto=format&n=ifOO5dfZ0pPInpZO&q=85&s=e9486bcb41826f1683427cd64b5a537b 280w, https://mintcdn.com/story/ifOO5dfZ0pPInpZO/images/tutorials/cross-chain-royalty-payments.png?w=560&fit=max&auto=format&n=ifOO5dfZ0pPInpZO&q=85&s=4f1c3bd9debc85a675f36b2a7072495d 560w, https://mintcdn.com/story/ifOO5dfZ0pPInpZO/images/tutorials/cross-chain-royalty-payments.png?w=840&fit=max&auto=format&n=ifOO5dfZ0pPInpZO&q=85&s=82051123aeeb3a9414b68bcce1633a0c 840w, https://mintcdn.com/story/ifOO5dfZ0pPInpZO/images/tutorials/cross-chain-royalty-payments.png?w=1100&fit=max&auto=format&n=ifOO5dfZ0pPInpZO&q=85&s=6e50806697ecc9816f2a2b811f0fcab2 1100w, https://mintcdn.com/story/ifOO5dfZ0pPInpZO/images/tutorials/cross-chain-royalty-payments.png?w=1650&fit=max&auto=format&n=ifOO5dfZ0pPInpZO&q=85&s=c7bb9d49f9dda7b51435739e65f24081 1650w, https://mintcdn.com/story/ifOO5dfZ0pPInpZO/images/tutorials/cross-chain-royalty-payments.png?w=2500&fit=max&auto=format&n=ifOO5dfZ0pPInpZO&q=85&s=349737a41ded139b11a8a508141bc8c5 2500w" />
</Frame>

## Step 1: Constructing the deBridge API Call

The first step is to construct a deBridge API call. The purpose of this API call is to receive back a response that will contain transaction data so we can then execute it on the source chain.

This deBridge order swaps tokens from one chain to another. We can also optionally attach a `dlnHook` that will execute an arbitrary action upon order completion (ex. after \$ETH has been swapped for \$WIP). This is where the magic happens.

<Note>
  You can learn more about dlnHooks [here](https://docs.debridge.finance/dln-the-debridge-liquidity-network-protocol/integration-guidelines/interacting-with-the-api).
</Note>

In this case, the `dlnHook` will be a call to `payRoyaltyOnBehalf`, which is a function [in this contract](https://www.storyscan.io/address/0xD2f60c40fEbccf6311f8B47c4f2Ec6b040400086?tab=contract) that pays royalties to an IP Asset on Story.

You may be wondering, *"where does the Royalty Module (the contract spending the tokens on Story) get approved to spend the \$WIP?"* The answer is that deBridge automatically handles token approvals for you using their `IExternalCallExecutor`, where it approves the target address to spend the tokens on the destination chain. In this case because the target address is the Royalty Module itself, token approval is handled for us without having to create a custom multicall contract like we do in the [cross-chain license minting](/developers/tutorials/cross-chain-license-mint) tutorial.

<Note>
  You can learn more about the `IExternalCallExecutor` [here](https://docs.debridge.finance/dln-the-debridge-liquidity-network-protocol/protocol-specs/hook-data/anatomy-of-a-hook-for-the-evm-based-chains#universal-hook).
</Note>

<Tip>
  To summarize, we will construct a deBridge API call that says *"we want to swap \$ETH for \$IP, then use a dlnHook to call a smart contract on Story that pays royalties to an IP Asset on Story".*
</Tip>

### Step 1a. Constructing the `dlnHook`

The `dlnHook` is a JSON object that will be attached to the deBridge API call. It will contain the following information:

* The type of action to execute (`evm_transaction_call`)
* The address of the contract to call (`RoyaltyModule.sol`)
* The calldata to execute (`payRoyaltyOnBehalf`)

```typescript main.ts theme={null}
const ROYALTY_MODULE =
  "0xD2f60c40fEbccf6311f8B47c4f2Ec6b040400086";

// Build the dlnHook for Story royalty payment
const buildRoyaltyPaymentHook = ({ ipId: `0x${string}`, amount: bigint }): string => {
  // Encode the payRoyaltyOnBehalf function call
  const calldata = encodeFunctionData({
    abi: [
      {
        name: "payRoyaltyOnBehalf",
        type: "function",
        inputs: [
          { name: "receiverIpId", type: "address" },
          { name: "payerIpId", type: "address" },
          { name: "token", type: "address" },
          { name: "amount", type: "uint256" },
        ],
      },
    ],
    functionName: "payRoyaltyOnBehalf",
    args: [
      ipId,
      zeroAddress, // because it's not coming from another IP Asset. It's coming from an external address.
      WIP_TOKEN_ADDRESS,
      amount,
    ],
  });

  // Build the dlnHook JSON
  const dlnHook = {
    type: "evm_transaction_call",
    data: {
      to: ROYALTY_MODULE,
      calldata: calldata,
      gas: 0,
    },
  };

  return JSON.stringify(dlnHook);
};
```

### Step 1b. Constructing the deBridge API Call

Now that we have the `dlnHook`, we can construct the whole deBridge API call, including the `dlnHook`.

<Note>
  You can view deBridge's documentation on the `create-tx` endpoint [here](https://docs.debridge.finance/dln-the-debridge-liquidity-network-protocol/integration-guidelines/interacting-with-the-api/creating-an-order). I also highly recommend checking out the [Swagger UI](https://dln.debridge.finance/v1.0#/DLN/DlnOrderControllerV10_createOrder) for the `create-tx` endpoint as well.
</Note>

| Attribute                       | Description                                                                                                                          |
| ------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------ |
| `srcChainId`                    | The ID of the source blockchain (e.g., Ethereum mainnet is 1).                                                                       |
| `srcChainTokenIn`               | The address of the token being swapped on the source chain (ETH in this case).                                                       |
| `srcChainTokenInAmount`         | The amount of the source token to swap, set to `auto` for automatic calculation.                                                     |
| `dstChainId`                    | The ID of the destination blockchain (e.g., Story mainnet is 100000013).                                                             |
| `dstChainTokenOut`              | The address of the token to receive on the destination chain (WIP token).                                                            |
| `dstChainTokenOutAmount`        | The amount of the destination token to receive. It should be the same as the amount we're paying in `payRoyaltyOnBehalf` in step 1a. |
| `dstChainTokenOutRecipient`     | This can just be the same as `senderAddress`.                                                                                        |
| `senderAddress`                 | The address initiating the transaction.                                                                                              |
| `srcChainOrderAuthorityAddress` | The address authorized to manage the order on the source chain. This can just be the same as `senderAddress`.                        |
| `dstChainOrderAuthorityAddress` | The address authorized to manage the order on the destination chain. This can just be the same as `senderAddress`.                   |
| `enableEstimate`                | A flag to enable transaction simulation and estimation.                                                                              |
| `prependOperatingExpenses`      | A flag to include operating expenses in the transaction.                                                                             |
| `dlnHook`                       | The URL-encoded hook that specifies additional actions to execute post-swap.                                                         |

```typescript main.ts theme={null}
import { base } from "viem/chains";
import { WIP_TOKEN_ADDRESS } from "@story-protocol/core-sdk";

// ... previous code here ...

// Build deBridge API URL for cross-chain royalty payment
const buildDeBridgeApiUrl = ({
  ipId: `0x${string}`,
  senderAddress: `0x${string}`,
  paymentAmount: string // should be in wei
}): string => {
  const dlnHook = buildRoyaltyPaymentHook({ ipId, paymentAmount });
  const encodedHook = encodeURIComponent(dlnHook);
  const url =
    `https://dln.debridge.finance/v1.0/dln/order/create-tx?` +
    `srcChainId=${base.id}` +
    // we make this zero address which represents the native token ($ETH)
    `&srcChainTokenIn=0x0000000000000000000000000000000000000000` +
    // we set this to auto which will automatically calculate the amount of $ETH to swap
    `&srcChainTokenInAmount=auto` +
    // Story's mainnet chain ID
    `&dstChainId=100000013` +
    // we make this zero address which represents the native token ($IP)
    `&dstChainTokenOut=${WIP_TOKEN_ADDRESS}` +
    // we set the amount of $IP to pay for the payment on Story
    `&dstChainTokenOutAmount=${paymentAmount}` +
    // the address of the contract that will pay the royalty on Story
    `&dstChainTokenOutRecipient=${senderAddress}` +
    // the address of the user initiating the transaction
    `&senderAddress=${senderAddress}` +
    // the address authorized to manage the order on the source chain
    `&srcChainOrderAuthorityAddress=${senderAddress}` +
    // the address authorized to manage the order on the destination chain
    `&dstChainOrderAuthorityAddress=${senderAddress}` +
    // we set this to true to enable transaction simulation and estimation
    `&enableEstimate=true` +
    // we set this to true to include operating expenses in the transaction
    `&prependOperatingExpenses=true` +
    `&dlnHook=${encodedHook}`;

  return url;
};
```

## Step 2: Executing the API Call

Once the API call is constructed, execute it to receive a response. This response includes transaction data and an estimate for running the transaction on the source swap chain (e.g., Ethereum, Solana).

<CodeGroup>
  ```typescript main.ts theme={null}
  // ... previous code here ...

  const getDeBridgeTransactionData = async ({
    ipId: `0x${string}`,
    senderAddress: `0x${string}`,
    paymentAmount: string // should be in wei
  }): Promise<DeBridgeApiResponse> => {
    try {
      const apiUrl = buildDeBridgeApiUrl({ ipId, senderAddress, paymentAmount });

      const response = await fetch(apiUrl, {
        method: "GET",
        headers: {
          Accept: "application/json",
        },
      });

      if (!response.ok) {
        throw new Error(
          `deBridge API error: ${response.status} ${response.statusText}`
        );
      }

      const data = (await response.json()) as DeBridgeApiResponse;

      // Validate the response
      if (!data.tx || !data.estimation || !data.orderId) {
        throw new Error("Invalid deBridge API response: missing required fields");
      }

      return data;
    } catch (error) {
      console.error("Error calling deBridge API:", error);
      throw error;
    }
  };
  ```

  ```typescript DeBridgeApiResponse theme={null}
  export interface DeBridgeApiResponse {
    estimation: {
      srcChainTokenIn: {
        amount: string;
        approximateOperatingExpense: string;
      };
      dstChainTokenOut: {
        amount: string;
        maxTheoreticalAmount: string;
      };
    };
    tx: {
      to: string;
      data: string;
      value: string;
    };
    orderId: string;
  }
  ```
</CodeGroup>

## Step 3: Executing the Transaction on the Source Chain

Next, you would take the API response and execute the transaction on the source chain.

<Note>
  View [the docs here](https://docs.debridge.finance/dln-the-debridge-liquidity-network-protocol/integration-guidelines/interacting-with-the-api/submitting-an-order-creation-transaction) on submitting the transaction, including how this would be done differently on Solana.
</Note>

```typescript TypeScript theme={null}
import { base } from "viem/chains";
import { createWalletClient, http, WalletClient, parseEther } from "viem";
import { privateKeyToAccount, Address, Account } from "viem/accounts";
import dotenv from "dotenv";

dotenv.config();

// Validate environment variables
if (!process.env.WALLET_PRIVATE_KEY) {
  throw new Error("WALLET_PRIVATE_KEY is required in .env file");
}

// Create account from private key
const account: Account = privateKeyToAccount(
  `0x${process.env.WALLET_PRIVATE_KEY}` as Address
);

// Initialize the wallet client
const walletClient = createWalletClient({
  chain: base,
  transport: http("https://mainnet.infura.io/v3/YOUR_INFURA_PROJECT_ID"), // Use Infura or another Ethereum provider
  account,
}) as WalletClient;

// ... previous code here ...

// Function to send a transaction
const executeLicenseMint = async (params: {
  ipId: `0x${string}`;
  senderAddress: `0x${string}`;
  paymentAmount: string; // should be in wei
}) => {
  // Get transaction data from deBridge
  const deBridgeResponse = await getDeBridgeTransactionData(params);

  try {
    // Execute the transaction using the user's wallet
    const txHash = await walletClient.sendTransaction({
      to: deBridgeResponse.tx.to as Address,
      data: deBridgeResponse.tx.data as Address,
      value: BigInt(deBridgeResponse.tx.value),
      account: account as Account,
      chain: base,
    });
    console.log("Transaction sent:", txHash);

    // Wait for the transaction to be mined
    const receipt = await walletClient.waitForTransactionReceipt(txHash);
    console.log("Transaction mined:", receipt.transactionHash);
  } catch (error) {
    console.error("Error sending transaction:", error);
  }
};

// Example usage with a mock API response
const params = {
  ipId: "0xcb6B9CCae4108A103097B30cFc25e1E257D4b5Fe",
  senderAddress: account.address,
  paymentAmount: parseEther("5"), // 5 $WIP
};

// Execute the function to send the transaction
executeLicenseMint(params);
```

## Conclusion

Congratulations! You have successfully set up cross-chain royalty payments using deBridge.
# How to Tip an IP

> Learn how to tip an IP Asset using the SDK and Smart Contracts.

* [Use the SDK](#using-the-sdk)
* [Use a Smart Contract](#using-a-smart-contract)

# Using the SDK

<CardGroup cols={1}>
  <Card title="Completed Code" href="https://github.com/storyprotocol/typescript-tutorial/blob/main/scripts/royalty/payRevenue.ts" icon="thumbs-up">
    See a completed, working example of setting up a simple derivative chain and
    then tipping the child IP Asset.
  </Card>
</CardGroup>

In this tutorial, you will learn how to send money ("tip") an IP Asset using the TypeScript SDK.

## The Explanation

In this scenario, let's say there is a parent IP Asset that represents Mickey Mouse. Someone else draws a hat on that Mickey Mouse and registers it as a derivative (or "child") IP Asset. The License Terms specify that the child must share 50% of all commercial revenue (`commercialRevShare = 50`) with the parent. Someone else (a 3rd party user) comes along and wants to send the derivative 2 \$WIP for being really cool.

For the purposes of this example, we will assume the child is already registered as a derivative IP Asset. If you want help learning this, check out [Register a Derivative](/developers/typescript-sdk/register-derivative).

* Parent IP ID: `0x42595dA29B541770D9F9f298a014bF912655E183`
* Child IP ID: `0xeaa4Eed346373805B377F5a4fe1daeFeFB3D182a`

## 0. Before you Start

There are a few steps you have to complete before you can start the tutorial.

1. You will need to install [Node.js](https://nodejs.org/en/download) and [npm](https://docs.npmjs.com/downloading-and-installing-node-js-and-npm). If you've coded before, you likely have these.
2. Add your Story Network Testnet wallet's private key to `.env` file:

```text env theme={null}
WALLET_PRIVATE_KEY=<YOUR_WALLET_PRIVATE_KEY>
```

3. Add your preferred RPC URL to your `.env` file. You can just use the public default one we provide:

```text env theme={null}
RPC_PROVIDER_URL=https://aeneid.storyrpc.io
```

4. Install the dependencies:

```bash Terminal theme={null}
npm install @story-protocol/core-sdk viem
```

## 1. Set up your Story Config

In a `utils.ts` file, add the following code to set up your Story Config:

* Associated docs: [TypeScript SDK Setup](/developers/typescript-sdk/setup)

```typescript utils.ts theme={null}
import { StoryClient, StoryConfig } from "@story-protocol/core-sdk";
import { http } from "viem";
import { privateKeyToAccount, Address, Account } from "viem/accounts";

const privateKey: Address = `0x${process.env.WALLET_PRIVATE_KEY}`;
export const account: Account = privateKeyToAccount(privateKey);

const config: StoryConfig = {
  account: account,
  transport: http(process.env.RPC_PROVIDER_URL),
  chainId: "aeneid",
};
export const client = StoryClient.newClient(config);
```

## 2. Tipping the Derivative IP Asset

Now create a `main.ts` file. We will use the `payRoyaltyOnBehalf` function to pay the derivative asset.

You will be paying the IP Asset with [\$WIP](https://aeneid.storyscan.io/address/0x1514000000000000000000000000000000000000). **Note that if you don't have enough \$WIP, the function will auto wrap an equivalent amount of \$IP into \$WIP for you.** If you don't have enough of either, it will fail.

<Note>
  **Whitelisted Revenue Tokens**

  Only tokens that are whitelisted by our protocol can be used as payment ("revenue") tokens. \$WIP is one of those tokens. To see that list, go [here](/developers/deployed-smart-contracts).
</Note>

Now we can call the `payRoyaltyOnBehalf` function. In this case:

1. `receiverIpId` is the `ipId` of the derivative (child) asset
2. `payerIpId` is `zeroAddress` because the payer is a 3rd party (someone that thinks Mickey Mouse with a hat on him is cool), and not necessarily another IP Asset
3. `token` is the address of \$WIP, which can be found [here](/concepts/royalty-module/ip-royalty-vault#whitelisted-revenue-tokens)
4. `amount` is 2, since the person tipping wants to send 2 \$WIP

```typescript main.ts theme={null}
import { client } from "./utils";
import { zeroAddress, parseEther } from "viem";
import { WIP_TOKEN_ADDRESS } from "@story-protocol/core-sdk";

async function main() {
  const response = await client.royalty.payRoyaltyOnBehalf({
    receiverIpId: "0xeaa4Eed346373805B377F5a4fe1daeFeFB3D182a",
    payerIpId: zeroAddress,
    token: WIP_TOKEN_ADDRESS,
    amount: parseEther("2"), // 2 $WIP
  });
  console.log(`Paid royalty at transaction hash ${response.txHash}`);
}

main();
```

## 3. Child Claiming Due Revenue

At this point we have already finished the tutorial: we learned how to tip an IP Asset. But what if the child and parent want to claim their due revenue?

The child has been paid 2 \$WIP. But remember, it shares 50% of its revenue with the parent IP because of the `commercialRevenue = 50` in the license terms.

The child IP can claim its 1 \$WIP by calling the `claimAllRevenue` function:

* `ancestorIpId` is the `ipId` we're claiming revenue for
* `currencyTokens` is an array that contains the address of \$WIP, which can be found [here](/concepts/royalty-module/ip-royalty-vault#whitelisted-revenue-tokens)
* `claimer` is the address that holds the [royalty tokens](/concepts/royalty-module/ip-royalty-vault#royalty-tokens) associated with the child's [IP Royalty Vault](/concepts/royalty-module/ip-royalty-vault). By default, they are in the IP Account, which is just the `ipId` of the child asset.

<Note>
  Claiming revenue is permissionless. Any wallet can run the claim revenue transaction for an IP.
</Note>

```typescript main.ts theme={null}
import { client } from "./utils";
import { zeroAddress, parseEther } from "viem";
import { WIP_TOKEN_ADDRESS } from "@story-protocol/core-sdk";

async function main() {
  // previous code here ...
  const response = await client.royalty.claimAllRevenue({
    ancestorIpId: "0xDa03c4B278AD44f5a669e9b73580F91AeDE0E3B2",
    claimer: "0xDa03c4B278AD44f5a669e9b73580F91AeDE0E3B2",
    currencyTokens: [WIP_TOKEN_ADDRESS],
    childIpIds: [],
    royaltyPolicies: [],
  });

  console.log(`Claimed revenue: ${response.claimedTokens}`);
}

main();
```

## 4. Parent Claiming Due Revenue

Continuing, the parent should be able to claim its revenue as well. In this example, the parent should be able to claim 1 \$WIP since the child earned 2 \$WIP and the `commercialRevShare = 50` in the license terms.

We will use the `claimAllRevenue` function to claim the due revenue tokens.

1. `ancestorIpId` is the `ipId` of the parent ("ancestor") asset
2. `claimer` is the address that holds the royalty tokens associated with the parent's [IP Royalty Vault](/concepts/royalty-module/ip-royalty-vault). By default, they are in the IP Account, which is just the `ipId` of the parent asset
3. `childIpIds` will have the `ipId` of the child asset
4. `royaltyPolicies` will contain the address of the royalty policy. As explained in [Royalty Module](/concepts/royalty-module), this is either `RoyaltyPolicyLAP` or `RoyaltyPolicyLRP`, depending on the license terms. In this case, let's assume the license terms specify a `RoyaltyPolicyLAP`. Simply go to [Deployed Smart Contracts](/developers/deployed-smart-contracts) and find the correct address.
5. `currencyTokens` is an array that contains the address of \$WIP, which can be found [here](/concepts/royalty-module/ip-royalty-vault#whitelisted-revenue-tokens)

<Note>
  Claiming revenue is permissionless. Any wallet can run the claim revenue transaction for an IP.
</Note>

```typescript main.ts theme={null}
import { client } from "./utils";
import { zeroAddress, parseEther } from "viem";
import { WIP_TOKEN_ADDRESS } from "@story-protocol/core-sdk";

async function main() {
  // previous code here ...

  const response = await client.royalty.claimAllRevenue({
    ancestorIpId: "0x089d75C9b7E441dA3115AF93FF9A855BDdbfe384",
    claimer: "0x089d75C9b7E441dA3115AF93FF9A855BDdbfe384",
    currencyTokens: [WIP_TOKEN_ADDRESS],
    childIpIds: ["0xDa03c4B278AD44f5a669e9b73580F91AeDE0E3B2"],
    royaltyPolicies: ["0xBe54FB168b3c982b7AaE60dB6CF75Bd8447b390E"],
  });

  console.log(`Claimed revenue: ${response.claimedTokens}`);
}

main();
```

## 5. Where does revenue get claimed to? Why do I not see it in my wallet? Why is it in the IP Account?

A couple of things to note here:

1. By default, revenue is claimed to the IP Account, not the IP owner's
   wallet. This is because when an IP is created, the royalty tokens for that IP
   (where revenue gets claimed to) are minted to the IP Account.

2. To transfer revenue from IP Account -> IP Owner's wallet, an IP owner can
   run the `transferErc20` function (it will not work
   if you run it for someone else's IP obviously).

   ```typescript main.ts theme={null}
   // Docs: https://docs.story.foundation/sdk-reference/ipaccount#transfererc20
   const transferFromIpAccount = await client.ipAccount.transferErc20({
     ipId: "0xDa03c4B278AD44f5a669e9b73580F91AeDE0E3B2",
     tokens: [
       {
         address: WIP_TOKEN_ADDRESS,
         amount: parseEther("1"),
         target: "0x02", // the external wallet
       },
     ],
   });
   ```

3. If the **IP owner** (the wallet that owns the underlying IP ownership NFT) had
   called `claimAllRevenue` before, our SDK would automatically transfer the revenue
   to the IP owner's wallet for convenience.

4. If the IP owner wants revenue to always be claimed to their wallet and
   avoid the middle step, they should transfer the royalty tokens from the IP
   account to their wallet.

   ```typescript main.ts theme={null}
   // Get the IP Royalty Vault Address
   // Note: This is equivalent to the currency address of the ERC-20
   // Royalty Tokens for this IP.
   const royaltyVaultAddress = await client.royalty.getRoyaltyVaultAddress(
     "0xDa03c4B278AD44f5a669e9b73580F91AeDE0E3B2" as Address
   );

   // Transfer the Royalty Tokens from the IP Account to the address
   // executing this transaction (you could use any other address as well)
   const transferRoyaltyTokens = await client.ipAccount.transferErc20({
     ipId: "0xDa03c4B278AD44f5a669e9b73580F91AeDE0E3B2" as Address,
     tokens: [
       {
         address: royaltyVaultAddress,
         amount: 100 * 1_000_000, // 100% of the royalty tokens
         target: "0x02", // the external wallet
       },
     ],
   });
   ```

## 6. Done!

<CardGroup cols={1}>
  <Card title="Completed Code" href="https://github.com/storyprotocol/typescript-tutorial/blob/main/scripts/royalty/payRevenue.ts" icon="thumbs-up">
    See a completed, working example of setting up a simple derivative chain and
    then tipping the child IP Asset.
  </Card>
</CardGroup>

# Using a Smart Contract

<CardGroup cols={1}>
  <Card title="Go to Smart Contract Tutorial" href="/developers/smart-contracts-guide/claim-revenue" icon="house">
    View the tutorial here!
  </Card>
</CardGroup>
# Easy $IP Onboarding

> An example of how to integrate purchasing $IP with Apple Pay, Venmo, Debit Card, Bank, and more with Halliday.

<CardGroup cols={1}>
  <Card title="Completed Code Example" href="https://github.com/jacob-tucker/halliday-story-example" icon="thumbs-up">
    View the completed code for this tutorial.
  </Card>
</CardGroup>

This tutorial will show you how to integrate purchasing \$IP with Apple Pay, Venmo, Debit Card, Bank, and more into your DApp with Halliday.

<Note>
  **This tutorial is a React/Next.js tutorial**. It is also based on the [Halliday Docs](https://docs.halliday.xyz/pages/index-page).
</Note>

Here is what the end result will look like:

<Frame>
  <img src="https://mintcdn.com/story/KwuxPVrS3UIa7CU1/images/tutorials/halliday-payment.png?fit=max&auto=format&n=KwuxPVrS3UIa7CU1&q=85&s=da6b1d523106f5cde5e3a0d327668f2a" alt="Halliday Payment End Result" width={300} data-og-width="988" data-og-height="1252" data-path="images/tutorials/halliday-payment.png" data-optimize="true" data-opv="3" srcset="https://mintcdn.com/story/KwuxPVrS3UIa7CU1/images/tutorials/halliday-payment.png?w=280&fit=max&auto=format&n=KwuxPVrS3UIa7CU1&q=85&s=df58e9a1da756c057353ddcb229b1997 280w, https://mintcdn.com/story/KwuxPVrS3UIa7CU1/images/tutorials/halliday-payment.png?w=560&fit=max&auto=format&n=KwuxPVrS3UIa7CU1&q=85&s=d52a92cf284b42116024b4e66d591bc3 560w, https://mintcdn.com/story/KwuxPVrS3UIa7CU1/images/tutorials/halliday-payment.png?w=840&fit=max&auto=format&n=KwuxPVrS3UIa7CU1&q=85&s=ff0169a9bcbadeb0f2f660c4ebdd8f78 840w, https://mintcdn.com/story/KwuxPVrS3UIa7CU1/images/tutorials/halliday-payment.png?w=1100&fit=max&auto=format&n=KwuxPVrS3UIa7CU1&q=85&s=dcd8df7ec620d844d472b868fc74b3c4 1100w, https://mintcdn.com/story/KwuxPVrS3UIa7CU1/images/tutorials/halliday-payment.png?w=1650&fit=max&auto=format&n=KwuxPVrS3UIa7CU1&q=85&s=2856314439af4f492ce05c9b0efd36de 1650w, https://mintcdn.com/story/KwuxPVrS3UIa7CU1/images/tutorials/halliday-payment.png?w=2500&fit=max&auto=format&n=KwuxPVrS3UIa7CU1&q=85&s=12ae18a63d0a35ea4f769da48e169bd3 2500w" />
</Frame>

## Instructions

<Steps>
  <Step title="Get an API Key">
    In order to use Halliday, you will need to get an API key. Right now the process is to email [partnerships@halliday.xyz](mailto:partnerships@halliday.xyz). But this may change, so I recommend checking the [Halliday Docs](https://docs.halliday.xyz/pages/payments-hello-world) for the most up to date information.
  </Step>

  <Step title="Install Halliday">
    Next, install the Halliday Payments SDK in the root folder of your project.

    <CodeGroup>
      ```bash npm theme={null}
      npm install @halliday-sdk/payments
      ```

      ```bash yarn theme={null}
      yarn add @halliday-sdk/payments
      ```
    </CodeGroup>
  </Step>

  <Step title="Setup Your .env">
    In your `.env` file, add your Halliday API key.

    ```env  theme={null}
    NEXT_PUBLIC_HALLIDAY_PUBLIC_API_KEY=your-api-key
    ```
  </Step>

  <Step title="Integrate Halliday">
    Lastly, integrate Halliday Payments into your existing application with a few lines of code.

    <Note>
      In this example, we make it so that the Halliday popup is embedded in a div with the id `halliday-embed`. Such that when the user loads the page, it is already there. However you can change this so that it pops up when the user clicks a button. Check out the [Halliday Docs](https://docs.halliday.xyz/pages/payments-widget) for more information.
    </Note>

    ```tsx  theme={null}
    "use client";
    import { openHallidayPayments } from "@halliday-sdk/payments";
    import { useEffect } from "react";

    export default function Home() {
      useEffect(() => {
        openHallidayPayments({
          apiKey: process.env.NEXT_PUBLIC_HALLIDAY_PUBLIC_API_KEY as string,
          // $IP on Story
          outputs: ["story:0x"],
          // $USDC.e on Story
          // outputs: ["story:0xf1815bd50389c46847f0bda824ec8da914045d14"],
          sandbox: false,
          windowType: "EMBED",
          targetElementId: "halliday-embed",
        });
      }, []);

      return (
        <div
          className="flex items-center justify-center min-h-screen bg-white"
          id="halliday-embed"
        ></div>
      );
    }
    ```
  </Step>
</Steps>

That's it! You can now use Halliday to purchase \$IP on Story.

<CardGroup cols={1}>
  <Card title="Completed Code Example" href="https://github.com/jacob-tucker/halliday-story-example" icon="thumbs-up">
    View the completed code for this tutorial.
  </Card>
</CardGroup>
# Email Login & Sponsored Transactions with Privy

> Learn how to implement email logins and sponsored transactions with Privy & Pimlico.

<Card title="Completed Code" href="https://github.com/jacob-tucker/story-privy-tutorial" icon="thumbs-up" color="#51af51">
  View the completed code for this tutorial.
</Card>

You are reading this tutorial because you probably want to do one or both of these things:

1. Enable users who don't have a wallet to login with email to your app ("Embedded Wallets")
2. Sponsor transactions for your users so they don't have to pay gas ("Smart Wallets")

Here is how Privy describes both of these things:

> Embedded wallets are self-custodial wallets provisioned by Privy itself for a wallet experience that is directly embedded in your application. Embedded wallets do not require a separate wallet client, like a browser extension or a mobile app, and can be accessed directly from your product. These are primarily designed for users of your app who may not already have an external wallet, or don't want to connect their external wallet.
>
> Smart wallets are programmable, onchain accounts that incorporate the features of account abstraction. With just a few lines of code, you can create smart wallets for your users to sponsor gas payments, send batched transactions, and more.

We will be implementing both using [Privy](https://www.privy.io/) + [Pimlico](https://www.pimlico.io/).

### ⚠️ Prerequisites

There are a few steps you have to complete before you can start the tutorial.

1. Create a new project on [Privy's Dashboard](https://dashboard.privy.io)
2. Copy your **"App ID"** under **"App settings > API keys"**. In your local project, make a `.env` file and add your App ID:

```Text .env theme={null}
NEXT_PUBLIC_PRIVY_APP_ID=
```

3. On your project dashboard, enable Smart Wallets under "**Wallet Configuration > Smart wallets**" and select "**Kernel (ZeroDev)**" as shown below:

<Frame>
  <img src="https://mintcdn.com/story/KwuxPVrS3UIa7CU1/images/tutorials/privy-tutorial-1.png?fit=max&auto=format&n=KwuxPVrS3UIa7CU1&q=85&s=d68057863ec71a8731d3ec777fe5c432" alt="Privy Dashboard" data-og-width="3024" width="3024" data-og-height="1530" height="1530" data-path="images/tutorials/privy-tutorial-1.png" data-optimize="true" data-opv="3" srcset="https://mintcdn.com/story/KwuxPVrS3UIa7CU1/images/tutorials/privy-tutorial-1.png?w=280&fit=max&auto=format&n=KwuxPVrS3UIa7CU1&q=85&s=f41c2cb4c765c55d783f37610ccb68f1 280w, https://mintcdn.com/story/KwuxPVrS3UIa7CU1/images/tutorials/privy-tutorial-1.png?w=560&fit=max&auto=format&n=KwuxPVrS3UIa7CU1&q=85&s=8bd3d61b77abf1ef4912a93d6649a5f6 560w, https://mintcdn.com/story/KwuxPVrS3UIa7CU1/images/tutorials/privy-tutorial-1.png?w=840&fit=max&auto=format&n=KwuxPVrS3UIa7CU1&q=85&s=fc696a95e834d26fa0d27f3528fa9732 840w, https://mintcdn.com/story/KwuxPVrS3UIa7CU1/images/tutorials/privy-tutorial-1.png?w=1100&fit=max&auto=format&n=KwuxPVrS3UIa7CU1&q=85&s=aae6e95b7415f3b52f47cda88f430bf5 1100w, https://mintcdn.com/story/KwuxPVrS3UIa7CU1/images/tutorials/privy-tutorial-1.png?w=1650&fit=max&auto=format&n=KwuxPVrS3UIa7CU1&q=85&s=45bfdad1d68e6ce07e1eb7bd24ae650b 1650w, https://mintcdn.com/story/KwuxPVrS3UIa7CU1/images/tutorials/privy-tutorial-1.png?w=2500&fit=max&auto=format&n=KwuxPVrS3UIa7CU1&q=85&s=412af66188b17dbabe8aedbc3a34fe63 2500w" />
</Frame>

4. Once you enable Smart wallets, right underneath make sure to put a "Custom chain" with the following values:
   1. Name: `Story Aeneid Testnet`
   2. ID number: `1315`
   3. RPC URL: `https://aeneid.storyrpc.io`
   4. For the Bundler URL and Paymaster URL, go to [Pimlico's Dashboard](https://dashboard.pimlico.io) and create a new app. Then click on "API Keys", create a new API Key, click "RPC URLs" as shown below, and then select "Story Aeneid Testnet" as the network:

<Warning>
  This is for testing. In a real scenario, you would have to set up proper sponsorship policies and billing info on Pimlico to automatically sponsor the transactions on behalf of your app. We don't have to do this on testnet.
</Warning>

<Frame>
  <img src="https://mintcdn.com/story/KwuxPVrS3UIa7CU1/images/tutorials/pimlico-dashboard.png?fit=max&auto=format&n=KwuxPVrS3UIa7CU1&q=85&s=ae0e505de6591cb2b0c8e05167a7b8a6" alt="Pimlico Dashboard" data-og-width="3024" width="3024" data-og-height="1530" height="1530" data-path="images/tutorials/pimlico-dashboard.png" data-optimize="true" data-opv="3" srcset="https://mintcdn.com/story/KwuxPVrS3UIa7CU1/images/tutorials/pimlico-dashboard.png?w=280&fit=max&auto=format&n=KwuxPVrS3UIa7CU1&q=85&s=301dd5be82c0effac9d2cbfb972e68d7 280w, https://mintcdn.com/story/KwuxPVrS3UIa7CU1/images/tutorials/pimlico-dashboard.png?w=560&fit=max&auto=format&n=KwuxPVrS3UIa7CU1&q=85&s=be344e73b7e8ce6ba8eaad93854b1b95 560w, https://mintcdn.com/story/KwuxPVrS3UIa7CU1/images/tutorials/pimlico-dashboard.png?w=840&fit=max&auto=format&n=KwuxPVrS3UIa7CU1&q=85&s=775e7c33418796bba5dd4015a2a73230 840w, https://mintcdn.com/story/KwuxPVrS3UIa7CU1/images/tutorials/pimlico-dashboard.png?w=1100&fit=max&auto=format&n=KwuxPVrS3UIa7CU1&q=85&s=ae21d8f7fb72884461d6d810f6c076da 1100w, https://mintcdn.com/story/KwuxPVrS3UIa7CU1/images/tutorials/pimlico-dashboard.png?w=1650&fit=max&auto=format&n=KwuxPVrS3UIa7CU1&q=85&s=96b4e0e55e61b8099ab66a1a5f4e4b05 1650w, https://mintcdn.com/story/KwuxPVrS3UIa7CU1/images/tutorials/pimlico-dashboard.png?w=2500&fit=max&auto=format&n=KwuxPVrS3UIa7CU1&q=85&s=080714ac8ec65f3963024a73aa39385a 2500w" />
</Frame>

5. Install the dependencies:

```Text Terminal theme={null}
npm install @story-protocol/core-sdk permissionless viem @privy-io/react-auth
```

## 1. Set up Embedded Wallets

<CardGroup cols={1}>
  <Card title="Official Privy Tutoral" href="https://docs.privy.io/wallets/using-wallets/evm-smart-wallets/setup/configuring-dashboard" icon="house">
    Follow Privy's official tutorial for setup instead of reading this step.
  </Card>
</CardGroup>

<Note>
  This part of the Privy documentation
  [here](https://docs.privy.io/basics/react/advanced/automatic-wallet-creation#automatic-wallet-creation)
  describes setting up Embedded Wallets automatically, which is a fancy way of
  saying it supports email login, such that when a user logs in with email it
  creates a wallet for them. In the below example, we simply create an embedded
  wallet for every user, but you may want more customization by reading their
  tutorial.
</Note>

You must wrap any component that will be using embedded/smart wallets with the `PrivyProvider` and `SmartWalletsProvider`. In a `providers.tsx` (or whatever you want to call it) file, add the following code:

```jsx providers.tsx theme={null}
"use client";

import { PrivyProvider } from "@privy-io/react-auth";
import { SmartWalletsProvider } from "@privy-io/react-auth/smart-wallets";
import { aeneid } from "@story-protocol/core-sdk";

export default function Providers({ children }: { children: React.ReactNode }) {
  return (
    <PrivyProvider
      appId={process.env.NEXT_PUBLIC_PRIVY_APP_ID as string}
      config={{
        // Customize Privy's appearance in your app
        appearance: {
          theme: "light",
          accentColor: "#676FFF",
          logo: "/story-logo.jpg",
        },
        // Create embedded wallets for users who don't have a wallet
        // when they sign in with email
        embeddedWallets: {
          createOnLogin: "all-users",
        },
        defaultChain: aeneid,
        supportedChains: [aeneid],
      }}
    >
      <SmartWalletsProvider>{children}</SmartWalletsProvider>
    </PrivyProvider>
  );
}
```

Then you can simply add it to your`layout.tsx` like so:

```jsx layout.tsx theme={null}
import Providers from "@/providers/providers";

/* other code here... */

export default function RootLayout({
  children,
}: Readonly<{
  children: React.ReactNode,
}>) {
  return (
    <html lang="en">
      <body
        className={`${geistSans.variable} ${geistMono.variable} antialiased`}
      >
        <Providers>{children}</Providers>
      </body>
    </html>
  );
}
```

## 2. Login & Logout

You can add email login to your app like so:

```jsx page.tsx theme={null}
import { usePrivy } from "@privy-io/react-auth";

export default function Home() {
  const { login, logout, user } = usePrivy();

  useEffect(() => {
    if (user) {
      const smartWallet = user.linkedAccounts.find(
        (account) => account.type === "smart_wallet"
      );
      // Logs the smart wallet's address
      console.log(smartWallet.address);
      // Logs the smart wallet type (e.g. 'safe', 'kernel', 'light_account', 'biconomy', 'thirdweb', 'coinbase_smart_wallet')
      console.log(smartWallet.type);
    }
  }, [user]);

  return (
    <div>
      <button onClick={user ? logout : login}>
        {user ? "Logout" : "Login with Privy"}
      </button>
    </div>
  );
}
```

## 3. Sign a Message with Privy

<CardGroup cols={1}>
  <Card title="Official Privy Tutoral" href="https://docs.privy.io/wallets/using-wallets/evm-smart-wallets/usage#sign-a-message" icon="house">
    Follow Privy's official tutorial for signing messages instead of reading
    this step.
  </Card>
</CardGroup>

We can use the generated smart wallet to sign messages:

```jsx page.tsx theme={null}
import { useSmartWallets } from "@privy-io/react-auth/smart-wallets";

export default function Home() {
  const { client: smartWalletClient } = useSmartWallets();

  /* previous code here */

  async function sign() {
    const uiOptions = {
      title: "Example Sign",
      description: "This is an example for a user to sign.",
      buttonText: "Sign",
    };
    const request = {
      message: "IP is cool",
    };
    const signature = await smartWalletClient?.signMessage(request, {
      uiOptions,
    });
  }

  return (
    <div>
      {/* previous code here */}
      <button onClick={sign}>Sign</button>
    </div>
  );
}
```

## 4. Send an Arbitrary Transaction

<CardGroup cols={1}>
  <Card title="Official Privy Tutoral" href="https://docs.privy.io/wallets/using-wallets/evm-smart-wallets/usage#send-a-transaction" icon="house">
    Follow Privy's official tutorial for sending transactions instead of reading
    this step.
  </Card>
</CardGroup>

We can also use the generated smart wallet to sponsor transactions for our users:

<CodeGroup>
  ```jsx page.tsx theme={null}
  import { useSmartWallets } from "@privy-io/react-auth/smart-wallets";
  import { encodeFunctionData } from "viem";
  import { defaultNftContractAbi } from "./defaultNftContractAbi";

  export default function Home() {
    const { client: smartWalletClient } = useSmartWallets();

    /* previous code here */

    async function mintNFT() {
      const uiOptions = {
        title: "Mint NFT",
        description: "This is an example transaction that mints an NFT.",
        buttonText: "Mint",
      };

      const transactionRequest = {
        to: "0x937bef10ba6fb941ed84b8d249abc76031429a9a", // example nft contract
        data: encodeFunctionData({
          abi: defaultNftContractAbi, // abi from another file
          functionName: "mintNFT",
          args: ["0x6B86B39F03558A8a4E9252d73F2bDeBfBedf5b68", "test-uri"],
        }),
      } as const;

      const txHash = await smartWalletClient?.sendTransaction(
        transactionRequest,
        { uiOptions }
      );
      console.log(`View Tx: https://aeneid.storyscan.io/tx/${txHash}`);
    }

    return (
      <div>
        {/* previous code here */}
        <button onClick={mintNFT}>Mint NFT</button>
      </div>
    )
  }
  ```

  ```Text defaultNftContractAbi.ts theme={null}
  export const defaultNftContractAbi = [
    {
      inputs: [],
      stateMutability: "nonpayable",
      type: "constructor",
    },
    {
      inputs: [
        {
          internalType: "address",
          name: "recipient",
          type: "address",
        },
        {
          internalType: "string",
          name: "tokenURI",
          type: "string",
        },
      ],
      name: "mintNFT",
      outputs: [
        {
          internalType: "uint256",
          name: "",
          type: "uint256",
        },
      ],
      stateMutability: "nonpayable",
      type: "function",
    },
    {
      inputs: [
        {
          internalType: "uint256",
          name: "tokenId",
          type: "uint256",
        },
      ],
      name: "tokenURI",
      outputs: [
        {
          internalType: "string",
          name: "",
          type: "string",
        },
      ],
      stateMutability: "view",
      type: "function",
    },
    {
      inputs: [
        {
          internalType: "uint256",
          name: "tokenId",
          type: "uint256",
        },
      ],
      name: "ownerOf",
      outputs: [
        {
          internalType: "address",
          name: "",
          type: "address",
        },
      ],
      stateMutability: "view",
      type: "function",
    },
    {
      inputs: [],
      name: "symbol",
      outputs: [
        {
          internalType: "string",
          name: "",
          type: "string",
        },
      ],
      stateMutability: "view",
      type: "function",
    },
    {
      inputs: [],
      name: "name",
      outputs: [
        {
          internalType: "string",
          name: "",
          type: "string",
        },
      ],
      stateMutability: "view",
      type: "function",
    },
    {
      inputs: [],
      name: "totalSupply",
      outputs: [
        {
          internalType: "uint256",
          name: "",
          type: "uint256",
        },
      ],
      stateMutability: "view",
      type: "function",
    },
  ];

  ```
</CodeGroup>

## 5. Send a Transaction from Story SDK

We can also use the generated smart wallet to send transactions from the [🛠️ TypeScript SDK](/developers/typescript-sdk). Some of the functions have an option to return the `encodedTxData`, which we can use to pass into Privy's smart wallet. You can see which functions support this in the [SDK Reference](/sdk-reference).

```jsx page.tsx theme={null}
import { useSmartWallets } from "@privy-io/react-auth/smart-wallets";
import {
  EncodedTxData,
  StoryClient,
  StoryConfig,
} from "@story-protocol/core-sdk";
import { http } from "viem";

export default function Home() {
  const { client: smartWalletClient } = useSmartWallets();

  /* previous code here */

  async function setupStoryClient() {
    const config: StoryConfig = {
      account: smartWalletClient!.account,
      transport: http("https://aeneid.storyrpc.io"),
      chainId: "aeneid",
    };
    const client = StoryClient.newClient(config);
    return client;
  }

  async function registerIp() {
    const storyClient = await setupStoryClient();

    const response = await storyClient.ipAsset.registerIpAsset({
      nft: {
        type: "mint",
        spgNftContract: "0xc32A8a0FF3beDDDa58393d022aF433e78739FAbc",
      },
    });

    const uiOptions = {
      title: "Register IP",
      description: "This is an example transaction that registers an IP.",
      buttonText: "Register",
    };

    const txHash = await smartWalletClient?.sendTransaction(
      response.encodedTxData as EncodedTxData,
      { uiOptions }
    );
    console.log(`View Tx: https://aeneid.storyscan.io/tx/${txHash}`);
  }

  return (
    <div>
      {/* previous code here */}
      <button onClick={registerIp}>Register IP</button>
    </div>
  );
}
```

## 6. Done!

<CardGroup cols={2}>
  <Card title="Completed Code" href="https://github.com/jacob-tucker/story-privy-tutorial" icon="thumbs-up" iconColor="#51af51">
    View the completed code for this tutorial.
  </Card>

  <Card title="Learn More" href="/developers/tutorials" icon="book-open">
    Explore more tutorials in our documentation
  </Card>
</CardGroup>
# Encode Function Data

> A short tutorial on how to encode Story smart contract function data for things like Crossmint.

Sometimes you want to encode smart contract function data for things like [sending arbitrary transactions via Crossmint](https://docs.crossmint.com/solutions/story-protocol/wallets/server-side-wallets#send-arbitrary-transaction).

As seen [in Crossmint's docs](https://docs.crossmint.com/solutions/story-protocol/wallets/server-side-wallets#send-arbitrary-transaction), you can get encoded function data via Story's SDK. However this is shortly going to be deprecated and it does not support every function anyway.

So here's a quick tutorial on how to get encoded function data for any Story smart contract function.

<CardGroup cols={1}>
  <Card title="Completed Code" href="https://github.com/storyprotocol/typescript-tutorial/blob/main/scripts/misc/sendRawTransaction.ts" icon="code">
    View the completed code for this tutorial.
  </Card>
</CardGroup>

## Step 1: Get the function data

As an example, let's try to call the [mintAndRegisterIpAndAttachPilTerms](https://github.com/storyprotocol/protocol-periphery-v1/blob/main/contracts/workflows/LicenseAttachmentWorkflows.sol#L130) in our periphery contract. This function mints & registers a new IP and attaches [PIL Terms](/concepts/programmable-ip-license/pil-terms) to it.

As shown in [Deployed Smart Contracts](/developers/deployed-smart-contracts), `LicenseAttachmentWorkflows` is deployed at `0xcC2E862bCee5B6036Db0de6E06Ae87e524a79fd8` on Aeneid (at the time of writing this tutorial).

There's a few things we'll need:

1. Contract ABI - you can get this by going to [our block explorer and looking up the contract](https://aeneid.storyscan.io/address/0xcC2E862bCee5B6036Db0de6E06Ae87e524a79fd8). This is a proxy contract, so go to Contract > Read/Write proxy > Click on the implementation address > Contract > ABI. After all that, you should end up [here](https://aeneid.storyscan.io/address/0x887c22833bf7F8E0E19F7d994fec964A82c030FB?tab=contract_abi).

2. Function Args - you can get these just by looking at the [code](https://github.com/storyprotocol/protocol-periphery-v1/blob/main/contracts/workflows/LicenseAttachmentWorkflows.sol#L130).

Great! Now let's build our transaction request.

```typescript  theme={null}
import { encodeFunctionData } from "viem";
import { Account, Address, privateKeyToAccount } from "viem/accounts";

const account: Account = privateKeyToAccount(
  `0x${process.env.WALLET_PRIVATE_KEY}` as Address
);

const transactionRequest = {
  to: "0xcC2E862bCee5B6036Db0de6E06Ae87e524a79fd8" as `0x${string}`,
  data: encodeFunctionData({
    abi: CONTRACT_ABI, // the abi you copied above
    functionName: "mintAndRegisterIpAndAttachPILTerms",
    args: [
      "0xc32A8a0FF3beDDDa58393d022aF433e78739FAbc", // example spg nft contract I use on Aeneid
      account.address,
      // example metadata values
      {
        ipMetadataURI:
          "https://ipfs.io/ipfs/bafkreiabrkevameeffdpjpizchywldogzai7kp5oodawbhgbojyeomk7uq",
        ipMetadataHash:
          "0x018a895030842946f4bd1911f1658dc6c811f53fae70c1609cc1727047315fa4",
        nftMetadataURI:
          "https://ipfs.io/ipfs/bafkreicbuti233kvewqs7uwb5y2toexj5gafgvsr5mqmnnx7cuof53gvsa",
        nftMetadataHash:
          "0x41a4d1aded5525a12fd2c1ee353712e9e980535651eb20c6b6ff151c5eecd590",
      },
      // example PIL terms
      [
        {
          terms: {
            transferable: true,
            royaltyPolicy: "0xBe54FB168b3c982b7AaE60dB6CF75Bd8447b390E",
            defaultMintingFee: 0n,
            expiration: 0n,
            commercialUse: true,
            commercialAttribution: true,
            commercializerChecker: "0x0000000000000000000000000000000000000000",
            commercializerCheckerData: "0x",
            commercialRevShare: 0,
            commercialRevCeiling: 0n,
            derivativesAllowed: true,
            derivativesAttribution: true,
            derivativesApproval: false,
            derivativesReciprocal: true,
            derivativeRevCeiling: 0n,
            currency: "0x1514000000000000000000000000000000000000",
            uri: "https://github.com/piplabs/pil-document/blob/ad67bb632a310d2557f8abcccd428e4c9c798db1/off-chain-terms/CommercialRemix.json",
          },
          licensingConfig: {
            mintingFee: 0n,
            isSet: false,
            disabled: false,
            commercialRevShare: 0,
            expectGroupRewardPool: "0x0000000000000000000000000000000000000000",
            expectMinimumGroupRewardShare: 0,
            licensingHook: "0x0000000000000000000000000000000000000000",
            hookData: "0x",
          },
        },
      ],
      true,
    ],
  }),
};
```

## Step 2: Send the transaction

At this point, we have the `data` and `to` needed for sending this transaction, for example if we were using [Crossmint](https://docs.crossmint.com/solutions/story-protocol/wallets/server-side-wallets#send-arbitrary-transaction).

However we could also then send this transaction ourselves:

```typescript  theme={null}
import { aeneid } from "@story-protocol/core-sdk";
import { createWalletClient, http, WalletClient } from "viem";

// other code here

const walletClient = createWalletClient({
  chain: aeneid,
  transport: http("https://aeneid.storyrpc.io"),
  account,
}) as WalletClient;

const txHash = await walletClient.sendTransaction({
  ...transactionRequest,
  account,
  chain: aeneid,
});

console.log(`Transaction sent: https://aeneid.storyscan.io/tx/${txHash}`);
```

## Done!

<CardGroup cols={2}>
  <Card title="Completed Code" href="https://github.com/storyprotocol/typescript-tutorial/blob/main/scripts/misc/sendRawTransaction.ts" icon="code">
    View the completed code for this tutorial.
  </Card>

  <Card title="Learn More" href="/developers/tutorials" icon="book-open">
    Explore more tutorials in our documentation
  </Card>
</CardGroup>
# Introduction

> Example section for showcasing API endpoints

Welcome to the Story API Reference! Please use the `https://api.storyapis.com` endpoint.

You can use the following public API key:

```http Headers theme={null}
// production
X-API-Key: MhBsxkU1z9fG6TofE59KqiiWV-YlYE8Q4awlLQehF3U

// staging (testnet)
X-API-Key: KOTbaGUSWQ6cUJWhiJYiOjPgB0kTRu1eCFFvQL0IWls
```

| Environment | Endpoint                                | Live Docs                                                                                                           | OpenAPI JSON                                                                                                                |
| ----------- | --------------------------------------- | ------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------- |
| Production  | `https://api.storyapis.com`             | <Icon icon="arrow-up-right-from-square" iconType="solid" /> [Go](https://api.storyapis.com/api/v4/docs)             | <Icon icon="arrow-up-right-from-square" iconType="solid" /> [Go](https://api.storyapis.com/api/v4/openapi.json)             |
| Staging     | `https://staging-api.storyprotocol.net` | <Icon icon="arrow-up-right-from-square" iconType="solid" /> [Go](https://staging-api.storyprotocol.net/api/v4/docs) | <Icon icon="arrow-up-right-from-square" iconType="solid" /> [Go](https://staging-api.storyprotocol.net/api/v4/openapi.json) |

## Rate Limit

The above public API key has a requests/second of 300. If you'd like an API key with a higher limit, please join our Builder Discord and describe your project needs in the discussion channel.
# Blockscout API

> Get gas price, average block time, market cap, token price, and more.

Storyscan has a public API endpoint that returns gas price, average block time, market cap, token price (coin gecko), and several other stats: `https://www.storyscan.io/api/v2/stats`

Here is an example response ⤵️

```json  theme={null}
{
  "average_block_time": 2364,
  "coin_image": "https://coin-images.coingecko.com/coins/images/54035/small/Transparent_bg.png?1738075331",
  "coin_price": "4.83",
  "coin_price_change_percentage": null,
  "gas_price_updated_at": "2025-03-10T14:47:27.175157Z",
  "gas_prices": {
    "slow": 0.1,
    "average": 0.57,
    "fast": 1.05
  },
  "gas_prices_update_in": 11735,
  "gas_used_today": "147032238744",
  "market_cap": "1209228486.984",
  "network_utilization_percentage": 10.8968948333333,
  "secondary_coin_image": null,
  "secondary_coin_price": null,
  "static_gas_price": null,
  "total_addresses": "686024",
  "total_blocks": "1765700",
  "total_gas_used": "0",
  "total_transactions": "5606580",
  "transactions_today": "221320",
  "tvl": null
}
```
# List IP Assets

> Retrieve a list of IP assets with pagination and filtering options. The 'where' field is optional and should only be provided when filtering by specific IP IDs, owner address, or token contract address. This endpoint can also be used to fetch a single asset by passing its ID in the ipIds filter.

## OpenAPI

````yaml https://api.storyapis.com/api/v4/openapi.json post /assets
paths:
  path: /assets
  method: post
  servers:
    - url: https://api.storyapis.com/api/v4
    - url: https://staging-api.storyprotocol.net/api/v4
    - url: http://localhost:8080/api/v4
      description: Local development server
  request:
    security:
      - title: ApiKeyAuth
        parameters:
          query: {}
          header:
            X-Api-Key:
              type: apiKey
          cookie: {}
    parameters:
      path: {}
      query: {}
      header: {}
      cookie: {}
    body:
      application/json:
        schemaArray:
          - type: object
            properties:
              includeLicenses:
                allOf:
                  - description: Include license information in response
                    examples:
                      - false
                    type: boolean
              moderated:
                allOf:
                  - description: Filter for moderated content only
                    examples:
                      - false
                    type: boolean
              orderBy:
                allOf:
                  - default: blockNumber
                    description: Field to order results by
                    enum:
                      - descendantCount
                      - blockNumber
                      - createdAt
                    type: string
              orderDirection:
                allOf:
                  - default: desc
                    description: Order direction for results
                    enum:
                      - asc
                      - desc
                    type: string
              pagination:
                allOf:
                  - $ref: '#/components/schemas/PaginationOptionsHuma'
                    description: Pagination configuration
              where:
                allOf:
                  - $ref: '#/components/schemas/IPAssetsWhereOptionsHuma'
                    description: Optional filter options for IP assets
            required: true
            refIdentifier: '#/components/schemas/IPAssetsRequestBodyHuma'
            additionalProperties: false
        examples:
          example:
            value:
              includeLicenses: false
              moderated: false
              orderBy: blockNumber
              orderDirection: desc
              pagination:
                limit: 20
                offset: 0
              where:
                ipIds:
                  - <string>
                ownerAddress: <string>
                tokenContract: <string>
  response:
    '200':
      application/json:
        schemaArray:
          - type: object
            properties:
              $schema:
                allOf:
                  - description: A URL to the JSON Schema for this object.
                    examples:
                      - >-
                        https://api.storyapis.com/api/v4/IPAssetsResponseHumaBody.json
                    format: uri
                    readOnly: true
                    type: string
              data:
                allOf:
                  - description: List of enriched IP assets
                    items:
                      $ref: '#/components/schemas/EnrichedIPAsset'
                    type:
                      - array
                      - 'null'
              pagination:
                allOf:
                  - $ref: '#/components/schemas/PaginationMetadataHuma'
                    description: Pagination metadata
            refIdentifier: '#/components/schemas/IPAssetsResponseHumaBody'
            requiredProperties:
              - data
            additionalProperties: false
        examples:
          example:
            value:
              $schema: https://api.storyapis.com/api/v4/IPAssetsResponseHumaBody.json
              data:
                - ancestorsCount: 123
                  blockNumber: 123
                  chainId: <string>
                  childrenCount: 123
                  createdAt: '2023-11-07T05:31:56Z'
                  descendantsCount: 123
                  description: <string>
                  infringementStatus:
                    - createdAt: '2023-11-07T05:31:56Z'
                      customData: <string>
                      infringementDetails: <string>
                      isInfringing: true
                      providerName: <string>
                      providerURL: <string>
                      responseTime: '2023-11-07T05:31:56Z'
                      status: <string>
                      updatedAt: '2023-11-07T05:31:56Z'
                  ipId: <string>
                  ipaMetadataUri: <string>
                  isInGroup: true
                  lastUpdatedAt: '2023-11-07T05:31:56Z'
                  licenses:
                    - createdAt: '2023-11-07T05:31:56Z'
                      licenseTemplateId: <string>
                      licenseTermsId: <string>
                      licensingConfig:
                        commercialRevShare: 123
                        disabled: true
                        expectGroupRewardPool: <string>
                        expectMinimumGroupRewardShare: 123
                        hookData: <string>
                        isSet: true
                        licensingHook: <string>
                        mintingFee: <string>
                      templateMetadataUri: <string>
                      templateName: <string>
                      terms:
                        commercialAttribution: true
                        commercialRevCeiling: <string>
                        commercialRevShare: 123
                        commercialUse: true
                        commercializerChecker: <string>
                        commercializerCheckerData: <string>
                        currency: <string>
                        defaultMintingFee: <string>
                        derivativeRevCeiling: <string>
                        derivativesAllowed: true
                        derivativesApproval: true
                        derivativesAttribution: true
                        derivativesReciprocal: true
                        expiration: <string>
                        royaltyPolicy: <string>
                        transferable: true
                        uri: <string>
                      updatedAt: '2023-11-07T05:31:56Z'
                  logIndex: 123
                  moderationStatus:
                    adult: <string>
                    medical: <string>
                    racy: <string>
                    spoof: <string>
                    violence: <string>
                  name: <string>
                  nftMetadata:
                    animation:
                      cachedUrl: <string>
                      contentType: <string>
                      originalUrl: <string>
                      size: 123
                    collection:
                      bannerImageUrl: <string>
                      externalUrl: <string>
                      name: <string>
                      slug: <string>
                    contract:
                      address: <string>
                      chain: <string>
                      contractDeployer: <string>
                      deployedBlockNumber: 123
                      name: <string>
                      openSeaMetadata:
                        bannerImageUrl: <string>
                        collectionName: <string>
                        collectionSlug: <string>
                        description: <string>
                        discordUrl: <string>
                        externalUrl: <string>
                        floorPrice: 123
                        imageUrl: <string>
                        lastIngestedAt: '2023-11-07T05:31:56Z'
                        safelistRequestStatus: <string>
                        twitterUsername: <string>
                      symbol: <string>
                      tokenType: <string>
                      totalSupply: <string>
                    contract_address: <string>
                    description: <string>
                    image:
                      cachedUrl: <string>
                      contentType: <string>
                      originalUrl: <string>
                      pngUrl: <string>
                      size: 123
                      thumbnailUrl: <string>
                    mint:
                      blockNumber: 123
                      mintAddress: <string>
                      timestamp: <string>
                      transactionHash: <string>
                    name: <string>
                    nft_id: <string>
                    raw: <any>
                    timeLastUpdated: '2023-11-07T05:31:56Z'
                    tokenId: <string>
                    tokenType: <string>
                    tokenUri: <string>
                  ownerAddress: <string>
                  parentsCount: 123
                  registrationDate: <string>
                  rootIPs:
                    - <string>
                  title: <string>
                  tokenContract: <string>
                  tokenId: <string>
                  txHash: <string>
                  uri: <string>
              pagination:
                hasMore: true
                limit: 123
                offset: 123
                total: 123
        description: OK
    default:
      application/problem+json:
        schemaArray:
          - type: object
            properties:
              $schema:
                allOf:
                  - description: A URL to the JSON Schema for this object.
                    examples:
                      - https://api.storyapis.com/api/v4/ErrorModel.json
                    format: uri
                    readOnly: true
                    type: string
              detail:
                allOf:
                  - description: >-
                      A human-readable explanation specific to this occurrence
                      of the problem.
                    examples:
                      - Property foo is required but is missing.
                    type: string
              errors:
                allOf:
                  - description: Optional list of individual error details
                    items:
                      $ref: '#/components/schemas/ErrorDetail'
                    type:
                      - array
                      - 'null'
              instance:
                allOf:
                  - description: >-
                      A URI reference that identifies the specific occurrence of
                      the problem.
                    examples:
                      - https://example.com/error-log/abc123
                    format: uri
                    type: string
              status:
                allOf:
                  - description: HTTP status code
                    examples:
                      - 400
                    format: int64
                    type: integer
              title:
                allOf:
                  - description: >-
                      A short, human-readable summary of the problem type. This
                      value should not change between occurrences of the error.
                    examples:
                      - Bad Request
                    type: string
              type:
                allOf:
                  - default: about:blank
                    description: >-
                      A URI reference to human-readable documentation for the
                      error.
                    examples:
                      - https://example.com/errors/example
                    format: uri
                    type: string
            refIdentifier: '#/components/schemas/ErrorModel'
            additionalProperties: false
        examples:
          example:
            value:
              $schema: https://api.storyapis.com/api/v4/ErrorModel.json
              detail: Property foo is required but is missing.
              errors:
                - location: <string>
                  message: <string>
                  value: <any>
              instance: https://example.com/error-log/abc123
              status: 400
              title: Bad Request
              type: https://example.com/errors/example
        description: Error
  deprecated: false
  type: path
components:
  schemas:
    ContractMetadata:
      additionalProperties: false
      properties:
        address:
          type: string
        chain:
          type: string
        contractDeployer:
          type: string
        deployedBlockNumber:
          format: int64
          type: integer
        name:
          type: string
        openSeaMetadata:
          $ref: '#/components/schemas/ContractMetadataOpenSeaMetadataStruct'
        symbol:
          type: string
        tokenType:
          type: string
        totalSupply:
          type: string
      required:
        - chain
        - address
        - name
        - symbol
        - totalSupply
        - tokenType
        - contractDeployer
        - deployedBlockNumber
        - openSeaMetadata
      type: object
    ContractMetadataOpenSeaMetadataStruct:
      additionalProperties: false
      properties:
        bannerImageUrl:
          type: string
        collectionName:
          type: string
        collectionSlug:
          type: string
        description:
          type: string
        discordUrl:
          type: string
        externalUrl:
          type:
            - string
            - 'null'
        floorPrice:
          format: double
          type: number
        imageUrl:
          type: string
        lastIngestedAt:
          format: date-time
          type: string
        safelistRequestStatus:
          type: string
        twitterUsername:
          type: string
      required:
        - floorPrice
        - collectionName
        - collectionSlug
        - safelistRequestStatus
        - imageUrl
        - description
        - externalUrl
        - twitterUsername
        - discordUrl
        - bannerImageUrl
        - lastIngestedAt
      type: object
    EnrichedIPAsset:
      additionalProperties: false
      properties:
        ancestorsCount:
          format: int64
          type: integer
        blockNumber:
          format: int64
          type: integer
        chainId:
          type: string
        childrenCount:
          format: int64
          type: integer
        createdAt:
          format: date-time
          type: string
        descendantsCount:
          format: int64
          type: integer
        description:
          type: string
        infringementStatus:
          items:
            $ref: '#/components/schemas/InfringementStatus'
          type:
            - array
            - 'null'
        ipId:
          type: string
        ipaMetadataUri:
          type: string
        isInGroup:
          type: boolean
        lastUpdatedAt:
          format: date-time
          type: string
        licenses:
          items:
            $ref: '#/components/schemas/License'
          type:
            - array
            - 'null'
        logIndex:
          format: int64
          type: integer
        moderationStatus:
          $ref: '#/components/schemas/ModerationStatus'
        name:
          type: string
        nftMetadata:
          $ref: '#/components/schemas/NFTMetadata'
        ownerAddress:
          type: string
        parentsCount:
          format: int64
          type: integer
        registrationDate:
          type: string
        rootIPs:
          items:
            type: string
          type:
            - array
            - 'null'
        title:
          type: string
        tokenContract:
          type: string
        tokenId:
          type: string
        txHash:
          type: string
        uri:
          type: string
      required:
        - rootIPs
        - ipId
        - ownerAddress
        - blockNumber
        - logIndex
        - txHash
        - chainId
        - tokenContract
        - tokenId
        - name
        - uri
        - registrationDate
        - lastUpdatedAt
        - createdAt
        - title
        - description
        - parentsCount
        - ancestorsCount
        - childrenCount
        - descendantsCount
        - isInGroup
      type: object
    ErrorDetail:
      additionalProperties: false
      properties:
        location:
          description: >-
            Where the error occurred, e.g. 'body.items[3].tags' or
            'path.thing-id'
          type: string
        message:
          description: Error message text
          type: string
        value:
          description: The value at the given location
      type: object
    IPAssetsWhereOptionsHuma:
      additionalProperties: false
      properties:
        ipIds:
          description: List of IP asset IDs to filter by (max 200)
          items:
            type: string
          maxItems: 200
          type:
            - array
            - 'null'
        ownerAddress:
          description: Owner wallet address to filter by
          pattern: ^0x[a-fA-F0-9]{40}$
          type: string
        tokenContract:
          description: Token contract address to filter by
          pattern: ^0x[a-fA-F0-9]{40}$
          type: string
      type: object
    InfringementStatus:
      additionalProperties: false
      properties:
        createdAt:
          format: date-time
          type: string
        customData:
          type: string
        infringementDetails:
          type: string
        isInfringing:
          type: boolean
        providerName:
          type: string
        providerURL:
          type: string
        responseTime:
          format: date-time
          type: string
        status:
          type: string
        updatedAt:
          format: date-time
          type: string
      required:
        - status
        - isInfringing
        - providerName
        - providerURL
        - infringementDetails
        - customData
        - responseTime
        - createdAt
        - updatedAt
      type: object
    License:
      additionalProperties: false
      properties:
        createdAt:
          format: date-time
          type: string
        licenseTemplateId:
          type: string
        licenseTermsId:
          type: string
        licensingConfig:
          $ref: '#/components/schemas/LicensingConfig'
        templateMetadataUri:
          type: string
        templateName:
          type: string
        terms:
          $ref: '#/components/schemas/LicenseTerms'
        updatedAt:
          format: date-time
          type: string
      required:
        - licenseTemplateId
        - licenseTermsId
        - templateName
        - templateMetadataUri
        - terms
        - licensingConfig
        - createdAt
        - updatedAt
      type: object
    LicenseTerms:
      additionalProperties: false
      properties:
        commercialAttribution:
          type: boolean
        commercialRevCeiling:
          type: string
        commercialRevShare:
          format: int64
          type: integer
        commercialUse:
          type: boolean
        commercializerChecker:
          type: string
        commercializerCheckerData:
          type: string
        currency:
          type: string
        defaultMintingFee:
          type: string
        derivativeRevCeiling:
          type: string
        derivativesAllowed:
          type: boolean
        derivativesApproval:
          type: boolean
        derivativesAttribution:
          type: boolean
        derivativesReciprocal:
          type: boolean
        expiration:
          type: string
        royaltyPolicy:
          type: string
        transferable:
          type: boolean
        uri:
          type: string
      required:
        - uri
        - currency
        - expiration
        - transferable
        - commercialUse
        - royaltyPolicy
        - defaultMintingFee
        - commercialRevShare
        - derivativesAllowed
        - derivativesApproval
        - commercialRevCeiling
        - derivativeRevCeiling
        - commercialAttribution
        - commercializerChecker
        - derivativesReciprocal
        - derivativesAttribution
        - commercializerCheckerData
      type: object
    LicensingConfig:
      additionalProperties: false
      properties:
        commercialRevShare:
          format: int64
          type: integer
        disabled:
          type: boolean
        expectGroupRewardPool:
          type: string
        expectMinimumGroupRewardShare:
          format: int64
          type: integer
        hookData:
          type: string
        isSet:
          type: boolean
        licensingHook:
          type: string
        mintingFee:
          type: string
      required:
        - isSet
        - disabled
        - hookData
        - mintingFee
        - licensingHook
        - commercialRevShare
        - expectGroupRewardPool
        - expectMinimumGroupRewardShare
      type: object
    ModerationStatus:
      additionalProperties: false
      properties:
        adult:
          type: string
        medical:
          type: string
        racy:
          type: string
        spoof:
          type: string
        violence:
          type: string
      required:
        - adult
        - spoof
        - medical
        - violence
        - racy
      type: object
    NFTMetadata:
      additionalProperties: false
      properties:
        animation:
          $ref: '#/components/schemas/NFTMetadataAnimationStruct'
        collection:
          $ref: '#/components/schemas/NFTMetadataCollectionStruct'
        contract:
          $ref: '#/components/schemas/ContractMetadata'
        contract_address:
          type: string
        description:
          type:
            - string
            - 'null'
        image:
          $ref: '#/components/schemas/NFTMetadataImageStruct'
        mint:
          $ref: '#/components/schemas/NFTMetadataMintStruct'
        name:
          type: string
        nft_id:
          type: string
        raw: {}
        timeLastUpdated:
          format: date-time
          type: string
        tokenId:
          type: string
        tokenType:
          type: string
        tokenUri:
          type: string
      required:
        - nft_id
        - contract_address
        - contract
        - tokenId
        - tokenType
        - name
        - description
        - tokenUri
        - image
        - animation
        - raw
        - collection
        - mint
        - timeLastUpdated
      type: object
    NFTMetadataAnimationStruct:
      additionalProperties: false
      properties:
        cachedUrl:
          type: string
        contentType:
          type: string
        originalUrl:
          type: string
        size:
          format: int64
          type: integer
      required:
        - cachedUrl
        - contentType
        - size
        - originalUrl
      type: object
    NFTMetadataCollectionStruct:
      additionalProperties: false
      properties:
        bannerImageUrl:
          type: string
        externalUrl:
          type:
            - string
            - 'null'
        name:
          type: string
        slug:
          type: string
      required:
        - name
        - slug
        - externalUrl
        - bannerImageUrl
      type: object
    NFTMetadataImageStruct:
      additionalProperties: false
      properties:
        cachedUrl:
          type: string
        contentType:
          type: string
        originalUrl:
          type: string
        pngUrl:
          type: string
        size:
          format: int64
          type: integer
        thumbnailUrl:
          type: string
      required:
        - cachedUrl
        - thumbnailUrl
        - pngUrl
        - contentType
        - size
        - originalUrl
      type: object
    NFTMetadataMintStruct:
      additionalProperties: false
      properties:
        blockNumber:
          format: int64
          type:
            - integer
            - 'null'
        mintAddress:
          type:
            - string
            - 'null'
        timestamp:
          type:
            - string
            - 'null'
        transactionHash:
          type:
            - string
            - 'null'
      required:
        - mintAddress
        - blockNumber
        - timestamp
        - transactionHash
      type: object
    PaginationMetadataHuma:
      additionalProperties: false
      properties:
        hasMore:
          description: Whether there are more items
          type: boolean
        limit:
          description: Current limit
          format: int64
          type: integer
        offset:
          description: Current offset
          format: int64
          type: integer
        total:
          description: Total count of items
          format: int64
          type: integer
      required:
        - offset
        - limit
        - total
        - hasMore
      type: object
    PaginationOptionsHuma:
      additionalProperties: false
      properties:
        limit:
          default: 20
          description: Number of items to return
          examples:
            - 20
          format: int64
          maximum: 200
          minimum: 1
          type: integer
        offset:
          default: 0
          description: Number of items to skip
          examples:
            - 0
          format: int64
          minimum: 0
          type: integer
      type: object

````
# List IP Asset Edges

> Retrieve a list of edges (derivative registered events) that represent relationships between IP assets. These edges show parent-child relationships formed through licensing.

## OpenAPI

````yaml https://api.storyapis.com/api/v4/openapi.json post /assets/edges
paths:
  path: /assets/edges
  method: post
  servers:
    - url: https://api.storyapis.com/api/v4
    - url: https://staging-api.storyprotocol.net/api/v4
    - url: http://localhost:8080/api/v4
      description: Local development server
  request:
    security:
      - title: ApiKeyAuth
        parameters:
          query: {}
          header:
            X-Api-Key:
              type: apiKey
          cookie: {}
    parameters:
      path: {}
      query: {}
      header: {}
      cookie: {}
    body:
      application/json:
        schemaArray:
          - type: object
            properties:
              orderBy:
                allOf:
                  - description: >-
                      Field to order results by (currently only blockNumber is
                      supported)
                    enum:
                      - blockNumber
                    type: string
              orderDirection:
                allOf:
                  - default: desc
                    description: Order direction for results
                    enum:
                      - asc
                      - desc
                    type: string
              pagination:
                allOf:
                  - $ref: '#/components/schemas/PaginationOptionsHuma'
                    description: Pagination configuration
              where:
                allOf:
                  - $ref: '#/components/schemas/EdgesWhereOptionsHuma'
                    description: Filter options for edges
            required: true
            refIdentifier: '#/components/schemas/EdgesRequestBodyHuma'
            additionalProperties: false
        examples:
          example:
            value:
              orderBy: blockNumber
              orderDirection: desc
              pagination:
                limit: 20
                offset: 0
              where:
                blockNumber: 1
                childIpId: <string>
                parentIpId: <string>
                txHash: <string>
  response:
    '200':
      application/json:
        schemaArray:
          - type: object
            properties:
              $schema:
                allOf:
                  - description: A URL to the JSON Schema for this object.
                    examples:
                      - >-
                        https://api.storyapis.com/api/v4/EdgesResponseHumaBody.json
                    format: uri
                    readOnly: true
                    type: string
              data:
                allOf:
                  - description: List of derivative registered events (edges)
                    items:
                      $ref: '#/components/schemas/DerivativeRegisteredEvent'
                    type:
                      - array
                      - 'null'
              pagination:
                allOf:
                  - $ref: '#/components/schemas/PaginationMetadataHuma'
                    description: Pagination metadata
            refIdentifier: '#/components/schemas/EdgesResponseHumaBody'
            requiredProperties:
              - data
            additionalProperties: false
        examples:
          example:
            value:
              $schema: https://api.storyapis.com/api/v4/EdgesResponseHumaBody.json
              data:
                - blockNumber: 123
                  blockTimestamp: '2023-11-07T05:31:56Z'
                  caller: <string>
                  childIpId: <string>
                  id: 123
                  licenseTemplate: <string>
                  licenseTermsId: <string>
                  licenseTokenId: <string>
                  logIndex: 123
                  parentIpId: <string>
                  processedAt: '2023-11-07T05:31:56Z'
                  txHash: <string>
              pagination:
                hasMore: true
                limit: 123
                offset: 123
                total: 123
        description: OK
    default:
      application/problem+json:
        schemaArray:
          - type: object
            properties:
              $schema:
                allOf:
                  - description: A URL to the JSON Schema for this object.
                    examples:
                      - https://api.storyapis.com/api/v4/ErrorModel.json
                    format: uri
                    readOnly: true
                    type: string
              detail:
                allOf:
                  - description: >-
                      A human-readable explanation specific to this occurrence
                      of the problem.
                    examples:
                      - Property foo is required but is missing.
                    type: string
              errors:
                allOf:
                  - description: Optional list of individual error details
                    items:
                      $ref: '#/components/schemas/ErrorDetail'
                    type:
                      - array
                      - 'null'
              instance:
                allOf:
                  - description: >-
                      A URI reference that identifies the specific occurrence of
                      the problem.
                    examples:
                      - https://example.com/error-log/abc123
                    format: uri
                    type: string
              status:
                allOf:
                  - description: HTTP status code
                    examples:
                      - 400
                    format: int64
                    type: integer
              title:
                allOf:
                  - description: >-
                      A short, human-readable summary of the problem type. This
                      value should not change between occurrences of the error.
                    examples:
                      - Bad Request
                    type: string
              type:
                allOf:
                  - default: about:blank
                    description: >-
                      A URI reference to human-readable documentation for the
                      error.
                    examples:
                      - https://example.com/errors/example
                    format: uri
                    type: string
            refIdentifier: '#/components/schemas/ErrorModel'
            additionalProperties: false
        examples:
          example:
            value:
              $schema: https://api.storyapis.com/api/v4/ErrorModel.json
              detail: Property foo is required but is missing.
              errors:
                - location: <string>
                  message: <string>
                  value: <any>
              instance: https://example.com/error-log/abc123
              status: 400
              title: Bad Request
              type: https://example.com/errors/example
        description: Error
  deprecated: false
  type: path
components:
  schemas:
    DerivativeRegisteredEvent:
      additionalProperties: false
      properties:
        blockNumber:
          format: int64
          type: integer
        blockTimestamp:
          format: date-time
          type: string
        caller:
          type: string
        childIpId:
          type: string
        id:
          format: int64
          type: integer
        licenseTemplate:
          type: string
        licenseTermsId:
          type: string
        licenseTokenId:
          type: string
        logIndex:
          format: int64
          type: integer
        parentIpId:
          type: string
        processedAt:
          format: date-time
          type: string
        txHash:
          type: string
      required:
        - id
        - blockNumber
        - blockTimestamp
        - txHash
        - logIndex
        - caller
        - childIpId
        - licenseTokenId
        - parentIpId
        - licenseTermsId
        - licenseTemplate
        - processedAt
      type: object
    EdgesWhereOptionsHuma:
      additionalProperties: false
      properties:
        blockNumber:
          description: Block number to filter by
          format: int64
          minimum: 0
          type: integer
        childIpId:
          description: Child IP ID to filter by
          pattern: ^0x[a-fA-F0-9]{40}$
          type: string
        parentIpId:
          description: Parent IP ID to filter by
          pattern: ^0x[a-fA-F0-9]{40}$
          type: string
        txHash:
          description: Transaction hash to filter by
          pattern: ^0x[a-fA-F0-9]{64}$
          type: string
      type: object
    ErrorDetail:
      additionalProperties: false
      properties:
        location:
          description: >-
            Where the error occurred, e.g. 'body.items[3].tags' or
            'path.thing-id'
          type: string
        message:
          description: Error message text
          type: string
        value:
          description: The value at the given location
      type: object
    PaginationMetadataHuma:
      additionalProperties: false
      properties:
        hasMore:
          description: Whether there are more items
          type: boolean
        limit:
          description: Current limit
          format: int64
          type: integer
        offset:
          description: Current offset
          format: int64
          type: integer
        total:
          description: Total count of items
          format: int64
          type: integer
      required:
        - offset
        - limit
        - total
        - hasMore
      type: object
    PaginationOptionsHuma:
      additionalProperties: false
      properties:
        limit:
          default: 20
          description: Number of items to return
          examples:
            - 20
          format: int64
          maximum: 200
          minimum: 1
          type: integer
        offset:
          default: 0
          description: Number of items to skip
          examples:
            - 0
          format: int64
          minimum: 0
          type: integer
      type: object

````
# List Collections

> Retrieve a list of collections with pagination and filtering options. Collections can be ordered by updatedAt, assetCount, or licensesCount (asc/desc). Collections are automatically enriched with metadata. The 'where' field is optional and should only be provided when filtering by specific collection addresses or asset counts. This endpoint can also be used to fetch a single collection by passing its address in the collectionAddresses filter. Collections that don't exist in Alchemy or encounter errors will return with empty metadata instead of failing the entire request.

## OpenAPI

````yaml https://api.storyapis.com/api/v4/openapi.json post /collections
paths:
  path: /collections
  method: post
  servers:
    - url: https://api.storyapis.com/api/v4
    - url: https://staging-api.storyprotocol.net/api/v4
    - url: http://localhost:8080/api/v4
      description: Local development server
  request:
    security:
      - title: ApiKeyAuth
        parameters:
          query: {}
          header:
            X-Api-Key:
              type: apiKey
          cookie: {}
    parameters:
      path: {}
      query: {}
      header: {}
      cookie: {}
    body:
      application/json:
        schemaArray:
          - type: object
            properties:
              orderBy:
                allOf:
                  - default: updatedAt
                    description: >-
                      Field to order results by: updatedAt, assetCount, or
                      licensesCount
                    enum:
                      - updatedAt
                      - assetCount
                      - licensesCount
                    type: string
              orderDirection:
                allOf:
                  - default: desc
                    description: >-
                      Order direction: asc for least recent, desc for most
                      recent
                    enum:
                      - asc
                      - desc
                    type: string
              pagination:
                allOf:
                  - $ref: '#/components/schemas/PaginationOptionsHuma'
                    description: Pagination configuration
              where:
                allOf:
                  - $ref: '#/components/schemas/CollectionsWhereOptionsHuma'
                    description: Optional filter options for collections
            required: true
            refIdentifier: '#/components/schemas/CollectionsRequestBodyHuma'
            additionalProperties: false
        examples:
          example:
            value:
              orderBy: updatedAt
              orderDirection: desc
              pagination:
                limit: 20
                offset: 0
              where:
                collectionAddresses:
                  - <string>
                maxAssetCount: 1
                minAssetCount: 1
  response:
    '200':
      application/json:
        schemaArray:
          - type: object
            properties:
              $schema:
                allOf:
                  - description: A URL to the JSON Schema for this object.
                    examples:
                      - >-
                        https://api.storyapis.com/api/v4/CollectionsResponseBodyHuma.json
                    format: uri
                    readOnly: true
                    type: string
              data:
                allOf:
                  - description: List of enriched collections
                    items:
                      $ref: '#/components/schemas/EnrichedCollection'
                    type:
                      - array
                      - 'null'
              pagination:
                allOf:
                  - $ref: '#/components/schemas/PaginationMetadataHuma'
                    description: Pagination metadata
            refIdentifier: '#/components/schemas/CollectionsResponseBodyHuma'
            requiredProperties:
              - data
            additionalProperties: false
        examples:
          example:
            value:
              $schema: >-
                https://api.storyapis.com/api/v4/CollectionsResponseBodyHuma.json
              data:
                - assetCount: 123
                  cancelledDisputeCount: 123
                  collectionAddress: <string>
                  collectionMetadata:
                    address: <string>
                    chain: <string>
                    contractDeployer: <string>
                    deployedBlockNumber: 123
                    name: <string>
                    openSeaMetadata:
                      bannerImageUrl: <string>
                      collectionName: <string>
                      collectionSlug: <string>
                      description: <string>
                      discordUrl: <string>
                      externalUrl: <string>
                      floorPrice: 123
                      imageUrl: <string>
                      lastIngestedAt: '2023-11-07T05:31:56Z'
                      safelistRequestStatus: <string>
                      twitterUsername: <string>
                    symbol: <string>
                    tokenType: <string>
                    totalSupply: <string>
                  createdAt: '2023-11-07T05:31:56Z'
                  judgedDisputeCount: 123
                  licensesCount: 123
                  raisedDisputeCount: 123
                  resolvedDisputeCount: 123
                  updatedAt: '2023-11-07T05:31:56Z'
              pagination:
                hasMore: true
                limit: 123
                offset: 123
                total: 123
        description: OK
    default:
      application/problem+json:
        schemaArray:
          - type: object
            properties:
              $schema:
                allOf:
                  - description: A URL to the JSON Schema for this object.
                    examples:
                      - https://api.storyapis.com/api/v4/ErrorModel.json
                    format: uri
                    readOnly: true
                    type: string
              detail:
                allOf:
                  - description: >-
                      A human-readable explanation specific to this occurrence
                      of the problem.
                    examples:
                      - Property foo is required but is missing.
                    type: string
              errors:
                allOf:
                  - description: Optional list of individual error details
                    items:
                      $ref: '#/components/schemas/ErrorDetail'
                    type:
                      - array
                      - 'null'
              instance:
                allOf:
                  - description: >-
                      A URI reference that identifies the specific occurrence of
                      the problem.
                    examples:
                      - https://example.com/error-log/abc123
                    format: uri
                    type: string
              status:
                allOf:
                  - description: HTTP status code
                    examples:
                      - 400
                    format: int64
                    type: integer
              title:
                allOf:
                  - description: >-
                      A short, human-readable summary of the problem type. This
                      value should not change between occurrences of the error.
                    examples:
                      - Bad Request
                    type: string
              type:
                allOf:
                  - default: about:blank
                    description: >-
                      A URI reference to human-readable documentation for the
                      error.
                    examples:
                      - https://example.com/errors/example
                    format: uri
                    type: string
            refIdentifier: '#/components/schemas/ErrorModel'
            additionalProperties: false
        examples:
          example:
            value:
              $schema: https://api.storyapis.com/api/v4/ErrorModel.json
              detail: Property foo is required but is missing.
              errors:
                - location: <string>
                  message: <string>
                  value: <any>
              instance: https://example.com/error-log/abc123
              status: 400
              title: Bad Request
              type: https://example.com/errors/example
        description: Error
  deprecated: false
  type: path
components:
  schemas:
    CollectionsWhereOptionsHuma:
      additionalProperties: false
      properties:
        collectionAddresses:
          description: List of collection addresses to filter by (max 200)
          items:
            type: string
          maxItems: 200
          type:
            - array
            - 'null'
        maxAssetCount:
          description: Maximum asset count threshold
          format: int64
          minimum: 0
          type: integer
        minAssetCount:
          description: Minimum asset count threshold
          format: int64
          minimum: 0
          type: integer
      type: object
    ContractMetadataByAddressResponse:
      additionalProperties: false
      properties:
        address:
          type: string
        chain:
          type: string
        contractDeployer:
          type: string
        deployedBlockNumber:
          format: int64
          type: integer
        name:
          type: string
        openSeaMetadata:
          $ref: >-
            #/components/schemas/ContractMetadataByAddressResponseOpenSeaMetadataStruct
        symbol:
          type: string
        tokenType:
          type: string
        totalSupply:
          type: string
      required:
        - chain
        - address
        - name
        - symbol
        - totalSupply
        - tokenType
        - contractDeployer
        - deployedBlockNumber
        - openSeaMetadata
      type: object
    ContractMetadataByAddressResponseOpenSeaMetadataStruct:
      additionalProperties: false
      properties:
        bannerImageUrl:
          type: string
        collectionName:
          type: string
        collectionSlug:
          type: string
        description:
          type: string
        discordUrl:
          type: string
        externalUrl:
          type:
            - string
            - 'null'
        floorPrice:
          format: double
          type: number
        imageUrl:
          type: string
        lastIngestedAt:
          format: date-time
          type: string
        safelistRequestStatus:
          type: string
        twitterUsername:
          type: string
      required:
        - floorPrice
        - collectionName
        - collectionSlug
        - safelistRequestStatus
        - imageUrl
        - description
        - externalUrl
        - twitterUsername
        - discordUrl
        - bannerImageUrl
        - lastIngestedAt
      type: object
    EnrichedCollection:
      additionalProperties: false
      properties:
        assetCount:
          format: int64
          type: integer
        cancelledDisputeCount:
          format: int64
          type: integer
        collectionAddress:
          type: string
        collectionMetadata:
          $ref: '#/components/schemas/ContractMetadataByAddressResponse'
        createdAt:
          format: date-time
          type: string
        judgedDisputeCount:
          format: int64
          type: integer
        licensesCount:
          format: int64
          type: integer
        raisedDisputeCount:
          format: int64
          type: integer
        resolvedDisputeCount:
          format: int64
          type: integer
        updatedAt:
          format: date-time
          type: string
      required:
        - collectionAddress
        - assetCount
        - licensesCount
        - resolvedDisputeCount
        - cancelledDisputeCount
        - raisedDisputeCount
        - judgedDisputeCount
        - updatedAt
        - createdAt
      type: object
    ErrorDetail:
      additionalProperties: false
      properties:
        location:
          description: >-
            Where the error occurred, e.g. 'body.items[3].tags' or
            'path.thing-id'
          type: string
        message:
          description: Error message text
          type: string
        value:
          description: The value at the given location
      type: object
    PaginationMetadataHuma:
      additionalProperties: false
      properties:
        hasMore:
          description: Whether there are more items
          type: boolean
        limit:
          description: Current limit
          format: int64
          type: integer
        offset:
          description: Current offset
          format: int64
          type: integer
        total:
          description: Total count of items
          format: int64
          type: integer
      required:
        - offset
        - limit
        - total
        - hasMore
      type: object
    PaginationOptionsHuma:
      additionalProperties: false
      properties:
        limit:
          default: 20
          description: Number of items to return
          examples:
            - 20
          format: int64
          maximum: 200
          minimum: 1
          type: integer
        offset:
          default: 0
          description: Number of items to skip
          examples:
            - 0
          format: int64
          minimum: 0
          type: integer
      type: object

````
# List Disputes

> Retrieve a paginated, filtered list of disputes from the SOS database. 
This endpoint supports various filtering options including:
- Filter by dispute ID, target IP ID, initiator address, or status
- Filter by block number ranges (blockNumber, blockNumberLte, blockNumberGte)
- Sort by block number, dispute timestamp, or ID
- Pagination with configurable limit and offset

Key v4 Enhancements:
- Flattened request structure: Query parameters are directly in the request body, not nested in an "options" object
- Offset-based pagination: Unlike v3, this endpoint supports both limit and offset parameters for flexible pagination
- Block number range filtering: Added blockNumberGte for greater-than-or-equal filtering (complements existing blockNumberLte)
- Pagination metadata in response: Returns total count and hasMore flag

The response format is aligned with v3 for compatibility, using big integers for numeric fields and hex strings for data fields.

## OpenAPI

````yaml https://api.storyapis.com/api/v4/openapi.json post /disputes
paths:
  path: /disputes
  method: post
  servers:
    - url: https://api.storyapis.com/api/v4
    - url: https://staging-api.storyprotocol.net/api/v4
    - url: http://localhost:8080/api/v4
      description: Local development server
  request:
    security:
      - title: ApiKeyAuth
        parameters:
          query: {}
          header:
            X-Api-Key:
              type: apiKey
          cookie: {}
    parameters:
      path: {}
      query: {}
      header: {}
      cookie: {}
    body:
      application/json:
        schemaArray:
          - type: object
            properties:
              orderBy:
                allOf:
                  - description: Field to order results by (must be blockNumber or empty)
                    type: string
              orderDirection:
                allOf:
                  - description: Order direction for results (asc or desc)
                    type: string
              pagination:
                allOf:
                  - $ref: '#/components/schemas/DisputePaginationHuma'
                    description: Pagination configuration
              where:
                allOf:
                  - $ref: '#/components/schemas/DisputeWhereHuma'
                    description: Filter options for disputes
            required: true
            refIdentifier: '#/components/schemas/DisputesRequestBodyHuma'
            additionalProperties: false
        examples:
          example:
            value:
              orderBy: <string>
              orderDirection: <string>
              pagination:
                limit: 100
                offset: 0
              where:
                blockNumber: '1500000'
                blockNumberGte: '1000000'
                blockNumberLte: '2000000'
                id: '123'
                initiator: '0xabcdef1234567890abcdef1234567890abcdef12'
                targetIpId: '0x1234567890abcdef1234567890abcdef12345678'
  response:
    '200':
      application/json:
        schemaArray:
          - type: object
            properties:
              $schema:
                allOf:
                  - description: A URL to the JSON Schema for this object.
                    examples:
                      - >-
                        https://api.storyapis.com/api/v4/ListDisputesResponseHumaBody.json
                    format: uri
                    readOnly: true
                    type: string
              data:
                allOf:
                  - description: List of disputes
                    items:
                      $ref: '#/components/schemas/Dispute'
                    type:
                      - array
                      - 'null'
              pagination:
                allOf:
                  - $ref: '#/components/schemas/DisputePaginationMetadataHuma'
                    description: Pagination metadata (v4 enhancement, not in v3)
            refIdentifier: '#/components/schemas/ListDisputesResponseHumaBody'
            requiredProperties:
              - data
            additionalProperties: false
        examples:
          example:
            value:
              $schema: >-
                https://api.storyapis.com/api/v4/ListDisputesResponseHumaBody.json
              data:
                - arbitrationPolicy: <string>
                  blockNumber: <string>
                  blockTimestamp: <string>
                  counterEvidenceHash: <string>
                  currentTag: <string>
                  data: <string>
                  deletedAt: <string>
                  disputeTimestamp: <string>
                  evidenceHash: <string>
                  id: <string>
                  initiator: <string>
                  liveness: <string>
                  logIndex: <string>
                  status: <string>
                  targetIpId: <string>
                  targetTag: <string>
                  transactionHash: <string>
                  umaLink: <string>
              pagination:
                hasMore: true
                limit: 123
                offset: 123
                total: 123
        description: OK
    default:
      application/problem+json:
        schemaArray:
          - type: object
            properties:
              $schema:
                allOf:
                  - description: A URL to the JSON Schema for this object.
                    examples:
                      - https://api.storyapis.com/api/v4/ErrorModel.json
                    format: uri
                    readOnly: true
                    type: string
              detail:
                allOf:
                  - description: >-
                      A human-readable explanation specific to this occurrence
                      of the problem.
                    examples:
                      - Property foo is required but is missing.
                    type: string
              errors:
                allOf:
                  - description: Optional list of individual error details
                    items:
                      $ref: '#/components/schemas/ErrorDetail'
                    type:
                      - array
                      - 'null'
              instance:
                allOf:
                  - description: >-
                      A URI reference that identifies the specific occurrence of
                      the problem.
                    examples:
                      - https://example.com/error-log/abc123
                    format: uri
                    type: string
              status:
                allOf:
                  - description: HTTP status code
                    examples:
                      - 400
                    format: int64
                    type: integer
              title:
                allOf:
                  - description: >-
                      A short, human-readable summary of the problem type. This
                      value should not change between occurrences of the error.
                    examples:
                      - Bad Request
                    type: string
              type:
                allOf:
                  - default: about:blank
                    description: >-
                      A URI reference to human-readable documentation for the
                      error.
                    examples:
                      - https://example.com/errors/example
                    format: uri
                    type: string
            refIdentifier: '#/components/schemas/ErrorModel'
            additionalProperties: false
        examples:
          example:
            value:
              $schema: https://api.storyapis.com/api/v4/ErrorModel.json
              detail: Property foo is required but is missing.
              errors:
                - location: <string>
                  message: <string>
                  value: <any>
              instance: https://example.com/error-log/abc123
              status: 400
              title: Bad Request
              type: https://example.com/errors/example
        description: Error
  deprecated: false
  type: path
components:
  schemas:
    Dispute:
      additionalProperties: false
      properties:
        arbitrationPolicy:
          type: string
        blockNumber:
          type:
            - string
            - 'null'
        blockTimestamp:
          type: string
        counterEvidenceHash:
          type: string
        currentTag:
          type: string
        data:
          type: string
        deletedAt:
          type: string
        disputeTimestamp:
          type:
            - string
            - 'null'
        evidenceHash:
          type: string
        id:
          type:
            - string
            - 'null'
        initiator:
          type: string
        liveness:
          type:
            - string
            - 'null'
        logIndex:
          type: string
        status:
          type: string
        targetIpId:
          type: string
        targetTag:
          type: string
        transactionHash:
          type: string
        umaLink:
          type: string
      required:
        - id
        - targetIpId
        - targetTag
        - currentTag
        - arbitrationPolicy
        - evidenceHash
        - initiator
        - data
        - blockNumber
        - disputeTimestamp
        - transactionHash
        - status
        - counterEvidenceHash
        - liveness
      type: object
    DisputePaginationHuma:
      additionalProperties: false
      properties:
        limit:
          default: 100
          description: 'Number of items to return (max: 200)'
          examples:
            - 100
          format: int64
          maximum: 200
          minimum: 1
          type: integer
        offset:
          default: 0
          description: Number of items to skip for pagination (v4 enhancement)
          examples:
            - 0
          format: int64
          minimum: 0
          type: integer
      type: object
    DisputePaginationMetadataHuma:
      additionalProperties: false
      properties:
        hasMore:
          description: Whether there are more disputes
          type: boolean
        limit:
          description: Current limit
          format: int64
          type: integer
        offset:
          description: Current offset
          format: int64
          type: integer
        total:
          description: Total count of disputes
          format: int64
          type: integer
      required:
        - offset
        - limit
        - hasMore
      type: object
    DisputeWhereHuma:
      additionalProperties: false
      properties:
        blockNumber:
          description: Filter by exact block number
          examples:
            - '1500000'
          pattern: ^[0-9]+$
          type: string
        blockNumberGte:
          description: Filter by block number >= this value (v4 enhancement)
          examples:
            - '1000000'
          pattern: ^[0-9]+$
          type: string
        blockNumberLte:
          description: Filter by block number <= this value
          examples:
            - '2000000'
          pattern: ^[0-9]+$
          type: string
        id:
          description: Dispute ID to filter by
          examples:
            - '123'
          pattern: ^[0-9]+$
          type: string
        initiator:
          description: Initiator wallet address to filter by
          examples:
            - '0xabcdef1234567890abcdef1234567890abcdef12'
          pattern: ^0x[a-fA-F0-9]{40}$
          type: string
        targetIpId:
          description: Target IP ID to filter by
          examples:
            - '0x1234567890abcdef1234567890abcdef12345678'
          pattern: ^0x[a-fA-F0-9]{40}$
          type: string
      type: object
    ErrorDetail:
      additionalProperties: false
      properties:
        location:
          description: >-
            Where the error occurred, e.g. 'body.items[3].tags' or
            'path.thing-id'
          type: string
        message:
          description: Error message text
          type: string
        value:
          description: The value at the given location
      type: object

````
# List IP Transactions

> Retrieve a list of IP transactions with pagination and filtering options. The ‘where’ field is optional and should only be provided when filtering by specific transaction hashes, event types, or block ranges. This endpoint can also be used to fetch specific transactions by passing their hashes in the txHashes filter.

## OpenAPI

````yaml https://api.storyapis.com/api/v4/openapi.json post /transactions
paths:
  path: /transactions
  method: post
  servers:
    - url: https://api.storyapis.com/api/v4
    - url: https://staging-api.storyprotocol.net/api/v4
    - url: http://localhost:8080/api/v4
      description: Local development server
  request:
    security:
      - title: ApiKeyAuth
        parameters:
          query: {}
          header:
            X-Api-Key:
              type: apiKey
          cookie: {}
    parameters:
      path: {}
      query: {}
      header: {}
      cookie: {}
    body:
      application/json:
        schemaArray:
          - type: object
            properties:
              orderBy:
                allOf:
                  - default: blockNumber
                    description: Field to order results by
                    enum:
                      - blockNumber
                      - createdAt
                      - eventType
                      - txHash
                      - ipId
                      - initiator
                    type: string
              orderDirection:
                allOf:
                  - default: desc
                    description: Order direction for results
                    enum:
                      - asc
                      - desc
                    type: string
              pagination:
                allOf:
                  - $ref: '#/components/schemas/PaginationOptionsHuma'
                    description: Pagination configuration
              where:
                allOf:
                  - $ref: '#/components/schemas/TransactionsWhereOptionsHuma'
                    description: Optional filter options for transactions
            required: true
            refIdentifier: '#/components/schemas/TransactionsRequestBodyHuma'
            additionalProperties: false
        examples:
          example:
            value:
              orderBy: blockNumber
              orderDirection: desc
              pagination:
                limit: 20
                offset: 0
              where:
                blockGte: 1
                blockLte: 1
                eventTypes:
                  - <string>
                initiators:
                  - <string>
                ipIds:
                  - <string>
                txHashes:
                  - <string>
  response:
    '200':
      application/json:
        schemaArray:
          - type: object
            properties:
              $schema:
                allOf:
                  - description: A URL to the JSON Schema for this object.
                    examples:
                      - >-
                        https://api.storyapis.com/api/v4/TransactionsResponseBodyHuma.json
                    format: uri
                    readOnly: true
                    type: string
              data:
                allOf:
                  - description: List of IP transactions
                    items:
                      $ref: '#/components/schemas/IPTransaction'
                    type:
                      - array
                      - 'null'
              pagination:
                allOf:
                  - $ref: '#/components/schemas/PaginationMetadataHuma'
                    description: Pagination information
            refIdentifier: '#/components/schemas/TransactionsResponseBodyHuma'
            requiredProperties:
              - data
            additionalProperties: false
        examples:
          example:
            value:
              $schema: >-
                https://api.storyapis.com/api/v4/TransactionsResponseBodyHuma.json
              data:
                - blockNumber: 123
                  createdAt: '2023-11-07T05:31:56Z'
                  eventType: <string>
                  id: 123
                  initiator: <string>
                  ipId: <string>
                  logIndex: 123
                  txHash: <string>
              pagination:
                hasMore: true
                limit: 123
                offset: 123
                total: 123
        description: OK
    default:
      application/problem+json:
        schemaArray:
          - type: object
            properties:
              $schema:
                allOf:
                  - description: A URL to the JSON Schema for this object.
                    examples:
                      - https://api.storyapis.com/api/v4/ErrorModel.json
                    format: uri
                    readOnly: true
                    type: string
              detail:
                allOf:
                  - description: >-
                      A human-readable explanation specific to this occurrence
                      of the problem.
                    examples:
                      - Property foo is required but is missing.
                    type: string
              errors:
                allOf:
                  - description: Optional list of individual error details
                    items:
                      $ref: '#/components/schemas/ErrorDetail'
                    type:
                      - array
                      - 'null'
              instance:
                allOf:
                  - description: >-
                      A URI reference that identifies the specific occurrence of
                      the problem.
                    examples:
                      - https://example.com/error-log/abc123
                    format: uri
                    type: string
              status:
                allOf:
                  - description: HTTP status code
                    examples:
                      - 400
                    format: int64
                    type: integer
              title:
                allOf:
                  - description: >-
                      A short, human-readable summary of the problem type. This
                      value should not change between occurrences of the error.
                    examples:
                      - Bad Request
                    type: string
              type:
                allOf:
                  - default: about:blank
                    description: >-
                      A URI reference to human-readable documentation for the
                      error.
                    examples:
                      - https://example.com/errors/example
                    format: uri
                    type: string
            refIdentifier: '#/components/schemas/ErrorModel'
            additionalProperties: false
        examples:
          example:
            value:
              $schema: https://api.storyapis.com/api/v4/ErrorModel.json
              detail: Property foo is required but is missing.
              errors:
                - location: <string>
                  message: <string>
                  value: <any>
              instance: https://example.com/error-log/abc123
              status: 400
              title: Bad Request
              type: https://example.com/errors/example
        description: Error
  deprecated: false
  type: path
components:
  schemas:
    ErrorDetail:
      additionalProperties: false
      properties:
        location:
          description: >-
            Where the error occurred, e.g. 'body.items[3].tags' or
            'path.thing-id'
          type: string
        message:
          description: Error message text
          type: string
        value:
          description: The value at the given location
      type: object
    IPTransaction:
      additionalProperties: false
      properties:
        blockNumber:
          format: int64
          type: integer
        createdAt:
          format: date-time
          type: string
        eventType:
          type: string
        id:
          format: int64
          type: integer
        initiator:
          type: string
        ipId:
          type: string
        logIndex:
          format: int64
          type: integer
        txHash:
          type: string
      required:
        - id
        - txHash
        - logIndex
        - blockNumber
        - eventType
        - ipId
        - initiator
        - createdAt
      type: object
    PaginationMetadataHuma:
      additionalProperties: false
      properties:
        hasMore:
          description: Whether there are more items
          type: boolean
        limit:
          description: Current limit
          format: int64
          type: integer
        offset:
          description: Current offset
          format: int64
          type: integer
        total:
          description: Total count of items
          format: int64
          type: integer
      required:
        - offset
        - limit
        - total
        - hasMore
      type: object
    PaginationOptionsHuma:
      additionalProperties: false
      properties:
        limit:
          default: 20
          description: Number of items to return
          examples:
            - 20
          format: int64
          maximum: 200
          minimum: 1
          type: integer
        offset:
          default: 0
          description: Number of items to skip
          examples:
            - 0
          format: int64
          minimum: 0
          type: integer
      type: object
    TransactionsWhereOptionsHuma:
      additionalProperties: false
      properties:
        blockGte:
          description: Filter transactions from this block number (inclusive)
          format: int64
          minimum: 0
          type: integer
        blockLte:
          description: Filter transactions up to this block number (inclusive)
          format: int64
          minimum: 0
          type: integer
        eventTypes:
          description: List of event types to filter by (max 50)
          items:
            type: string
          maxItems: 50
          type:
            - array
            - 'null'
        initiators:
          description: List of initiator addresses to filter by (max 200)
          items:
            type: string
          maxItems: 200
          type:
            - array
            - 'null'
        ipIds:
          description: List of IP asset IDs to filter by (max 200)
          items:
            type: string
          maxItems: 200
          type:
            - array
            - 'null'
        txHashes:
          description: List of transaction hashes to filter by (max 200)
          items:
            type: string
          maxItems: 200
          type:
            - array
            - 'null'
      type: object

````
# Search IP Assets

> Perform vector search for IP assets based on query text and optional media type filter. This endpoint uses AI-powered search to find relevant assets by semantic similarity.

## OpenAPI

````yaml https://api.storyapis.com/api/v4/openapi.json post /search
paths:
  path: /search
  method: post
  servers:
    - url: https://api.storyapis.com/api/v4
    - url: https://staging-api.storyprotocol.net/api/v4
    - url: http://localhost:8080/api/v4
      description: Local development server
  request:
    security:
      - title: ApiKeyAuth
        parameters:
          query: {}
          header:
            X-Api-Key:
              type: apiKey
          cookie: {}
    parameters:
      path: {}
      query: {}
      header: {}
      cookie: {}
    body:
      application/json:
        schemaArray:
          - type: object
            properties:
              mediaType:
                allOf:
                  - description: >-
                      Optional media type filter - must be 'audio', 'video', or
                      'image'. Leave empty to search all media types
                    enum:
                      - audio
                      - video
                      - image
                    examples:
                      - image
                    type: string
              pagination:
                allOf:
                  - $ref: '#/components/schemas/PaginationOptionsHuma'
                    description: Pagination configuration
              query:
                allOf:
                  - description: The search query string
                    examples:
                      - dragon NFT
                    maxLength: 1000
                    minLength: 1
                    type: string
            required: true
            refIdentifier: '#/components/schemas/SearchRequestBodyHuma'
            requiredProperties:
              - query
            additionalProperties: false
        examples:
          example:
            value:
              mediaType: image
              pagination:
                limit: 20
                offset: 0
              query: dragon NFT
  response:
    '200':
      application/json:
        schemaArray:
          - type: object
            properties:
              $schema:
                allOf:
                  - description: A URL to the JSON Schema for this object.
                    examples:
                      - >-
                        https://api.storyapis.com/api/v4/SearchResponseBodyHuma.json
                    format: uri
                    readOnly: true
                    type: string
              data:
                allOf:
                  - description: List of IP asset search results
                    items:
                      $ref: '#/components/schemas/IPSearchResult'
                    type:
                      - array
                      - 'null'
              pagination:
                allOf:
                  - $ref: '#/components/schemas/PaginationMetadataHuma'
                    description: Pagination information
              total:
                allOf:
                  - description: Total number of search results found
                    format: int64
                    type: integer
            refIdentifier: '#/components/schemas/SearchResponseBodyHuma'
            requiredProperties:
              - data
              - total
            additionalProperties: false
        examples:
          example:
            value:
              $schema: https://api.storyapis.com/api/v4/SearchResponseBodyHuma.json
              data:
                - description: <string>
                  ipId: <string>
                  mediaType: <string>
                  score: 123
                  similarity: 123
                  title: <string>
              pagination:
                hasMore: true
                limit: 123
                offset: 123
                total: 123
              total: 123
        description: OK
    default:
      application/problem+json:
        schemaArray:
          - type: object
            properties:
              $schema:
                allOf:
                  - description: A URL to the JSON Schema for this object.
                    examples:
                      - https://api.storyapis.com/api/v4/ErrorModel.json
                    format: uri
                    readOnly: true
                    type: string
              detail:
                allOf:
                  - description: >-
                      A human-readable explanation specific to this occurrence
                      of the problem.
                    examples:
                      - Property foo is required but is missing.
                    type: string
              errors:
                allOf:
                  - description: Optional list of individual error details
                    items:
                      $ref: '#/components/schemas/ErrorDetail'
                    type:
                      - array
                      - 'null'
              instance:
                allOf:
                  - description: >-
                      A URI reference that identifies the specific occurrence of
                      the problem.
                    examples:
                      - https://example.com/error-log/abc123
                    format: uri
                    type: string
              status:
                allOf:
                  - description: HTTP status code
                    examples:
                      - 400
                    format: int64
                    type: integer
              title:
                allOf:
                  - description: >-
                      A short, human-readable summary of the problem type. This
                      value should not change between occurrences of the error.
                    examples:
                      - Bad Request
                    type: string
              type:
                allOf:
                  - default: about:blank
                    description: >-
                      A URI reference to human-readable documentation for the
                      error.
                    examples:
                      - https://example.com/errors/example
                    format: uri
                    type: string
            refIdentifier: '#/components/schemas/ErrorModel'
            additionalProperties: false
        examples:
          example:
            value:
              $schema: https://api.storyapis.com/api/v4/ErrorModel.json
              detail: Property foo is required but is missing.
              errors:
                - location: <string>
                  message: <string>
                  value: <any>
              instance: https://example.com/error-log/abc123
              status: 400
              title: Bad Request
              type: https://example.com/errors/example
        description: Error
  deprecated: false
  type: path
components:
  schemas:
    ErrorDetail:
      additionalProperties: false
      properties:
        location:
          description: >-
            Where the error occurred, e.g. 'body.items[3].tags' or
            'path.thing-id'
          type: string
        message:
          description: Error message text
          type: string
        value:
          description: The value at the given location
      type: object
    IPSearchResult:
      additionalProperties: false
      properties:
        description:
          type: string
        ipId:
          type: string
        mediaType:
          type: string
        score:
          format: double
          type: number
        similarity:
          format: double
          type: number
        title:
          type: string
      required:
        - ipId
        - title
        - description
        - similarity
        - score
        - mediaType
      type: object
    PaginationMetadataHuma:
      additionalProperties: false
      properties:
        hasMore:
          description: Whether there are more items
          type: boolean
        limit:
          description: Current limit
          format: int64
          type: integer
        offset:
          description: Current offset
          format: int64
          type: integer
        total:
          description: Total count of items
          format: int64
          type: integer
      required:
        - offset
        - limit
        - total
        - hasMore
      type: object
    PaginationOptionsHuma:
      additionalProperties: false
      properties:
        limit:
          default: 20
          description: Number of items to return
          examples:
            - 20
          format: int64
          maximum: 200
          minimum: 1
          type: integer
        offset:
          default: 0
          description: Number of items to skip
          examples:
            - 0
          format: int64
          minimum: 0
          type: integer
      type: object

````
# SDK Reference Overview

> A detailed description of every function in our TypeScript SDK

This section provides a detailed description of every function in our TypeScript SDK.

| Package                                                        | Compatibility                               | Package                                                                                                 | GitHub                                                                                                             |                                 |
| -------------------------------------------------------------- | ------------------------------------------- | ------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------ | ------------------------------- |
| <Icon icon="screwdriver-wrench" iconType="solid" /> TypeScript | <Icon icon="check" iconType="solid" /> Full | <Icon icon="box-open" iconType="solid" /> [npm](https://www.npmjs.com/package/@story-protocol/core-sdk) | <Icon icon="arrow-up-right-from-square" iconType="solid" /> [Code](https://github.com/storyprotocol/sdk/tree/main) |                                 |
| <Icon icon="python" iconType="solid" /> Python                 | <Icon icon="check" iconType="solid" /> Full | <Icon icon="box-open" iconType="solid" /> [PyPi](https://pypi.org/project/story-protocol-python-sdk)    | <Icon icon="arrow-up-right-from-square" iconType="solid" /> [Code](https://github.com/storyprotocol/python-sdk)    | [SWITCH](/sdk-reference/python) |

***

<Card title="Step-by-Step Guide" icon="house" href="/developers/typescript-sdk">
  Learn our SDK through a series of tutorials with the TypeScript SDK Guide.
</Card>

## Licensing Module

<CardGroup cols={2}>
  <Card title="Register an IP Asset" icon="house" href="/sdk-reference/ipasset">
    Learn how to register an IP asset using the SDK.
  </Card>

  <Card title="Mint & Attach License Terms" icon="house" href="/sdk-reference/license">
    Learn how to mint and attach license terms using the SDK.
  </Card>
</CardGroup>

## Royalty Module

<CardGroup cols={2}>
  <Card title="Pay & Claim Royalty" icon="house" href="/sdk-reference/royalty">
    Learn how to pay and claim royalty using the SDK.
  </Card>
</CardGroup>

## Dispute Module

<CardGroup cols={2}>
  <Card title="Raise a Dispute" icon="house" href="/sdk-reference/dispute">
    Learn how to raise a dispute using the SDK.
  </Card>
</CardGroup>

## Grouping Module

<CardGroup cols={2}>
  <Card title="Manage Groups" icon="house" href="/sdk-reference/group">
    Learn how to manage groups using the SDK.
  </Card>
</CardGroup>

## Utility Clients

Additional utility and extra clients:

<CardGroup cols={2}>
  <Card title="Set Permissions" icon="house" href="/sdk-reference/permissions">
    Learn how to set permissions using the SDK.
  </Card>

  <Card title="NFT Client" icon="house" href="/sdk-reference/nftclient">
    Interact with SPG NFTs using the SDK.
  </Card>

  <Card title="WIP Client" icon="house" href="/sdk-reference/wip-client">
    Learn how to use the WIP client using the SDK.
  </Card>
</CardGroup>
# IP Asset

> IPAssetClient allows you to create, get, and list IP Assets within Story.

## IPAssetClient

### Methods

* registerIpAsset
* registerDerivativeIpAsset
* linkDerivative

### registerIpAsset

Register your IP as an [🧩 IP Asset](/concepts/ip-asset). It supports the following workflows:

1. Register an IP Asset
   1a. register an existing NFT as an IP Asset
   1b. mint a new NFT and register as an IP Asset
2. Attach license terms to the IP Asset
3. Distribute royalty tokens

<Note title="NFT Metadata">
  Note that this function will also set the underlying NFT's `tokenUri` to
  whatever is passed under `ipMetadata.nftMetadataURI`.
</Note>

| Method            | Type                                                                    |
| ----------------- | ----------------------------------------------------------------------- |
| `registerIpAsset` | `(request: RegisterIpAssetRequest) => Promise<RegisterIpAssetResponse>` |

Parameters:

* `request.nft`: You have two options here
  * `{ type: "minted", nftContract: Address, tokenId: number | bigint }`: Register an existing NFT as an IP Asset. This is typically the harder option because you need to already have an NFT minted.
  * `{ type: "mint", spgNftContract: Address, recipient?: Address, allowDuplicates?: boolean }`: Mint a new NFT and register as an IP Asset. This is typically the easier option because you don't need to worry about already having an NFT minted. Just create an spgNftContract, or use a default one, to mint for you.
* `request.licenseTermsData`: If you want to attach license terms.
  * `request.licenseTermsData.terms`: The [license terms](/concepts/programmable-ip-license/pil-terms) to attach to the IP Asset.
  * `request.licenseTermsData.licensingConfig`: The [licensing config](/concepts/licensing-module/license-config) to attach to the IP Asset.
  * `request.licenseTermsData.maxLicenseTokens`: The max number of license tokens that can be minted from this license term.
* `request.royaltyShares`: If you want to distribute royalty tokens out.
  * `request.royaltyShares.recipient`: The address of the recipient of the royalty shares.
  * `request.royaltyShares.percentage`: The percentage of the royalty shares.
* `request.ipMetadata`: The metadata of the IP Asset
  * `request.ipMetadata.ipMetadataURI`: The URI of the metadata for the IP.
  * `request.ipMetadata.ipMetadataHash`: The hash of the metadata for the IP.
  * `request.ipMetadata.nftMetadataURI`: The URI of the metadata for the NFT.
  * `request.ipMetadata.nftMetadataHash`: The hash of the metadata for the IP NFT.
* `request.deadline`: The deadline for the signature in milliseconds. **Defaults to 1000**.

<CodeGroup>
  ```typescript Example theme={null}
  import { PILFlavor, WIP_TOKEN_ADDRESS } from "@story-protocol/core-sdk";
  import { toHex } from "viem";

  // an example of an SPG NFT contract address
  // you can create one via `client.nftClient.createNFTCollection`
  const spgNftContract = "0xc32A8a0FF3beDDDa58393d022aF433e78739FAbc";

  const response = await client.ipAsset.registerIpAsset({
    nft: { type: "mint", spgNftContract: spgNftContract },
    licenseTermsData: [
      {
        terms: PILFlavor.creativeCommonsAttribution({
          currency: WIP_TOKEN_ADDRESS,
          // RoyaltyPolicyLAP address from https://docs.story.foundation/docs/deployed-smart-contracts
          royaltyPolicy: "0xBe54FB168b3c982b7AaE60dB6CF75Bd8447b390E",
        }),
      },
      {
        terms: PILFlavor.commercialRemix({
          defaultMintingFee: 10000n,
          commercialRevShare: 20, // 20%
          currency: WIP_TOKEN_ADDRESS,
          // RoyaltyPolicyLAP address from https://docs.story.foundation/docs/deployed-smart-contracts
          royaltyPolicy: "0xBe54FB168b3c982b7AaE60dB6CF75Bd8447b390E",
        }),
        maxLicenseTokens: 100,
      },
    ],
    royaltyShares: [
      {
        recipient: "0x123...",
        percentage: 10,
      },
    ],
    ipMetadata: {
      ipMetadataURI:
        "https://ipfs.io/ipfs/bafkreiardkgvkejqnnkdqp4pamkx2e5bs4lzus5trrw3hgmoa7dlbb6foe",
      ipMetadataHash: toHex("test-metadata-hash", { size: 32 }),
      nftMetadataURI:
        "https://ipfs.io/ipfs/bafkreicexrvs2fqvwblmgl3gnwiwh76pfycvfs66ck7w4s5omluyhti2kq",
      nftMetadataHash: toHex("test-nft-metadata-hash", { size: 32 }),
    },
  });

  console.log(
    `Root IPA created at transaction hash ${response.txHash}, IPA ID: ${response.ipId}`
  );
  ```

  ```typescript RegisterIpAssetRequest theme={null}
  export type RegisterRequest = {
    nft: MintedNFT | MintNFT;
    // attach license terms
    licenseTermsData?: LicenseTermsDataInput[];
    // sent royalty tokens out
    royaltyShares?: RoyaltyShare[];
    // add metadata
    ipMetadata?: {
      ipMetadataURI: string;
      ipMetadataHash: Hex;
      nftMetadataURI: string;
      nftMetadataHash: Hex;
    };
    deadline?: number | bigint;
  };

  type MintedNFT = {
    type: "minted";
    /** The address of the NFT contract. */
    nftContract: Address;
    tokenId: number | bigint;
  };

  type MintNFT = {
    type: "mint";
    /**
     * The address of the SPG NFT contract.
     * You can create one via `client.nftClient.createNFTCollection`.
     */
    spgNftContract: Address;
    /**
     * The address to receive the NFT.
     * Defaults to client's wallet address if not provided.
     */
    recipient?: Address;
    /**
     * Set to true to allow minting an NFT with a duplicate metadata hash.
     * @default true
     */
    allowDuplicates?: boolean;
  };

  type LicenseTermsDataInput = {
    terms: LicenseTerms;
    licensingConfig?: LicensingConfig;
    /**
     * The max number of license tokens that can be minted from this license term.
     *
     * - When not specified, there is no limit on license token minting
     * - When specified, minting is capped at this value and the TotalLicenseTokenLimitHook
     *   is automatically configured as the licensingConfig.licensingHook
     */
    maxLicenseTokens?: number | bigint;
  };

  type RoyaltyShare = {
    recipient: Address;
    /**
     * The percentage of the total royalty share. For example, a
     * value of 10 represents 10% of max royalty shares, which is 10,000,000.
     * @example 10
     */
    percentage: number | bigint;
  };
  ```

  ```typescript RegisterIpAssetResponse theme={null}
  export type RegisterIpResponse = {
    txHash?: Hex;
    // ipId of the newly registered IP Asset
    ipId: Address;
    // if license terms were attached
    licenseTermsIds?: bigint[];
    // other fields based on input
    // ...
  };
  ```
</CodeGroup>

### registerDerivativeIpAsset

Register an IP as a derivative of another IP Asset. This function allows you to use an existing license token to register as derivative, or it will mint one for you. To register an IP as a derivative, it must be an IP Asset itself. So this function allows you to register an existing NFT as an IP Asset (which will be the derivative), or mint a new NFT for you (and register it as a derivative).

| Method                      | Type                                                                              |
| --------------------------- | --------------------------------------------------------------------------------- |
| `registerDerivativeIpAsset` | `(request: RegisterDerivativeIpRequest) => Promise<RegisterDerivativeIpResponse>` |

Parameters:

* `request.nft`: You have two options here
  * `{ type: "minted", nftContract: Address, tokenId: number | bigint }`: Register an existing NFT as an IP Asset. This is typically the harder option because you need to already have an NFT minted.
  * `{ type: "mint", spgNftContract: Address, recipient?: Address, allowDuplicates?: boolean }`: Mint a new NFT and register as an IP Asset. This is typically the easier option because you don't need to worry about already having an NFT minted. Just create an spgNftContract, or use a default one, to mint for you.
* `request.licenseTokenIds`: If you want to use a license token to register as derivative.
* `request.derivData`: If you want to mint a license token for you.
  * `request.derivData.parentIpIds`: The IDs of the parent IPs to link the registered derivative IP.
  * `request.derivData.licenseTermsIds`: The IDs of the license terms to be used for the linking.
* `request.royaltyShares`: If you want to distribute royalty tokens out.
  * `request.royaltyShares.recipient`: The address of the recipient of the royalty shares.
  * `request.royaltyShares.percentage`: The percentage of the royalty shares.
* `request.maxRts`: The maximum number of royalty tokens that can be distributed to the external royalty policies. Must be between 0 and 100,000,000. **Recommended for simplicity: 100\_000\_000**
* `request.ipMetadata`: The metadata of the IP Asset
  * `request.ipMetadata.ipMetadataURI`: The URI of the metadata for the IP.
  * `request.ipMetadata.ipMetadataHash`: The hash of the metadata for the IP.
  * `request.ipMetadata.nftMetadataURI`: The URI of the metadata for the NFT.
  * `request.ipMetadata.nftMetadataHash`: The hash of the metadata for the IP NFT.
* `request.deadline`: The deadline for the signature in milliseconds. **Defaults to 1000**.

<CodeGroup>
  ```typescript Example theme={null}
  import { toHex } from "viem";

  // an example of an SPG NFT contract address
  // you can create one via `client.nftClient.createNFTCollection`
  const spgNftContract = "0xc32A8a0FF3beDDDa58393d022aF433e78739FAbc";

  // an example of a parent IP ID
  const parentIpId = "0x456...";

  // an example of a commercial remix license terms ID
  const commercialRemixLicenseTermsId = 5;

  const response = await client.ipAsset.registerDerivativeIpAsset({
    nft: { type: "mint", spgNftContract },
    derivData: {
      parentIpIds: [parentIpId],
      licenseTermsIds: [commercialRemixLicenseTermsId],
    },
    ipMetadata: {
      ipMetadataURI:
        "https://ipfs.io/ipfs/bafkreiardkgvkejqnnkdqp4pamkx2e5bs4lzus5trrw3hgmoa7dlbb6foe",
      ipMetadataHash: toHex("test-metadata-hash", { size: 32 }),
      nftMetadataURI:
        "https://ipfs.io/ipfs/bafkreicexrvs2fqvwblmgl3gnwiwh76pfycvfs66ck7w4s5omluyhti2kq",
      nftMetadataHash: toHex("test-nft-metadata-hash", { size: 32 }),
    },
    royaltyShares: [
      {
        recipient: "0x123...",
        percentage: 10,
      },
    ],
  });

  console.log(
    `Derivative IPA linked to parent at transaction hash ${response.txHash}`
  );
  ```

  ```typescript Request Type theme={null}
  export type RegisterDerivativeIpRequest = {
    nft: MintedNFT | MintNFT;
    /** The IDs of the license tokens to be burned for linking the IP to parent IPs.
     * Must be provided together with `maxRts`.
     */
    licenseTokenIds?: number[] | bigint[];
    /**
     * The derivative data containing parent IP information and licensing terms.
     * This will be used to mint a license token for you.
     * @remarks
     * This should not be provided if you are using a license token to register as derivative.
     * Because the license token is already minted.
     */
    derivData?: DerivativeDataInput;
    /**
     * Authors of the IP and their shares of the royalty tokens.
     *
     * @remarks
     * Royalty shares can only be specified if `derivData` is also provided.
     * This ensures that royalty distribution is always associated with derivative IP registration.
     * The shares define how royalty tokens will be distributed among IP authors.
     */
    royaltyShares?: RoyaltyShare[];
    ipMetadata?: {
      ipMetadataURI: string;
      ipMetadataHash: Hex;
      nftMetadataURI: string;
      nftMetadataHash: Hex;
    };
    /**
     * The maximum number of royalty tokens that can be distributed to the external royalty policies (max: 100,000,000).
     * Must be provided together with `licenseTokenIds`.
     * Just use 100_000_000 for simplicity.
     */
    maxRts?: number;
    /**
     * The deadline for the signature in seconds.
     * @default 1000
     */
    deadline?: number | bigint;
  };

  type MintedNFT = {
    type: "minted";
    /** The address of the NFT contract. */
    nftContract: Address;
    tokenId: number | bigint;
  };

  type MintNFT = {
    type: "mint";
    /**
     * The address of the SPG NFT contract.
     * You can create one via `client.nftClient.createNFTCollection`.
     */
    spgNftContract: Address;
    /**
     * The address to receive the NFT.
     * Defaults to client's wallet address if not provided.
     */
    recipient?: Address;
    /**
     * Set to true to allow minting an NFT with a duplicate metadata hash.
     * @default true
     */
    allowDuplicates?: boolean;
  };

  export type DerivativeDataInput = {
    parentIpIds: Address[];
    /** The IDs of the license terms that the parent IP supports. */
    licenseTermsIds: bigint[] | number[];
    /**
     * The maximum minting fee that the caller is willing to pay. if set to 0 then no limit.
     * @default 0
     */
    maxMintingFee?: bigint | number;
    /**
     *  The maximum number of royalty tokens that can be distributed to the external royalty policies (max: 100,000,000).
     * @default 100_000_000
     */
    maxRts?: number;
    /**
     * The maximum revenue share percentage allowed for minting the License Tokens. Must be between 0 and 100 (where 100% represents 100_000_000).
     * @default 100
     */
    maxRevenueShare?: number;
    /**
     * The address of the license template.
     * @default Defaults to https://docs.story.foundation/developers/deployed-smart-contracts
     * PILicenseTemplate address if not provided.
     */
    licenseTemplate?: Address;
  };

  type RoyaltyShare = {
    recipient: Address;
    /**
     * The percentage of the total royalty share. For example, a
     * value of 10 represents 10% of max royalty shares, which is 10,000,000.
     * @example 10
     */
    percentage: number | bigint;
  };
  ```

  ```typescript Response Type theme={null}
  export type RegisterDerivativeIpResponse = {
    txHash?: Hex;
    ipId?: Address;
  };
  ```
</CodeGroup>

### linkDerivative

Link an existing derivative IP to a parent IP.

| Method           | Type                                                                  |
| ---------------- | --------------------------------------------------------------------- |
| `linkDerivative` | `(request: LinkDerivativeRequest) => Promise<LinkDerivativeResponse>` |

Parameters:

<Tabs>
  <Tab title="Without License Tokens">
    * `request.childIpId`: The ID of the child IP.
    * `request.licenseTermIds`: The IDs of the license terms to be used for the linking.
    * `request.parentIpIds`: The IDs of the parent IPs.

    <CodeGroup>
      ```typescript TypeScript theme={null}
      const response = await client.ipAsset.linkDerivative({
        childIpId: "0xC92EC2f4c86458AFee7DD9EB5d8c57920BfCD0Ba",
        parentIpIds: ["0xC92EC2f4c86458AFee7DD9EB5d8c57920BfCD0Ba"],
        licenseTermsIds: [5],
      });

      console.log(
        `Derivative IPA linked to parent at transaction hash ${response.txHash}`
      );
      ```

      ```typescript Request Type theme={null}
      export type LinkDerivativeRequest = {
        parentIpIds: Address[];
        childIpId: Address;
        /** The IDs of the license terms that the parent IP supports. */
        licenseTermsIds: number[] | bigint[];
        /**
        * The maximum minting fee that the caller is willing to pay. if set to 0 then no limit.
        * @default 0
        */
        maxMintingFee?: bigint | number;
        /**
        *  The maximum number of royalty tokens that can be distributed to the external royalty policies (max: 100,000,000).
        * @default 100_000_000
        */
        maxRts?: number;
        /**
        * The maximum revenue share percentage allowed for minting the License Tokens. Must be between 0 and 100 (where 100% represents 100_000_000).
        * @default 100
        */
        maxRevenueShare?: number;
        /**
        * The address of the license template.
        * Defaults to {@link https://docs.story.foundation/docs/programmable-ip-license | License Template} address if not provided.
        */
        licenseTemplate?: Address;
      };
      ```

      ```typescript Response Type theme={null}
      export type LinkDerivativeResponse = {
        txHash?: Hex;
      };
      ```
    </CodeGroup>
  </Tab>

  <Tab title="With License Tokens">
    * `request.childIpId`: The ID of the child IP.
    * `request.licenseTokenIds`: The IDs of the license tokens to be used for the linking.

    <CodeGroup>
      ```typescript TypeScript theme={null}
      const response = await client.ipAsset.linkDerivative({
        childIpId: "0xC92EC2f4c86458AFee7DD9EB5d8c57920BfCD0Ba",
        licenseTokenIds: [1115],
      });

      console.log(
        `Derivative IPA linked to parent at transaction hash ${response.txHash}`
      );
      ```

      ```typescript Request Type theme={null}
      export type LinkDerivativeRequest = {
        /** The derivative IP ID. */
        childIpId: Address;
        /** The IDs of the license tokens. */
        licenseTokenIds: number[] | bigint[];
        /**
        * The maximum number of royalty tokens that can be distributed to the external royalty policies (max: 100,000,000).
        * @default 100_000_000
        */
        maxRts?: number;
      };
      ```

      ```typescript Response Type theme={null}
      export type LinkDerivativeResponse = {
        txHash?: Hex;
      };
      ```
    </CodeGroup>
  </Tab>
</Tabs>
# IP Account

> IPAccountClient allows you to manage IP Account metadata and execute transactions.

## IPAccountClient

### Methods

* setIpMetadata
* execute
* executeWithSig
* transferErc20

### setIpMetadata

Sets the metadataURI for an IP asset.

| Method          | Type                                    |
| --------------- | --------------------------------------- |
| `setIpMetadata` | `(SetIpMetadataRequest) => Promis<Hex>` |

Parameters:

* `request.ipId`: The IP to set the metadata for.
* `request.metadataURI`: The metadataURI to set for the IP asset. Should be a URL pointing to metadata that fits the [IPA Metadata Standard](/concepts/ip-asset/ipa-metadata-standard).
* `request.metadataHash`: The hash of metadata at metadataURI.

<CodeGroup>
  ```typescript TypeScript theme={null}
  const txHash = await client.ipAccount.setIpMetadata({
    ipId: "0x01",
    metadataURI:
      "https://ipfs.io/ipfs/bafkreiardkgvkejqnnkdqp4pamkx2e5bs4lzus5trrw3hgmoa7dlbb6foe",
    // example hash (not accurate)
    metadataHash:
      "0x129f7dd802200f096221dd89d5b086e4bd3ad6eafb378a0c75e3b04fc375f997",
  });
  ```

  ```typescript Request Type theme={null}
  export type SetIpMetadataRequest = {
    ipId: Address;
    metadataURI: string;
    metadataHash: Hex;
  };
  ```
</CodeGroup>

### execute

Executes a transaction from the IP Account.

| Method    | Type                                                            |
| --------- | --------------------------------------------------------------- |
| `execute` | `(IPAccountExecuteRequest) => Promis<IPAccountExecuteResponse>` |

Parameters:

* `request.ipId`: The Ip Id to get ip account.
* `request.to`: The recipient of the transaction.
* `request.value`: The amount of Ether to send.
* `request.data`: The data to send along with the transaction.

<CodeGroup>
  ```typescript Request Type theme={null}
  export type IPAccountExecuteRequest = {
    ipId: Address;
    to: Address;
    value: number;
    data: Hex;
  };
  ```

  ```typescript Response Type theme={null}
  export type IPAccountExecuteResponse = {
    txHash?: Hex;
    encodedTxData?: EncodedTxData;
  };
  ```
</CodeGroup>

### executeWithSig

Executes a transaction from the IP Account.

| Method           | Type                                                            |
| ---------------- | --------------------------------------------------------------- |
| `executeWithSig` | `(IPAccountExecuteRequest) => Promis<IPAccountExecuteResponse>` |

Parameters:

* `request.ipId`: The Ip Id to get ip account.
* `request.to`: The recipient of the transaction.
* `request.data`: The data to send along with the transaction.
* `request.signer`: The signer of the transaction.
* `request.deadline`: The deadline of the transaction signature.
* `request.signature`: The signature of the transaction, EIP-712 encoded.
* `request.value`: \[Optional] The amount of Ether to send.

<CodeGroup>
  ```typescript Request Type theme={null}
  export type IPAccountExecuteWithSigRequest = {
    ipId: Address;
    to: Address;
    data: Hex;
    signer: Address;
    deadline: number | bigint | string;
    signature: Address;
    value?: number | bigint | string;
  };
  ```

  ```typescript Response Type theme={null}
  export type IPAccountExecuteWithSigResponse = {
    txHash?: Hex;
    encodedTxData?: EncodedTxData;
  };
  ```
</CodeGroup>

### transferErc20

Transfers an ERC20 token from the IP Account.

| Method          | Type                                                              |
| --------------- | ----------------------------------------------------------------- |
| `transferErc20` | `(request: TransferErc20Request) => Promise<TransactionResponse>` |

Parameters:

* `request.ipId`: The `ipId` of the account
* `request.tokens`: The token info to transfer
  * `request.tokens.address`: The address of the ERC20 token including WIP and standard ERC20.
  * `request.tokens.amount`: The amount of tokens to transfer
  * `request.tokens.target`: The address of the recipient.

<CodeGroup>
  ```typescript Request Type theme={null}
  export type TransferErc20Request = {
    ipId: Address;
    tokens: {
      address: Address;
      amount: bigint | number;
      target: Address;
    }[];
  };
  ```

  ```typescript Response Type theme={null}
  export type TransactionResponse = {
    txHash: Hex;

    /** Transaction receipt, only available if waitForTransaction is set to true */
    receipt?: TransactionReceipt;
  };
  ```
</CodeGroup>
# License

> LicenseClient allows you to manage license terms and tokens within Story.

## LicenseClient

### Methods

* attachLicenseTerms
* mintLicenseTokens
* registerPILTerms
* registerPilTermsAndAttach
* registerNonComSocialRemixingPIL
* registerCommercialUsePIL
* registerCommercialRemixPIL
* registerCreativeCommonsAttributionPIL
* getLicenseTerms
* predictMintingLicenseFee
* setLicensingConfig
* getLicensingConfig
* setMaxLicenseTokens

### attachLicenseTerms

Attaches license terms to an IP.

| Method               | Type                                                                 |
| -------------------- | -------------------------------------------------------------------- |
| `attachLicenseTerms` | `(request: AttachLicenseTermsRequest) => AttachLicenseTermsResponse` |

Parameters:

* `request.ipId`: The address of the IP to which the license terms are attached.
* `request.licenseTermsId`: The ID of the license terms.
* `request.licenseTemplate`: \[Optional] The address of the license template.

<CodeGroup>
  ```typescript TypeScript theme={null}
  const response = await client.license.attachLicenseTerms({
    licenseTermsId: "1",
    ipId: "0x4c1f8c1035a8cE379dd4ed666758Fb29696CF721",
  });

  if (response.success) {
    console.log(
      `Attached License Terms to IPA at transaction hash ${response.txHash}.`
    );
  } else {
    console.log(`License Terms already attached to this IPA.`);
  }
  ```

  ```typescript Request Type theme={null}
  export type AttachLicenseTermsRequest = {
    ipId: Address;
    licenseTermsId: string | number | bigint;
    licenseTemplate?: Address;
  };
  ```

  ```typescript Response Type theme={null}
  export type AttachLicenseTermsResponse = {
    txHash?: Hex;
    encodedTxData?: EncodedTxData;
    success?: boolean;
  };
  ```
</CodeGroup>

### mintLicenseTokens

Mints [License Tokens](/concepts/licensing-module/license-token) that give permission to use the IP Asset based on [License Terms](/concepts/licensing-module/license-terms). The license tokens are minted to the `receiver`.

Note that a license token can only be minted if the `licenseTermsId` are already attached to the IP Asset, making it a publicly available license. The IP owner can, however, mint a [private license](/concepts/licensing-module/license-token#private-licenses) by minting a license token with a `licenseTermsId` that is not attached to the IP Asset.

<Warning>
  It might require the caller pay a minting fee, depending on the license terms or configured by the IP owner. The minting fee is paid in the minting fee token specified in the license terms or configured by the IP owner. IP owners can configure the minting fee of their IPs or configure the minting fee module to determine the minting fee.
</Warning>

<Frame>
  <img src="https://mintcdn.com/story/Ci-RgMKFKns3XzFq/images/concepts/private-licenses.png?fit=max&auto=format&n=Ci-RgMKFKns3XzFq&q=85&s=41fbeab6460274071950c739ed5cbd75" alt="A diagram showing how private licenses are minted." data-og-width="2026" width="2026" data-og-height="1312" height="1312" data-path="images/concepts/private-licenses.png" data-optimize="true" data-opv="3" srcset="https://mintcdn.com/story/Ci-RgMKFKns3XzFq/images/concepts/private-licenses.png?w=280&fit=max&auto=format&n=Ci-RgMKFKns3XzFq&q=85&s=1fa422cc2bad8e99538b4ffdfea2f63e 280w, https://mintcdn.com/story/Ci-RgMKFKns3XzFq/images/concepts/private-licenses.png?w=560&fit=max&auto=format&n=Ci-RgMKFKns3XzFq&q=85&s=7552e504d95a122ca4f9e0f407aa0772 560w, https://mintcdn.com/story/Ci-RgMKFKns3XzFq/images/concepts/private-licenses.png?w=840&fit=max&auto=format&n=Ci-RgMKFKns3XzFq&q=85&s=e25f1901e325363915ba86eb9556cbea 840w, https://mintcdn.com/story/Ci-RgMKFKns3XzFq/images/concepts/private-licenses.png?w=1100&fit=max&auto=format&n=Ci-RgMKFKns3XzFq&q=85&s=ed1215a3c2796c10031d11174ae4b44a 1100w, https://mintcdn.com/story/Ci-RgMKFKns3XzFq/images/concepts/private-licenses.png?w=1650&fit=max&auto=format&n=Ci-RgMKFKns3XzFq&q=85&s=56686f5f20b862ef9d992e692b8e73e7 1650w, https://mintcdn.com/story/Ci-RgMKFKns3XzFq/images/concepts/private-licenses.png?w=2500&fit=max&auto=format&n=Ci-RgMKFKns3XzFq&q=85&s=f139e240fec93390df8a1373b736f348 2500w" />
</Frame>

| Method              | Type                                                                        |
| ------------------- | --------------------------------------------------------------------------- |
| `mintLicenseTokens` | `(request: MintLicenseTokensRequest) => Promise<MintLicenseTokensResponse>` |

Parameters:

* `request.licensorIpId`: The licensor IP ID.
* `request.licenseTermsId`: The ID of the license terms within the license template.
* `request.maxMintingFee`: The maximum minting fee to be paid when minting a license.
* `request.maxRevenueShare`: The maximum revenue share to be paid when minting a license.
* `request.amount`: \[Optional] The amount of license tokens to mint.
* `request.receiver`: \[Optional] The address of the receiver.
* `request.licenseTemplate`: \[Optional] The address of the license template.

<CodeGroup>
  ```typescript TypeScript theme={null}
  const response = await client.license.mintLicenseTokens({
    licenseTermsId: "1",
    licensorIpId: "0xC92EC2f4c86458AFee7DD9EB5d8c57920BfCD0Ba",
    receiver: "0x14dC79964da2C08b23698B3D3cc7Ca32193d9955", // optional
    amount: 1,
    maxMintingFee: BigInt(0), // disabled
    maxRevenueShare: 100, // default
  });

  console.log(
    `License Token minted at transaction hash ${response.txHash}, License IDs: ${response.licenseTokenIds}`
  );
  ```

  ```typescript Request Type theme={null}
  export type MintLicenseTokensRequest = {
    licensorIpId: Address;
    licenseTermsId: string | number | bigint;
    licenseTemplate?: Address;
    maxMintingFee: bigint | string | number;
    maxRevenueShare: number | string;
    amount?: number | string | bigint;
    receiver?: Address;
  } & WithWipOptions;
  ```

  ```typescript Response Type theme={null}
  export type MintLicenseTokensResponse = {
    licenseTokenIds?: bigint[];
    receipt?: TransactionReceipt;
    txHash?: Hex;
    encodedTxData?: EncodedTxData;
  };
  ```
</CodeGroup>

### registerPILTerms

Registers new license terms and return the ID of the newly registered license terms.

| Method             | Type                                                                 |
| ------------------ | -------------------------------------------------------------------- |
| `registerPILTerms` | `(request: RegisterPILTermsRequest) => Promise<RegisterPILResponse>` |

Parameters:

* Expected Parameters: Instead of listing all of the expected parameters here, please see `LicenseTerms` type in [this](https://github.com/storyprotocol/sdk/blob/main/packages/core-sdk/src/types/resources/license.ts) file. They all come from the [PIL Terms](/concepts/programmable-ip-license/pil-terms).

<CodeGroup>
  ```typescript TypeScript theme={null}
  import {
    LicenseTerms,
    PILFlavor,
    WIP_TOKEN_ADDRESS,
  } from "@story-protocol/core-sdk";
  import { zeroAddress, parseEther } from "viem";

  // OPTION 1. If you want to specify all the terms

  const licenseTerms: LicenseTerms = {
    transferable: false,
    royaltyPolicy: "0xBe54FB168b3c982b7AaE60dB6CF75Bd8447b390E", // RoyaltyPolicyLAP address from https://docs.story.foundation/docs/deployed-smart-contracts
    defaultMintingFee: 0n,
    expiration: 0n,
    commercialUse: false,
    commercialAttribution: false,
    commercializerChecker: zeroAddress,
    commercializerCheckerData: "0x",
    commercialRevShare: 10, // 10%
    commercialRevCeiling: 0n,
    derivativesAllowed: true,
    derivativesAttribution: false,
    derivativesApproval: false,
    derivativesReciprocal: false,
    derivativeRevCeiling: 0n,
    currency: "0x1514000000000000000000000000000000000000", // $WIP address from https://docs.story.foundation/docs/deployed-smart-contracts
    uri: "",
  };

  const response = await client.license.registerPILTerms({
    ...licenseTerms,
  });

  console.log(
    `PIL Terms registered at transaction hash ${response.txHash}, License Terms ID: ${response.licenseTermsId}`
  );

  // OPTION 2. If you want to use a PIL flavor for convenience

  const response = await client.license.registerPILTerms(
    PILFlavor.commercialRemix({
      commercialRevShare: 5,
      defaultMintingFee: parseEther("1"), // 1 $IP
      currency: WIP_TOKEN_ADDRESS,
    })
  );

  console.log(
    `PIL Terms registered at transaction hash ${response.txHash}, License Terms ID: ${response.licenseTermsId}`
  );
  ```

  ```typescript Request Type theme={null}
  export type RegisterPILTermsRequest = Omit<
    LicenseTerms,
    | "defaultMintingFee"
    | "expiration"
    | "commercialRevCeiling"
    | "derivativeRevCeiling"
  > & {
    defaultMintingFee: bigint | string | number;
    expiration: bigint | string | number;
    commercialRevCeiling: bigint | string | number;
    derivativeRevCeiling: bigint | string | number;
  };

  export type LicenseTerms = {
    /*Indicates whether the license is transferable or not.*/
    transferable: boolean;
    /*The address of the royalty policy contract which required to StoryProtocol in advance.*/
    royaltyPolicy: Address;
    /*The default minting fee to be paid when minting a license.*/
    defaultMintingFee: bigint;
    /*The expiration period of the license.*/
    expiration: bigint;
    /*Indicates whether the work can be used commercially or not.*/
    commercialUse: boolean;
    /*Whether attribution is required when reproducing the work commercially or not.*/
    commercialAttribution: boolean;
    /*Commercializers that are allowed to commercially exploit the work. If zero address, then no restrictions is enforced.*/
    commercializerChecker: Address;
    /*The data to be passed to the commercializer checker contract.*/
    commercializerCheckerData: Address;
    /**Percentage of revenue that must be shared with the licensor. Must be from 0-100.*/
    commercialRevShare: number;
    /*The maximum revenue that can be generated from the commercial use of the work.*/
    commercialRevCeiling: bigint;
    /*Indicates whether the licensee can create derivatives of his work or not.*/
    derivativesAllowed: boolean;
    /*Indicates whether attribution is required for derivatives of the work or not.*/
    derivativesAttribution: boolean;
    /*Indicates whether the licensor must approve derivatives of the work before they can be linked to the licensor IP ID or not.*/
    derivativesApproval: boolean;
    /*Indicates whether the licensee must license derivatives of the work under the same terms or not.*/
    derivativesReciprocal: boolean;
    /*The maximum revenue that can be generated from the derivative use of the work.*/
    derivativeRevCeiling: bigint;
    /*The ERC20 token to be used to pay the minting fee. the token must be registered in story protocol.*/
    currency: Address;
    /*The URI of the license terms, which can be used to fetch the offchain license terms.*/
    uri: string;
  };
  ```

  ```typescript Response Type theme={null}
  export type RegisterPILResponse = {
    licenseTermsId?: bigint;
    txHash?: Hex;
    encodedTxData?: EncodedTxData;
  };
  ```
</CodeGroup>

### registerPilTermsAndAttach

Register Programmable IP License Terms (if unregistered) and attach it to IP.

| Method                      | Type                                                                                        |
| --------------------------- | ------------------------------------------------------------------------------------------- |
| `registerPilTermsAndAttach` | `(request: RegisterPilTermsAndAttachRequest) => Promise<RegisterPilTermsAndAttachResponse>` |

Parameters:

* `request.ipId`: The ID of the IP.
* `request.licenseTermsData[]`: The array of license terms to be attached.
  * `request.licenseTermsData.terms`: See the [LicenseTerms type](https://github.com/storyprotocol/sdk/blob/main/packages/core-sdk/src/types/resources/license.ts#L26).
  * `request.licenseTermsData.licensingConfig`: \[Optional] See the [LicensingConfig type](https://github.com/storyprotocol/sdk/blob/main/packages/core-sdk/src/types/common.ts#L15). If none provided, it will default to the one shown [here](https://github.com/storyprotocol/sdk/blob/main/packages/core-sdk/src/utils/validateLicenseConfig.ts).
* `request.deadline`: \[Optional] The deadline for the signature in milliseconds. **Defaults to 1000**.

<CodeGroup>
  ```typescript TypeScript theme={null}
  import { PILFlavor, WIP_TOKEN_ADDRESS } from "@story-protocol/core-sdk";
  import { parseEther } from "viem";

  const response = await client.license.registerPilTermsAndAttach({
    ipId: "0x4c1f8c1035a8cE379dd4ed666758Fb29696CF721",
    licenseTermsData: [
      {
        terms: PILFlavor.commercialRemix({
          commercialRevShare: 5,
          defaultMintingFee: parseEther("1"), // 1 $IP
          currency: WIP_TOKEN_ADDRESS,
        }),
      },
    ],
  });
  console.log(`License Terms ${response.licenseTermsId} attached to IP Asset.`);
  ```

  ```typescript Request Type theme={null}
  export type RegisterPilTermsAndAttachRequest = {
    ipId: Address;
    licenseTermsData: LicenseTermsData<
      RegisterPILTermsRequest,
      LicensingConfig
    >[];
    deadline?: string | number | bigint;
  };
  ```

  ```typescript Response Type theme={null}
  export type RegisterPilTermsAndAttachResponse = {
    txHash?: Hex;
    encodedTxData?: EncodedTxData;
    licenseTermsIds?: bigint[];
  };
  ```
</CodeGroup>

### registerNonComSocialRemixingPIL

Convenient function to register a PIL non commercial social remix license to the registry.

<Warning>
  No reason to call this function. Non-Commercial Social Remixing terms are already registered with `licenseTermdId = 1` in our protocol. There's no reason to register them again.
</Warning>

| Method                            | Type                                                                                 |
| --------------------------------- | ------------------------------------------------------------------------------------ |
| `registerNonComSocialRemixingPIL` | `(request?: RegisterNonComSocialRemixingPILRequest) => Promise<RegisterPILResponse>` |

Parameters:

<CodeGroup>
  ```typescript TypeScript theme={null}
  const response = await client.license.registerNonComSocialRemixingPIL({});

  console.log(
    `PIL Terms registered at transaction hash ${response.txHash}, License Terms ID: ${response.licenseTermsId}`
  );
  ```

  ```typescript Request Type theme={null}
  export type RegisterNonComSocialRemixingPILRequest = {};
  ```

  ```typescript Response Type theme={null}
  export type RegisterPILResponse = {
    licenseTermsId?: bigint;
    txHash?: Hex;
    encodedTxData?: EncodedTxData;
  };
  ```
</CodeGroup>

### registerCommercialUsePIL

Convenient function to register a PIL commercial use license to the registry.

| Method                     | Type                                                                         |
| -------------------------- | ---------------------------------------------------------------------------- |
| `registerCommercialUsePIL` | `(request: RegisterCommercialUsePILRequest) => Promise<RegisterPILResponse>` |

Parameters:

* `request.defaultMintingFee`: The fee to be paid when minting a license.
* `request.currency`: The ERC20 token to be used to pay the minting fee and the token must be registered on Story's protocol.
* `request.royaltyPolicyAddress`: \[Optional] The address of the royalty policy contract, default value is LAP.

<CodeGroup>
  ```typescript TypeScript theme={null}
  import { parseEther } from "viem";

  const commercialUseParams = {
    currency: "0x1514000000000000000000000000000000000000", // $WIP address from https://docs.story.foundation/docs/deployed-smart-contracts
    defaultMintingFee: parseEther("1"), // 1 $WIP
    royaltyPolicyAddress: "0xBe54FB168b3c982b7AaE60dB6CF75Bd8447b390E", // RoyaltyPolicyLAP address from https://docs.story.foundation/docs/deployed-smart-contracts
  };

  const response = await client.license.registerCommercialUsePIL({
    ...commercialUseParams,
  });

  console.log(
    `PIL Terms registered at transaction hash ${response.txHash}, License Terms ID: ${response.licenseTermsId}`
  );
  ```

  ```typescript Request Type theme={null}
  export type RegisterCommercialUsePILRequest = {
    defaultMintingFee: string | number | bigint;
    currency: Address;
    royaltyPolicyAddress?: Address;
  };
  ```

  ```typescript Response Type theme={null}
  export type RegisterPILResponse = {
    licenseTermsId?: bigint;
    txHash?: Hex;
    encodedTxData?: EncodedTxData;
  };
  ```
</CodeGroup>

### registerCommercialRemixPIL

Convenient function to register a PIL commercial Remix license to the registry.

| Method                       | Type                                                                           |
| ---------------------------- | ------------------------------------------------------------------------------ |
| `registerCommercialRemixPIL` | `(request: RegisterCommercialRemixPILRequest) => Promise<RegisterPILResponse>` |

Parameters:

* `request.defaultMintingFee`: The fee to be paid when minting a license.
* `request.commercialRevShare`: Percentage of revenue that must be shared with the licensor.
* `request.currency`: The ERC20 token to be used to pay the minting fee and the token must be registered on Story's protocol.
* `request.royaltyPolicyAddress`: \[Optional] The address of the royalty policy contract, default value is LAP.

<CodeGroup>
  ```typescript TypeScript theme={null}
  import { parseEther } from "viem";

  const commercialRemixParams = {
    currency: "0x1514000000000000000000000000000000000000", // $WIP address from https://docs.story.foundation/docs/deployed-smart-contracts
    defaultMintingFee: parseEther("1"), // 1 $WIP
    royaltyPolicyAddress: "0xBe54FB168b3c982b7AaE60dB6CF75Bd8447b390E", // RoyaltyPolicyLAP address from https://docs.story.foundation/docs/deployed-smart-contracts
    commercialRevShare: 10, // 10%
  };

  const response = await client.license.registerCommercialRemixPIL({
    ...commercialRemixParams,
  });

  console.log(
    `PIL Terms registered at transaction hash ${response.txHash}, License Terms ID: ${response.licenseTermsId}`
  );
  ```

  ```typescript Request Type theme={null}
  export type RegisterCommercialRemixPILRequest = {
    defaultMintingFee: string | number | bigint;
    commercialRevShare: number;
    currency: Address;
    royaltyPolicyAddress?: Address;
  };
  ```

  ```typescript Response Type theme={null}
  export type RegisterPILResponse = {
    licenseTermsId?: bigint;
    txHash?: Hex;
    encodedTxData?: EncodedTxData;
  };
  ```
</CodeGroup>

### registerCreativeCommonsAttributionPIL

Convenient function to register a PIL creative commons attribution license to the registry.

| Method                                  | Type                                                                                      |
| --------------------------------------- | ----------------------------------------------------------------------------------------- |
| `registerCreativeCommonsAttributionPIL` | `(request: RegisterCreativeCommonsAttributionPILRequest) => Promise<RegisterPILResponse>` |

Parameters:

* `request.currency`: The ERC20 token to be used to pay the minting fee and the token must be registered on Story's protocol.
* `request.royaltyPolicyAddress`: \[Optional] The address of the royalty policy contract, default value is LAP.

<CodeGroup>
  ```typescript TypeScript theme={null}
  const response = await client.license.registerCreativeCommonsAttributionPIL({
    currency: "0x1514000000000000000000000000000000000000", // $WIP address from https://docs.story.foundation/docs/deployed-smart-contracts
    royaltyPolicyAddress: "0xBe54FB168b3c982b7AaE60dB6CF75Bd8447b390E", // RoyaltyPolicyLAP address from https://docs.story.foundation/docs/deployed-smart-contracts
  });

  console.log(
    `PIL Terms registered at transaction hash ${response.txHash}, License Terms ID: ${response.licenseTermsId}`
  );
  ```

  ```typescript Request Type theme={null}
  export type RegisterCreativeCommonsAttributionPILRequest = {
    currency: Address;
    royaltyPolicyAddress?: Address;
  };
  ```

  ```typescript Response Type theme={null}
  export type RegisterPILResponse = {
    licenseTermsId?: bigint;
    txHash?: Hex;
    encodedTxData?: EncodedTxData;
  };
  ```
</CodeGroup>

### getLicenseTerms

Gets License Terms of the given ID.

| Method            | Type                                                                                               |
| :---------------- | :------------------------------------------------------------------------------------------------- |
| `getLicenseTerms` | `(selectedLicenseTermsId: string \| number \| bigint) => PiLicenseTemplateGetLicenseTermsResponse` |

Parameters:

* `selectedLicenseTermsId`: The ID of the license terms.

```typescript Response Type theme={null}
export type PiLicenseTemplateGetLicenseTermsResponse = {
  terms: {
    transferable: boolean;
    royaltyPolicy: Address;
    defaultMintingFee: bigint;
    expiration: bigint;
    commercialUse: boolean;
    commercialAttribution: boolean;
    commercializerChecker: Address;
    commercializerCheckerData: Hex;
    commercialRevShare: number;
    commercialRevCeiling: bigint;
    derivativesAllowed: boolean;
    derivativesAttribution: boolean;
    derivativesApproval: boolean;
    derivativesReciprocal: boolean;
    derivativeRevCeiling: bigint;
    currency: Address;
    uri: string;
  };
};
```

### predictMintingLicenseFee

Pre-compute the minting license fee for the given IP and license terms. The function can be used to calculate the minting license fee before minting license tokens.

| Method                     | Type                                                                                            |
| -------------------------- | ----------------------------------------------------------------------------------------------- |
| `predictMintingLicenseFee` | `(request: PredictMintingLicenseFeeRequest) => LicensingModulePredictMintingLicenseFeeResponse` |

Parameters:

* `request.licensorIpId`: The IP ID of the licensor.
* `request.licenseTermsId`: The ID of the license terms.
* `request.amount`: The amount of license tokens to mint.
* `request.licenseTemplate`: \[Optional] The address of the license template, default value is Programmable IP License.
* `request.receiver`: \[Optional] The address of the receiver, default value is your wallet address.

```typescript Response Type theme={null}
export type LicensingModulePredictMintingLicenseFeeResponse = {
  currencyToken: Address;
  tokenAmount: bigint;
};
```

### setLicensingConfig

Sets the licensing configuration for a specific license terms of an IP.

| Method               | Type                                                                 |
| -------------------- | -------------------------------------------------------------------- |
| `setLicensingConfig` | `(request: SetLicensingConfigRequest) => SetLicensingConfigResponse` |

Parameters:

* `request.ipId`: The address of the IP for which the configuration is being set.
* `request.licenseTermsId`: The ID of the license terms within the license template.
* `request.licenseTemplate`: \[Optional] The address of the license template used, If not specified, the configuration applies to all licenses.
* `request.licensingConfig`: The licensing configuration for the license.
  * `request.licensingConfig.isSet`: Whether the configuration is set or not.
  * `request.licensingConfig.mintingFee`: The minting fee to be paid when minting license tokens.
  * `request.licensingConfig.hookData`: The data to be used by the licensing hook.
  * `request.licensingConfig.licensingHook`: The hook contract address for the licensing module, or address(0) if none.
  * `request.licensingConfig.commercialRevShare`: The commercial revenue share percentage (from 0 to 100).
  * `request.licensingConfig.disabled`: Whether the licensing is disabled or not. If this is true, then no licenses can be minted and no more derivatives can be attached at all.
  * `request.licensingConfig.expectMinimumGroupRewardShare`: The minimum percentage of the group's reward share (from 0 to 100).
  * `request.licensingConfig.expectGroupRewardPool`: The address of the expected group reward pool. The IP can only be added to a group with this specified reward pool address, or zero address if the IP does not want to be added to any group.

<CodeGroup>
  ```typescript TypeScript theme={null}
  import { parseEther, zeroAddress } from "viem";

  const response = await client.license.setLicensingConfig({
    ipId: "0x4c1f8c1035a8cE379dd4ed666758Fb29696CF721",
    licenseTermsId: 1,
    licensingConfig: {
      isSet: true,
      mintingFee: parseEther("1"),
      licensingHook: "0xaBAD364Bfa41230272b08f171E0Ca939bD600478",
      hookData: "0x",
      commercialRevShare: 10,
      disabled: false,
      expectMinimumGroupRewardShare: 0,
      expectGroupRewardPool: zeroAddress,
    },
  });
  ```

  ```typescript Request Type theme={null}
  export type SetLicensingConfigRequest = GetLicensingConfigRequest & {
    /** The licensing configuration for the license. */
    licensingConfig: LicensingConfigInput;
  };

  export type GetLicensingConfigRequest = {
    /** The address of the IP for which the configuration is being set. */
    ipId: Address;
    /** The ID of the license terms within the license template. */
    licenseTermsId: number | bigint;
    /**
     * The address of the license template.
     * Defaults to {@link https://docs.story.foundation/docs/programmable-ip-license | PIL} address if not provided.
     */
    licenseTemplate?: Address;
  };

  export type LicensingConfigInput = {
    /** Whether the licensing configuration is active. If false, the configuration is ignored. */
    isSet: boolean;
    /** The minting fee to be paid when minting license tokens. */
    mintingFee: bigint | string | number;
    /**
     * The licensingHook is an address to a smart contract that implements the `ILicensingHook` interface.
     * This contract's `beforeMintLicenseTokens` function is executed before a user mints a License Token,
     * allowing for custom validation or business logic to be enforced during the minting process.
     * For detailed documentation on licensing hook, visit {@link https://docs.story.foundation/concepts/hooks#licensing-hooks}
     */
    licensingHook: Address;
    /**
     * The data to be used by the licensing hook.
     * Set to a zero hash if no data is provided.
     */
    hookData: Hex;
    /** The commercial revenue share percentage (from 0 to 100%, represented as 100_000_000). */
    commercialRevShare: number | string;
    /** Whether the licensing is disabled or not. If this is true, then no licenses can be minted and no more derivatives can be attached at all. */
    disabled: boolean;
    /** The minimum percentage of the group’s reward share (from 0 to 100%, represented as 100_000_000) that can be allocated to the IP when it is added to the group. */
    expectMinimumGroupRewardShare: number | string;
    /** The address of the expected group reward pool. The IP can only be added to a group with this specified reward pool address, or zero address if the IP does not want to be added to any group. */
    expectGroupRewardPool: Address;
  };
  ```

  ```typescript Response Type theme={null}
  export type SetLicensingConfigResponse = {
    txHash?: Hex;
    encodedTxData?: EncodedTxData;
    success?: boolean;
  };
  ```
</CodeGroup>

### getLicensingConfig

Gets the licensing configuration for a specific license terms of an IP.

| Method               | Type                                                      |
| -------------------- | --------------------------------------------------------- |
| `getLicensingConfig` | `(request: GetLicensingConfigRequest) => LicensingConfig` |

Parameters:

* `request.ipId`: The address of the IP for which the configuration is being fetched.
* `request.licenseTermsId`: The ID of the license terms within the license template.
* `request.licenseTemplate`: \[Optional] The address of the license template used.

<CodeGroup>
  ```typescript TypeScript theme={null}
  const licensingConfig = await client.license.getLicensingConfig({
    ipId: "0x4c1f8c1035a8cE379dd4ed666758Fb29696CF721",
    licenseTermsId: 1,
  });
  ```

  ```typescript Request Type theme={null}
  export type GetLicensingConfigRequest = {
    /** The address of the IP for which the configuration is being set. */
    ipId: Address;
    /** The ID of the license terms within the license template. */
    licenseTermsId: number | bigint;
    /**
     * The address of the license template.
     * Defaults to {@link https://docs.story.foundation/docs/programmable-ip-license | PIL} address if not provided.
     */
    licenseTemplate?: Address;
  };
  ```

  ```typescript Response Type theme={null}
  export type LicensingConfig = {
    /** Whether the licensing configuration is active. If false, the configuration is ignored. */
    isSet: boolean;
    /** The minting fee to be paid when minting license tokens. */
    mintingFee: bigint;
    /**
     * The licensingHook is an address to a smart contract that implements the `ILicensingHook` interface.
     * This contract's `beforeMintLicenseTokens` function is executed before a user mints a License Token,
     * allowing for custom validation or business logic to be enforced during the minting process.
     * For detailed documentation on licensing hook, visit {@link https://docs.story.foundation/concepts/hooks#licensing-hooks}
     */
    licensingHook: Address;
    /**
     * The data to be used by the licensing hook.
     * Set to a zero hash if no data is provided.
     */
    hookData: Hex;
    /** The commercial revenue share percentage (from 0 to 100%, represented as 100_000_000). */
    commercialRevShare: number;
    /** Whether the licensing is disabled or not. If this is true, then no licenses can be minted and no more derivatives can be attached at all. */
    disabled: boolean;
    /** The minimum percentage of the group's reward share (from 0 to 100%, represented as 100_000_000) that can be allocated to the IP when it is added to the group. */
    expectMinimumGroupRewardShare: number;
    /** The address of the expected group reward pool. The IP can only be added to a group with this specified reward pool address, or zero address if the IP does not want to be added to any group. */
    expectGroupRewardPool: Address;
  };
  ```
</CodeGroup>

### setMaxLicenseTokens

Set the max license token limit for a specific license.

This method automatically configures the licensing hook to use the [TotalLicenseTokenLimitHook](https://github.com/storyprotocol/protocol-periphery-v1/blob/release/1.3/contracts/hooks/TotalLicenseTokenLimitHook.sol) contract if the current licensing hook is not set to `TotalLicenseTokenLimitHook`, and sets the max license tokens to the specified limit.

| Method                | Type                                                                    |
| --------------------- | ----------------------------------------------------------------------- |
| `setMaxLicenseTokens` | `(request: SetMaxLicenseTokensRequest) => Promise<TransactionResponse>` |

Parameters:

* `request.ipId`: The address of the IP for which the configuration is being set.
* `request.licenseTermsId`: The ID of the license terms within the license template.
* `request.maxLicenseTokens`: The total license token limit, 0 means no limit.
* `request.licenseTemplate`: \[Optional] The address of the license template used.

<CodeGroup>
  ```typescript TypeScript theme={null}
  const response = await client.license.setMaxLicenseTokens({
    ipId: "0x4c1f8c1035a8cE379dd4ed666758Fb29696CF721",
    licenseTermsId: 1,
    maxLicenseTokens: 1000,
  });

  console.log(`Max license tokens set at transaction hash ${response.txHash}`);
  ```

  ```typescript Request Type theme={null}
  export type SetMaxLicenseTokensRequest = GetLicensingConfigRequest & {
    /** The total license token limit, 0 means no limit */
    maxLicenseTokens: bigint | number;
  };

  export type GetLicensingConfigRequest = {
    /** The address of the IP for which the configuration is being set. */
    ipId: Address;
    /** The ID of the license terms within the license template. */
    licenseTermsId: number | bigint;
    /**
     * The address of the license template.
     * Defaults to {@link https://docs.story.foundation/docs/programmable-ip-license | PIL} address if not provided.
     */
    licenseTemplate?: Address;
  };
  ```

  ```typescript Response Type theme={null}
  export type TransactionResponse = {
    txHash?: Hex;
    encodedTxData?: EncodedTxData;
    success?: boolean;
  };
  ```
</CodeGroup>
# Dispute

> DisputeClient allows you to manage disputes within Story.

## DisputeClient

### Methods

* raiseDispute
* cancelDispute
* resolveDispute
* tagIfRelatedIpInfringed
* disputeAssertion
* disputeIdToAssertionId

### raiseDispute

Raises a dispute on a given ipId

| Method         | Type                                                              |
| -------------- | ----------------------------------------------------------------- |
| `raiseDispute` | `(request: RaiseDisputeRequest) => Promise<RaiseDisputeResponse>` |

Parameters:

* `request.targetIpId`: The IP ID that is the target of the dispute.
* `request.targetTag`: The target tag of the dispute. See [dispute tags](https://docs.story.foundation/docs/dispute-module#dispute-tags). **Example: "IMPROPER\_REGISTRATION"**
* `request.cid`: Content Identifier (CID) for the dispute evidence. This should be obtained by uploading your dispute evidence (documents, images, etc.) to IPFS. **Example: "QmX4zdp8VpzqvtKuEqMo6gfZPdoUx9TeHXCgzKLcFfSUbk"**
* `request.liveness`: The liveness is the time window (in seconds) in which a counter dispute can be presented (30days).
* `request.bond`: \[Optional] **If not specified, it defaults to the minimum bond value**. The amount of wrapper IP that the dispute initiator pays upfront into a pool. To counter that dispute the opposite party of the dispute has to place a bond of the same amount. The winner of the dispute gets the original bond back + 50% of the other party bond. The remaining 50% of the loser party bond goes to the reviewer.

<Note>
  UMA will be adjusting the minimum \$IP bond size as the IP price fluctuates.
  The correct way to obtain the current minimum bond size is via
  `getMinimumBond()` on `OptimisticOracleV3.sol` (OOV3), found on our [aeneid
  testnet](https://aeneid.storyscan.io/address/0xABac6a158431edED06EE6cba37eDE8779F599eE4?tab=read_write_contract#0x4360af3d)
  and
  [mainnet](https://www.storyscan.io/address/0x8EF424F90C6BC1b98153A09c0Cac5072545793e8?tab=read_write_contract#0x4360af3d).
</Note>

* `request.wipOptions`: \[Optional]
  * `request.wipOptions.enableAutoWrapIp`: \[Optional]By default IP is converted to WIP if the current WIP balance does not cover the fees. Set this to `false` to disable this behavior. **Default: true**
  * `request.wipOptions.enableAutoApprove`: \[Optional]Automatically approve WIP usage when WIP is needed but current allowance is not sufficient. Set this to `false` to disable this behavior. **Default: true**

<CodeGroup>
  ```typescript TypeScript theme={null}
  import { parseEther } from "viem";
  import { DisputeTargetTag } from "@story-protocol/core-sdk";

  const response = await client.dispute.raiseDispute({
    targetIpId: "0xC92EC2f4c86458AFee7DD9EB5d8c57920BfCD0Ba",
    // NOTE: you must use your own CID here, because every time it is used,
    // the protocol does not allow you to use it again
    cid: "QmbWqxBEKC3P8tqsKc98xmWNzrzDtRLMiMPL8wBuTGsMnR",
    // you must pick from one of the whitelisted tags here:
    // https://docs.story.foundation/docs/dispute-module#dispute-tags
    targetTag: DisputeTargetTag.IMPROPER_REGISTRATION,
    bond: parseEther("0.1"), // minimum of 0.1
    liveness: 2592000,
  });
  console.log(
    `Dispute raised at transaction hash ${disputeResponse.txHash}, Dispute ID: ${disputeResponse.disputeId}`
  );
  ```

  ```typescript Request Type theme={null}
  export type RaiseDisputeRequest = {
    targetIpId: Address;
    cid: string;
    targetTag: DisputeTargetTag;
    liveness: bigint | number | string;
    bond?: bigint | number | string;
    wipOptions?: {
      enableAutoWrapIp?: boolean;
      enableAutoApprove?: boolean;
    };
  };

  export enum DisputeTargetTag {
    /** Refers to registration of IP that already exists. */
    IMPROPER_REGISTRATION = "IMPROPER_REGISTRATION",
    /**
     * Refers to improper use of an IP Asset across multiple items.
     * For more details, @see {@link https://docs.story.foundation/concepts/programmable-ip-license/overview | Programmable IP License (PIL)} documentation.
     */
    IMPROPER_USAGE = "IMPROPER_USAGE",
    /** Refers to missing payments associated with an IP. */
    IMPROPER_PAYMENT = "IMPROPER_PAYMENT",
    /**
     * Refers to “No-Hate”, “Suitable-for-All-Ages”, “No-Drugs-or-Weapons” and “No-Pornography”.
     * These items can be found in more detail in the {@link https://docs.story.foundation/concepts/programmable-ip-license/overview  | 💊 Programmable IP License (PIL) } legal document.
     */
    CONTENT_STANDARDS_VIOLATION = "CONTENT_STANDARDS_VIOLATION",
    /**
     * Different from the other 4, this is a temporary tag that goes away
     * at the end of a dispute and is replaced by “0x” in case of no infringement or is replaced by one of the other tags.
     */
    IN_DISPUTE = "IN_DISPUTE",
  }
  ```

  ```typescript Response Type theme={null}
  export type RaiseDisputeResponse = {
    txHash?: Hex;
    encodedTxData?: EncodedTxData;
    disputeId?: bigint;
  };
  ```
</CodeGroup>

### cancelDispute

Cancels an ongoing dispute

| Method          | Type                                                                |
| --------------- | ------------------------------------------------------------------- |
| `cancelDispute` | `(request: CancelDisputeRequest) => Promise<CancelDisputeResponse>` |

Parameters:

* `request.disputeId`: The ID of the dispute to be cancelled.
* `request.data`: \[Optional] Additional data used in the cancellation process. **Defaults to "0x"**.

<CodeGroup>
  ```typescript  theme={null}
  const response = await client.dispute.cancelDispute({
    disputeId: 1,
  });
  ```

  ```typescript Request Type theme={null}
  export type CancelDisputeRequest = {
    disputeId: number | string | bigint;
    data?: Hex;
  };
  ```

  ```typescript Response Type theme={null}
  export type CancelDisputeResponse = {
    txHash?: Hex;
    encodedTxData?: EncodedTxData;
  };
  ```
</CodeGroup>

### resolveDispute

Resolves a dispute after it has been judged

| Method           | Type                                                                  |
| ---------------- | --------------------------------------------------------------------- |
| `resolveDispute` | `(request: ResolveDisputeRequest) => Promise<ResolveDisputeResponse>` |

Parameters:

* `request.disputeId`: The ID of the dispute to be resolved.
* `request.data`: \[Optional] The data to resolve the dispute. **Defaults to "0x"**.

<CodeGroup>
  ```typescript  theme={null}
  const response = await client.dispute.resolveDispute({
    disputeId: 1,
    data: "0x",
  });
  ```

  ```typescript Request Type theme={null}
  export type ResolveDisputeRequest = {
    disputeId: number | string | bigint;
    data?: Hex;
  };
  ```

  ```typescript Response Type theme={null}
  export type ResolveDisputeResponse = {
    txHash?: Hex;
    encodedTxData?: EncodedTxData;
  };
  ```
</CodeGroup>

### tagIfRelatedIpInfringed

Tags a derivative if a parent has been tagged with an infringement tag or a group ip if a group member has been tagged with an infringement tag.

| Method                    | Type                                                                          |
| ------------------------- | ----------------------------------------------------------------------------- |
| `tagIfRelatedIpInfringed` | `(request: TagIfRelatedIpInfringedRequest) => Promise<TransactionResponse[]>` |

Parameters:

* `request.infringementTags[]`: An array of tags relating to the dispute
  * `request.infringementTags[].ipId`: The `ipId` to tag
  * `request.infringementTags[].disputeId`: The dispute id that tagged the related infringing parent IP
* `request.options`: \[Optional]
  * `request.options.useMulticallWhenPossible`: \[Optional] Use multicall to batch the calls into one transaction when possible. If only 1 infringementTag is provided, multicall will not be used. **Default: true**

<CodeGroup>
  ```typescript  theme={null}
  const response = await client.dispute.tagIfRelatedIpInfringed({
    infringementTags: [
      {
        ipId: "0xa1BaAA464716eC76A285Ef873d27f97645fE0366",
        disputeId: 1,
      },
    ],
  });
  ```

  ```typescript Request Type theme={null}
  export type TagIfRelatedIpInfringedRequest = {
    infringementTags: {
      ipId: Address;
      disputeId: number | string | bigint;
    }[];
    options?: {
      useMulticallWhenPossible?: boolean;
    };
  };
  ```

  ```typescript Response Type theme={null}
  export type TransactionResponse = {
    txHash: Hex;

    /** Transaction receipt, only available if waitForTransaction is set to true */
    receipt?: TransactionReceipt;
  };
  ```
</CodeGroup>

### disputeAssertion

Counters a dispute that was raised by another party on an IP using counter evidence.

This method can only be called by the IP's owner to counter a dispute by providing counter evidence. The counter evidence (e.g., documents, images) should be uploaded to IPFS, and its corresponding CID is converted to a hash for the request.

If you only have a `disputeId`, call `disputeIdToAssertionId` to get the `assertionId` needed here.

| Method             | Type                                                                 |
| ------------------ | -------------------------------------------------------------------- |
| `disputeAssertion` | `(request: DisputeAssertionRequest) => Promise<TransactionResponse>` |

Parameters:

* `request.ipId`: The IP ID that is the target of the dispute.
* `request.assertionId`: The identifier of the assertion that was disputed. You can get this from the `disputeId` by calling `dispute.disputeIdToAssertionId`.
* `request.counterEvidenceCID`: Content Identifier (CID) for the counter evidence. This should be obtained by uploading your dispute evidence (documents, images, etc.) to IPFS. **Example: "QmX4zdp8VpzqvtKuEqMo6gfZPdoUx9TeHXCgzKLcFfSUbk"**
* `request.wipOptions`: \[Optional]
  * `request.wipOptions.enableAutoWrapIp`: \[Optional]By default IP is converted to WIP if the current WIP balance does not cover the fees. Set this to `false` to disable this behavior. **Default: true**
  * `request.wipOptions.enableAutoApprove`: \[Optional]Automatically approve WIP usage when WIP is needed but current allowance is not sufficient. Set this to `false` to disable this behavior. **Default: true**

<CodeGroup>
  ```typescript  theme={null}
  const assertionId = await client.dispute.disputeIdToAssertionId(1);

  const result = await client.dispute.disputeAssertion({
    ipId: "0xa1BaAA464716eC76A285Ef873d27f97645fE0366",
    assertionId: assertionId,
    counterEvidenceCID: "QmX4zdp8VpzqvtKuEqMo6gfZPdoUx9TeHXCgzKLcFfSUbk",
  });
  ```

  ```typescript Request Type theme={null}
  export type DisputeAssertionRequest = {
    ipId: Address;
    assertionId: Hex;
    counterEvidenceCID: string;
    wipOptions?: {
      enableAutoWrapIp?: boolean;
      enableAutoApprove?: boolean;
    };
  };
  ```

  ```typescript Response Type theme={null}
  export type TransactionResponse = {
    txHash: Hex;

    /** Transaction receipt, only available if waitForTransaction is set to true */
    receipt?: TransactionReceipt;
  };
  ```
</CodeGroup>

### disputeIdToAssertionId

Maps a dispute id to an assertion id

| Method                   | Type                                  |
| ------------------------ | ------------------------------------- |
| `disputeIdToAssertionId` | `(disputeId: number) => Promise<Hex>` |

Parameters:

* `request.disputeId`: The dispute ID.

```typescript  theme={null}
const result = await client.dispute.disputeIdToAssertionId(1);
```
# Group

> GroupClient allows you to create groups and add IP Assets to them.

## GroupClient

### Methods

* registerGroup
* mintAndRegisterIpAndAttachLicenseAndAddToGroup
* registerIpAndAttachLicenseAndAddToGroup
* registerGroupAndAttachLicense
* registerGroupAndAttachLicenseAndAddIps
* collectAndDistributeGroupRoyalties
* addIpsToGroup
* getClaimableReward
* removeIpsFromGroup
* claimReward
* collectRoyalties

### registerGroup

Registers a Group IPA.

| Method          | Type                                                                |
| --------------- | ------------------------------------------------------------------- |
| `registerGroup` | `(request: RegisterGroupRequest) => Promise<RegisterGroupResponse>` |

Parameters:

* `request.groupPool`: The address specifying how royalty will be split amongst the pool of IPs in the group.

```typescript Response Type theme={null}
export type RegisterGroupResponse = {
  txHash?: Hex;
  encodedTxData?: EncodedTxData;
  groupId?: Address;
};
```

### mintAndRegisterIpAndAttachLicenseAndAddToGroup

Mint an NFT from a SPGNFT collection, register it with metadata as an IP, attach license terms to the registered IP, and add it to a group IP.

| Method                                           | Type                                                                                                                                  |
| ------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------- |
| `mintAndRegisterIpAndAttachLicenseAndAddToGroup` | `(request: MintAndRegisterIpAndAttachLicenseAndAddToGroupRequest) => Promise<MintAndRegisterIpAndAttachLicenseAndAddToGroupResponse>` |

Parameters:

* `request.nftContract`: The address of the NFT collection.
* `request.groupId`: The ID of the group IP to add the newly registered IP.
* `request.licenseTermsId`: The ID of the registered license terms that will be attached to the new IP.
* `request.recipient`: \[Optional] The address of the recipient of the minted NFT,default value is your wallet address.
* `request.licenseTemplate`: \[Optional] The address of the license template to be attached to the new group IP,default value is Programmable IP License.
* `request.deadline`: \[Optional] The deadline for the signature in milliseconds,default value is 1000ms.
* `request.ipMetadata`: \[Optional] The desired metadata for the newly minted NFT and newly registered IP.
  * `request.ipMetadata.ipMetadataURI` \[Optional] The URI of the metadata for the IP.
  * `request.ipMetadata.ipMetadataHash` \[Optional] The hash of the metadata for the IP.
  * `request.ipMetadata.nftMetadataURI` \[Optional] The URI of the metadata for the NFT.
  * `request.ipMetadata.nftMetadataHash` \[Optional] The hash of the metadata for the IP NFT.

```typescript Response Type theme={null}
export type MintAndRegisterIpAndAttachLicenseAndAddToGroupResponse = {
  txHash?: Hex;
  encodedTxData?: EncodedTxData;
  ipId?: Address;
  tokenId?: bigint;
};
```

### registerIpAndAttachLicenseAndAddToGroup

Register an NFT as IP with metadata, attach license terms to the registered IP, and add it to a group IP.

| Method                                    | Type                                                                                                                    |
| ----------------------------------------- | ----------------------------------------------------------------------------------------------------------------------- |
| `registerIpAndAttachLicenseAndAddToGroup` | `(request: RegisterIpAndAttachLicenseAndAddToGroupRequest) => Promise<RegisterIpAndAttachLicenseAndAddToGroupResponse>` |

Parameters:

* `request.spgNftContract`: The address of the NFT collection.
* `request.tokenId`: The ID of the NFT.
* `request.groupId`: The ID of the group IP to add the newly registered IP.
* `request.licenseTermsId`: The ID of the registered license terms that will be attached to the new IP.
* `request.licenseTemplate`: \[Optional] The address of the license template to be attached to the new group IP, default value is Programmable IP License.
* `request.deadline`: \[Optional] The deadline for the signature in milliseconds, default is 1000ms.
* `request.ipMetadata`: \[Optional] The desired metadata for the newly minted NFT and newly registered IP.
  * `request.ipMetadata.ipMetadataURI` \[Optional] The URI of the metadata for the IP.
  * `request.ipMetadata.ipMetadataHash` \[Optional] The hash of the metadata for the IP.
  * `request.ipMetadata.nftMetadataURI` \[Optional] The URI of the metadata for the NFT.
  * `request.ipMetadata.nftMetadataHash` \[Optional] The hash of the metadata for the IP NFT.

```typescript Response Type theme={null}
export type RegisterIpAndAttachLicenseAndAddToGroupResponse = {
  txHash?: Hex;
  encodedTxData?: EncodedTxData;
  ipId?: Address;
  tokenId?: bigint;
};
```

### registerGroupAndAttachLicense

Register a group IP with a group reward pool and attach license terms to the group IP.

| Method                          | Type                                                                                                |
| ------------------------------- | --------------------------------------------------------------------------------------------------- |
| `registerGroupAndAttachLicense` | `(request: RegisterGroupAndAttachLicenseRequest) => Promise<RegisterGroupAndAttachLicenseResponse>` |

Parameters:

* `request.groupPool`: The address specifying how royalty will be split amongst the pool of IPs in the group.
* `request.licenseTermsId`: The ID of the registered license terms that will be attached to the new group IP.
* `request.licenseTemplate`: \[Optional] The address of the license template to be attached to the new group IP, default value is Programmable IP License.

```typescript Response Type theme={null}
export type RegisterGroupAndAttachLicenseResponse = {
  txHash?: Hex;
  encodedTxData?: EncodedTxData;
  groupId?: Address;
};
```

### registerGroupAndAttachLicenseAndAddIps

Register a group IP with a group reward pool, attach license terms to the group IP, and add individual IPs to the group IP.

| Method                                   | Type                                                                                                                  |
| ---------------------------------------- | --------------------------------------------------------------------------------------------------------------------- |
| `registerGroupAndAttachLicenseAndAddIps` | `(request: RegisterGroupAndAttachLicenseAndAddIpsRequest) => Promise<RegisterGroupAndAttachLicenseAndAddIpsResponse>` |

Parameters:

* `request.ipIds`: The IP IDs of the IPs to be added to the group.
* `request.groupPool`: The address specifying how royalty will be split amongst the pool of IPs in the group.
* `request.maxAllowedRevShare`: The maximum reward share percentage that can be allocated to each member IP.
* `request.licenseData`: The data of the license and its configuration to be attached to the new group IP.
  * `request.licenseData.licenseTermsId`: The ID of the registered license terms that will be attached to the new group IP.
  * `request.licenseData.licensingConfig`: \[Optional] See the [LicensingConfig type](https://github.com/storyprotocol/sdk/blob/main/packages/core-sdk/src/types/common.ts#L15). If none provided, it will default to the one shown [here](https://github.com/storyprotocol/sdk/blob/main/packages/core-sdk/src/utils/validateLicenseConfig.ts).
  * `request.licenseData.licenseTemplate`: \[Optional] The address of the license template to be attached to the new group IP, default value is Programmable IP License.

<CodeGroup>
  ```typescript TypeScript theme={null}
  const response =
    await client.groupClient.registerGroupAndAttachLicenseAndAddIps({
      groupPool: "0xf96f2c30b41Cb6e0290de43C8528ae83d4f33F89", // EvenSplitGroupPool from https://docs.story.foundation/docs/deployed-smart-contracts
      maxAllowedRewardShare: 5,
      ipIds: ["0x01"],
      licenseData: {
        licenseTermsId: "5",
      },
    });
  ```

  ```typescript Request Type theme={null}
  export type RegisterGroupAndAttachLicenseAndAddIpsRequest = {
    groupPool: Address;
    ipIds: Address[];
    licenseData: LicenseData;
    maxAllowedRewardShare: number | string;
  };
  ```

  ```typescript Response Type theme={null}
  export type RegisterGroupAndAttachLicenseAndAddIpsResponse = {
    txHash?: Hex;
    encodedTxData?: EncodedTxData;
    groupId?: Address;
  };
  ```
</CodeGroup>

### collectAndDistributeGroupRoyalties

Collect royalties for the entire group and distribute the rewards to each member IP's royalty vault.

| Method                               | Type                                                                                                          |
| ------------------------------------ | ------------------------------------------------------------------------------------------------------------- |
| `collectAndDistributeGroupRoyalties` | `(request: CollectAndDistributeGroupRoyaltiesRequest) => Promise<CollectAndDistributeGroupRoyaltiesResponse>` |

Parameters:

* `request.groupIpId`: The IP ID of the group.
* `request.currencyTokens`: The addresses of the currency (revenue) tokens to claim.
* `request.memberIpIds`: The IDs of the member IPs to distribute the rewards to.

<CodeGroup>
  ```typescript TypeScript theme={null}
  import { WIP_TOKEN_ADDRESS } from "@story-protocol/core-sdk";

  const response = await client.groupClient.collectAndDistributeGroupRoyalties({
    groupIpId: "0x01",
    currencyTokens: [WIP_TOKEN_ADDRESS],
    memberIpIds: ["0x02"],
  });
  ```

  ```typescript Request Type theme={null}
  export type CollectAndDistributeGroupRoyaltiesRequest = {
    groupIpId: Address;
    currencyTokens: Address[];
    memberIpIds: Address[];
  };
  ```

  ```typescript Response Type theme={null}
  export type CollectAndDistributeGroupRoyaltiesResponse = {
    txHash: Hash;
    receipts?: TransactionReceipt[];
    collectedRoyalties?: Omit<
      GroupingModuleCollectedRoyaltiesToGroupPoolEvent,
      "pool"
    >[];
    royaltiesDistributed?: {
      ipId: Address;
      amount: bigint;
      token: Address;
      /**
       * Amount after the fee to the royalty module treasury.
       */
      amountAfterFee: bigint;
    }[];
  };
  ```
</CodeGroup>

### addIpsToGroup

Adds IPs to a group. The function must be called by the Group IP owner or an authorized operator.

| Method          | Type                                                      |
| --------------- | --------------------------------------------------------- |
| `addIpsToGroup` | `(request: AddIpRequest) => Promise<TransactionResponse>` |

Parameters:

* `request.groupIpId`: The ID of the group IP to add the IPs to.
* `request.ipIds`: The addresses of the IPs to add to the Group IP. IP IDs must be attached to the group IP license terms.
* `request.maxAllowedRewardSharePercentage`: \[Optional] The maximum reward share percentage that can be allocated to each member IP. Must be between 0 and 100 (where 100% represents 100\_000\_000). Default is 100.

<CodeGroup>
  ```typescript TypeScript theme={null}
  const response = await client.groupClient.addIpsToGroup({
    groupIpId: "0x01",
    ipIds: ["0x02", "0x03"],
  });
  ```

  ```typescript Request Type theme={null}
  export type AddIpRequest = {
    groupIpId: Address;
    ipIds: Address[];
    maxAllowedRewardSharePercentage?: number;
  };
  ```

  ```typescript Response Type theme={null}
  export type TransactionResponse = {
    txHash: Hash;
    receipt?: TransactionReceipt;
  };
  ```
</CodeGroup>

### getClaimableReward

Returns the available reward for each IP in the group.

| Method               | Type                                                        |
| -------------------- | ----------------------------------------------------------- |
| `getClaimableReward` | `(request: GetClaimableRewardRequest) => Promise<bigint[]>` |

Parameters:

* `request.groupIpId`: The ID of the group IP.
* `request.currencyToken`: The address of the currency (revenue) token to check.
* `request.memberIpIds`: The IDs of the member IPs to check rewards for.

<CodeGroup>
  ```typescript TypeScript theme={null}
  import { WIP_TOKEN_ADDRESS } from "@story-protocol/core-sdk";

  const rewards = await client.groupClient.getClaimableReward({
    groupIpId: "0x01",
    currencyToken: WIP_TOKEN_ADDRESS,
    memberIpIds: ["0x02", "0x03"],
  });
  ```

  ```typescript Request Type theme={null}
  export type GetClaimableRewardRequest = {
    groupIpId: Address;
    currencyToken: Address;
    memberIpIds: Address[];
  };
  ```

  ```typescript Response Type theme={null}
  // Returns an array of bigint values representing the claimable reward amount for each member IP
  type Response = bigint[];
  ```
</CodeGroup>

### removeIpsFromGroup

Removes IPs from a group. The function must be called by the Group IP owner or an authorized operator.

| Method               | Type                                                                   |
| -------------------- | ---------------------------------------------------------------------- |
| `removeIpsFromGroup` | `(request: RemoveIpsFromGroupRequest) => Promise<TransactionResponse>` |

Parameters:

* `request.groupIpId`: The ID of the group IP to remove the IPs from.
* `request.ipIds`: The addresses of the IPs to remove from the Group IP.

<CodeGroup>
  ```typescript TypeScript theme={null}
  const response = await client.groupClient.removeIpsFromGroup({
    groupIpId: "0x01",
    ipIds: ["0x02", "0x03"],
  });
  ```

  ```typescript Request Type theme={null}
  export type RemoveIpsFromGroupRequest = {
    groupIpId: Address;
    ipIds: Address[];
  };
  ```

  ```typescript Response Type theme={null}
  export type TransactionResponse = {
    txHash: Hash;
    receipt?: TransactionReceipt;
  };
  ```
</CodeGroup>

### claimReward

Claims reward for member IPs in a group. Emits an on-chain [ClaimedReward](https://github.com/storyprotocol/protocol-core-v1/blob/v1.3.1/contracts/interfaces/modules/grouping/IGroupingModule.sol#L31) event.

| Method        | Type                                                            |
| ------------- | --------------------------------------------------------------- |
| `claimReward` | `(request: ClaimRewardRequest) => Promise<ClaimRewardResponse>` |

Parameters:

* `request.groupIpId`: The ID of the group IP.
* `request.currencyToken`: The address of the currency (revenue) token to claim.
* `request.memberIpIds`: The IDs of the member IPs to distribute the rewards to.

<CodeGroup>
  ```typescript TypeScript theme={null}
  import { WIP_TOKEN_ADDRESS } from "@story-protocol/core-sdk";

  const response = await client.groupClient.claimReward({
    groupIpId: "0x01",
    currencyToken: WIP_TOKEN_ADDRESS,
    memberIpIds: ["0x02", "0x03"],
  });
  ```

  ```typescript Request Type theme={null}
  export type ClaimRewardRequest = {
    groupIpId: Address;
    currencyToken: Address;
    memberIpIds: Address[];
  };
  ```

  ```typescript Response Type theme={null}
  export type ClaimRewardResponse = {
    txHash: Hash;
    claimedReward?: GroupingModuleClaimedRewardEvent[];
  };
  ```
</CodeGroup>

### collectRoyalties

Collects royalties into the pool, making them claimable by group member IPs. Emits an on-chain [CollectedRoyaltiesToGroupPool](https://github.com/storyprotocol/protocol-core-v1/blob/v1.3.1/contracts/interfaces/modules/grouping/IGroupingModule.sol#L38) event.

| Method             | Type                                                                      |
| ------------------ | ------------------------------------------------------------------------- |
| `collectRoyalties` | `(request: CollectRoyaltiesRequest) => Promise<CollectRoyaltiesResponse>` |

Parameters:

* `request.groupIpId`: The ID of the group IP.
* `request.currencyToken`: The address of the currency (revenue) token to collect.

<CodeGroup>
  ```typescript TypeScript theme={null}
  import { WIP_TOKEN_ADDRESS } from "@story-protocol/core-sdk";

  const response = await client.groupClient.collectRoyalties({
    groupIpId: "0x01",
    currencyToken: WIP_TOKEN_ADDRESS,
  });
  ```

  ```typescript Request Type theme={null}
  export type CollectRoyaltiesRequest = {
    groupIpId: Address;
    currencyToken: Address;
  };
  ```

  ```typescript Response Type theme={null}
  export type CollectRoyaltiesResponse = {
    txHash: Hash;
    collectedRoyalties?: bigint;
  };
  ```
</CodeGroup>
# Royalty

> RoyaltyClient allows you to manage royalty payments and claims within Story.

## RoyaltyClient

### Methods

* payRoyaltyOnBehalf
* claimableRevenue
* claimAllRevenue
* batchClaimAllRevenue
* getRoyaltyVaultAddress
* batchClaimAllRevenue
* transferToVault

### payRoyaltyOnBehalf

Allows the function caller to pay royalties to a receiver IP asset on behalf of the payer IP Asset.

| Method               | Type                                                                          |
| -------------------- | ----------------------------------------------------------------------------- |
| `payRoyaltyOnBehalf` | `(request: PayRoyaltyOnBehalfRequest) => Promise<PayRoyaltyOnBehalfResponse>` |

Parameters:

* `request.receiverIpId`: The ipId that receives the royalties.

* `request.payerIpId`: The ID of the IP asset that pays the royalties.

* `request.token`: The token to use to pay the royalties.

* `request.amount`: The amount to pay.

* `request.wipOptions`: \[Optional]
  * `request.wipOptions.useMulticallWhenPossible`: \[Optional] Use multicall to batch the WIP calls into one transaction when possible. **Default: true**
  * `request.wipOptions.enableAutoWrapIp`: \[Optional] By default IP is converted to WIP if the current WIP balance does not cover the fees. Set this to `false` to disable this behavior. **Default: true**
  * `request.wipOptions.enableAutoApprove`: \[Optional] Automatically approve WIP usage when WIP is needed but current allowance is not sufficient. Set this to `false` to disable this behavior. **Default: true**

* `request.erc20Options`: \[Optional]
  * `request.erc20Options.enableAutoApprove`: \[Optional] Automatically approve ERC20 usage when ERC20 is needed but current allowance is not sufficient. Set this to `false` to disable this behavior. **Default: true**

<CodeGroup>
  ```typescript TypeScript theme={null}
  import { WIP_TOKEN_ADDRESS } from "@story-protocol/core-sdk";
  import { parseEther, zeroAddress } from "viem";

  // In this case, lets say there is a root IPA 'A' and a derivative IPA 'B'.
  // Someone wants to pay 'B' for whatever reason (they bought it, they want to tip it, etc).
  // Since the payer is not an IP Asset (rather an external user), the `payerIpId` can
  // be a zeroAddress. And the receiver is, well, the receiver's ipId which is B.
  //
  // It's important to note that both 'B' and its parent 'A' will be able
  // to claim revenue from this based on the negotiated license terms
  const payRoyalty = await client.royalty.payRoyaltyOnBehalf({
    receiverIpId: "0x0b825D9E5FA196e6B563C0a446e8D9885057f9B1", // B's ipId
    payerIpId: zeroAddress,
    token: WIP_TOKEN_ADDRESS,
    amount: parseEther("2"), // 2 $WIP
  });
  console.log(`Paid royalty at transaction hash ${payRoyalty.txHash}`);

  // In this case, lets say there is a root IPA 'A' and a derivative IPA 'B'.
  // 'B' earns revenue off-chain, but must pay 'A' based on their negotiated license terms.
  // So 'B' pays 'A' what they are due
  const payRoyalty = await client.royalty.payRoyaltyOnBehalf({
    receiverIpId: "0x6B86B39F03558A8a4E9252d73F2bDeBfBedf5b68", // A's ipId
    payerIpId: "0x0b825D9E5FA196e6B563C0a446e8D9885057f9B1", // B's ipId
    token: WIP_TOKEN_ADDRESS,
    amount: parseEther("2"), // 2 $WIP
  });
  console.log(`Paid royalty at transaction hash ${payRoyalty.txHash}`);
  ```

  ```typescript Request Type theme={null}
  export type PayRoyaltyOnBehalfRequest = {
    receiverIpId: Address;
    payerIpId: Address;
    token: Address;
    amount: TokenAmountInput;
  } & WithERC20Options &
    WithWipOptions;
  ```

  ```typescript Response Type theme={null}
  export type PayRoyaltyOnBehalfResponse = {
    txHash?: Hex;
    receipt?: TransactionReceipt;
    encodedTxData?: EncodedTxData;
  };
  ```
</CodeGroup>

### claimableRevenue

Get total amount of revenue token claimable by a royalty token holder.

<Note>
  This function will only return the claimable revenue that is sitting in the IP Royalty Vault. If a parent is claiming revenue from a child and the revenue is in the Royalty Module, it won't be returned by this function.
</Note>

| Method             | Type                                                                      |
| ------------------ | ------------------------------------------------------------------------- |
| `claimableRevenue` | `(request: ClaimableRevenueRequest) => Promise<ClaimableRevenueResponse>` |

Parameters:

* `request.ipId`: The id of the royalty vault.
* `request.claimer`: The address of the royalty token holder. This is most commonly the IP Account, since by default the IP Account is the owner of the royalty tokens.
* `request.token`: The revenue token to claim.

<CodeGroup>
  ```typescript TypeScript theme={null}
  import { WIP_TOKEN_ADDRESS } from "@story-protocol/core-sdk";

  const claimableRevenue = await client.royalty.claimableRevenue({
    ipId: "0x01",
    claimer: "0x01",
    token: WIP_TOKEN_ADDRESS,
  });
  ```

  ```typescript Request Type theme={null}
  export type ClaimableRevenueRequest = {
    ipId: Address;
    claimer: Address;
    token: Address;
  };
  ```

  ```typescript Response Type theme={null}
  export type ClaimableRevenueResponse = bigint;
  ```
</CodeGroup>

### claimAllRevenue

Claims all revenue from child IP Assets and/or from your own IP Royalty Vault.

| Method            | Type                                                                    |
| ----------------- | ----------------------------------------------------------------------- |
| `claimAllRevenue` | `(request: ClaimAllRevenueRequest) => Promise<ClaimAllRevenueResponse>` |

Parameters:

* `request.ancestorIpId`: The address of the ancestor IP from which the revenue is being claimed.
* `request.claimer`: The address of the claimer of the currency (revenue) tokens. This is normally the ipId of the ancestor IP if the IP has all royalty tokens. Otherwise, this would be the address that is holding the ancestor IP royalty tokens.
* `request.childIpIds[]`: The addresses of the child IPs from which royalties are derived.
* `request.royaltyPolicies[]`: The addresses of the royalty policies, where royaltyPolicies\[i] governs the royalty flow for childIpIds\[i].
* `request.currencyTokens[]`: The addresses of the currency tokens in which royalties will be claimed.
* `request.claimOptions`: \[Optional]
  * `request.claimOptions.autoTransferAllClaimedTokensFromIp`: \[Optional] When enabled, all claimed tokens on the claimer are transferred to the wallet address if the wallet owns the IP. If the wallet is the claimer or if the claimer is not an IP owned by the wallet, then the tokens will not be transferred. Set to false to disable auto transferring claimed tokens from the claimer. **Default: true**
  * `request.claimOptions.autoUnwrapIpTokens`: \[Optional] By default all claimed WIP tokens are converted back to IP after they are transferred. Set this to false to disable this behavior. **Default: false**

<CodeGroup>
  ```typescript TypeScript theme={null}
  import { WIP_TOKEN_ADDRESS } from "@story-protocol/core-sdk";

  const claimRevenue = await client.royalty.claimAllRevenue({
    // IP Asset 1's (parent) ipId
    ancestorIpId: "0x089d75C9b7E441dA3115AF93FF9A855BDdbfe384",
    // whoever owns the royalty tokens associated with IP Royalty Vault 1
    // (most likely the associated ipId, which is IP Asset 1's ipId)
    claimer: "0x089d75C9b7E441dA3115AF93FF9A855BDdbfe384",
    currencyTokens: [WIP_TOKEN_ADDRESS],
    // IP Asset 2's (child) ipId
    childIpIds: ["0xDa03c4B278AD44f5a669e9b73580F91AeDE0E3B2"],
    // testnet address of RoyaltyPolicyLAP
    royaltyPolicies: ["0xBe54FB168b3c982b7AaE60dB6CF75Bd8447b390E"],
  });

  console.log(`Claimed revenue: ${claimRevenue.claimedTokens}`);
  ```

  ```typescript Request Type theme={null}
  export type ClaimAllRevenueRequest = {
    ancestorIpId: Address;
    claimer: Address;
    childIpIds: Address[];
    royaltyPolicies: Address[];
    currencyTokens: Address[];
  } & WithClaimOptions;

  export type WithClaimOptions = {
    claimOptions?: {
      autoTransferAllClaimedTokensFromIp?: boolean;
      autoUnwrapIpTokens?: boolean;
    };
  };
  ```

  ```typescript Response Type theme={null}
  export type ClaimAllRevenueResponse = {
    txHashes: Hash[];
    receipt?: TransactionReceipt;
    claimedTokens?: ClaimedToken[];
  };

  export type ClaimedToken = {
    token: Address;
    amount: bigint;
  };
  ```
</CodeGroup>

### batchClaimAllRevenue

Automatically batch claims all revenue from the child IPs of multiple ancestor IPs. If multicall is disabled, it will call `claimAllRevenue` for each ancestor IP. Then transfer all claimed tokens to the wallet if the wallet owns the IP or is the claimer. If claimed token is WIP, it will also be converted back to IP.

| Method                 | Type                                                                              |
| ---------------------- | --------------------------------------------------------------------------------- |
| `batchClaimAllRevenue` | `(request: BatchClaimAllRevenueRequest) => Promise<BatchClaimAllRevenueResponse>` |

Parameters:

* `request.ancestorIps[]`: An array of ancestor IP information from which the revenue is being claimed.
  * `request.ancestorIps[].ipId`: The address of the ancestor IP from which the revenue is being claimed.
  * `request.ancestorIps[].claimer`: The address of the claimer of the currency (revenue) tokens. This is normally the ipId of the ancestor IP if the IP has all royalty tokens. Otherwise, this would be the address that is holding the ancestor IP royalty tokens.
  * `request.ancestorIps[].childIpIds[]`: The addresses of the child IPs from which royalties are derived.
  * `request.ancestorIps[].royaltyPolicies[]`: The addresses of the royalty policies, where royaltyPolicies\[i] governs the royalty flow for childIpIds\[i].
  * `request.ancestorIps[].currencyTokens[]`: The addresses of the currency tokens in which royalties will be claimed.
* `request.claimOptions`: \[Optional]
  * `request.claimOptions.autoTransferAllClaimedTokensFromIp`: \[Optional] When enabled, all claimed tokens on the claimer are transferred to the wallet address if the wallet owns the IP. If the wallet is the claimer or if the claimer is not an IP owned by the wallet, then the tokens will not be transferred. Set to false to disable auto transferring claimed tokens from the claimer. **Default: true**
  * `request.claimOptions.autoUnwrapIpTokens`: \[Optional] By default all claimed WIP tokens are converted back to IP after they are transferred. Set this to false to disable this behavior. **Default: false**
* `request.options`: \[Optional]
  * `request.options.useMulticallWhenPossible`: \[Optional] Use multicall to batch the calls `claimAllRevenue` into one transaction when possible. If only 1 ancestorIp is provided, multicall will not be used. **Default: true**

<CodeGroup>
  ```typescript TypeScript theme={null}
  import { WIP_TOKEN_ADDRESS } from "@story-protocol/core-sdk";

  const claimRevenue = await client.royalty.batchClaimAllRevenue({
    ancestorIps: [
      {
        ipId: "0x089d75C9b7E441dA3115AF93FF9A855BDdbfe384",
        claimer: "0x089d75C9b7E441dA3115AF93FF9A855BDdbfe384",
        currencyTokens: [WIP_TOKEN_ADDRESS],
        childIpIds: ["0xDa03c4B278AD44f5a669e9b73580F91AeDE0E3B2"],
        royaltyPolicies: ["0xBe54FB168b3c982b7AaE60dB6CF75Bd8447b390E"],
      },
    ],
  });

  console.log(`Claimed revenue: ${claimRevenue.claimedTokens}`);
  ```

  ```typescript Request Type theme={null}
  export type BatchClaimAllRevenueRequest = WithClaimOptions & {
    ancestorIps: {
      ipId: Address;
      claimer: Address;
      childIpIds: Address[];
      royaltyPolicies: Address[];
      currencyTokens: Address[];
    }[];
    options?: {
      useMulticallWhenPossible?: boolean;
    };
  };

  export type WithClaimOptions = {
    claimOptions?: {
      autoTransferAllClaimedTokensFromIp?: boolean;
      autoUnwrapIpTokens?: boolean;
    };
  };
  ```

  ```typescript Response Type theme={null}
  export type BatchClaimAllRevenueResponse = {
    txHashes: Hash[];
    receipts: TransactionReceipt[];
    claimedTokens?: IpRoyaltyVaultImplRevenueTokenClaimedEvent[];
  };
  ```
</CodeGroup>

### getRoyaltyVaultAddress

Get the royalty vault proxy address of given ipId.

| Method                   | Type                              |
| ------------------------ | --------------------------------- |
| `getRoyaltyVaultAddress` | `(ipId: Hex) => Promise<Address>` |

Parameters:

* `ipId`: the `ipId` associated with the royalty vault.

### transferToVault

Transfers to vault an amount of revenue tokens claimable via a royalty policy.

| Method            | Type                                                                |
| ----------------- | ------------------------------------------------------------------- |
| `transferToVault` | `(request: TransferToVaultRequest) => Promise<TransactionResponse>` |

Parameters:

* `request.royaltyPolicy`: The royalty policy to use.
* `request.ipId`: The ID of the IP asset that pays the royalties.
* `request.ancestorIpId`: The ID of the ancestor IP asset.
* `request.token`: The token address to transfer.

<CodeGroup>
  ```typescript Request Type theme={null}
  export type TransferToVaultRequest = {
    royaltyPolicy: RoyaltyPolicyInput;
    ipId: Address;
    ancestorIpId: Address;
    token: Address;
  };
  ```

  ```typescript Response Type theme={null}
  export type TransactionResponse = {
    txHash: Hex;

    /** Transaction receipt, only available if waitForTransaction is set to true */
    receipt?: TransactionReceipt;
  };
  ```
</CodeGroup>
# Permissions

> PermissionClient allows you to manage permissions for IP Accounts within Story.

## PermissionClient

### Methods

* setPermission
* createSetPermissionSignature
* setAllPermissions
* setBatchPermissions
* createBatchPermissionSignature

### setPermission

Sets the permission for a specific function call.

Each policy is represented as a mapping from an IP account address to a signer address to a recipient\
address to a function selector to a permission level. The permission level can be 0 (ABSTAIN), 1 (ALLOW), or\
2 (DENY).

By default, all policies are set to 0 (ABSTAIN), which means that the permission is not set. The owner of IP Account by default has all permission.

| Method          | Type                                                                  |
| --------------- | --------------------------------------------------------------------- |
| `setPermission` | `(request: SetPermissionsRequest) => Promise<SetPermissionsResponse>` |

Parameters:

* `request.ipId`: The IP ID that grants the permission for `signer`.
* `request.signer`: The address that can call `to` on behalf of the `ipAccount`.
* `request.to`: The address that can be called by the `signer` (currently only modules can be `to`)
* `request.permission`: The new permission level.
* `request.func`: \[Optional] The function selector string of `to` that can be called by the `signer` on behalf of the `ipAccount`. By default, it allows all functions.

```typescript Response Type theme={null}
export type SetPermissionsResponse = {
  txHash?: Hex;
  encodedTxData?: EncodedTxData;
  success?: boolean;
};
```

### createSetPermissionSignature

Specific permission overrides wildcard permission with signature.

| Method                         | Type                                                                                |
| ------------------------------ | ----------------------------------------------------------------------------------- |
| `createSetPermissionSignature` | `(request: CreateSetPermissionSignatureRequest) => Promise<SetPermissionsResponse>` |

Parameters:

* `request.ipId`: The IP ID that grants the permission for `signer`.
* `request.signer`: The address that can call `to` on behalf of the `ipAccount`.
* `request.to`: The address that can be called by the `signer` (currently only modules can be `to`)
* `request.permission`: The new permission level.
* `request.func`: \[Optional] The function selector string of `to` that can be called by the `signer` on behalf of the `ipAccount`. By default, it allows all functions.
* `request.deadline`: \[Optional] The deadline for the signature in milliseconds, default is 1000ms.

```typescript Response Type theme={null}
export type SetPermissionsResponse = {
  txHash?: Hex;
  encodedTxData?: EncodedTxData;
  success?: boolean;
};
```

### setAllPermissions

Sets permission to a signer for all functions across all modules.

| Method              | Type                                                                     |
| ------------------- | ------------------------------------------------------------------------ |
| `setAllPermissions` | `(request: SetAllPermissionsRequest) => Promise<SetPermissionsResponse>` |

Parameters:

* `request.ipId`: The IP ID that grants the permission for `signer`.
* `request.signer`: The address of the signer receiving the permissions.
* `request.permission`: The new permission.

```typescript Response Type theme={null}
export type SetPermissionsResponse = {
  txHash?: Hex;
  encodedTxData?: EncodedTxData;
  success?: boolean;
};
```

### setBatchPermissions

Sets a batch of permissions in a single transaction.

| Method                | Type                                                                       |
| --------------------- | -------------------------------------------------------------------------- |
| `setBatchPermissions` | `(request: SetBatchPermissionsRequest) => Promise<SetPermissionsResponse>` |

Parameters:

* `request.permissions[]`: An array of `Permission` structure, each representing the permission to be set.
  * `request.permissions[].ipId`: The IP ID that grants the permission for `signer`.
  * `request.permissions[].signer`: The address that can call `to` on behalf of the `ipAccount`.
  * `request.permissions[].to`: The address that can be called by the `signer` (currently only modules can be `to`)
  * `request.permissions[].permission`: The new permission level.
  * `request.permissions[].func`: \[Optional] The function selector string of `to` that can be called by the `signer` on behalf of the `ipAccount`. By default, it allows all functions.
* `request.deadline`: \[Optional] The deadline for the signature in milliseconds, default is 1000ms.

```typescript Response Type theme={null}
export type SetPermissionsResponse = {
  txHash?: Hex;
  encodedTxData?: EncodedTxData;
  success?: boolean;
};
```

### createBatchPermissionSignature

Sets a batch of permissions in a single transaction with signature.

| Method                           | Type                                                                                  |
| -------------------------------- | ------------------------------------------------------------------------------------- |
| `createBatchPermissionSignature` | `(request: CreateBatchPermissionSignatureRequest) => Promise<SetPermissionsResponse>` |

Parameters:

* `request.ipId`: The IP ID that grants the permission for `signer`
* `request.permissions[]` - An array of `Permission` structure, each representing the permission to be set.
  * `request.permissions[].ipId`: The IP ID that grants the permission for `signer`.
  * `request.permissions[].signer`: The address that can call `to` on behalf of the `ipAccount`.
  * `request.permissions[].to`: The address that can be called by the `signer` (currently only modules can be `to`)
  * `request.permissions[].permission`: The new permission level.
  * `request.permissions[].func`: \[Optional] The function selector string of `to` that can be called by the `signer` on behalf of the `ipAccount`. By default, it allows all functions.

```typescript Response Type theme={null}
export type SetPermissionsResponse = {
  txHash?: Hex;
  encodedTxData?: EncodedTxData;
  success?: boolean;
};
```
# NFT Client

> Used to mint a new SPG collection for use with Story.

## NftClient

### Methods

* createNFTCollection
* getMintFeeToken
* getMintFee
* setTokenURI
* getTokenURI

### createNFTCollection

Creates a new SPG NFT Collection.

| Method                | Type                                                                            |
| --------------------- | ------------------------------------------------------------------------------- |
| `createNFTCollection` | `(request: CreateNFTCollectionRequest) => Promise<CreateNFTCollectionResponse>` |

Parameters:

* `request.name`: The name of the collection.
* `request.symbol`: The symbol of the collection.
* `request.isPublicMinting`: If true, anyone can mint from the collection. If false, only the addresses with the minter role can mint.
* `request.mintOpen`: Whether the collection is open for minting on creation.
* `request.mintFeeRecipient`: The address to receive mint fees.
* `request.contractURI`: The contract URI for the collection. Follows ERC-7572 standard. See [here](https://eips.ethereum.org/EIPS/eip-7572).
* `request.baseURI`: \[Optional] The base URI for the collection. If baseURI is not empty, tokenURI will be either baseURI + token ID (if nftMetadataURI is empty) or baseURI + nftMetadataURI.
* `request.maxSupply`: \[Optional] The maximum supply of the collection.
* `request.mintFee`: \[Optional] The cost to mint a token.
* `request.mintFeeToken`: \[Optional] The token to mint.
* `request.owner`: \[Optional] The owner of the collection.

<CodeGroup>
  ```typescript TypeScript theme={null}
  import { zeroAddress } from "viem";

  // Create a new SPG NFT collection
  //
  // NOTE: Use this code to create a new SPG NFT collection. You can then use the
  // `newCollection.spgNftContract` address as the `spgNftContract` argument in
  // functions like `registerIpAsset` in the IPAsset Client.
  //
  // You will mostly only have to do this once. Once you get your nft contract address,
  // you can use it in SPG functions.
  //
  const newCollection = await client.nftClient.createNFTCollection({
    name: "Test NFT",
    symbol: "TEST",
    isPublicMinting: true,
    mintOpen: true,
    mintFeeRecipient: zeroAddress,
    contractURI: "",
  });

  console.log(
    `New SPG NFT collection created at transaction hash ${newCollection.txHash}`
  );
  console.log(`NFT contract address: ${newCollection.spgNftContract}`);
  ```

  ```typescript Request Type theme={null}
  export type CreateNFTCollectionRequest = {
    name: string;
    symbol: string;
    isPublicMinting: boolean;
    mintOpen: boolean;
    mintFeeRecipient: Address;
    contractURI: string;
    baseURI?: string;
    maxSupply?: number;
    mintFee?: bigint;
    mintFeeToken?: Hex;
    owner?: Hex;
  };
  ```

  ```typescript Response Type theme={null}
  export type CreateNFTCollectionResponse = {
    txHash?: Hex;
    encodedTxData?: EncodedTxData;
    spgNftContract?: Address; // the address of the newly created contract
  };
  ```
</CodeGroup>

### getMintFeeToken

Returns the current mint token of the collection.

| Method            | Type                                            |
| ----------------- | ----------------------------------------------- |
| `getMintFeeToken` | `(spgNftContract: Address) => Promise<Address>` |

Parameters:

* `spgNftContract`: The address of the NFT contract.

<CodeGroup>
  ```typescript TypeScript theme={null}
  const mintFeeToken = await client.nftClient.getMintFeeToken("0x01");
  ```
</CodeGroup>

### getMintFee

Returns the current mint fee of the collection.

| Method       | Type                                           |
| ------------ | ---------------------------------------------- |
| `getMintFee` | `(spgNftContract: Address) => Promise<bigint>` |

Parameters:

* `spgNftContract`: The address of the NFT contract.

<CodeGroup>
  ```typescript TypeScript theme={null}
  const mintFee = await client.nftClient.getMintFee("0x01");
  ```
</CodeGroup>

### setTokenURI

Sets the token URI for a given token.

| Method        | Type                                                            |
| ------------- | --------------------------------------------------------------- |
| `setTokenURI` | `(request: SetTokenURIRequest) => Promise<TransactionResponse>` |

Parameters:

* `request.spgNftContract`: The address of the NFT contract.
* `request.tokenId`: The ID of the token.
* `request.tokenURI`: The URI to set.

<CodeGroup>
  ```typescript TypeScript theme={null}
  const response = await client.nftClient.setTokenURI({
    spgNftContract: "0x01",
    tokenId: 1,
    tokenURI:
      "https://ipfs.io/ipfs/QmX4zdp8VpzqvtKuEqMo6gfZPdoUx9TeHXCgzKLcFfSUbk",
  });
  ```

  ```typescript Request Type theme={null}
  export type SetTokenURIRequest = {
    spgNftContract: Address;
    tokenId: bigint | number;
    tokenURI: string;
  };
  ```

  ```typescript Response Type theme={null}
  export type TransactionResponse = {
    txHash: Hex;
    /** Transaction receipt, only available if waitForTransaction is set to true */
    receipt?: TransactionReceipt;
  };
  ```
</CodeGroup>

### getTokenURI

Returns the token URI for a given token.

| Method        | Type                                               |
| ------------- | -------------------------------------------------- |
| `getTokenURI` | `(request: GetTokenURIRequest) => Promise<string>` |

Parameters:

* `request.spgNftContract`: The address of the SPG NFT contract.
* `request.tokenId`: The ID of the token.

<CodeGroup>
  ```typescript TypeScript theme={null}
  const tokenURI = await client.nftClient.getTokenURI({
    spgNftContract: "0x01",
    tokenId: 1,
  });
  ```
</CodeGroup>

```typescript Request Type theme={null}
export type GetTokenURIRequest = {
  spgNftContract: Address;
  tokenId: bigint | number;
};
```
# WIP Client

> Used to handle the wrapping/unwrapping of WIP (Wrapped IP) tokens within Story.

## WipClient

### Methods

* deposit
* withdraw
* approve
* balanceOf
* transfer
* transferFrom

### deposit

Wraps the selected amount of IP to WIP. The WIP will be deposited to the wallet that transferred the IP.

| Method    | Type                        |
| --------- | --------------------------- |
| `deposit` | `(request: DepositRequest)` |

Parameters:

* `request.amount`: The amount to deposit.

<CodeGroup>
  ```typescript TypeScript theme={null}
  import { parseEther } from "viem";

  const response = await client.wipClient.deposit({
    amount: parseEther("10"), // 10 IP tokens
  });
  ```

  ```typescript Request Type theme={null}
  export type DepositRequest = {
    amount: TokenAmountInput;
  };
  ```
</CodeGroup>

### withdraw

Unwraps the selected amount of WIP to IP.

| Method     | Type                         |
| ---------- | ---------------------------- |
| `withdraw` | `(request: WithdrawRequest)` |

Parameters:

* `request.amount`: The amount to withdraw.

<CodeGroup>
  ```typescript TypeScript theme={null}
  import { parseEther } from "viem";

  const response = await client.wipClient.withdraw({
    amount: parseEther("5"), // 5 WIP tokens
  });
  ```

  ```typescript Request Type theme={null}
  export type WithdrawRequest = {
    amount: TokenAmountInput;
  };
  ```
</CodeGroup>

### approve

Approve a spender to use the wallet's WIP balance.

| Method    | Type                        |
| --------- | --------------------------- |
| `approve` | `(request: ApproveRequest)` |

Parameters:

* `request.amount`: The amount of WIP tokens to approve.
* `request.spender`: The address that will use the WIP tokens

<CodeGroup>
  ```typescript TypeScript theme={null}
  import { parseEther } from "viem";

  const response = await client.wipClient.approve({
    spender: "0xC92EC2f4c86458AFee7DD9EB5d8c57920BfCD0Ba",
    amount: parseEther("20"), // 20 WIP tokens
  });
  ```

  ```typescript Request Type theme={null}
  export type ApproveRequest = {
    spender: Address;
    amount: TokenAmountInput;
  };
  ```
</CodeGroup>

### balanceOf

Returns the balance of WIP for an address.

| Method      | Type                                 |
| ----------- | ------------------------------------ |
| `balanceOf` | `(addr: Address) => Promise<bigint>` |

Parameters:

* `addr`: The address you want to check the baalnce for.

### transfer

Transfers `amount` of WIP to a recipient `to`.

| Method     | Type                         |
| ---------- | ---------------------------- |
| `transfer` | `(request: TransferRequest)` |

Parameters:

* `request.to`: Who you're transferring to.
* `request.amount`: The amount to transfer.

<CodeGroup>
  ```typescript TypeScript theme={null}
  import { parseEther } from "viem";

  const response = await client.wipClient.transfer({
    to: "0xC92EC2f4c86458AFee7DD9EB5d8c57920BfCD0Ba",
    amount: parseEther("3"), // 3 WIP tokens
  });
  ```

  ```typescript Request Type theme={null}
  export type TransferRequest = {
    to: Address;
    amount: TokenAmountInput;
  };
  ```
</CodeGroup>

### transferFrom

Transfers `amount` of WIP from `from` to a recipient `to`.

| Method         | Type                             |
| -------------- | -------------------------------- |
| `transferFrom` | `(request: TransferFromRequest)` |

Parameters:

* `request.to`: Who you're transferring to.
* `request.amount`: The amount to transfer.
* `request.from`: The address to transfer from.

<CodeGroup>
  ```typescript TypeScript theme={null}
  import { parseEther } from "viem";

  const response = await client.wipClient.transferFrom({
    to: "0xC92EC2f4c86458AFee7DD9EB5d8c57920BfCD0Ba",
    amount: parseEther("2"), // 2 WIP tokens
    from: "0x6B86B39F03558A8a4E9252d73F2bDeBfBedf5b68",
  });
  ```

  ```typescript Request Type theme={null}
  export type TransferFromRequest = {
    to: Address;
    amount: TokenAmountInput;
    from: Address;
  };
  ```
</CodeGroup>
# IPAccountImpl

The IPAccountImpl contract is Story's implementation of the IP Account, which follows the ERC-6551 standard for token-bound accounts. It provides functionality for IP assets to own and manage other assets, execute transactions, and interact with other contracts in a permissioned manner.

## State Variables

### ACCESS\_CONTROLLER

```solidity  theme={null}
address public immutable ACCESS_CONTROLLER
```

The address of the AccessController contract used for permission checks. This is immutable and set during construction.

## Inheritance

IPAccountImpl inherits from:

* ERC6551: Base implementation of the ERC-6551 standard
* IPAccountStorage: Storage contract for IP Account data
* IIPAccount: Interface for IP Account functionality

## Functions

### constructor

```solidity  theme={null}
constructor(
    address accessController,
    address ipAssetRegistry,
    address licenseRegistry,
    address moduleRegistry
)
```

Creates a new IPAccountImpl contract instance.

**Parameters:**

* `accessController`: The address of the AccessController contract to be used for permission checks
* `ipAssetRegistry`: The address of the IP Asset Registry
* `licenseRegistry`: The address of the License Registry
* `moduleRegistry`: The address of the Module Registry

### supportsInterface

```solidity  theme={null}
function supportsInterface(bytes4 interfaceId) public view returns (bool)
```

Checks if the contract supports a specific interface.

**Parameters:**

* `interfaceId`: The interface identifier, as specified in ERC-165

**Returns:**

* Boolean indicating if the contract supports the interface

### token

```solidity  theme={null}
function token() public view returns (uint256, address, uint256)
```

Returns the identifier of the non-fungible token which owns the account.

**Returns:**

* `chainId`: The EIP-155 ID of the chain the token exists on
* `tokenContract`: The contract address of the token
* `tokenId`: The ID of the token

### isValidSigner

```solidity  theme={null}
function isValidSigner(address signer, bytes calldata data) public view returns (bytes4 result)
```

Checks if the signer is valid for executing specific actions on behalf of the IP Account.

**Parameters:**

* `signer`: The signer to check
* `data`: The data to be checked, encoded as `abi.encode(address to, bytes calldata)`

**Returns:**

* The function selector if the signer is valid, 0 otherwise

### isValidSigner

```solidity  theme={null}
function isValidSigner(address signer, address to, bytes calldata data) public view returns (bool)
```

Checks if the signer is valid for the given data and recipient via the AccessController permission system.

**Parameters:**

* `signer`: The signer to check
* `to`: The recipient of the transaction
* `data`: The calldata to check against

**Returns:**

* Boolean indicating if the signer is valid

### owner

```solidity  theme={null}
function owner() public view returns (address)
```

Returns the owner of the IP Account.

**Returns:**

* The address of the owner

### state

```solidity  theme={null}
function state() public view returns (bytes32 result)
```

Returns the IPAccount's internal nonce for transaction ordering.

**Returns:**

* The current state (nonce) of the account

### updateStateForValidSigner

```solidity  theme={null}
function updateStateForValidSigner(address signer, address to, bytes calldata data) external
```

Updates the IP Account's state if the signer is valid for the given data and recipient.

**Parameters:**

* `signer`: The signer to check
* `to`: The recipient of the transaction
* `data`: The calldata to check against

### executeWithSig

```solidity  theme={null}
function executeWithSig(
    address to,
    uint256 value,
    bytes calldata data,
    address signer,
    uint256 deadline,
    bytes calldata signature
) external payable returns (bytes memory result)
```

Executes a transaction from the IP Account on behalf of the signer.

**Parameters:**

* `to`: The recipient of the transaction
* `value`: The amount of Ether to send
* `data`: The data to send along with the transaction
* `signer`: The signer of the transaction
* `deadline`: The deadline of the transaction signature
* `signature`: The signature of the transaction, EIP-712 encoded

**Returns:**

* The return data from the transaction

### execute

```solidity  theme={null}
function execute(address to, uint256 value, bytes calldata data) external payable returns (bytes memory result)
```

Executes a transaction from the IP Account.

**Parameters:**

* `to`: The recipient of the transaction
* `value`: The amount of Ether to send
* `data`: The data to send along with the transaction

**Returns:**

* The return data from the transaction

### execute

```solidity  theme={null}
function execute(
    address to,
    uint256 value,
    bytes calldata data,
    uint8 operation
) public payable returns (bytes memory result)
```

Executes a transaction from the IP Account with a specified operation type.

**Parameters:**

* `to`: The recipient of the transaction
* `value`: The amount of Ether to send
* `data`: The data to send along with the transaction
* `operation`: The operation type to perform, only 0 - CALL is supported

**Returns:**

* The return data from the transaction

### executeBatch

```solidity  theme={null}
function executeBatch(
    Call[] calldata calls,
    uint8 operation
) public payable returns (bytes[] memory results)
```

Executes a batch of transactions from the IP Account.

**Parameters:**

* `calls`: The array of calls to execute
* `operation`: The operation type to perform, only 0 - CALL is supported

**Returns:**

* The return data from the transactions

### isValidSignature

```solidity  theme={null}
function isValidSignature(bytes32 hash, bytes calldata signature) public view returns (bytes4 result)
```

ERC1271 signature verification is disabled for the IP Account.

**Parameters:**

* `hash`: The hash of the data to be signed
* `signature`: The signature to verify

**Returns:**

* Always returns 0xffffffff (disabled)

## Events

### Executed

```solidity  theme={null}
event Executed(address to, uint256 value, bytes data, bytes32 state)
```

Emitted when a transaction is executed from the IP Account.

**Parameters:**

* `to`: The recipient of the transaction
* `value`: The amount of Ether sent
* `data`: The data sent along with the transaction
* `state`: The new state (nonce) of the account

### ExecutedWithSig

```solidity  theme={null}
event ExecutedWithSig(address to, uint256 value, bytes data, bytes32 state, uint256 deadline, address signer, bytes signature)
```

Emitted when a transaction is executed from the IP Account on behalf of a signer.

**Parameters:**

* `to`: The recipient of the transaction
* `value`: The amount of Ether sent
* `data`: The data sent along with the transaction
* `state`: The new state (nonce) of the account
* `deadline`: The deadline of the transaction signature
* `signer`: The signer of the transaction
* `signature`: The signature of the transaction

## Security Considerations

The IPAccountImpl contract implements several security measures:

1. **Permission System**: Uses an AccessController to manage permissions for different signers and operations.

2. **Signature Verification**: Implements EIP-712 typed data signing for secure transaction authorization.

3. **Deadline Checking**: Includes transaction deadlines to prevent replay attacks.

4. **Nonce Management**: Uses a state (nonce) system to prevent transaction replay.

5. **Input Validation**: Validates inputs and checks for edge cases, such as preventing invalid operations.

6. **Signature Malleability Protection**: Includes protections against signature malleability attacks.

7. **Limited Operations**: Only supports the CALL operation (0) for security reasons, restricting potentially dangerous operations.

8. **Upgradability Disabled**: The contract disables UUPS upgradability to ensure contract immutability.

## Usage Examples

### Executing a Transaction

An IP asset owner can execute a transaction through their IP Account:

```solidity  theme={null}
// Assuming 'ipAccount' is an instance of IPAccountImpl
ipAccount.execute(
    targetContract,
    0, // No ETH sent
    abi.encodeWithSignature("someFunction(uint256)", 123)
);
```

### Executing with a Signature

A permitted signer can execute a transaction on behalf of the IP Account:

```solidity  theme={null}
// Generate signature off-chain
bytes signature = signEIP712Message(...);

// Execute transaction
ipAccount.executeWithSig(
    targetContract,
    0, // No ETH sent
    abi.encodeWithSignature("someFunction(uint256)", 123),
    signer,
    deadline,
    signature
);
```
# DisputeModule

The Dispute Module acts as an enforcement layer for IP assets that allows raising and resolving disputes through arbitration by judges. It enables users to challenge IP assets that may violate rules or infringe on other IP rights.

## State Variables

### name

```solidity  theme={null}
string public constant override name = DISPUTE_MODULE_KEY
```

Returns the name of the module.

### IN\_DISPUTE

```solidity  theme={null}
bytes32 public constant IN_DISPUTE = bytes32("IN_DISPUTE")
```

Tag to represent the dispute is in dispute state waiting for judgement.

### LICENSE\_REGISTRY

```solidity  theme={null}
ILicenseRegistry public immutable LICENSE_REGISTRY
```

Returns the protocol-wide license registry.

### GROUP\_IP\_ASSET\_REGISTRY

```solidity  theme={null}
IGroupIPAssetRegistry public immutable GROUP_IP_ASSET_REGISTRY
```

Returns the protocol-wide group IP asset registry.

### IP\_GRAPH\_ACL

```solidity  theme={null}
IPGraphACL public immutable IP_GRAPH_ACL
```

Returns the protocol-wide IP Graph Access Control List.

## Functions

### initialize

```solidity  theme={null}
function initialize(address accessManager) external initializer
```

Initializer for this implementation contract.

**Parameters:**

* `accessManager`: The address of the protocol admin roles contract.

### whitelistDisputeTag

```solidity  theme={null}
function whitelistDisputeTag(bytes32 tag, bool allowed) external restricted
```

Whitelists a dispute tag.

**Parameters:**

* `tag`: The dispute tag.
* `allowed`: Indicates if the dispute tag is whitelisted or not.

### whitelistArbitrationPolicy

```solidity  theme={null}
function whitelistArbitrationPolicy(address arbitrationPolicy, bool allowed) external restricted
```

Whitelists an arbitration policy.

**Parameters:**

* `arbitrationPolicy`: The address of the arbitration policy.
* `allowed`: Indicates if the arbitration policy is whitelisted or not.

### setArbitrationRelayer

```solidity  theme={null}
function setArbitrationRelayer(address arbitrationPolicy, address arbPolicyRelayer) external restricted
```

Sets the arbitration relayer for a given arbitration policy.

**Parameters:**

* `arbitrationPolicy`: The address of the arbitration policy.
* `arbPolicyRelayer`: The address of the arbitration relayer.

### setBaseArbitrationPolicy

```solidity  theme={null}
function setBaseArbitrationPolicy(address arbitrationPolicy) external restricted
```

Sets the base arbitration policy.

**Parameters:**

* `arbitrationPolicy`: The address of the arbitration policy.

### setArbitrationPolicyCooldown

```solidity  theme={null}
function setArbitrationPolicyCooldown(uint256 cooldown) external restricted
```

Sets the arbitration policy cooldown.

**Parameters:**

* `cooldown`: The cooldown in seconds.

### setArbitrationPolicy

```solidity  theme={null}
function setArbitrationPolicy(
    address ipId,
    address nextArbitrationPolicy
) external whenNotPaused verifyPermission(ipId)
```

Sets the arbitration policy for an ipId.

**Parameters:**

* `ipId`: The ipId.
* `nextArbitrationPolicy`: The address of the arbitration policy.

### raiseDispute

```solidity  theme={null}
function raiseDispute(
    address targetIpId,
    bytes32 disputeEvidenceHash,
    bytes32 targetTag,
    bytes calldata data
) external nonReentrant whenNotPaused returns (uint256)
```

Raises a dispute on a given ipId.

**Parameters:**

* `targetIpId`: The ipId that is the target of the dispute.
* `disputeEvidenceHash`: The hash pointing to the dispute evidence.
* `targetTag`: The target tag of the dispute.
* `data`: The data to initialize the policy.

**Returns:**

* `disputeId`: The id of the newly raised dispute.

### setDisputeJudgement

```solidity  theme={null}
function setDisputeJudgement(
    uint256 disputeId,
    bool decision,
    bytes calldata data
) external nonReentrant whenNotPaused
```

Sets the dispute judgement on a given dispute. Only whitelisted arbitration relayers can call to judge.

**Parameters:**

* `disputeId`: The dispute id.
* `decision`: The decision of the dispute.
* `data`: The data to set the dispute judgement.

### cancelDispute

```solidity  theme={null}
function cancelDispute(uint256 disputeId, bytes calldata data) external nonReentrant whenNotPaused
```

Cancels an ongoing dispute.

**Parameters:**

* `disputeId`: The dispute id.
* `data`: The data to cancel the dispute.

### tagIfRelatedIpInfringed

```solidity  theme={null}
function tagIfRelatedIpInfringed(address ipIdToTag, uint256 infringerDisputeId) external whenNotPaused
```

Tags a derivative if a parent has been tagged with an infringement tag or a group ip if a group member has been tagged with an infringement tag.

**Parameters:**

* `ipIdToTag`: The ipId to tag.
* `infringerDisputeId`: The dispute id that tagged the related infringing ipId.

### resolveDispute

```solidity  theme={null}
function resolveDispute(uint256 disputeId, bytes calldata data) external nonReentrant whenNotPaused
```

Resolves a dispute after it has been judged.

**Parameters:**

* `disputeId`: The dispute id.
* `data`: The data to resolve the dispute.

### updateActiveArbitrationPolicy

```solidity  theme={null}
function updateActiveArbitrationPolicy(address ipId) external whenNotPaused returns (address arbitrationPolicy)
```

Updates the active arbitration policy for a given ipId.

**Parameters:**

* `ipId`: The ipId.

**Returns:**

* `arbitrationPolicy`: The address of the arbitration policy.

### isIpTagged

```solidity  theme={null}
function isIpTagged(address ipId) external view returns (bool)
```

Returns true if the ipId is tagged with any tag (meaning at least one dispute went through).

**Parameters:**

* `ipId`: The ipId.

**Returns:**

* `isTagged`: True if the ipId is tagged.

### disputeCounter

```solidity  theme={null}
function disputeCounter() external view returns (uint256)
```

Returns the dispute ID counter.

**Returns:**

* `uint256`: The current dispute counter value.

### arbitrationPolicyCooldown

```solidity  theme={null}
function arbitrationPolicyCooldown() external view returns (uint256)
```

Returns the arbitration policy cooldown.

**Returns:**

* `uint256`: The cooldown in seconds.

### baseArbitrationPolicy

```solidity  theme={null}
function baseArbitrationPolicy() external view returns (address)
```

Returns the address of the base arbitration policy.

**Returns:**

* `address`: The base arbitration policy address.

### disputes

```solidity  theme={null}
function disputes(
    uint256 disputeId
)
    external
    view
    returns (
        address targetIpId,
        address disputeInitiator,
        uint256 disputeTimestamp,
        address arbitrationPolicy,
        bytes32 disputeEvidenceHash,
        bytes32 targetTag,
        bytes32 currentTag,
        uint256 infringerDisputeId
    )
```

Returns the dispute information for a given dispute id.

**Parameters:**

* `disputeId`: The dispute id.

**Returns:**

* `targetIpId`: The ipId that is the target of the dispute.
* `disputeInitiator`: The address of the dispute initiator.
* `disputeTimestamp`: The timestamp of the dispute.
* `arbitrationPolicy`: The address of the arbitration policy.
* `disputeEvidenceHash`: The hash pointing to the dispute evidence.
* `targetTag`: The target tag of the dispute.
* `currentTag`: The current tag of the dispute.
* `infringerDisputeId`: The infringer dispute id.

### isWhitelistedDisputeTag

```solidity  theme={null}
function isWhitelistedDisputeTag(bytes32 tag) external view returns (bool allowed)
```

Indicates if a dispute tag is whitelisted.

**Parameters:**

* `tag`: The dispute tag.

**Returns:**

* `allowed`: True if the tag is whitelisted.

### isWhitelistedArbitrationPolicy

```solidity  theme={null}
function isWhitelistedArbitrationPolicy(address arbitrationPolicy) external view returns (bool allowed)
```

Indicates if an arbitration policy is whitelisted.

**Parameters:**

* `arbitrationPolicy`: The address of the arbitration policy.

**Returns:**

* `allowed`: True if the policy is whitelisted.

### arbitrationRelayer

```solidity  theme={null}
function arbitrationRelayer(address arbitrationPolicy) external view returns (address)
```

Returns the arbitration relayer for a given arbitration policy.

**Parameters:**

* `arbitrationPolicy`: The address of the arbitration policy.

**Returns:**

* `address`: The arbitration relayer address.

### arbitrationPolicies

```solidity  theme={null}
function arbitrationPolicies(address ipId) external view returns (address policy)
```

Returns the arbitration policy for a given ipId.

**Parameters:**

* `ipId`: The ipId.

**Returns:**

* `policy`: The arbitration policy address.

### nextArbitrationPolicies

```solidity  theme={null}
function nextArbitrationPolicies(address ipId) external view returns (address policy)
```

Returns the next arbitration policy for a given ipId.

**Parameters:**

* `ipId`: The ipId.

**Returns:**

* `policy`: The next arbitration policy address.

### nextArbitrationUpdateTimestamps

```solidity  theme={null}
function nextArbitrationUpdateTimestamps(address ipId) external view returns (uint256 timestamp)
```

Returns the next arbitration update timestamp for a given ipId.

**Parameters:**

* `ipId`: The ipId.

**Returns:**

* `timestamp`: The update timestamp.
# GroupingModule

The Grouping Module is the main entry point for the IPA grouping on Story. It is responsible for:

* Registering a group
* Adding IP to group
* Removing IP from group
* Claiming reward

## State Variables

### name

```solidity  theme={null}
string public constant override name = GROUPING_MODULE_KEY
```

Returns the name of the module.

### ROYALTY\_MODULE

```solidity  theme={null}
IRoyaltyModule public immutable ROYALTY_MODULE
```

Returns the canonical protocol-wide RoyaltyModule.

### LICENSE\_TOKEN

```solidity  theme={null}
ILicenseToken public immutable LICENSE_TOKEN
```

Returns the canonical protocol-wide LicenseToken.

### GROUP\_NFT

```solidity  theme={null}
IGroupNFT public immutable GROUP_NFT
```

Returns the address GROUP NFT contract.

### GROUP\_IP\_ASSET\_REGISTRY

```solidity  theme={null}
IGroupIPAssetRegistry public immutable GROUP_IP_ASSET_REGISTRY
```

Returns the canonical protocol-wide Group IP Asset Registry.

### LICENSE\_REGISTRY

```solidity  theme={null}
ILicenseRegistry public immutable LICENSE_REGISTRY
```

Returns the canonical protocol-wide LicenseRegistry.

### DISPUTE\_MODULE

```solidity  theme={null}
IDisputeModule public immutable DISPUTE_MODULE
```

Returns the protocol-wide dispute module.

## Functions

### initialize

```solidity  theme={null}
function initialize(address accessManager) public initializer
```

Initializer for this implementation contract.

**Parameters:**

* `accessManager`: The address of the protocol admin roles contract.

### registerGroup

```solidity  theme={null}
function registerGroup(address groupPool) external nonReentrant whenNotPaused returns (address groupId)
```

Registers a Group IPA.

**Parameters:**

* `groupPool`: The address of the group pool.

**Returns:**

* `groupId`: The address of the newly registered Group IPA.

### whitelistGroupRewardPool

```solidity  theme={null}
function whitelistGroupRewardPool(address rewardPool, bool allowed) external restricted
```

Whitelists a group reward pool.

**Parameters:**

* `rewardPool`: The address of the group reward pool.
* `allowed`: Whether the group reward pool is whitelisted.

### addIp

```solidity  theme={null}
function addIp(
    address groupIpId,
    address[] calldata ipIds,
    uint256 maxAllowedRewardShare
) external nonReentrant whenNotPaused verifyPermission(groupIpId)
```

Adds IP to group. The function must be called by the Group IP owner or an authorized operator.

**Parameters:**

* `groupIpId`: The address of the group IP.
* `ipIds`: The IP IDs.
* `maxAllowedRewardShare`: The maximum reward share percentage that can be allocated to each member IP.

### removeIp

```solidity  theme={null}
function removeIp(
    address groupIpId,
    address[] calldata ipIds
) external nonReentrant whenNotPaused verifyPermission(groupIpId)
```

Removes IP from group. The function must be called by the Group IP owner or an authorized operator.

**Parameters:**

* `groupIpId`: The address of the group IP.
* `ipIds`: The IP IDs.

### claimReward

```solidity  theme={null}
function claimReward(address groupId, address token, address[] calldata ipIds) external nonReentrant whenNotPaused
```

Claims reward.

**Parameters:**

* `groupId`: The address of the group.
* `token`: The address of the token.
* `ipIds`: The IP IDs.

### collectRoyalties

```solidity  theme={null}
function collectRoyalties(
    address groupId,
    address token
) external nonReentrant whenNotPaused returns (uint256 royalties)
```

Collects royalties into the pool, making them claimable by group member IPs.

**Parameters:**

* `groupId`: The address of the group.
* `token`: The address of the token.

**Returns:**

* `royalties`: The amount of royalties collected.

### name

```solidity  theme={null}
function name() external pure override returns (string memory)
```

Returns the name of the module.

**Returns:**

* `string`: The name of the module.

### getClaimableReward

```solidity  theme={null}
function getClaimableReward(
    address groupId,
    address token,
    address[] calldata ipIds
) external view returns (uint256[] memory)
```

Returns the available reward for each IP in the group.

**Parameters:**

* `groupId`: The address of the group.
* `token`: The address of the token.
* `ipIds`: The IP IDs.

**Returns:**

* `uint256[] memory`: The rewards for each IP.
# EvenSplitGroupPool

The EvenSplitGroupPool is a contract that implements the IGroupRewardPool interface and manages the distribution of rewards among IP members within a group. It uses an even split mechanism to distribute rewards fairly among all members.

## State Variables

### ROYALTY\_MODULE

```solidity  theme={null}
IRoyaltyModule public immutable ROYALTY_MODULE
```

The address of the protocol-wide Royalty Module.

### GROUPING\_MODULE

```solidity  theme={null}
IGroupingModule public immutable GROUPING_MODULE
```

The address of the protocol-wide Grouping Module.

### GROUP\_IP\_ASSET\_REGISTRY

```solidity  theme={null}
IGroupIPAssetRegistry public immutable GROUP_IP_ASSET_REGISTRY
```

The address of the protocol-wide Group IP Asset Registry.

### MAX\_GROUP\_SIZE

```solidity  theme={null}
uint32 public constant MAX_GROUP_SIZE = 1_000
```

The maximum number of IP members allowed in a group.

### GroupInfo

```solidity  theme={null}
struct GroupInfo {
    address token;
    uint32 totalMembers;
    uint128 pendingBalance;
    uint128 accRewardPerIp;
    uint256 averageRewardShare;
}
```

Storage structure for the GroupInfo:

* `token`: The reward token for the group, defined by the license terms attached to the group IP
* `totalMembers`: Total number of IPs in the group
* `pendingBalance`: Pending balance to be added to accRewardPerIp
* `accRewardPerIp`: Accumulated rewards per IP, times MAX\_GROUP\_SIZE
* `averageRewardShare`: The average reward share per IP, only increases as new IPs join with higher minimum share

## Functions

### initialize

```solidity  theme={null}
function initialize(address accessManager) public initializer
```

Initializes the EvenSplitGroupPool contract.

**Parameters:**

* `accessManager`: The address of the protocol admin roles contract.

### addIp

```solidity  theme={null}
function addIp(
    address groupId,
    address ipId,
    uint256 minimumGroupRewardShare
) external onlyGroupingModule returns (uint256 totalGroupRewardShare)
```

Adds an IP to the group pool. Only the GroupingModule can call this function.

**Parameters:**

* `groupId`: The group ID.
* `ipId`: The IP ID.
* `minimumGroupRewardShare`: The minimum group reward share the IP expects to be added to the group.

**Returns:**

* `totalGroupRewardShare`: The total group reward share after adding the IP.

### removeIp

```solidity  theme={null}
function removeIp(address groupId, address ipId) external onlyGroupingModule
```

Removes an IP from the group pool. Only the GroupingModule can call this function.

**Parameters:**

* `groupId`: The group ID.
* `ipId`: The IP ID.

### depositReward

```solidity  theme={null}
function depositReward(address groupId, address token, uint256 amount) external onlyGroupingModule
```

Deposits reward to the group pool directly.

**Parameters:**

* `groupId`: The group ID.
* `token`: The reward token.
* `amount`: The amount of reward.

### getAvailableReward

```solidity  theme={null}
function getAvailableReward(
    address groupId,
    address token,
    address[] calldata ipIds
) external view returns (uint256[] memory)
```

Returns the reward for each IP in the group.

**Parameters:**

* `groupId`: The group ID.
* `token`: The reward token.
* `ipIds`: The IP IDs.

**Returns:**

* `uint256[] memory`: The rewards for each IP.

### distributeRewards

```solidity  theme={null}
function distributeRewards(
    address groupId,
    address token,
    address[] calldata ipIds
) external whenNotPaused onlyGroupingModule returns (uint256[] memory rewards)
```

Distributes rewards to the given IP accounts in the pool.

**Parameters:**

* `groupId`: The group ID.
* `token`: The reward tokens.
* `ipIds`: The IP IDs.

**Returns:**

* `rewards`: An array containing the reward amounts distributed to each IP.

### getTotalIps

```solidity  theme={null}
function getTotalIps(address groupId) external view returns (uint256)
```

Returns the total number of IPs in the group.

**Parameters:**

* `groupId`: The group ID.

**Returns:**

* `uint256`: The total number of IPs in the group.

### getIpAddedTime

```solidity  theme={null}
function getIpAddedTime(address groupId, address ipId) external view returns (uint256)
```

Returns the timestamp when an IP was added to the group.

**Parameters:**

* `groupId`: The group ID.
* `ipId`: The IP ID.

**Returns:**

* `uint256`: The timestamp when the IP was added to the group.

### getIpRewardDebt

```solidity  theme={null}
function getIpRewardDebt(address groupId, address token, address ipId) external view returns (uint256)
```

Returns the reward debt of an IP in the group.

**Parameters:**

* `groupId`: The group ID.
* `token`: The reward token.
* `ipId`: The IP ID.

**Returns:**

* `uint256`: The reward debt of the IP.

### isIPAdded

```solidity  theme={null}
function isIPAdded(address groupId, address ipId) external view returns (bool)
```

Checks if an IP is added to the group.

**Parameters:**

* `groupId`: The group ID.
* `ipId`: The IP ID.

**Returns:**

* `bool`: True if the IP is added to the group, false otherwise.

### getMinimumRewardShare

```solidity  theme={null}
function getMinimumRewardShare(address groupId, address ipId) external view returns (uint256)
```

Returns the minimum reward share of an IP in the group.

**Parameters:**

* `groupId`: The group ID.
* `ipId`: The IP ID.

**Returns:**

* `uint256`: The minimum reward share of the IP.

### getTotalAllocatedRewardShare

```solidity  theme={null}
function getTotalAllocatedRewardShare(address groupId) external view returns (uint256)
```

Returns the total allocated reward share of the group.

**Parameters:**

* `groupId`: The group ID.

**Returns:**

* `uint256`: The total allocated reward share of the group.
# LicensingModule

The Licensing Module is the main entry point for the licensing system on Story. It is responsible for:

* Attaching license terms to IP assets
* Minting license tokens
* Registering derivatives

## State Variables

### name

```solidity  theme={null}
string public constant override name = LICENSING_MODULE_KEY
```

Returns the name of the module.

### ROYALTY\_MODULE

```solidity  theme={null}
RoyaltyModule public immutable ROYALTY_MODULE
```

Returns the canonical protocol-wide RoyaltyModule.

### LICENSE\_REGISTRY

```solidity  theme={null}
ILicenseRegistry public immutable LICENSE_REGISTRY
```

Returns the canonical protocol-wide LicenseRegistry.

### DISPUTE\_MODULE

```solidity  theme={null}
IDisputeModule public immutable DISPUTE_MODULE
```

Returns the protocol-wide dispute module.

### LICENSE\_NFT

```solidity  theme={null}
ILicenseToken public immutable LICENSE_NFT
```

Returns the License NFT.

### MODULE\_REGISTRY

```solidity  theme={null}
IModuleRegistry public immutable MODULE_REGISTRY
```

Returns the protocol-wide ModuleRegistry.

### IP\_GRAPH\_ACL

```solidity  theme={null}
IPGraphACL public immutable IP_GRAPH_ACL
```

Returns the protocol-wide IP Graph Access Control List.

## Functions

### initialize

```solidity  theme={null}
function initialize(address accessManager) public initializer
```

Initializer for this implementation contract.

**Parameters:**

* `accessManager`: The address of the protocol admin roles contract.

### attachDefaultLicenseTerms

```solidity  theme={null}
function attachDefaultLicenseTerms(address ipId) external
```

Attaches the default license terms to an IP.

**Parameters:**

* `ipId`: The IP ID to attach default license terms to.

### attachLicenseTerms

```solidity  theme={null}
function attachLicenseTerms(
    address ipId,
    address licenseTemplate,
    uint256 licenseTermsId
) external
```

Attaches specific license terms to an IP. The function must be called by the IP owner or an authorized operator.

**Parameters:**

* `ipId`: The IP ID.
* `licenseTemplate`: The address of the license template.
* `licenseTermsId`: The ID of the license terms.

### mintLicenseTokens

```solidity  theme={null}
function mintLicenseTokens(
    address licensorIpId,
    address licenseTemplate,
    uint256 licenseTermsId,
    uint256 amount,
    address receiver,
    bytes calldata royaltyContext,
    uint256 maxMintingFee,
    uint32 maxRevenueShare
) external returns (uint256 startLicenseTokenId)
```

Mints license tokens for the license terms attached to an IP. The license tokens are minted to the receiver.

The license terms must be attached to the IP before calling this function, but it can mint license tokens of default license terms without explicitly attaching them, since they are attached to all IPs by default.

IP owners can mint license tokens for their IPs for arbitrary license terms without attaching the license terms to the IP.

It might require the caller to pay a minting fee, depending on the license terms or as configured by the IP owner. The minting fee is paid in the minting fee token specified in the license terms or configured by the IP owner.

**Parameters:**

* `licensorIpId`: The licensor IP ID.
* `licenseTemplate`: The address of the license template.
* `licenseTermsId`: The ID of the license terms within the license template.
* `amount`: The amount of license tokens to mint.
* `receiver`: The address of the receiver.
* `royaltyContext`: The context of the royalty.
* `maxMintingFee`: The maximum minting fee that the caller is willing to pay. If set to 0, then no limit.
* `maxRevenueShare`: The maximum revenue share percentage allowed for minting the License Tokens.

**Returns:**

* `startLicenseTokenId`: The start ID of the minted license tokens.

### registerDerivative

```solidity  theme={null}
function registerDerivative(
    address childIpId,
    address[] calldata parentIpIds,
    uint256[] calldata licenseTermsIds,
    address licenseTemplate,
    bytes calldata royaltyContext,
    uint256 maxMintingFee,
    uint32 maxRts,
    uint32 maxRevenueShare
) external
```

Registers a derivative directly with parent IP's license terms, without needing license tokens, and attaches the license terms of the parent IPs to the derivative IP.

The license terms must be attached to the parent IP before calling this function. All IPs have default license terms attached by default.

The derivative IP owner must be the caller or an authorized operator.

**Parameters:**

* `childIpId`: The derivative IP ID.
* `parentIpIds`: The parent IP IDs.
* `licenseTermsIds`: The IDs of the license terms that the parent IP supports.
* `licenseTemplate`: The address of the license template of the license terms IDs.
* `royaltyContext`: The context of the royalty.
* `maxMintingFee`: The maximum minting fee that the caller is willing to pay. If set to 0, then no limit.
* `maxRts`: The maximum number of royalty tokens that can be distributed to the external royalty policies.
* `maxRevenueShare`: The maximum revenue share percentage allowed for minting the License Tokens.

### registerDerivativeWithLicenseTokens

```solidity  theme={null}
function registerDerivativeWithLicenseTokens(
    address childIpId,
    uint256[] calldata licenseTokenIds,
    bytes calldata royaltyContext,
    uint32 maxRts
) external
```

Registers a derivative with license tokens. The derivative IP is registered with license tokens minted from the parent IP's license terms.

The license terms of the parent IPs issued with license tokens are attached to the derivative IP.

The caller must be the derivative IP owner or an authorized operator.

**Parameters:**

* `childIpId`: The derivative IP ID.
* `licenseTokenIds`: The IDs of the license tokens.
* `royaltyContext`: The context of the royalty.
* `maxRts`: The maximum number of royalty tokens that can be distributed to the external royalty policies.

### setLicensingConfig

```solidity  theme={null}
function setLicensingConfig(
    address ipId,
    address licenseTemplate,
    uint256 licenseTermsId,
    Licensing.LicensingConfig memory licensingConfig
) external
```

Sets the licensing configuration for a specific license terms of an IP.

If both licenseTemplate and licenseTermsId are not specified, then the licensing config applies to all licenses of the given IP.

**Parameters:**

* `ipId`: The address of the IP for which the configuration is being set.
* `licenseTemplate`: The address of the license template used. If not specified, the configuration applies to all licenses.
* `licenseTermsId`: The ID of the license terms within the license template. If not specified, the configuration applies to all licenses.
* `licensingConfig`: The licensing configuration for the license.

### predictMintingLicenseFee

```solidity  theme={null}
function predictMintingLicenseFee(
    address licensorIpId,
    address licenseTemplate,
    uint256 licenseTermsId,
    uint256 amount,
    address receiver,
    bytes calldata royaltyContext
) external view returns (address currencyToken, uint256 tokenAmount)
```

Pre-computes the minting license fee for the given IP and license terms.

This function can be used to calculate the minting license fee before minting license tokens.

**Parameters:**

* `licensorIpId`: The IP ID of the licensor.
* `licenseTemplate`: The address of the license template.
* `licenseTermsId`: The ID of the license terms.
* `amount`: The amount of license tokens to mint.
* `receiver`: The address of the receiver.
* `royaltyContext`: The context of the royalty.

**Returns:**

* `currencyToken`: The address of the ERC20 token used for minting license fee.
* `tokenAmount`: The amount of the currency token to be paid for minting license tokens.
# PILicenseTemplate

The PILicenseTemplate (Programmable IP License Template) is a smart contract that defines and manages license terms for IP assets on Story. It allows IP owners to create customizable license terms that can be attached to their IP assets, enabling them to control how their IP can be used commercially and for derivative works.

## State Variables

### LICENSE\_REGISTRY

```solidity  theme={null}
ILicenseRegistry public immutable LICENSE_REGISTRY
```

The address of the License Registry contract that tracks license terms and tokens.

### ROYALTY\_MODULE

```solidity  theme={null}
IRoyaltyModule public immutable ROYALTY_MODULE
```

The address of the Royalty Module contract that handles royalty payments and policies.

### licenseTerms

```solidity  theme={null}
mapping(uint256 licenseTermsId => PILTerms) licenseTerms
```

Maps license terms IDs to their corresponding PILTerms structures.

### hashedLicenseTerms

```solidity  theme={null}
mapping(bytes32 licenseTermsHash => uint256 licenseTermsId) hashedLicenseTerms
```

Maps the hash of license terms to their corresponding license terms ID.

### licenseTermsCounter

```solidity  theme={null}
uint256 licenseTermsCounter
```

Counter for the number of registered license terms.

## Functions

### initialize

```solidity  theme={null}
function initialize(address accessManager, string memory name, string memory metadataURI) external initializer
```

Initializer for this implementation contract.

**Parameters:**

* `accessManager`: The address of the protocol admin roles contract.
* `name`: The name of the license template.
* `metadataURI`: The URL to the off-chain metadata.

### registerLicenseTerms

```solidity  theme={null}
function registerLicenseTerms(PILTerms calldata terms) external nonReentrant returns (uint256 id)
```

Registers new license terms and returns the ID of the newly registered license terms. The license terms are hashed and the hash is used to check if the terms are already registered. It will return an existing ID if the terms are already registered.

**Parameters:**

* `terms`: The PILTerms to register.

**Returns:**

* `id`: The ID of the newly registered license terms.

### exists

```solidity  theme={null}
function exists(uint256 licenseTermsId) external view override returns (bool)
```

Checks if a license terms exists.

**Parameters:**

* `licenseTermsId`: The ID of the license terms.

**Returns:**

* Returns true if the license terms exists, false otherwise.

### verifyMintLicenseToken

```solidity  theme={null}
function verifyMintLicenseToken(
    uint256 licenseTermsId,
    address licensee,
    address licensorIpId,
    uint256
) external override nonReentrant returns (bool)
```

Verifies the minting of a license token. The function will be called by the LicensingModule when minting a license token to verify if the minting is allowed by the license terms.

**Parameters:**

* `licenseTermsId`: The ID of the license terms.
* `licensee`: The address of the licensee who will receive the license token.
* `licensorIpId`: The IP ID of the licensor who attached the license terms minting the license token.

**Returns:**

* Returns true if the minting is verified, false otherwise.

### verifyRegisterDerivative

```solidity  theme={null}
function verifyRegisterDerivative(
    address childIpId,
    address parentIpId,
    uint256 licenseTermsId,
    address licensee
) external override returns (bool)
```

Verifies the registration of a derivative. This function is invoked by the LicensingModule during the registration of a derivative work to ensure compliance with the parent IP's licensing terms.

**Parameters:**

* `childIpId`: The IP ID of the derivative.
* `parentIpId`: The IP ID of the parent.
* `licenseTermsId`: The ID of the license terms.
* `licensee`: The address of the licensee.

**Returns:**

* Returns true if the registration is verified, false otherwise.

### verifyCompatibleLicenses

```solidity  theme={null}
function verifyCompatibleLicenses(uint256[] calldata licenseTermsIds) external view override returns (bool)
```

Verifies if the licenses are compatible. This function is called by the LicensingModule to verify license compatibility when registering a derivative IP to multiple parent IPs.

**Parameters:**

* `licenseTermsIds`: The IDs of the license terms.

**Returns:**

* Returns true if the licenses are compatible, false otherwise.

### verifyRegisterDerivativeForAllParents

```solidity  theme={null}
function verifyRegisterDerivativeForAllParents(
    address childIpId,
    address[] calldata parentIpIds,
    uint256[] calldata licenseTermsIds,
    address childIpOwner
) external override returns (bool)
```

Verifies the registration of a derivative for all parent IPs. This function is called by the LicensingModule to verify licenses for registering a derivative IP to multiple parent IPs.

**Parameters:**

* `childIpId`: The IP ID of the derivative.
* `parentIpIds`: The IP IDs of the parents.
* `licenseTermsIds`: The IDs of the license terms.
* `childIpOwner`: The address of the derivative IP owner.

**Returns:**

* Returns true if the registration is verified, false otherwise.

### getRoyaltyPolicy

```solidity  theme={null}
function getRoyaltyPolicy(
    uint256 licenseTermsId
) external view returns (address royaltyPolicy, bytes memory royaltyData, uint256 mintingFee, address currency)
```

Returns the royalty policy of a license terms.

**Parameters:**

* `licenseTermsId`: The ID of the license terms.

**Returns:**

* `royaltyPolicy`: The address of the royalty policy specified for the license terms.
* `royaltyData`: The data of the royalty policy.
* `mintingFee`: The fee for minting a license.
* `currency`: The address of the ERC20 token, used for minting license fee and royalties.

### isLicenseTransferable

```solidity  theme={null}
function isLicenseTransferable(uint256 licenseTermsId) external view override returns (bool)
```

Checks if a license terms is transferable.

**Parameters:**

* `licenseTermsId`: The ID of the license terms.

**Returns:**

* Returns true if the license terms is transferable, false otherwise.

### getEarlierExpireTime

```solidity  theme={null}
function getEarlierExpireTime(
    uint256[] calldata licenseTermsIds,
    uint256 start
) external view override returns (uint256)
```

Returns the earliest expiration time among the given license terms.

**Parameters:**

* `licenseTermsIds`: The IDs of the license terms.
* `start`: The start time.

**Returns:**

* Returns the earliest expiration time.

### getExpireTime

```solidity  theme={null}
function getExpireTime(uint256 licenseTermsId, uint256 start) external view returns (uint256)
```

Returns the expiration time of a license terms.

**Parameters:**

* `licenseTermsId`: The ID of the license terms.
* `start`: The start time.

**Returns:**

* Returns the expiration time.

### getLicenseTermsId

```solidity  theme={null}
function getLicenseTermsId(PILTerms calldata terms) external view returns (uint256 selectedLicenseTermsId)
```

Gets the ID of the given license terms.

**Parameters:**

* `terms`: The PILTerms to get the ID for.

**Returns:**

* `selectedLicenseTermsId`: The ID of the given license terms.

### getLicenseTerms

```solidity  theme={null}
function getLicenseTerms(uint256 selectedLicenseTermsId) external view returns (PILTerms memory terms)
```

Gets license terms of the given ID.

**Parameters:**

* `selectedLicenseTermsId`: The ID of the license terms.

**Returns:**

* `terms`: The PILTerms associated with the given ID.

### getLicenseTermsURI

```solidity  theme={null}
function getLicenseTermsURI(uint256 licenseTermsId) external view returns (string memory)
```

Returns the URI of the license terms.

**Parameters:**

* `licenseTermsId`: The ID of the license terms.

**Returns:**

* Returns the URI of the license terms.

### totalRegisteredLicenseTerms

```solidity  theme={null}
function totalRegisteredLicenseTerms() external view returns (uint256)
```

Returns the total number of registered license terms.

**Returns:**

* Returns the total number of registered license terms.

### supportsInterface

```solidity  theme={null}
function supportsInterface(
    bytes4 interfaceId
) public view virtual override(BaseLicenseTemplateUpgradeable, IERC165) returns (bool)
```

Checks whether the contract supports the given interface.

**Parameters:**

* `interfaceId`: The interface identifier.

**Returns:**

* Returns true if the contract supports the interface, false otherwise.

### toJson

```solidity  theme={null}
function toJson(uint256 licenseTermsId) public view returns (string memory)
```

Converts the license terms to a JSON string which will be part of the metadata of the license token.

**Parameters:**

* `licenseTermsId`: The ID of the license terms.

**Returns:**

* Returns the JSON string of the license terms, following the OpenSea metadata standard.

## PILTerms Structure

The PILTerms structure defines the terms for a Programmable IP License (PIL):

```solidity  theme={null}
struct PILTerms {
    bool transferable;
    address royaltyPolicy;
    uint256 mintingFee;
    uint256 expiration;
    bool commercialUse;
    bool commercialAttribution;
    address commercializerChecker;
    bytes commercializerCheckerData;
    uint32 commercialRevShare;
    uint256 commercialRevCelling;
    bool derivativesAllowed;
    bool derivativesAttribution;
    bool derivativesApproval;
    bool derivativesReciprocal;
    uint256 derivativeRevCelling;
    address currency;
    string uri;
}
```

**Parameters:**

* `transferable`: Indicates whether the license is transferable or not.
* `royaltyPolicy`: The address of the royalty policy contract which is required by StoryProtocol in advance.
* `mintingFee`: The fee to be paid when minting a license.
* `expiration`: The expiration period of the license.
* `commercialUse`: Indicates whether the work can be used commercially or not.
* `commercialAttribution`: Whether attribution is required when reproducing the work commercially or not.
* `commercializerChecker`: Commercializers that are allowed to commercially exploit the work. If zero address, then no restrictions are enforced.
* `commercializerCheckerData`: The data to be passed to the commercializer checker contract.
* `commercialRevShare`: Percentage of revenue that must be shared with the licensor.
* `commercialRevCelling`: The maximum revenue that can be generated from the commercial use of the work.
* `derivativesAllowed`: Indicates whether the licensee can create derivatives of their work or not.
* `derivativesAttribution`: Indicates whether attribution is required for derivatives of the work or not.
* `derivativesApproval`: Indicates whether the licensor must approve derivatives of the work before they can be linked to the licensor IP ID or not.
* `derivativesReciprocal`: Indicates whether the licensee must license derivatives of the work under the same terms or not.
* `derivativeRevCelling`: The maximum revenue that can be generated from the derivative use of the work.
* `currency`: The ERC20 token to be used to pay the minting fee. The token must be registered in Story Protocol.
* `uri`: The URI of the license terms, which can be used to fetch the off-chain license terms.
# LicenseToken

The LicenseToken contract, also known as LNFT (License NFT), is an ERC721 token that represents a license agreement for IP assets within the Story ecosystem. It enables the creation, transfer, and management of programmable IP licenses.

## State Variables

### LICENSE\_REGISTRY

```solidity  theme={null}
ILicenseRegistry public immutable LICENSE_REGISTRY
```

The address of the protocol-wide License Registry.

### LICENSING\_MODULE

```solidity  theme={null}
ILicensingModule public immutable LICENSING_MODULE
```

The address of the protocol-wide Licensing Module.

### DISPUTE\_MODULE

```solidity  theme={null}
IDisputeModule public immutable DISPUTE_MODULE
```

The address of the protocol-wide Dispute Module.

### MAX\_COMMERCIAL\_REVENUE\_SHARE

```solidity  theme={null}
uint32 public constant MAX_COMMERCIAL_REVENUE_SHARE = 100_000_000
```

The maximum royalty percentage is 100\_000\_000, which represents 100%.

### LicenseTokenMetadata

```solidity  theme={null}
struct LicenseTokenMetadata {
    address licensorIpId;
    address licenseTemplate;
    uint256 licenseTermsId;
    bool transferable;
    uint32 commercialRevShare;
}
```

Metadata structure for license tokens:

* `licensorIpId`: The IP asset that is the licensor
* `licenseTemplate`: The license template contract address
* `licenseTermsId`: The ID of the license terms
* `transferable`: Whether the license token can be transferred
* `commercialRevShare`: The commercial revenue share percentage

## Functions

### initialize

```solidity  theme={null}
function initialize(address accessManager, string memory imageUrl) public initializer
```

Initializes the LicenseToken contract.

**Parameters:**

* `accessManager`: The address of the access manager.
* `imageUrl`: The URL of the default image for license tokens.

### setLicensingImageUrl

```solidity  theme={null}
function setLicensingImageUrl(string calldata url) external restricted
```

Sets the licensing image URL for all license tokens.

**Parameters:**

* `url`: The URL of the licensing image.

### mintLicenseTokens

```solidity  theme={null}
function mintLicenseTokens(
    address licensorIpId,
    address licenseTemplate,
    uint256 licenseTermsId,
    uint256 amount,
    address minter,
    address receiver,
    uint32 maxRevenueShare
) external onlyLicensingModule returns (uint256 startLicenseTokenId)
```

Mints a specified amount of License Tokens (LNFTs).

**Parameters:**

* `licensorIpId`: The ID of the licensor IP for which the License Tokens are minted.
* `licenseTemplate`: The address of the License Template.
* `licenseTermsId`: The ID of the License Terms.
* `amount`: The amount of License Tokens to mint.
* `minter`: The address of the minter.
* `receiver`: The address of the receiver of the minted License Tokens.
* `maxRevenueShare`: The maximum revenue share percentage allowed for minting the License Tokens.

**Returns:**

* `startLicenseTokenId`: The start ID of the minted License Tokens.

### burnLicenseTokens

```solidity  theme={null}
function burnLicenseTokens(address holder, uint256[] calldata tokenIds) external onlyLicensingModule
```

Burns the License Tokens (LTs) for the given token IDs.

**Parameters:**

* `holder`: The address of the holder of the License Tokens.
* `tokenIds`: An array of IDs of the License Tokens to be burned.

### validateLicenseTokensForDerivative

```solidity  theme={null}
function validateLicenseTokensForDerivative(
    address caller,
    address childIpId,
    uint256[] calldata tokenIds
) external view returns (
    address licenseTemplate,
    address[] memory licensorIpIds,
    uint256[] memory licenseTermsIds,
    uint32[] memory commercialRevShares
)
```

Validates License Tokens for registering a derivative IP.

**Parameters:**

* `caller`: The address of the caller who register derivative with the given tokens.
* `childIpId`: The ID of the derivative IP.
* `tokenIds`: An array of IDs of the License Tokens to validate.

**Returns:**

* `licenseTemplate`: The address of the License Template associated with the License Tokens.
* `licensorIpIds`: An array of licensor IPs associated with each License Token.
* `licenseTermsIds`: An array of License Terms associated with each validated License Token.
* `commercialRevShares`: An array of commercial revenue share percentages associated with each License Token.

### totalMintedTokens

```solidity  theme={null}
function totalMintedTokens() external view returns (uint256)
```

Returns the total number of minted License Tokens since beginning. The number won't decrease when license tokens are burned.

**Returns:**

* `uint256`: The total number of minted License Tokens.

### getLicenseTokenMetadata

```solidity  theme={null}
function getLicenseTokenMetadata(uint256 tokenId) external view returns (LicenseTokenMetadata memory)
```

Returns the license data for the given license ID.

**Parameters:**

* `tokenId`: The ID of the license token.

**Returns:**

* `LicenseTokenMetadata`: The metadata of the license token.

### getLicensorIpId

```solidity  theme={null}
function getLicensorIpId(uint256 tokenId) external view returns (address)
```

Returns the ID of the IP asset that is the licensor of the given license ID.

**Parameters:**

* `tokenId`: The ID of the license token.

**Returns:**

* `address`: The ID of the licensor IP.

### getLicenseTermsId

```solidity  theme={null}
function getLicenseTermsId(uint256 tokenId) external view returns (uint256)
```

Returns the ID of the license terms that are used for the given license ID.

**Parameters:**

* `tokenId`: The ID of the license token.

**Returns:**

* `uint256`: The ID of the license terms.

### getLicenseTemplate

```solidity  theme={null}
function getLicenseTemplate(uint256 tokenId) external view returns (address)
```

Returns the address of the license template that is used for the given license ID.

**Parameters:**

* `tokenId`: The ID of the license token.

**Returns:**

* `address`: The address of the license template.

### getTotalTokensByLicensor

```solidity  theme={null}
function getTotalTokensByLicensor(address licensorIpId) external view returns (uint256)
```

Retrieves the total number of License Tokens minted for a given licensor IP.

**Parameters:**

* `licensorIpId`: The ID of the licensor IP.

**Returns:**

* `uint256`: The total number of License Tokens minted for the licensor IP.

### isLicenseTokenRevoked

```solidity  theme={null}
function isLicenseTokenRevoked(uint256 tokenId) public view returns (bool)
```

Returns true if the license has been revoked (licensor IP tagged after a dispute in the dispute module). If the tag is removed, the license is not revoked anymore.

**Parameters:**

* `tokenId`: The ID of the license token.

**Returns:**

* `bool`: True if the license is revoked.

### tokenURI

```solidity  theme={null}
function tokenURI(uint256 id) public view virtual override(ERC721Upgradeable, IERC721Metadata) returns (string memory)
```

ERC721 OpenSea metadata JSON representation of the LNFT parameters.

**Parameters:**

* `id`: The ID of the license token.

**Returns:**

* `string`: The metadata URI of the license token.
# CoreMetadataModule

The CoreMetadataModule manages the core metadata for IP assets within Story. It allows setting and updating metadata attributes for IP assets, with the ability to freeze metadata to prevent further changes.

## State Variables

### name

```solidity  theme={null}
string public constant override name = CORE_METADATA_MODULE_KEY
```

Returns the name of the module.

## Functions

### initialize

```solidity  theme={null}
function initialize(address accessManager) public initializer
```

Initializes the CoreMetadataModule contract.

**Parameters:**

* `accessManager`: The address of the protocol admin roles contract.

### name

```solidity  theme={null}
function name() external pure override returns (string memory)
```

Returns the name of the module.

**Returns:**

* `string`: The name of the module.

### updateNftTokenURI

```solidity  theme={null}
function updateNftTokenURI(address ipId, bytes32 nftMetadataHash) external verifyPermission(ipId)
```

Update the nftTokenURI for an IP asset by retrieving the latest TokenURI from the IP NFT to which the IP Asset is bound.

**Parameters:**

* `ipId`: The address of the IP asset.
* `nftMetadataHash`: A bytes32 hash representing the metadata of the NFT. This metadata is associated with the IP Asset and is accessible via the NFT's TokenURI. Use bytes32(0) to indicate that the metadata is not available.

### setMetadataURI

```solidity  theme={null}
function setMetadataURI(
    address ipId,
    string memory metadataURI,
    bytes32 metadataHash
) external verifyPermission(ipId)
```

Sets the metadataURI for an IP asset.

**Parameters:**

* `ipId`: The address of the IP asset.
* `metadataURI`: The metadataURI to set for the IP asset.
* `metadataHash`: The hash of metadata at metadataURI. Use bytes32(0) to indicate that the metadata is not available.

### setAll

```solidity  theme={null}
function setAll(
    address ipId,
    string memory metadataURI,
    bytes32 metadataHash,
    bytes32 nftMetadataHash
) external verifyPermission(ipId)
```

Sets all core metadata for an IP asset.

**Parameters:**

* `ipId`: The address of the IP asset.
* `metadataURI`: The metadataURI to set for the IP asset.
* `metadataHash`: The hash of metadata at metadataURI. Use bytes32(0) to indicate that the metadata is not available.
* `nftMetadataHash`: A bytes32 hash representing the metadata of the NFT. This metadata is associated with the IP Asset and is accessible via the NFT's TokenURI. Use bytes32(0) to indicate that the metadata is not available.

### freezeMetadata

```solidity  theme={null}
function freezeMetadata(address ipId) external verifyPermission(ipId)
```

Makes all metadata of the IP Asset immutable.

**Parameters:**

* `ipId`: The address of the IP asset.

### isMetadataFrozen

```solidity  theme={null}
function isMetadataFrozen(address ipId) external view returns (bool)
```

Checks if the metadata of the IP Asset is immutable.

**Parameters:**

* `ipId`: The address of the IP asset.

**Returns:**

* `bool`: True if the metadata is frozen, false otherwise.

### supportsInterface

```solidity  theme={null}
function supportsInterface(bytes4 interfaceId) public view virtual override(BaseModule, IERC165) returns (bool)
```

Implements the IERC165 interface.

**Parameters:**

* `interfaceId`: The interface identifier.

**Returns:**

* `bool`: True if the contract supports the interface, false otherwise.
# CoreMetadataViewModule

The CoreMetadataViewModule is a view module that provides read-only access to core metadata of IP assets within Story. It retrieves metadata information such as metadataURI, metadataHash, NFT token URI, and registration date from the IP assets.

## State Variables

### name

```solidity  theme={null}
string public constant override name = CORE_METADATA_VIEW_MODULE_KEY
```

Returns the name of the module.

### IP\_ASSET\_REGISTRY

```solidity  theme={null}
address public immutable IP_ASSET_REGISTRY
```

The address of the IP Asset Registry contract.

### MODULE\_REGISTRY

```solidity  theme={null}
address public immutable MODULE_REGISTRY
```

The address of the Module Registry contract.

### coreMetadataModule

```solidity  theme={null}
address public coreMetadataModule
```

The address of the CoreMetadataModule contract.

## Functions

### constructor

```solidity  theme={null}
constructor(address ipAssetRegistry, address moduleRegistry)
```

Initializes the CoreMetadataViewModule contract.

**Parameters:**

* `ipAssetRegistry`: The address of the IP Asset Registry contract.
* `moduleRegistry`: The address of the Module Registry contract.

### updateCoreMetadataModule

```solidity  theme={null}
function updateCoreMetadataModule() external
```

Updates the address of the CoreMetadataModule used by this view module by retrieving it from the ModuleRegistry.

### getCoreMetadata

```solidity  theme={null}
function getCoreMetadata(address ipId) external view returns (CoreMetadata memory)
```

Retrieves all core metadata of the IP asset.

**Parameters:**

* `ipId`: The address of the IP asset.

**Returns:**

* `CoreMetadata`: A struct containing all core metadata of the IP asset.

### getMetadataURI

```solidity  theme={null}
function getMetadataURI(address ipId) public view returns (string memory)
```

Retrieves the metadataURI of the IP asset set by CoreMetadataModule.

**Parameters:**

* `ipId`: The address of the IP asset.

**Returns:**

* `string`: The metadataURI of the IP asset.

### getMetadataHash

```solidity  theme={null}
function getMetadataHash(address ipId) public view returns (bytes32)
```

Retrieves the metadata hash of the IP asset set by CoreMetadataModule.

**Parameters:**

* `ipId`: The address of the IP asset.

**Returns:**

* `bytes32`: The metadata hash of the IP asset.

### getRegistrationDate

```solidity  theme={null}
function getRegistrationDate(address ipId) public view returns (uint256)
```

Retrieves the registration date of the IP asset from IPAssetRegistry.

**Parameters:**

* `ipId`: The address of the IP asset.

**Returns:**

* `uint256`: The registration date of the IP asset.

### getNftTokenURI

```solidity  theme={null}
function getNftTokenURI(address ipId) public view returns (string memory)
```

Retrieves the TokenURI of NFT to which the IP asset is bound, preferring the TokenURI from CoreMetadataModule if available.

**Parameters:**

* `ipId`: The address of the IP asset.

**Returns:**

* `string`: The NFT TokenURI bound to the IP asset.

### getNftMetadataHash

```solidity  theme={null}
function getNftMetadataHash(address ipId) public view returns (bytes32)
```

Retrieves the NFT metadata hash of the IP asset set by CoreMetadataModule.

**Parameters:**

* `ipId`: The address of the IP asset.

**Returns:**

* `bytes32`: The NFT metadata hash of the IP asset.

### getOwner

```solidity  theme={null}
function getOwner(address ipId) public view returns (address)
```

Retrieves the owner of the IP asset.

**Parameters:**

* `ipId`: The address of the IP asset.

**Returns:**

* `address`: The address of the owner of the IP asset.

### getJsonString

```solidity  theme={null}
function getJsonString(address ipId) external view returns (string memory)
```

Generates a JSON string formatted according to the standard NFT metadata schema for the IP asset, including all relevant metadata fields. This function consolidates metadata from both IPAssetRegistry and CoreMetadataModule, with "NFT TokenURI" from CoreMetadataModule taking precedence.

**Parameters:**

* `ipId`: The address of the IP asset.

**Returns:**

* `string`: A base64-encoded JSON string representing all metadata of the IP asset.

### isSupported

```solidity  theme={null}
function isSupported(address ipAccount) external view returns (bool)
```

Checks whether the view module is supported for the given IP account.

**Parameters:**

* `ipAccount`: The address of the IP account.

**Returns:**

* `bool`: True if the view module is supported, false otherwise.

### supportsInterface

```solidity  theme={null}
function supportsInterface(bytes4 interfaceId) public view virtual override(BaseModule, IERC165) returns (bool)
```

Implements the IERC165 interface.

**Parameters:**

* `interfaceId`: The interface identifier.

**Returns:**

* `bool`: True if the contract supports the interface, false otherwise.
# IPAssetRegistry

The IPAssetRegistry acts as the source of truth for all IP registered on Story. An IP is identified by its contract address, token id, and chain id, meaning any NFT may be conceptualized as an IP. Once an IP is registered into the protocol, a corresponding IP asset is generated, which references an IP resolver for metadata attribution and an IP account for protocol authorization.

## State Variables

### totalSupply

```solidity  theme={null}
uint256 totalSupply
```

The total number of IP assets registered in the protocol.

### treasury

```solidity  theme={null}
address treasury
```

The address of the treasury that receives registration fees.

### feeToken

```solidity  theme={null}
address feeToken
```

The address of the token used to pay registration fees.

### feeAmount

```solidity  theme={null}
uint96 feeAmount
```

The amount of the registration fee.

## Functions

### initialize

```solidity  theme={null}
function initialize(address accessManager) public initializer
```

Initializes the IPAssetRegistry contract.

**Parameters:**

* `accessManager`: The address of the access manager.

### register

```solidity  theme={null}
function register(
    uint256 chainid,
    address tokenContract,
    uint256 tokenId
) external whenNotPaused returns (address id)
```

Registers an NFT as an IP asset and creates an IP account for it. If the IP was already registered, returns the IP address.

**Parameters:**

* `chainid`: The chain identifier of where the IP NFT resides.
* `tokenContract`: The address of the NFT.
* `tokenId`: The token identifier of the NFT.

**Returns:**

* `id`: The address of the newly registered IP.

### setRegistrationFee

```solidity  theme={null}
function setRegistrationFee(address treasury, address feeToken, uint96 feeAmount) external restricted
```

Sets the registration fee for IP assets.

**Parameters:**

* `treasury`: The address of the treasury that will receive the fee.
* `feeToken`: The address of the token used to pay the fee.
* `feeAmount`: The amount of the fee.

### upgradeIPAccountImpl

```solidity  theme={null}
function upgradeIPAccountImpl(address newIpAccountImpl) external restricted
```

Upgrades the IP account implementation.

**Parameters:**

* `newIpAccountImpl`: The address of the new IP account implementation.

### ipId

```solidity  theme={null}
function ipId(uint256 chainId, address tokenContract, uint256 tokenId) public view returns (address)
```

Gets the canonical IP identifier associated with an IP NFT. This is equivalent to the address of its bound IP account.

**Parameters:**

* `chainId`: The chain identifier of where the IP resides.
* `tokenContract`: The address of the IP.
* `tokenId`: The token identifier of the IP.

**Returns:**

* `ipId`: The IP's canonical address identifier.

### isRegistered

```solidity  theme={null}
function isRegistered(address id) external view returns (bool)
```

Checks whether an IP was registered based on its ID.

**Parameters:**

* `id`: The canonical identifier for the IP.

**Returns:**

* `isRegistered`: Whether the IP was registered into the protocol.

### totalSupply

```solidity  theme={null}
function totalSupply() external view returns (uint256)
```

Gets the total number of IP assets registered in the protocol.

**Returns:**

* `uint256`: The total number of IP assets registered.

### getTreasury

```solidity  theme={null}
function getTreasury() external view returns (address)
```

Retrieves the treasury address for IP assets.

**Returns:**

* `treasury`: The address of the treasury.

### getFeeToken

```solidity  theme={null}
function getFeeToken() external view returns (address)
```

Retrieves the registration fee token for IP assets.

**Returns:**

* `feeToken`: The address of the token used to pay the fee.

### getFeeAmount

```solidity  theme={null}
function getFeeAmount() external view returns (uint96)
```

Retrieves the registration fee amount for IP assets.

**Returns:**

* `feeAmount`: The amount of the fee.
# IPAccountRegistry

The IPAccountRegistry is responsible for managing the registration and tracking of IP Accounts. It leverages a public ERC6551 registry to deploy IPAccount contracts, which represent tokenized intellectual property assets within the Story ecosystem.

## State Variables

### IP\_ACCOUNT\_IMPL

```solidity  theme={null}
address public immutable IP_ACCOUNT_IMPL
```

Returns the IPAccount implementation address.

### IP\_ACCOUNT\_SALT

```solidity  theme={null}
bytes32 public immutable IP_ACCOUNT_SALT
```

Returns the IPAccount salt.

### ERC6551\_PUBLIC\_REGISTRY

```solidity  theme={null}
address public immutable ERC6551_PUBLIC_REGISTRY
```

Returns the public ERC6551 registry address.

### IP\_ACCOUNT\_IMPL\_UPGRADEABLE\_BEACON

```solidity  theme={null}
address public immutable IP_ACCOUNT_IMPL_UPGRADEABLE_BEACON
```

The IPAccount implementation upgradeable beacon address.

## Functions

### ipAccount

```solidity  theme={null}
function ipAccount(uint256 chainId, address tokenContract, uint256 tokenId) public view returns (address)
```

Returns the IPAccount address for the given NFT token.

**Parameters:**

* `chainId`: The chain ID where the IP Account is located.
* `tokenContract`: The address of the token contract associated with the IP Account.
* `tokenId`: The ID of the token associated with the IP Account.

**Returns:**

* `ipAccountAddress`: The address of the IP Account associated with the given NFT token.

### getIPAccountImpl

```solidity  theme={null}
function getIPAccountImpl() external view override returns (address)
```

Returns the IPAccount implementation address.

**Returns:**

* `address`: The address of the IPAccount implementation.

### \_registerIpAccount (internal)

```solidity  theme={null}
function _registerIpAccount(
    uint256 chainId,
    address tokenContract,
    uint256 tokenId
) internal returns (address ipAccountAddress)
```

Deploys an IPAccount contract with the IPAccount implementation and returns the address of the new IP. The IPAccount deployment delegates to public ERC6551 Registry.

**Parameters:**

* `chainId`: The chain ID where the IP Account will be created.
* `tokenContract`: The address of the token contract to be associated with the IP Account.
* `tokenId`: The ID of the token to be associated with the IP Account.

**Returns:**

* `ipAccountAddress`: The address of the newly created IP Account.

### \_get6551AccountAddress (internal)

```solidity  theme={null}
function _get6551AccountAddress(
    uint256 chainId,
    address tokenContract,
    uint256 tokenId
) internal view returns (address)
```

Helper function to get the IPAccount address from the ERC6551 registry.

**Parameters:**

* `chainId`: The chain ID where the IP Account is located.
* `tokenContract`: The address of the token contract associated with the IP Account.
* `tokenId`: The ID of the token associated with the IP Account.

**Returns:**

* `address`: The address of the IP Account.

### \_upgradeIPAccountImpl (internal)

```solidity  theme={null}
function _upgradeIPAccountImpl(address newIpAccountImpl) internal
```

Helper function to upgrade the IPAccount implementation.

**Parameters:**

* `newIpAccountImpl`: The address of the new IPAccount implementation.
# LicenseRegistry

The LicenseRegistry manages the registration and tracking of License NFTs (LNFTs), which represent licenses granted by IP ID licensors to create derivative IPs. It provides functionality for managing license templates, license terms, and the relationships between parent and derivative IP assets.

## State Variables

### MAX\_PARENTS

```solidity  theme={null}
uint256 public constant MAX_PARENTS = 16
```

The maximum number of parent IPs a derivative IP can have.

### MAX\_ANCESTORS

```solidity  theme={null}
uint256 public constant MAX_ANCESTORS = 1024
```

The maximum number of ancestor IPs a derivative IP can have.

### IP\_GRAPH

```solidity  theme={null}
address public constant IP_GRAPH = address(0x0101)
```

The address of the IP Graph contract that tracks relationships between IPs.

### GROUP\_IP\_ASSET\_REGISTRY

```solidity  theme={null}
IGroupIPAssetRegistry public immutable GROUP_IP_ASSET_REGISTRY
```

The address of the Group IP Asset Registry contract.

### LICENSING\_MODULE

```solidity  theme={null}
ILicensingModule public immutable LICENSING_MODULE
```

The address of the Licensing Module contract.

### DISPUTE\_MODULE

```solidity  theme={null}
IDisputeModule public immutable DISPUTE_MODULE
```

The address of the Dispute Module contract.

### IP\_GRAPH\_ACL

```solidity  theme={null}
IPGraphACL public immutable IP_GRAPH_ACL
```

The address of the IP Graph Access Control List contract.

### EXPIRATION\_TIME

```solidity  theme={null}
bytes32 public constant EXPIRATION_TIME = "EXPIRATION_TIME"
```

The key used to store expiration time in IP Account storage.

## Functions

### initialize

```solidity  theme={null}
function initialize(address accessManager) public initializer
```

Initializes the LicenseRegistry contract.

**Parameters:**

* `accessManager`: The address of the protocol admin roles contract.

### setDefaultLicenseTerms

```solidity  theme={null}
function setDefaultLicenseTerms(address newLicenseTemplate, uint256 newLicenseTermsId) external restricted
```

Sets the default license terms that are attached to all IPs by default.

**Parameters:**

* `newLicenseTemplate`: The address of the new default license template.
* `newLicenseTermsId`: The ID of the new default license terms.

### registerLicenseTemplate

```solidity  theme={null}
function registerLicenseTemplate(address licenseTemplate) external restricted
```

Registers a new license template on Story.

**Parameters:**

* `licenseTemplate`: The address of the license template to register.

### setLicensingConfigForLicense

```solidity  theme={null}
function setLicensingConfigForLicense(
    address ipId,
    address licenseTemplate,
    uint256 licenseTermsId,
    Licensing.LicensingConfig calldata licensingConfig
) external onlyLicensingModule
```

Sets the minting license configuration for a specific license attached to a specific IP.

**Parameters:**

* `ipId`: The address of the IP for which the configuration is being set.
* `licenseTemplate`: The address of the license template used.
* `licenseTermsId`: The ID of the license terms within the license template.
* `licensingConfig`: The configuration for minting the license.

### attachLicenseTermsToIp

```solidity  theme={null}
function attachLicenseTermsToIp(
    address ipId,
    address licenseTemplate,
    uint256 licenseTermsId
) external onlyLicensingModule
```

Attaches license terms to an IP.

**Parameters:**

* `ipId`: The address of the IP to which the license terms are attached.
* `licenseTemplate`: The address of the license template.
* `licenseTermsId`: The ID of the license terms.

### registerDerivativeIp

```solidity  theme={null}
function registerDerivativeIp(
    address childIpId,
    address[] calldata parentIpIds,
    address licenseTemplate,
    uint256[] calldata licenseTermsIds,
    bool isUsingLicenseToken
) external onlyLicensingModule
```

Registers a derivative IP and its relationship to parent IPs.

**Parameters:**

* `childIpId`: The address of the derivative IP.
* `parentIpIds`: An array of addresses of the parent IPs.
* `licenseTemplate`: The address of the license template used.
* `licenseTermsIds`: An array of IDs of the license terms.
* `isUsingLicenseToken`: Whether the derivative IP is registered with license tokens.

### initializeLicenseTemplate

```solidity  theme={null}
function initializeLicenseTemplate(address ipId, address licenseTemplate) external onlyLicensingModule
```

Sets license template for an IP, if the IP has no license template set.

**Parameters:**

* `ipId`: The address of the IP to which the license template is attached.
* `licenseTemplate`: The address of the license template.

### verifyMintLicenseToken

```solidity  theme={null}
function verifyMintLicenseToken(
    address licensorIpId,
    address licenseTemplate,
    uint256 licenseTermsId,
    bool isMintedByIpOwner
) external view returns (Licensing.LicensingConfig memory)
```

Verifies the minting of a license token.

**Parameters:**

* `licensorIpId`: The address of the licensor IP.
* `licenseTemplate`: The address of the license template where the license terms are defined.
* `licenseTermsId`: The ID of the license terms will mint the license token.
* `isMintedByIpOwner`: Whether the license token is minted by the IP owner.

**Returns:**

* `Licensing.LicensingConfig`: The configuration for minting the license.

### verifyGroupAddIp

```solidity  theme={null}
function verifyGroupAddIp(
    address groupId,
    address groupRewardPool,
    address ipId,
    address groupLicenseTemplate,
    uint256 groupLicenseTermsId
) external view returns (Licensing.LicensingConfig memory ipLicensingConfig)
```

Verifies the group can add given IP.

**Parameters:**

* `groupId`: The address of the group.
* `groupRewardPool`: The address of the reward pool of the group.
* `ipId`: The address of the IP to be added to the group.
* `groupLicenseTemplate`: The address of the license template attached to the group.
* `groupLicenseTermsId`: The ID of the license terms attached to the group.

**Returns:**

* `ipLicensingConfig`: The configuration for license attached to the IP.

### isRegisteredLicenseTemplate

```solidity  theme={null}
function isRegisteredLicenseTemplate(address licenseTemplate) external view returns (bool)
```

Checks if a license template is registered.

**Parameters:**

* `licenseTemplate`: The address of the license template to check.

**Returns:**

* `bool`: Whether the license template is registered.

### isDerivativeIp

```solidity  theme={null}
function isDerivativeIp(address childIpId) external view returns (bool)
```

Checks if an IP is a derivative IP.

**Parameters:**

* `childIpId`: The address of the IP to check.

**Returns:**

* `bool`: Whether the IP is a derivative IP.

### hasDerivativeIps

```solidity  theme={null}
function hasDerivativeIps(address parentIpId) external view returns (bool)
```

Checks if an IP has derivative IPs.

**Parameters:**

* `parentIpId`: The address of the IP to check.

**Returns:**

* `bool`: Whether the IP has derivative IPs.

### exists

```solidity  theme={null}
function exists(address licenseTemplate, uint256 licenseTermsId) external view returns (bool)
```

Checks if license terms exist.

**Parameters:**

* `licenseTemplate`: The address of the license template where the license terms are defined.
* `licenseTermsId`: The ID of the license terms.

**Returns:**

* `bool`: Whether the license terms exist.

### hasIpAttachedLicenseTerms

```solidity  theme={null}
function hasIpAttachedLicenseTerms(
    address ipId,
    address licenseTemplate,
    uint256 licenseTermsId
) external view returns (bool)
```

Checks if an IP has attached any license terms.

**Parameters:**

* `ipId`: The address of the IP to check.
* `licenseTemplate`: The address of the license template where the license terms are defined.
* `licenseTermsId`: The ID of the license terms.

**Returns:**

* `bool`: Whether the IP has attached any license terms.

### getAttachedLicenseTerms

```solidity  theme={null}
function getAttachedLicenseTerms(
    address ipId,
    uint256 index
) external view returns (address licenseTemplate, uint256 licenseTermsId)
```

Gets the attached license terms of an IP by its index.

**Parameters:**

* `ipId`: The address of the IP.
* `index`: The index of the attached license terms within the array of all attached license terms of the IP.

**Returns:**

* `licenseTemplate`: The address of the license template where the license terms are defined.
* `licenseTermsId`: The ID of the license terms.

### getAttachedLicenseTermsCount

```solidity  theme={null}
function getAttachedLicenseTermsCount(address ipId) external view returns (uint256)
```

Gets the count of attached license terms of an IP.

**Parameters:**

* `ipId`: The address of the IP.

**Returns:**

* `uint256`: The count of attached license terms.

### getDerivativeIp

```solidity  theme={null}
function getDerivativeIp(address parentIpId, uint256 index) external view returns (address childIpId)
```

Gets the derivative IP of an IP by its index.

**Parameters:**

* `parentIpId`: The address of the IP.
* `index`: The index of the derivative IP within the array of all derivative IPs of the IP.

**Returns:**

* `childIpId`: The address of the derivative IP.

### getDerivativeIpCount

```solidity  theme={null}
function getDerivativeIpCount(address parentIpId) external view returns (uint256)
```

Gets the count of derivative IPs of an IP.

**Parameters:**

* `parentIpId`: The address of the IP.

**Returns:**

* `uint256`: The count of derivative IPs.

### getParentIp

```solidity  theme={null}
function getParentIp(address childIpId, uint256 index) external view returns (address parentIpId)
```

Gets the parent IP of an IP by its index.

**Parameters:**

* `childIpId`: The address of the IP.
* `index`: The index of the parent IP within the array of all parent IPs of the IP.

**Returns:**

* `parentIpId`: The address of the parent IP.

### isParentIp

```solidity  theme={null}
function isParentIp(address parentIpId, address childIpId) external view returns (bool)
```

Checks if an IP is a parent of another IP.

**Parameters:**

* `parentIpId`: The address of the potential parent IP.
* `childIpId`: The address of the potential child IP.

**Returns:**

* `bool`: Whether the IP is a parent of the other IP.

### getParentIpCount

```solidity  theme={null}
function getParentIpCount(address childIpId) external view returns (uint256)
```

Gets the count of parent IPs.

**Parameters:**

* `childIpId`: The address of the child IP.

**Returns:**

* `uint256`: The count of parent IPs.

### getAncestorsCount

```solidity  theme={null}
function getAncestorsCount(address ipId) external returns (uint256)
```

Gets the count of ancestors IPs.

**Parameters:**

* `ipId`: The ID of IP asset.

**Returns:**

* `uint256`: The count of ancestor IPs.

### getLicensingConfig

```solidity  theme={null}
function getLicensingConfig(
    address ipId,
    address licenseTemplate,
    uint256 licenseTermsId
) external view returns (Licensing.LicensingConfig memory)
```

Retrieves the minting license configuration for a given license terms of the IP.

**Parameters:**

* `ipId`: The address of the IP.
* `licenseTemplate`: The address of the license template where the license terms are defined.
* `licenseTermsId`: The ID of the license terms.

**Returns:**

* `Licensing.LicensingConfig`: The configuration for minting the license.

### getExpireTime

```solidity  theme={null}
function getExpireTime(address ipId) external view returns (uint256)
```

Gets the expiration time for an IP.

**Parameters:**

* `ipId`: The address of the IP.

**Returns:**

* `uint256`: The expiration time, 0 means never expired.

### isExpiredNow

```solidity  theme={null}
function isExpiredNow(address ipId) external view returns (bool)
```

Checks if an IP is expired.

**Parameters:**

* `ipId`: The address of the IP.

**Returns:**

* `bool`: Whether the IP is expired.

### getDefaultLicenseTerms

```solidity  theme={null}
function getDefaultLicenseTerms() external view returns (address licenseTemplate, uint256 licenseTermsId)
```

Returns the default license terms.

**Returns:**

* `licenseTemplate`: The address of the default license template.
* `licenseTermsId`: The ID of the default license terms.

### isDefaultLicense

```solidity  theme={null}
function isDefaultLicense(address licenseTemplate, uint256 licenseTermsId) external view returns (bool)
```

Checks if the license terms are the default license terms.

**Parameters:**

* `licenseTemplate`: The address of the license template.
* `licenseTermsId`: The ID of the license terms.

**Returns:**

* `bool`: Whether the license terms are the default license terms.

### getParentLicenseTerms

```solidity  theme={null}
function getParentLicenseTerms(
    address childIpId,
    address parentIpId
) external view returns (address licenseTemplate, uint256 licenseTermsId)
```

Returns the license terms through which a child IP links to a parent IP.

**Parameters:**

* `childIpId`: The address of the child IP.
* `parentIpId`: The address of the parent IP.

**Returns:**

* `licenseTemplate`: The address of the license template.
* `licenseTermsId`: The ID of the license terms.

### getRoyaltyPercent

```solidity  theme={null}
function getRoyaltyPercent(
    address ipId,
    address licenseTemplate,
    uint256 licenseTermsId
) external view returns (uint32 royaltyPercent)
```

Return the Royalty percentage of the license terms of the IP.

**Parameters:**

* `ipId`: The address of the IP.
* `licenseTemplate`: The address of the license template where the license terms are defined.
* `licenseTermsId`: The ID of the license terms.

**Returns:**

* `royaltyPercent`: The Royalty percentage 100% is 100\_000\_000.
# GroupIPAssetRegistry

The GroupIPAssetRegistry manages the registration and tracking of Group IP Assets (IPAs), including the group members and reward pools. It provides functionality for registering groups, managing group membership, and handling group reward pools.

## State Variables

### MAX\_GROUP\_SIZE

```solidity  theme={null}
uint256 public constant MAX_GROUP_SIZE = 1000
```

The maximum number of members allowed in a group.

### GROUPING\_MODULE

```solidity  theme={null}
IGroupingModule public immutable GROUPING_MODULE
```

The address of the protocol-wide Grouping Module.

## Functions

### registerGroup

```solidity  theme={null}
function registerGroup(
    address groupNft,
    uint256 groupNftId,
    address rewardPool,
    address registerFeePayer
) external onlyGroupingModule whenNotPaused returns (address groupId)
```

Registers a Group IPA.

**Parameters:**

* `groupNft`: The address of the group NFT.
* `groupNftId`: The ID of the group NFT.
* `rewardPool`: The address of the group reward pool.
* `registerFeePayer`: The address of the account that pays the registration fee.

**Returns:**

* `groupId`: The address of the newly registered Group IPA.

### whitelistGroupRewardPool

```solidity  theme={null}
function whitelistGroupRewardPool(address rewardPool, bool allowed) external onlyGroupingModule whenNotPaused
```

Whitelists a group reward pool.

**Parameters:**

* `rewardPool`: The address of the group reward pool.
* `allowed`: Whether the group reward pool is whitelisted.

### addGroupMember

```solidity  theme={null}
function addGroupMember(address groupId, address[] calldata ipIds) external onlyGroupingModule whenNotPaused
```

Adds members to a Group IPA.

**Parameters:**

* `groupId`: The address of the Group IPA.
* `ipIds`: The addresses of the IPs to add to the Group IPA.

### removeGroupMember

```solidity  theme={null}
function removeGroupMember(address groupId, address[] calldata ipIds) external onlyGroupingModule whenNotPaused
```

Removes members from a Group IPA.

**Parameters:**

* `groupId`: The address of the Group IPA.
* `ipIds`: The addresses of the IPs to remove from the Group IPA.

### isRegisteredGroup

```solidity  theme={null}
function isRegisteredGroup(address groupId) external view returns (bool)
```

Checks whether a group IPA was registered based on its ID.

**Parameters:**

* `groupId`: The address of the Group IPA.

**Returns:**

* `isRegistered`: Whether the Group IPA was registered into the protocol.

### getGroupRewardPool

```solidity  theme={null}
function getGroupRewardPool(address groupId) external view returns (address)
```

Retrieves the group reward pool for a Group IPA.

**Parameters:**

* `groupId`: The address of the Group IPA.

**Returns:**

* `rewardPool`: The address of the group reward pool.

### isWhitelistedGroupRewardPool

```solidity  theme={null}
function isWhitelistedGroupRewardPool(address rewardPool) external view returns (bool isWhitelisted)
```

Checks whether a group reward pool is whitelisted.

**Parameters:**

* `rewardPool`: The address of the group reward pool.

**Returns:**

* `isWhitelisted`: Whether the group reward pool is whitelisted.

### getGroupMembers

```solidity  theme={null}
function getGroupMembers(
    address groupId,
    uint256 startIndex,
    uint256 size
) external view returns (address[] memory results)
```

Retrieves the group members for a Group IPA.

**Parameters:**

* `groupId`: The address of the Group IPA.
* `startIndex`: The start index of the group members to retrieve.
* `size`: The size of the group members to retrieve.

**Returns:**

* `results`: The addresses of the group members.

### containsIp

```solidity  theme={null}
function containsIp(address groupId, address ipId) external view returns (bool)
```

Checks whether an IP is a member of a Group IPA.

**Parameters:**

* `groupId`: The address of the Group IPA.
* `ipId`: The address of the IP.

**Returns:**

* `isMember`: Whether the IP is a member of the Group IPA.

### totalMembers

```solidity  theme={null}
function totalMembers(address groupId) external view returns (uint256)
```

Retrieves the total number of members in a Group IPA.

**Parameters:**

* `groupId`: The address of the Group IPA.

**Returns:**

* `totalMembers`: The total number of members in the Group IPA.
# ModuleRegistry

The ModuleRegistry contract is used to register and track modules within the Story ecosystem. It serves as a central registry for all protocol modules, allowing for easy discovery and management of different module types and implementations.

## State Variables

### ModuleRegistryStorage

```solidity  theme={null}
struct ModuleRegistryStorage {
    mapping(string moduleName => address moduleAddress) modules;
    mapping(address moduleAddress => string moduleType) moduleTypes;
    mapping(string moduleType => bytes4 moduleTypeInterface) allModuleTypes;
}
```

Storage structure for the ModuleRegistry containing:

* `modules`: Maps module names to their addresses
* `moduleTypes`: Maps module addresses to their types
* `allModuleTypes`: Maps module types to their interface IDs

### ModuleRegistryStorageLocation

```solidity  theme={null}
bytes32 private constant ModuleRegistryStorageLocation
```

The storage location for the ModuleRegistry storage structure, following ERC-7201 for namespace storage pattern.

## Functions

### initialize

```solidity  theme={null}
function initialize(address accessManager) public initializer
```

Initializes the ModuleRegistry contract.

**Parameters:**

* `accessManager`: The address of the governance contract.

### registerModuleType

```solidity  theme={null}
function registerModuleType(string memory name, bytes4 interfaceId) external override restricted
```

Registers a new module type in the registry associated with an interface.

**Parameters:**

* `name`: The name of the module type to be registered.
* `interfaceId`: The interface ID associated with the module type.

### removeModuleType

```solidity  theme={null}
function removeModuleType(string memory name) external override restricted
```

Removes a module type from the registry.

**Parameters:**

* `name`: The name of the module type to be removed.

### registerModule (Default Type)

```solidity  theme={null}
function registerModule(string memory name, address moduleAddress) external restricted
```

Registers a new module in the registry with the default module type.

**Parameters:**

* `name`: The name of the module.
* `moduleAddress`: The address of the module.

### registerModule (Specific Type)

```solidity  theme={null}
function registerModule(string memory name, address moduleAddress, string memory moduleType) external restricted
```

Registers a new module in the registry with a specific module type.

**Parameters:**

* `name`: The name of the module to be registered.
* `moduleAddress`: The address of the module.
* `moduleType`: The type of the module being registered.

### removeModule

```solidity  theme={null}
function removeModule(string memory name) external restricted
```

Removes a module from the registry.

**Parameters:**

* `name`: The name of the module to be removed.

### isRegistered

```solidity  theme={null}
function isRegistered(address moduleAddress) external view returns (bool)
```

Checks if a module is registered in the protocol.

**Parameters:**

* `moduleAddress`: The address of the module.

**Returns:**

* `bool`: True if the module is registered, false otherwise.

### getModule

```solidity  theme={null}
function getModule(string memory name) external view returns (address)
```

Returns the address of a module.

**Parameters:**

* `name`: The name of the module.

**Returns:**

* `address`: The address of the module.

### getModuleType

```solidity  theme={null}
function getModuleType(address moduleAddress) external view returns (string memory)
```

Returns the module type of a given module address.

**Parameters:**

* `moduleAddress`: The address of the module.

**Returns:**

* `string`: The type of the module as a string.

### getModuleTypeInterfaceId

```solidity  theme={null}
function getModuleTypeInterfaceId(string memory moduleType) external view returns (bytes4)
```

Returns the interface ID associated with a given module type.

**Parameters:**

* `moduleType`: The type of the module as a string.

**Returns:**

* `bytes4`: The interface ID of the module type.

## Internal Functions

### \_registerModule

```solidity  theme={null}
function _registerModule(string memory name, address moduleAddress, string memory moduleType) internal
```

Internal function to register a new module in the registry.

**Parameters:**

* `name`: The name of the module.
* `moduleAddress`: The address of the module.
* `moduleType`: The type of the module being registered.

### \_getModuleRegistryStorage

```solidity  theme={null}
function _getModuleRegistryStorage() private pure returns (ModuleRegistryStorage storage $)
```

Returns the storage struct of the ModuleRegistry.

**Returns:**

* `ModuleRegistryStorage`: The storage structure for the ModuleRegistry.

### \_authorizeUpgrade

```solidity  theme={null}
function _authorizeUpgrade(address newImplementation) internal override restricted
```

Hook to authorize the upgrade according to UUPSUpgradeable.

**Parameters:**

* `newImplementation`: The address of the new implementation.

## Events

### ModuleAdded

```solidity  theme={null}
event ModuleAdded(string name, address moduleAddress, bytes4 moduleTypeInterfaceId, string moduleType)
```

Emitted when a new module is added to the registry.

**Parameters:**

* `name`: The name of the module.
* `moduleAddress`: The address of the module.
* `moduleTypeInterfaceId`: The interface ID of the module type.
* `moduleType`: The type of the module.

### ModuleRemoved

```solidity  theme={null}
event ModuleRemoved(string name, address moduleAddress)
```

Emitted when a module is removed from the registry.

**Parameters:**

* `name`: The name of the module.
* `moduleAddress`: The address of the module.

## Security Considerations

The ModuleRegistry contract implements several security measures:

1. **Access Control**: Most functions are restricted to be called only by the protocol admin through the `restricted` modifier.

2. **Input Validation**: The contract validates all inputs to ensure they meet the required criteria:
   * Module addresses must be non-zero and must be contracts
   * Names and module types cannot be empty strings
   * Module types must be registered before modules of that type can be registered
   * Modules must support the expected interface for their type

3. **Duplicate Prevention**: The contract prevents duplicate registrations:
   * A module type cannot be registered twice with the same name
   * A module cannot be registered twice with different names
   * A name cannot be used for multiple modules

4. **Upgradability**: The contract is upgradable using the UUPS pattern, with upgrade authorization restricted to the protocol admin.
# RoyaltyModule

The RoyaltyModule is the main entry point for handling royalty payments on Story. It allows IP owners to set royalty policies for their IP assets and enables derivative IP owners to pay royalties to their parent IPs.

## State Variables

### LICENSE\_REGISTRY

```solidity  theme={null}
ILicenseRegistry public immutable LICENSE_REGISTRY
```

The address of the License Registry contract that tracks license terms and tokens.

### DISPUTE\_MODULE

```solidity  theme={null}
IDisputeModule public immutable DISPUTE_MODULE
```

The address of the Dispute Module contract that handles dispute resolution.

### licensingModule

```solidity  theme={null}
address licensingModule
```

The address of the Licensing Module contract.

### isWhitelistedRoyaltyPolicy

```solidity  theme={null}
mapping(address royaltyPolicy => bool isWhitelisted) isWhitelistedRoyaltyPolicy
```

Indicates if a royalty policy is whitelisted.

### isWhitelistedRoyaltyToken

```solidity  theme={null}
mapping(address token => bool) isWhitelistedRoyaltyToken
```

Indicates if a royalty token is whitelisted.

### royaltyPolicies

```solidity  theme={null}
mapping(address ipId => address royaltyPolicy) royaltyPolicies
```

Maps IP IDs to their royalty policies.

## Functions

### initialize

```solidity  theme={null}
function initialize(address accessManager) external initializer
```

Initializer for this implementation contract.

**Parameters:**

* `accessManager`: The address of the protocol admin roles contract.

### setLicensingModule

```solidity  theme={null}
function setLicensingModule(address licensing) external restricted
```

Sets the licensing module.

**Parameters:**

* `licensing`: The address of the license module.

### whitelistRoyaltyPolicy

```solidity  theme={null}
function whitelistRoyaltyPolicy(address royaltyPolicy, bool allowed) external restricted
```

Whitelist a royalty policy.

**Parameters:**

* `royaltyPolicy`: The address of the royalty policy.
* `allowed`: Indicates if the royalty policy is whitelisted or not.

### whitelistRoyaltyToken

```solidity  theme={null}
function whitelistRoyaltyToken(address token, bool allowed) external restricted
```

Whitelist a royalty token.

**Parameters:**

* `token`: The token address.
* `allowed`: Indicates if the token is whitelisted or not.

### onLicenseMinting

```solidity  theme={null}
function onLicenseMinting(
    address ipId,
    address royaltyPolicy,
    bytes calldata licenseData,
    bytes calldata externalData
) external nonReentrant onlyLicensingModule
```

Executes royalty related logic on license minting.

**Parameters:**

* `ipId`: The ipId whose license is being minted (licensor).
* `royaltyPolicy`: The royalty policy address of the license being minted.
* `licenseData`: The license data custom to each the royalty policy.
* `externalData`: The external data custom to each the royalty policy.

### onLinkToParents

```solidity  theme={null}
function onLinkToParents(
    address ipId,
    address royaltyPolicy,
    address[] calldata parentIpIds,
    bytes[] memory licenseData,
    bytes calldata externalData
) external nonReentrant onlyLicensingModule
```

Executes royalty related logic on linking to parents.

**Parameters:**

* `ipId`: The children ipId that is being linked to parents.
* `royaltyPolicy`: The common royalty policy address of all the licenses being burned.
* `parentIpIds`: The parent ipIds that the children ipId is being linked to.
* `licenseData`: The license data custom to each the royalty policy.
* `externalData`: The external data custom to each the royalty policy.

### payRoyaltyOnBehalf

```solidity  theme={null}
function payRoyaltyOnBehalf(
    address receiverIpId,
    address payerIpId,
    address token,
    uint256 amount
) external nonReentrant whenNotPaused
```

Allows the function caller to pay royalties to the receiver IP asset on behalf of the payer IP asset.

**Parameters:**

* `receiverIpId`: The ipId that receives the royalties.
* `payerIpId`: The ipId that pays the royalties.
* `token`: The token to use to pay the royalties.
* `amount`: The amount to pay.

### payLicenseMintingFee

```solidity  theme={null}
function payLicenseMintingFee(
    address receiverIpId,
    address payerAddress,
    address licenseRoyaltyPolicy,
    address token,
    uint256 amount
) external onlyLicensingModule
```

Allows to pay the minting fee for a license.

**Parameters:**

* `receiverIpId`: The ipId that receives the royalties.
* `payerAddress`: The address that pays the royalties.
* `licenseRoyaltyPolicy`: The royalty policy of the license being minted.
* `token`: The token to use to pay the royalties.
* `amount`: The amount to pay.

### licensingModule

```solidity  theme={null}
function licensingModule() external view returns (address)
```

Returns the licensing module address.

**Returns:**

* The address of the licensing module.

### isWhitelistedRoyaltyPolicy

```solidity  theme={null}
function isWhitelistedRoyaltyPolicy(address royaltyPolicy) external view returns (bool)
```

Indicates if a royalty policy is whitelisted.

**Parameters:**

* `royaltyPolicy`: The address of the royalty policy.

**Returns:**

* `isWhitelisted`: True if the royalty policy is whitelisted.

### isWhitelistedRoyaltyToken

```solidity  theme={null}
function isWhitelistedRoyaltyToken(address token) external view returns (bool)
```

Indicates if a royalty token is whitelisted.

**Parameters:**

* `token`: The address of the royalty token.

**Returns:**

* `isWhitelisted`: True if the royalty token is whitelisted.

### royaltyPolicies

```solidity  theme={null}
function royaltyPolicies(address ipId) external view returns (address)
```

Indicates the royalty policy for a given IP asset.

**Parameters:**

* `ipId`: The ID of IP asset.

**Returns:**

* `royaltyPolicy`: The address of the royalty policy.

### supportsInterface

```solidity  theme={null}
function supportsInterface(bytes4 interfaceId) public view virtual override(BaseModule, IERC165) returns (bool)
```

IERC165 interface support.

**Parameters:**

* `interfaceId`: The interface identifier.

**Returns:**

* Returns true if the interface is supported.

## Security Considerations

The RoyaltyModule contract implements several security measures:

1. **Access Control**: Most administrative functions are restricted to be called only by the protocol admin through the `restricted` modifier.

2. **Module Interaction Control**: Functions like `onLicenseMinting` and `payLicenseMintingFee` can only be called by the Licensing Module through the `onlyLicensingModule` modifier.

3. **Reentrancy Protection**: The `nonReentrant` modifier is used on functions that handle token transfers to prevent reentrancy attacks.

4. **Pausability**: The contract can be paused in emergency situations using the `whenNotPaused` modifier.

5. **Whitelisting Mechanism**: The contract implements whitelisting for royalty policies and tokens to ensure that only approved components can interact with the royalty system.

6. **Dispute Resolution Integration**: The contract integrates with the Dispute Module to handle any disputes related to royalty payments.
# IPRoyaltyVault

The IPRoyaltyVault contract manages the claiming of royalty and revenue tokens for a given IP. It allows token holders to claim their share of revenue tokens based on snapshots, and ancestors to collect their royalty tokens.

## State Variables

### ipId

```solidity  theme={null}
address ipId
```

The IP ID to which this royalty vault belongs.

### tokens

```solidity  theme={null}
EnumerableSet.AddressSet tokens
```

The set of revenue tokens in the vault.

### unclaimedRoyaltyTokens

```solidity  theme={null}
uint32 unclaimedRoyaltyTokens
```

The amount of unclaimed royalty tokens.

### lastSnapshotTimestamp

```solidity  theme={null}
uint256 lastSnapshotTimestamp
```

The timestamp of the last snapshot.

### ancestorsVaultAmount

```solidity  theme={null}
mapping(address token => uint256 amount) ancestorsVaultAmount
```

Maps token addresses to the amount in the ancestors vault.

### isCollectedByAncestor

```solidity  theme={null}
mapping(address ancestorIpId => bool isCollected) isCollectedByAncestor
```

Indicates whether an ancestor has collected their royalty tokens.

### claimVaultAmount

```solidity  theme={null}
mapping(address token => uint256 amount) claimVaultAmount
```

Maps token addresses to the amount in the claim vault.

### claimableAtSnapshot

```solidity  theme={null}
mapping(uint256 snapshotId => mapping(address token => uint256 amount)) claimableAtSnapshot
```

Maps snapshot IDs and token addresses to the claimable amount at that snapshot.

### unclaimedAtSnapshot

```solidity  theme={null}
mapping(uint256 snapshotId => uint32 amount) unclaimedAtSnapshot
```

Maps snapshot IDs to the amount of unclaimed tokens at that snapshot.

### isClaimedAtSnapshot

```solidity  theme={null}
mapping(uint256 snapshotId => mapping(address claimer => mapping(address token => bool isClaimed))) isClaimedAtSnapshot
```

Indicates whether a claimer has claimed a token at a specific snapshot.

## Functions

### initialize

```solidity  theme={null}
function initialize(
    string memory name,
    string memory symbol,
    uint256 totalSupply,
    uint32 royaltyStack,
    address ipId_
) external initializer
```

Initializer for this implementation contract.

**Parameters:**

* `name`: The name of the royalty token.
* `symbol`: The symbol of the royalty token.
* `totalSupply`: The total supply of the royalty token.
* `royaltyStack`: The royalty stack of the IP asset.
* `ipId_`: The IP ID to which this royalty vault belongs.

### addIpRoyaltyVaultTokens

```solidity  theme={null}
function addIpRoyaltyVaultTokens(address token) external nonReentrant whenNotPaused returns (bool)
```

Adds a token to the royalty vault.

**Parameters:**

* `token`: The token address to add.

**Returns:**

* `isAdded`: True if the token was added, false if it was already in the vault.

### snapshot

```solidity  theme={null}
function snapshot() external whenNotPaused returns (uint256)
```

Takes a snapshot of the claimable revenue and royalty token amounts.

**Returns:**

* `snapshotId`: The ID of the snapshot.

### claimRevenueToken

```solidity  theme={null}
function claimRevenueToken(uint256[] calldata snapshotIds, address token) external nonReentrant whenNotPaused
```

Allows token holders to claim their share of revenue tokens.

**Parameters:**

* `snapshotIds`: The snapshot IDs to claim from.
* `token`: The revenue token to claim.

### collectRoyaltyTokens

```solidity  theme={null}
function collectRoyaltyTokens(address ancestorIpId) external nonReentrant whenNotPaused
```

Allows ancestors to claim the royalty tokens and any accrued revenue tokens.

**Parameters:**

* `ancestorIpId`: The IP ID of the ancestor to whom the royalty tokens belong.

### ipId

```solidity  theme={null}
function ipId() external view returns (address)
```

Returns the IP ID to which this royalty vault belongs.

**Returns:**

* The IP ID address.

### unclaimedRoyaltyTokens

```solidity  theme={null}
function unclaimedRoyaltyTokens() external view returns (uint32)
```

Returns the amount of unclaimed royalty tokens.

**Returns:**

* The amount of unclaimed royalty tokens.

### lastSnapshotTimestamp

```solidity  theme={null}
function lastSnapshotTimestamp() external view returns (uint256)
```

Returns the last snapshotted timestamp.

**Returns:**

* The last snapshot timestamp.

### ancestorsVaultAmount

```solidity  theme={null}
function ancestorsVaultAmount(address token) external view returns (uint256)
```

Returns the amount of revenue token in the ancestors vault.

**Parameters:**

* `token`: The address of the revenue token.

**Returns:**

* The amount of revenue token in the ancestors vault.

### isCollectedByAncestor

```solidity  theme={null}
function isCollectedByAncestor(address ancestorIpId) external view returns (bool)
```

Indicates whether the ancestor has collected the royalty tokens.

**Parameters:**

* `ancestorIpId`: The ancestor IP ID address.

**Returns:**

* True if the ancestor has collected the royalty tokens.

### claimVaultAmount

```solidity  theme={null}
function claimVaultAmount(address token) external view returns (uint256)
```

Returns the amount of revenue token in the claim vault.

**Parameters:**

* `token`: The address of the revenue token.

**Returns:**

* The amount of revenue token in the claim vault.

### claimableAtSnapshot

```solidity  theme={null}
function claimableAtSnapshot(uint256 snapshotId, address token) external view returns (uint256)
```

Returns the amount of revenue token claimable at a given snapshot.

**Parameters:**

* `snapshotId`: The snapshot ID.
* `token`: The address of the revenue token.

**Returns:**

* The amount of revenue token claimable at the snapshot.

### unclaimedAtSnapshot

```solidity  theme={null}
function unclaimedAtSnapshot(uint256 snapshotId) external view returns (uint32)
```

Returns the amount of unclaimed revenue tokens at the snapshot.

**Parameters:**

* `snapshotId`: The snapshot ID.

**Returns:**

* The amount of unclaimed revenue tokens at the snapshot.

### isClaimedAtSnapshot

```solidity  theme={null}
function isClaimedAtSnapshot(uint256 snapshotId, address claimer, address token) external view returns (bool)
```

Indicates whether the claimer has claimed the revenue tokens at a given snapshot.

**Parameters:**

* `snapshotId`: The snapshot ID.
* `claimer`: The address of the claimer.
* `token`: The address of the revenue token.

**Returns:**

* True if the claimer has claimed the revenue tokens at the snapshot.

### tokens

```solidity  theme={null}
function tokens() external view returns (address[] memory)
```

Returns the list of revenue tokens in the vault.

**Returns:**

* The array of revenue token addresses.

## Security Considerations

The IPRoyaltyVault contract implements several security measures:

1. **Access Control**: Functions for adding tokens, taking snapshots, and claiming tokens are protected with appropriate modifiers.

2. **Reentrancy Protection**: The `nonReentrant` modifier is used on functions that handle token transfers to prevent reentrancy attacks.

3. **Pausability**: The contract can be paused in emergency situations using the `whenNotPaused` modifier.

4. **Snapshot Mechanism**: The contract uses a snapshot mechanism to ensure fair distribution of revenue tokens based on holdings at specific points in time.

5. **Claim Verification**: The contract tracks claimed tokens to prevent double-claiming by the same address.
# RoyaltyPolicyLAP

The RoyaltyPolicyLAP (Liquid Absolute Percentage) contract defines the logic for splitting royalties for a given IP asset using a liquid absolute percentage mechanism. It manages the royalty relationships between IP assets and their ancestors, allowing for the transfer of revenue tokens to the appropriate royalty vaults.

## State Variables

### RoyaltyPolicyLAPStorage

```solidity  theme={null}
struct RoyaltyPolicyLAPStorage {
    mapping(address ipId => uint32) royaltyStackLAP;
    mapping(address ipId => mapping(address ancestorIpId => uint32)) ancestorPercentLAP;
    mapping(address ipId => mapping(address ancestorIpId => mapping(address token => uint256))) transferredTokenLAP;
}
```

Storage structure for the RoyaltyPolicyLAP containing:

* `royaltyStackLAP`: Sum of the royalty percentages to be paid to all ancestors for LAP royalty policy
* `ancestorPercentLAP`: The royalty percentage between an IP asset and a given ancestor for LAP royalty policy
* `transferredTokenLAP`: Total lifetime revenue tokens transferred to a vault from a descendant IP via LAP

### IP\_GRAPH

```solidity  theme={null}
address public constant IP_GRAPH = address(0x0101)
```

The address of the IP Graph precompile contract that tracks relationships between IPs.

### ROYALTY\_MODULE

```solidity  theme={null}
IRoyaltyModule public immutable ROYALTY_MODULE
```

The address of the Royalty Module contract.

### IP\_GRAPH\_ACL

```solidity  theme={null}
IPGraphACL public immutable IP_GRAPH_ACL
```

The address of the IP Graph Access Control List contract.

## Functions

### constructor

```solidity  theme={null}
constructor(address royaltyModule, address ipGraphAcl)
```

Constructor for the RoyaltyPolicyLAP contract.

**Parameters:**

* `royaltyModule`: The RoyaltyModule address
* `ipGraphAcl`: The IPGraphACL address

### initialize

```solidity  theme={null}
function initialize(address accessManager) external initializer
```

Initializer for this implementation contract.

**Parameters:**

* `accessManager`: The address of the protocol admin roles contract.

### onLicenseMinting

```solidity  theme={null}
function onLicenseMinting(
    address ipId,
    uint32 licensePercent,
    bytes calldata
) external nonReentrant onlyRoyaltyModule
```

Executes royalty related logic on minting a license.

**Parameters:**

* `ipId`: The ipId whose license is being minted (licensor)
* `licensePercent`: The license percentage of the license being minted

### onLinkToParents

```solidity  theme={null}
function onLinkToParents(
    address ipId,
    address[] calldata parentIpIds,
    address[] memory licenseRoyaltyPolicies,
    uint32[] calldata licensesPercent,
    bytes calldata
) external nonReentrant onlyRoyaltyModule returns (uint32 newRoyaltyStackLAP)
```

Executes royalty related logic on linking to parents.

**Parameters:**

* `ipId`: The children ipId that is being linked to parents
* `parentIpIds`: The parent ipIds that the children ipId is being linked to
* `licenseRoyaltyPolicies`: The royalty policies of the licenses
* `licensesPercent`: The license percentage of the licenses being minted

**Returns:**

* `newRoyaltyStackLAP`: The royalty stack of the child ipId for LAP royalty policy

### transferToVault

```solidity  theme={null}
function transferToVault(
    address ipId,
    address ancestorIpId,
    address token
) external whenNotPaused returns (uint256)
```

Transfers to vault an amount of revenue tokens claimable via LAP royalty policy.

**Parameters:**

* `ipId`: The ipId of the IP asset
* `ancestorIpId`: The ancestor ipId of the IP asset
* `token`: The token address to transfer

**Returns:**

* The amount of revenue tokens transferred

### getPolicyRtsRequiredToLink

```solidity  theme={null}
function getPolicyRtsRequiredToLink(address ipId, uint32 licensePercent) external view returns (uint32)
```

Returns the amount of royalty tokens required to link a child to a given IP asset.

**Parameters:**

* `ipId`: The ipId of the IP asset
* `licensePercent`: The percentage of the license

**Returns:**

* The amount of royalty tokens required to link a child to a given IP asset (always 0 for LAP)

### getPolicyRoyaltyStack

```solidity  theme={null}
function getPolicyRoyaltyStack(address ipId) external view returns (uint32)
```

Returns the LAP royalty stack for a given IP asset.

**Parameters:**

* `ipId`: The ipId to get the royalty stack for

**Returns:**

* Sum of the royalty percentages to be paid to all ancestors for LAP royalty policy

### getPolicyRoyalty

```solidity  theme={null}
function getPolicyRoyalty(address ipId, address ancestorIpId) external returns (uint32)
```

Returns the royalty percentage between an IP asset and its ancestors via LAP.

**Parameters:**

* `ipId`: The ipId to get the royalty for
* `ancestorIpId`: The ancestor ipId to get the royalty for

**Returns:**

* The royalty percentage between an IP asset and its ancestors via LAP

### getTransferredTokens

```solidity  theme={null}
function getTransferredTokens(address ipId, address ancestorIpId, address token) external view returns (uint256)
```

Returns the total lifetime revenue tokens transferred to a vault from a descendant IP via LAP.

**Parameters:**

* `ipId`: The ipId of the IP asset
* `ancestorIpId`: The ancestor ipId of the IP asset
* `token`: The token address to transfer

**Returns:**

* The total lifetime revenue tokens transferred to a vault from a descendant IP via LAP

### isSupportGroup

```solidity  theme={null}
function isSupportGroup() external view returns (bool)
```

Returns whether the royalty policy supports working with groups.

**Returns:**

* False (LAP royalty policy does not support working with groups)

## Internal Functions

### \_getRoyaltyStackLAP

```solidity  theme={null}
function _getRoyaltyStackLAP(address ipId) internal returns (uint32)
```

Returns the royalty stack for a given IP asset for LAP royalty policy.

**Parameters:**

* `ipId`: The ipId to get the royalty stack for

**Returns:**

* The royalty stack for a given IP asset for LAP royalty policy

### \_setRoyaltyLAP

```solidity  theme={null}
function _setRoyaltyLAP(address ipId, address parentIpId, uint32 royalty) internal
```

Sets the LAP royalty for a given link between an IP asset and its ancestor.

**Parameters:**

* `ipId`: The ipId to set the royalty for
* `parentIpId`: The parent ipId to set the royalty for
* `royalty`: The LAP license royalty percentage

### \_getRoyaltyLAP

```solidity  theme={null}
function _getRoyaltyLAP(address ipId, address ancestorIpId) internal returns (uint32)
```

Returns the royalty percentage between an IP asset and its ancestor via royalty policy LAP.

**Parameters:**

* `ipId`: The ipId to get the royalty for
* `ancestorIpId`: The ancestor ipId to get the royalty for

**Returns:**

* The royalty percentage between an IP asset and its ancestor via royalty policy LAP

### \_getRoyaltyPolicyLAPStorage

```solidity  theme={null}
function _getRoyaltyPolicyLAPStorage() private pure returns (RoyaltyPolicyLAPStorage storage $)
```

Returns the storage struct of RoyaltyPolicyLAP.

**Returns:**

* The storage structure for the RoyaltyPolicyLAP

### \_authorizeUpgrade

```solidity  theme={null}
function _authorizeUpgrade(address newImplementation) internal override restricted
```

Hook to authorize the upgrade according to UUPSUpgradeable.

**Parameters:**

* `newImplementation`: The address of the new implementation

## Events

### RevenueTransferredToVault

```solidity  theme={null}
event RevenueTransferredToVault(address ipId, address ancestorIpId, address token, uint256 amount)
```

Emitted when revenue tokens are transferred to a vault.

**Parameters:**

* `ipId`: The ipId of the IP asset
* `ancestorIpId`: The ancestor ipId of the IP asset
* `token`: The token address transferred
* `amount`: The amount of tokens transferred

## Security Considerations

The RoyaltyPolicyLAP contract implements several security measures:

1. **Access Control**: Functions like `onLicenseMinting` and `onLinkToParents` can only be called by the Royalty Module through the `onlyRoyaltyModule` modifier.

2. **Reentrancy Protection**: The `nonReentrant` modifier is used on functions that handle token transfers to prevent reentrancy attacks.

3. **Pausability**: The contract can be paused in emergency situations using the `whenNotPaused` modifier.

4. **Safe Token Transfers**: The contract uses OpenZeppelin's SafeERC20 library to ensure safe token transfers.

5. **Upgradability**: The contract is upgradable using the UUPS pattern, with upgrade authorization restricted to the protocol admin.

6. **Input Validation**: The contract validates inputs and checks for edge cases, such as preventing transfers between the same IP.
# RoyaltyPolicyLRP

The RoyaltyPolicyLRP (Liquid Relative Percentage) contract defines the logic for splitting royalties for a given IP asset using a liquid relative percentage mechanism. It manages the royalty relationships between IP assets and their ancestors, allowing for the transfer of revenue tokens to the appropriate royalty vaults.

## State Variables

### RoyaltyPolicyLRPStorage

```solidity  theme={null}
struct RoyaltyPolicyLRPStorage {
    mapping(address ipId => uint32) royaltyStackLRP;
    mapping(address ipId => mapping(address ancestorIpId => uint32)) ancestorPercentLRP;
    mapping(address ipId => mapping(address ancestorIpId => mapping(address token => uint256))) transferredTokenLRP;
}
```

Storage structure for the RoyaltyPolicyLRP containing:

* `royaltyStackLRP`: Sum of the royalty percentages to be paid to all ancestors for LRP royalty policy
* `ancestorPercentLRP`: The royalty percentage between an IP asset and a given ancestor for LRP royalty policy
* `transferredTokenLRP`: Total lifetime revenue tokens transferred to a vault from a descendant IP via LRP

### IP\_GRAPH

```solidity  theme={null}
address public constant IP_GRAPH = address(0x0101)
```

The address of the IP Graph precompile contract that tracks relationships between IPs.

### ROYALTY\_MODULE

```solidity  theme={null}
IRoyaltyModule public immutable ROYALTY_MODULE
```

The address of the Royalty Module contract.

### ROYALTY\_POLICY\_LAP

```solidity  theme={null}
IGraphAwareRoyaltyPolicy public immutable ROYALTY_POLICY_LAP
```

The address of the RoyaltyPolicyLAP contract.

### IP\_GRAPH\_ACL

```solidity  theme={null}
IPGraphACL public immutable IP_GRAPH_ACL
```

The address of the IP Graph Access Control List contract.

## Functions

### constructor

```solidity  theme={null}
constructor(address royaltyModule, address royaltyPolicyLAP, address ipGraphAcl)
```

Constructor for the RoyaltyPolicyLRP contract.

**Parameters:**

* `royaltyModule`: The RoyaltyModule address
* `royaltyPolicyLAP`: The RoyaltyPolicyLAP address
* `ipGraphAcl`: The IPGraphACL address

### initialize

```solidity  theme={null}
function initialize(address accessManager) external initializer
```

Initializer for this implementation contract.

**Parameters:**

* `accessManager`: The address of the protocol admin roles contract.

### onLicenseMinting

```solidity  theme={null}
function onLicenseMinting(
    address ipId,
    uint32 licensePercent,
    bytes calldata
) external nonReentrant onlyRoyaltyModule
```

Executes royalty related logic on minting a license.

**Parameters:**

* `ipId`: The ipId whose license is being minted (licensor)
* `licensePercent`: The license percentage of the license being minted

### onLinkToParents

```solidity  theme={null}
function onLinkToParents(
    address ipId,
    address[] calldata parentIpIds,
    address[] memory licenseRoyaltyPolicies,
    uint32[] calldata licensesPercent,
    bytes calldata
) external nonReentrant onlyRoyaltyModule returns (uint32 newRoyaltyStackLRP)
```

Executes royalty related logic on linking to parents.

**Parameters:**

* `ipId`: The children ipId that is being linked to parents
* `parentIpIds`: The parent ipIds that the children ipId is being linked to
* `licenseRoyaltyPolicies`: The royalty policies of the licenses
* `licensesPercent`: The license percentage of the licenses being minted

**Returns:**

* `newRoyaltyStackLRP`: The royalty stack of the child ipId for LRP royalty policy

### transferToVault

```solidity  theme={null}
function transferToVault(
    address ipId,
    address ancestorIpId,
    address token
) external whenNotPaused returns (uint256)
```

Transfers to vault an amount of revenue tokens claimable via LRP royalty policy.

**Parameters:**

* `ipId`: The ipId of the IP asset
* `ancestorIpId`: The ancestor ipId of the IP asset
* `token`: The token address to transfer

**Returns:**

* The amount of revenue tokens transferred

### getPolicyRtsRequiredToLink

```solidity  theme={null}
function getPolicyRtsRequiredToLink(address ipId, uint32 licensePercent) external view returns (uint32)
```

Returns the amount of royalty tokens required to link a child to a given IP asset.

**Parameters:**

* `ipId`: The ipId of the IP asset
* `licensePercent`: The percentage of the license

**Returns:**

* The amount of royalty tokens required to link a child to a given IP asset (always 0 for LRP)

### getPolicyRoyaltyStack

```solidity  theme={null}
function getPolicyRoyaltyStack(address ipId) external view returns (uint32)
```

Returns the LRP royalty stack for a given IP asset.

**Parameters:**

* `ipId`: The ipId to get the royalty stack for

**Returns:**

* Sum of the royalty percentages to be paid to all ancestors for LRP royalty policy

### getPolicyRoyalty

```solidity  theme={null}
function getPolicyRoyalty(address ipId, address ancestorIpId) external returns (uint32)
```

Returns the royalty percentage between an IP asset and its ancestors via LRP.

**Parameters:**

* `ipId`: The ipId to get the royalty for
* `ancestorIpId`: The ancestor ipId to get the royalty for

**Returns:**

* The royalty percentage between an IP asset and its ancestors via LRP

### getTransferredTokens

```solidity  theme={null}
function getTransferredTokens(address ipId, address ancestorIpId, address token) external view returns (uint256)
```

Returns the total lifetime revenue tokens transferred to a vault from a descendant IP via LRP.

**Parameters:**

* `ipId`: The ipId of the IP asset
* `ancestorIpId`: The ancestor ipId of the IP asset
* `token`: The token address to transfer

**Returns:**

* The total lifetime revenue tokens transferred to a vault from a descendant IP via LRP

### isSupportGroup

```solidity  theme={null}
function isSupportGroup() external view returns (bool)
```

Returns whether the royalty policy supports working with groups.

**Returns:**

* True (LRP royalty policy supports working with groups)

## Internal Functions

### \_getRoyaltyStackLRP

```solidity  theme={null}
function _getRoyaltyStackLRP(address ipId) internal returns (uint32)
```

Returns the royalty stack for a given IP asset for LRP royalty policy.

**Parameters:**

* `ipId`: The ipId to get the royalty stack for

**Returns:**

* The royalty stack for a given IP asset for LRP royalty policy

### \_setRoyaltyLRP

```solidity  theme={null}
function _setRoyaltyLRP(address ipId, address parentIpId, uint32 royalty) internal
```

Sets the LRP royalty for a given link between an IP asset and its ancestor.

**Parameters:**

* `ipId`: The ipId to set the royalty for
* `parentIpId`: The parent ipId to set the royalty for
* `royalty`: The LRP license royalty percentage

### \_getRoyaltyLRP

```solidity  theme={null}
function _getRoyaltyLRP(address ipId, address ancestorIpId) internal returns (uint32)
```

Returns the royalty percentage between an IP asset and its ancestor via royalty policy LRP.

**Parameters:**

* `ipId`: The ipId to get the royalty for
* `ancestorIpId`: The ancestor ipId to get the royalty for

**Returns:**

* The royalty percentage between an IP asset and its ancestor via royalty policy LRP

### \_getRoyaltyPolicyLRPStorage

```solidity  theme={null}
function _getRoyaltyPolicyLRPStorage() private pure returns (RoyaltyPolicyLRPStorage storage $)
```

Returns the storage struct of RoyaltyPolicyLRP.

**Returns:**

* The storage structure for the RoyaltyPolicyLRP

### \_authorizeUpgrade

```solidity  theme={null}
function _authorizeUpgrade(address newImplementation) internal override restricted
```

Hook to authorize the upgrade according to UUPSUpgradeable.

**Parameters:**

* `newImplementation`: The address of the new implementation

## Events

### RevenueTransferredToVault

```solidity  theme={null}
event RevenueTransferredToVault(address ipId, address ancestorIpId, address token, uint256 amount)
```

Emitted when revenue tokens are transferred to a vault.

**Parameters:**

* `ipId`: The ipId of the IP asset
* `ancestorIpId`: The ancestor ipId of the IP asset
* `token`: The token address transferred
* `amount`: The amount of tokens transferred

## Security Considerations

The RoyaltyPolicyLRP contract implements several security measures:

1. **Access Control**: Functions like `onLicenseMinting` and `onLinkToParents` can only be called by the Royalty Module through the `onlyRoyaltyModule` modifier.

2. **Reentrancy Protection**: The `nonReentrant` modifier is used on functions that handle token transfers to prevent reentrancy attacks.

3. **Pausability**: The contract can be paused in emergency situations using the `whenNotPaused` modifier.

4. **Safe Token Transfers**: The contract uses OpenZeppelin's SafeERC20 library to ensure safe token transfers.

5. **Upgradability**: The contract is upgradable using the UUPS pattern, with upgrade authorization restricted to the protocol admin.

6. **Input Validation**: The contract validates inputs and checks for edge cases, such as preventing transfers between the same IP.

## Royalty Dilution Considerations

The LRP (Liquid Relative Percentage) royalty policy allows each remixed IP to receive a percentage of the revenue generated by its direct derivatives. However, it's important to understand the potential dilution of royalties as more derivatives are created between two IPs.

This dilution can reduce the earnings of the original IP creator as more layers of derivatives are added. For example:

1. Creator 1 - Registers IP1, mints an LRP license of 10%, and sells the license to Creator 2.
2. Creator 2 - Registers IP2 as a derivative of IP1 and mints an LRP license of 20% for himself/herself.
3. Creator 2 - Registers IP3 as a derivative of IP2 and promotes IP3 commercially in the market.

The earnings for Creator 1 are diluted because they will only receive 10% of the 20% royalties from IP3, resulting in an effective royalty of 2%. If Creator 2 had chosen to promote IP2 instead, Creator 1 would have earned 10% directly, avoiding this dilution.

In contrast, the LAP (Liquid Absolute Percentage) royalty policy enforces a fixed percentage on every descendant IP, protecting the original creator from dilution.
