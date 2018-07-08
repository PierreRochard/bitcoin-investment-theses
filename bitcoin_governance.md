# Bitcoin Governance

## Why do we care?

Bitcoin's governance matters because Bitcoin is the first successful, most liquid, and most widely known crypto-currency. In the words of Michael Goldstein, "Sound money is a foundational pillar of civilization, and Bitcoin restores this powerful tool for social coordination." If Bitcoin's governance model is flawed, it could prevent Bitcoin from reaching its full potential. If Bitcoin's governance is flawed, Bitcoin's stakeholders should work to fix it. 

Conversations regarding Bitcoin's governance tend to focus on who the decision makers ultimately are, perennial candidates include miners, nodes, and investors. The purpose and mechanics of governance are often just implied or even disconnected from reality. Views on the efficacy of past governance are often driven by who "won" or "lost" a specific decision, rather than the adequacy of the decision making process itself.

## What is Bitcoin governance? 

Bitcoin governance is the process by which a set of transaction and block verification rules are decided upon, implemented, and enforced, such that individuals adopt these rules for verifying that payments they received in transactions and blocks fit their subjective definition of "Bitcoin". If two or more individuals adopt the same set validation of rules, they form an inter-subjective social consensus of what "Bitcoin" is.
[EXPLAIN Schelling Point]

## What is the purpose of Bitcoin's governance?

There is a wide range of views regarding what the purpose of Bitcoin's governance should be. What outcomes should governance optimize for?

 - Matt Corallo [argues](http://bluematt.bitcoin.ninja/2017/02/28/bitcoin-trustlessness/) that trustlessness is the most important property of Bitcoin. Matt defines trustlessness as "the ability to use Bitcoin without trusting anything but the open-source software you run". Without the property of trustlessness, all other positive outcomes are jeopardized.

 - Daniel Krawisz [argues](https://nakamotoinstitute.org/mempool/who-controls-bitcoin/) that maximizing the value of a bitcoin is what governance de facto optimizes for. Daniel states that "the general rule about Bitcoin upgrades [...] is that upgrades which increase Bitcoin's value will be adopted and those which do not will not."
 
In the context of Bitcoin's governance, these two views mirror the classic divide between [deontological](https://en.wikipedia.org/wiki/Deontological_ethics) and [consequentialist](https://en.wikipedia.org/wiki/Consequentialism) ethics respectively. I favor Matt's deontological approach of focusing on trustlessness. Throughout monetary history, from ancient coin producers to modern central banks, trusting others to produce money has resulted in abuse of that trust. Compromising on trustlessness could help the Bitcoin price find a local maximum, at the expense of finding a much higher global maximum. Furthermore, there is no evidence that Bitcoin's price has been correlated with upgrades to the Bitcoin protocol. Perhaps Bitcoin's fundamental value is affected by upgrades, but Bitcoin is so illiquid and volatile that the price does not reliably reflect fundamental value. If we can't observe the consequences of an upgrade on Bitcoin's value, the consequentialist approach seems inadequate.

Before we can evaluate the current Bitcoin governance process against the stated goals of maintaining trustlessness or increasing the value of Bitcoin, we should attempt to define how the current Bitcoin governance process actually works.

## How does the current Bitcoin governance process work?

The Bitcoin governance process maintains a set of verification rules. At a high level, this long set of verification rules covers syntax, data structures, resource usage limits, sanity checks, time locking, reconciliation with the memory pool and main branch, the coinbase reward and fee calculation, and block header verification. Amending these rules without tradeoffs is no easy feat.

Most of these rules were inherited from Satoshi Nakamoto. Some have been added or amended to address bugs and denial-of-service vulnerabilities. Other rule changes occurred to enable innovative new projects. For example, the new Check Sequence Verify opcode was added to [enable](https://github.com/bitcoin/bips/blob/master/bip-0112.mediawiki) new scripts.

Every rule change begins with __research__. For example, SegWit began with research into fixing transaction malleability. Transaction malleability had become a serious issue because it prevented the Lightning Network from deploying on Bitcoin. Industry and independent researchers collaborated on what eventually became SegWit.

Critics have pointed out occasional disconnects between what researchers want to research, user expectations, and what is good for the network's properties. Additionally, academic computer scientists prefer "scientific simulations" over "engineering experiments". This has been a source of tension in the research community.

When a researcher has discovered a solution to a problem, they share their results with other protocol developers. This sharing could be in the form of an email to the bitcoin-dev mailing list, a formal white paper, and/or a Bitcoin Improvement Proposal (BIP)

implemented 
These rules are implemented in node software. 
Soft fork vs hard fork

3. Developer interest
 a. IRC
 b. Mailing lists
 c. Bitcoin Improvement Proposal (BIP)
 d. Implementation

deployed
4. User rough consensus
 a. Exchanges
 b. Traders
 c. Holders
 d. Picking your node software: Schelling point consensus
 e. Miners picking their node software: BIP-34 and BIP-9

enforced

 
5. p2p network of full nodes consensus
6. Proof-of-work time-stamping

Node operators choose which  Nodes use the verification rules to independently verify that payments received by the node operator are in valid Bitcoin transactions and are included in valid Bitcoin blocks. 
Nodes will not propagate  transactions and blocks which break the rules. In fact, nodes will disconnect and ban peers which are sending invalid transactions and blocks. 

## Has the current Bitcoin governance model resulted in more trustlessness?


## Possible deciders?

Social media

Users
* Users of the Bitcoin network 
* Users of businesses that use the Bitcoin network

Businesses

Investors

Developers

Miners

Full nodes



