# Blockchain-Reading
A list of resources for learning more about blockchains.

## Table of Contents

* [Fundamentals](#fundamentals)
* [NetworkLayer](#NetworkLayer)
* [ProtocolLayer](#ProtocolLayer)
* [ConsensusMechanisms](#ConsensusMechanisms)
* [Layer1Scaling](#Layer1Scaling)
* [Layer2Scaling](#Layer2Scaling)
* [ApplicationLayer](#ApplicationLayer)
* [Privacy](#privacy)
* [Cryptography](#cryptography)
* [License](#license)

## Fundamentals

### Intro to Cryptoeconomics
* [Introduction to Cryptoeconomics](https://www.youtube.com/watch?v=pKqdjaH1dRo) - Vitalik Buterin's introduction to the field
* [What is Cryptoeconomics?](https://www.youtube.com/watch?v=9lw3s7iGUXQ) - Vlad Zamfir at Cryptoeconomicon
* [Design Rationale](https://github.com/ethereum/wiki/wiki/Design-Rationale) - The Ethereum design rationale
* [Griefing Factors](http://vitalik.ca/files/extortion_griefing_bounds.pdf) - "A Note on Limits on Incentive Compatibility and Griefing Factors" by Vitalik Buterin
* [The current state of Cryptoeconomics](https://www.youtube.com/watch?v=u6VSPD5TrP4) - Another talk by Vlad Zamfir
* [Making Sense of Cryptoeconomics](https://medium.com/@jjmstark/making-sense-of-cryptoeconomics-c6455776669) - An overview of cryptoeconomics by [Josh Stark](http://0xstark.com/about/)
* [A Crash Course in Mechanism Design for Cryptoeconomic Applications](https://medium.com/blockchannel/a-crash-course-in-mechanism-design-for-cryptoeconomic-applications-a9f06ab6a976) - Understanding the Basic Fundamentals of “Cryptoeconomics”
* [Programmable Incentives - Intro to Cryptoeconomics](https://www.youtube.com/watch?v=-alrVUv6E24) - A talk by Karl Floresch at DevCon 3

### Pre-Bitcoin Publications
* [Hashcash](http://www.hashcash.org/hashcash.pdf) - Hashcash: A Denial of Service Counter-Measure
* [A Cypherpunk's Manifesto](https://w2.eff.org/Privacy/Crypto/Crypto_misc/cypherpunk.manifesto) - Eric Hughes

## NetworkLayer

### Communication Protocols
* [Dandelion](https://arxiv.org/abs/1701.04439) - Redesigning the Bitcoin Network for Anonymity
* [Whisper](https://github.com/ethereum/wiki/wiki/Whisper) - Communication Protocol for DApps
* [Onion Routing](https://www.onion-router.net/Publications/SSP-1997.pdf) - Anonymous Connections and Onion Routing
* [bloXroute](https://bloxroute.com/wp-content/uploads/2018/03/bloXroute-whitepaper.pdf) - A Scalable Trustless Blockchain Distribution Network

## ProtocolLayer

### Bitcoin
* [Bitcoin Whitepaper](https://bitcoin.org/bitcoin.pdf) - Bitcoin: A Peer-to-Peer Electronic Cash System

### Ethereum
* [Ethereum Whitepaper](https://github.com/ethereum/wiki/wiki/White-Paper) - A Next-Generation Smart Contract and Decentralized Application Platform
* [Ethereum Yellowpaper](http://gavwood.com/paper.pdf) - A Secure Decentralised Generalised Transaction Ledger by Dr. Gavin Wood

### Fault Attribution
* [The problem of censorship](https://blog.ethereum.org/2015/06/06/the-problem-of-censorship/) - Vitalik Buterin on attributability of censorship
* [Minimal Slashing Conditions](https://medium.com/@VitalikButerin/minimal-slashing-conditions-20f0b500fc6c) - Vitalik Buterin on slashing conditions
* [Shapley values](https://en.wikipedia.org/wiki/Shapley_value) - Technique for translating fault attributions into penalties

### Mechanism Design
* [Mechanism Design](https://en.wikipedia.org/wiki/Mechanism_design) - Wikipedia article
* [On Anti-Pre-Revelation Games](https://blog.ethereum.org/2015/08/28/on-anti-pre-revelation-games/) - Vitalik Buterin on anti-pre-revelation games
* [Blockchain and Smart Contract Mechanism Design Challenge](http://fc17.ifca.ai/wtsc/Vitalik%20Malta.pdf) - Vitalik talk in Malta

### Data Availability & Erasure Coding
* [A note on data availability and erasure coding](https://github.com/ethereum/research/wiki/A-note-on-data-availability-and-erasure-coding) - Comprehensive review of the data availability problem from the Ethereum Foundation
* [Secret Sharing and Erasure Coding](https://blog.ethereum.org/2014/08/16/secret-sharing-erasure-coding-guide-aspiring-dropbox-decentralizer/) - Vitalik Buterin guide for the Aspiring Dropbox Decentralizer

### Stablecoins
* [Stablecoins](https://www.youtube.com/watch?v=Z8LV56xNwus) - A talk at Cryptoeconomicon
* [The Search for a Stable Cryptocurrency](https://blog.ethereum.org/2014/11/11/search-stable-cryptocurrency/) - Vitalik Buterin on stablecoins
* [The Dai Stablecoin System](https://github.com/makerdao/docs/blob/master/Dai.md) - MakerDAO's approach to a stable currency
* [Arc primer and overview (non-technical)](https://www.arccy.org/sites/default/files/arc-public-docs/arc-primer-and-overview.pdf) - A practical, intrinsic-value and financial-market approach for a stablecoin
* [A Note on Cryptocurrency Stabilisation](https://github.com/rmsams/stablecoins/blob/master/paper.pdf) - Research by Robert Sams on Seigniorage Shares

### Governance
* [Futarchy](https://blog.ethereum.org/2014/08/21/introduction-futarchy/) - An intro to futarchy by Vitalik Buterin
* [Tezos](https://www.tezos.com/static/papers/white_paper.pdf) - Whitepaper of Tezos, "a self-amending crypto-ledger"
* [Hard Forks, Soft Forks, Defaults and Coercion](http://vitalik.ca/general/2017/03/14/forks_and_markets.html) - Vitalik Buterin on when to hard fork or soft fork (and more)
* [A Note on Metcalfe's Law, Externalities and Ecosystem Splits](http://vitalik.ca/general/2017/07/27/metcalfe.html)] - Vitalik Buterin on blockchain splitting

## ConsensusMechanisms

### Proof of Stake
* [Cryptoeconomics in Casper](https://docs.google.com/presentation/d/1m1TuGRGQcdFXizpKf44AOZYECdjUFzTX5tAUf5dQhNA/edit#slide=id.p) - A Google Slides presentation by Jon Choi
* [A Proof of Stake Design Philosophy](https://medium.com/@VitalikButerin/a-proof-of-stake-design-philosophy-506585978d51) - Vitalik Buterin post about the design of a PoS system
* [The Triangle of Harm](http://vitalik.ca/general/2017/07/16/triangle_of_harm.html) - Post on Casper’s incentivization philosophy
* [Proof of Stake](https://www.youtube.com/watch?v=1tdxPzQt4ZI) - A talk at Cryptoeconomicon
* [Proof of Stake with Casper](https://www.youtube.com/watch?v=9nQPcNY32JQ) - Vlad Zamfir podcast about Casper
* [The History of Casper](https://medium.com/@Vlad_Zamfir/the-history-of-casper-part-1-59233819c9a9) - Vlad Zamfir on Casper, a Proof of Stake Consensus Protcol
* [Ethereum Casper 101](https://medium.com/@jonchoi/ethereum-casper-101-7a851a4f1eb0) - Great article on Cryptoeconomics overall with a focus on PoS
* [On Stake](https://blog.ethereum.org/2014/07/05/stake/) - Early Vitalik post on staking
* [Proof of Stake FAQ](https://github.com/ethereum/wiki/wiki/Proof-of-Stake-FAQ) - FAQ from the Ethereum wiki

### Proof of Work
* [Bitcoin](https://bitcoin.org/bitcoin.pdf) - Bitcoin: A Peer-to-Peer Electronic Cash System
* [Proof of Work](https://www.youtube.com/watch?v=sADoZx7Ar4A) - A talk at Cryptoeconomicon

### More PoS
* [On Inflation, Transaction Fees and Cryptocurrency Monetary Policy](https://blog.ethereum.org/2016/07/27/inflation-transaction-fees-cryptocurrency-monetary-policy/) - Vitalik Buterin
* [On Settlement Finality](https://blog.ethereum.org/2016/05/09/on-settlement-finality/) - Vitalik Buterin on settlement finality
* [Light Clients and Proof of Stake](https://blog.ethereum.org/2015/01/10/light-clients-proof-stake/) - Vitalik Buterin post on light clients using PoS
* [Weak Subjectivity](https://blog.ethereum.org/2014/11/25/proof-stake-learned-love-weak-subjectivity/) - Vitalik Buterin on PoS
* [Cryptocurrencies without Proof of Work](https://arxiv.org/abs/1406.5694)
* [Slasher Ghost, and Other Developments in Proof of Stake](https://blog.ethereum.org/2014/10/03/slasher-ghost-developments-proof-stake/)
* [Least Authority Performs Incentive Analysis For Ethereum](https://leastauthority.com/blog/least_authority_performs_incentive_analysis_for_ethereum/)
* [Demystifying incentives in the consensus computer](https://eprint.iacr.org/2015/702)
* [Formal methods on some PoS stuff](https://medium.com/@pirapira/formal-methods-on-some-pos-stuff-e309775c2ab8) - Formalizing PoS Medium article
* [Safety Under Dynamic Validator Sets](https://medium.com/@VitalikButerin/safety-under-dynamic-validator-sets-ef0c3bbdf9f6) - Vitalik Buterin medium post on safety
* [A mechanized safety proof with dynamic validators](https://medium.com/@pirapira/a-mechanized-safety-proof-for-pos-with-dynamic-validators-17e9b45faff4) - A reply to the Vitalik Buterin post above
* [Formal methods on another Casper](https://medium.com/@pirapira/formal-methods-on-another-casper-8a75f6e02073) - Talking about the differences betwen Vlad and Vitalik's approach to Casper
* [Nothing at Stake Problem](https://ethereum.stackexchange.com/questions/2402/what-exactly-is-the-nothing-at-stake-problem) - StackExchange "What exactly is the Nothing-At-Stake problem?"

## Attacks
* [51 percent attack](https://bitcoin.stackexchange.com/questions/658/what-can-an-attacker-with-51-of-hash-power-do) - StackExchange answer to "What can an attacker with 51% of hash power do?"
* [Cost of a 51 percent attack](https://gobitcoin.io/tools/cost-51-attack/) - Present day cost for someone to do a 51% attack the Bitcoin network
* [The P+ epsilon Attack](https://blog.ethereum.org/2015/01/28/p-epsilon-attack/) - Vitalik Buterin on the P+ epsilon attack
* [Long-Range Attacks](https://blog.ethereum.org/2014/05/15/long-range-attacks-the-serious-problem-with-adaptive-proof-of-work/) - Post by Vitalik Buterin "The Serious Problem With Adaptive Proof of Work"

## Layer1Scaling

### Sharding
* [Ethereum Sharding Doc](https://github.com/ethereum/sharding/blob/develop/docs/doc.md) - Vlad Zamfir
* [Ethereum Sharding: Overview and Finality](https://medium.com/@icebearhww/ethereum-sharding-and-finality-65248951f649) - Hsiao-Wei Wang
* [Sharding AMA](https://www.youtube.com/watch?v=qDa4xjQq1RE) - Vlad Zamfir

## Layer2Scaling

### State Channels
* [Lightning Network](http://lightning.network/) - Payment channels on the Bitcoin network
* [Raiden Network](http://Raiden.network/) - Payment channels on the Ethereum network
* [Perun Network](http://perun.network) - Perun Network (virtual channels)
* [State Channels Explanation](http://www.jeffcoleman.ca/state-channels/) - Jeff Coleman on state channels
* [Layer2Scaling Overview](https://medium.com/l4-media/making-sense-of-ethereums-layer-2-scaling-solutions-state-channels-plasma-and-truebit-22cb40dcc2f4) - Josh Stark on State Channels, Plasma and Truebit

### Plasma
* [Plasma: Scalable Autonomous Smart Contracts](http://plasma.io/plasma.pdf) - Paper on Plasma by Joseph Poon & Vitalik Buterin
* [Plasma in 10 minutes](https://medium.com/chain-cloud-company-blog/plasma-in-10-minutes-c856da94e339) - Easy to understand overview of Plasma proposal by Anthony Akentiev

### Truebit
* [Truebit Overview](https://medium.com/truebit/truebit-the-marketplace-for-verifiable-computation-f51d1726798f) - The Marketplace for Verifiable Computation by Sina Habibian
* [Truebit Paper](https://people.cs.uchicago.edu/~teutsch/papers/truebit.pdf) - Scalable Verification Solution for Blockchains by Jason Teusch and Christian Reitweßner

### Sidechains
* [Sidechains](https://blockstream.com/sidechains.pdf) - Blockstream: Enabling Blockchain Innovations with Pegged Sidechains
* [Cosmos - A Network of Distributed Ledgers](https://cosmos.network/about/whitepaper) - Cosmos whitepaper

## ApplicationLayer

### Token Design
* [How Does REP Work](http://blog.augur.net/faq/how-does-reputation-rep-work/) - Augur report on incentive structure of their prediction market token, REP
* [Introducing the Gnosis Tokens (GNO)](https://blog.gnosis.pm/introducing-the-gnosis-tokens-gno-and-wiz-5295a65c3822) - Background and reasoning for design decisions for Gnosis and the GNO token
* [Applications of Security Deposits and Prediction Markets](https://blog.ethereum.org/2015/11/24/applications-of-security-deposits-and-prediction-markets-you-might-not-have-thought-about/) - Vitalik Buterin on a few topics
* [SchellingCoin](https://blog.ethereum.org/2014/03/28/schellingcoin-a-minimal-trust-universal-data-feed/) - Vitalik Buterin on SchellingCoins

### Token Sales
* [Introducing the Gnosis Token Launch](https://blog.gnosis.pm/introducing-the-gnosis-token-launch-3cc4cffb5098) - Gnosis on using a dutch auction
* [Analyzing Token Sale Models](http://vitalik.ca/general/2017/06/09/sales.html) - Vitalik Buterin reviewing token sale models, including Gnosis' dutch auction
* [Vickrey auction](https://en.wikipedia.org/wiki/Vickrey_auction#Proof_of_dominance_of_truthful_bidding) - Method used to keep bids secret and have the winner pay the 2nd highest amount
* [Long-Term Cryptocurrency Distribution Models](https://blog.ethereum.org/2014/05/24/on-long-term-cryptocurrency-distribution-models/) - Early Vitalik Buterin post on token distribution

## Privacy

### Privacy on the Blockchain
* [Privacy on the Blockchain](https://blog.ethereum.org/2016/01/15/privacy-on-the-blockchain/) - Vitalik Buterin on privacy

### Zero Knowledge
* [ZK-Snarks](https://medium.com/@VitalikButerin/zk-snarks-under-the-hood-b33151a013f6) - ZK-Snarks under the hood by Vitalik Buterin
* [ZK-Starks](https://www.bitcoinisle.com/2017/09/30/zk-starks-new-take-on-zcash-tech-could-power-truly-private-blockchains/) - Early article on ZK-Starks

## Cryptography Reading

### Cryptography Fundamentals
* [Public-private key cryptography](https://security.stackexchange.com/questions/25741/how-can-i-explain-the-concept-of-public-and-private-keys-without-technical-jargo) - Simple explanation on StackExchange
* [Hash functions](https://medium.com/@ConsenSys/blockchain-underpinnings-hashing-7f4746cbd66b) - Basics of Hashing from Consensys

### Homomorphic Encryption
* [Homomorphic encryption](https://blog.cryptographyengineering.com/2012/01/02/very-casual-introduction-to-fully/) - Blog post by Matthew Green

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)
