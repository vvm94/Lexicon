# Glossary of Cryptocurrency and Blockchain Terms (EOS Specific)

This glossary is an attempt to better understand English blockchain terminology and provide Arabic alternatives that can be used when writing in Arabic without needing to include the English terms.

The glossary is incomplete and may contain flaws, which is why we invite everyone to participate in translation and suggest better alternatives. Contributors' names will be added to a dedicated page linked to the glossary.

# EOS Blockchain Glossary - Alphabetical Index

| Letter | Terms |
|--------|-------|
| **A**  | [Action](#action) - [Active Permission](#active-permission) - [Airdrop](#airdrop) - [Airgrab](#airgrab) - [Approval Voting](#approval-voting) |
| **B**  | [Bandwidth](#bandwidth) - [BFT](#byzantine-fault-tolerance-bft) - [BIOS Boot Sequence](#bios-boot-sequence) - [Block Explorer](#block-explorer) - [Block Producer](#block-producer) |
| **C**  | [CPU](#cpu-central-processing-unit) - [Child Permission](#child-permission) - [Chintai](#chintai) - [Cold Storage](#cold-storage) - [Consensus](#consensus) |
| **D**  | [DAC](#decentralized-autonomous-corporation-dac) - [dApp](#dapp-decentralized-application) - [Deferred Transaction](#deferred-transaction) - [Delegate](#delegate) - [DPoS](#dpos-delegated-proof-of-stake) |
| **E**  | [EEP](#eos-enhancement-proposal-eep) - [EOS](#eos) - [EOSIO](#eosio) - [ERC-20](#erc-20) |
| **F**  | [Fiat](#fiat-currency) - [Finality](#finality) - [Fork](#fork) - [FUD](#fud-fear-uncertainty-doubt) |
| **G**  | [Genesis Block](#genesis-block) - [GitHub](#github) - [Governance](#governance) |
| **H**  | [Hash](#hash) - [Hardware Key](#hardware-key) |
| **I**  | [IBC](#ibc-inter-blockchain-communication) - [ICO](#ico-initial-coin-offering) - [Immutable](#immutable) |
| **J**  | [Jungle Testnet](#jungle-testnet) |
| **K**  | [Kylin Testnet](#kylin-testnet) |
| **L**  | [LIB](#lib-last-irreversible-block) |
| **M**  | [Mainnet](#mainnet) - [Mapping](#mapping) - [Merkle Tree](#merkle-tree) |
| **N**  | [Namespace](#namespace) - [Network](#network) - [Node](#node) |
| **O**  | [Oracle](#oracle) - [Owner Permission](#owner-permission) |
| **P**  | [Permissions](#permissions) - [PoS](#pos-proof-of-stake) - [PoW](#pow-proof-of-work) |
| **R**  | [RAM](#ram) - [Referendum](#referendum) - [REX](#rex-resource-exchange) |
| **S**  | [Smart Contract](#smart-contract) - [Staking](#staking) - [Supernode](#supernode) |
| **T**  | [TaPoS](#tpos-transaction-as-proof-of-stake) - [Testnet](#testnet) - [Tokenomics](#tokenomics) |
| **U**  | [User](#user) |
| **V**  | [Vote](#vote) - [Vote Decay](#vote-decay) |
| **W**  | [Wallet](#wallet) - [Whale](#whale) - [WPS](#wps-worker-proposal-system) |

---


---



---

## A
### Action
Every transaction in a block consists of one or more actions. Each action is an instruction to perform a specific task. A transaction can be based on multiple related actions.

### Active Permission
Within the account permission structure, the active permission is by default the primary "child" permission of the owner. The active permission can execute all account actions except restructuring permissions. It is one of two default permissions that come with a new account: "owner" and "active."

### Airdrop
Airdrop (derived from the concept of dropping supplies from aircraft) refers to the distribution of tokens to wallets, originally described in the context of Ethereum. It is commonly used in Initial Coin Offerings (ICOs), where tokens are sold during a specific period and then airdropped to participants' wallets. Another use case is distributing tokens for free to build a user base for the currency.

### Airgrab
A mechanism developed to address the costs of airdrops. The key difference is that an airgrab requires each user to claim their tokens, thus using their own RAM to store the associated information instead of the token developer's. This idea emerged due to the high cost of RAM during the initial launch of the EOS mainnet.

### Approval Voting
There are many ways to organize voting mechanisms in a community. EOS.IO uses approval voting, a system where voters can cast equal-weight votes for multiple candidates. This allows for a more decentralized distribution of votes, as an account can vote for 1 to 30 different block producers instead of selecting just one.

---

## B
### Bandwidth
EOS operates with two types of bandwidth: NET (referred to as "network") and CPU (processing). You must delegate your tokens to access the allocated bandwidth for each resource. This ensures you a proportional share of the network's capacity for your transactions, which is part of how EOS remains fee-free.

### Byzantine Fault Tolerance (BFT)
Byzantine Fault Tolerance (BFT) refers to a system's ability to continue functioning correctly even if some components fail or act maliciously, even when there is incomplete information about which components are functioning correctly. In blockchain, it is crucial for consensus mechanisms to have this property. Specifically for EOS.IO, the Delegated Proof of Stake (DPoS) mechanism must remain functional even if some block producers fail or misbehave. The term "Byzantine" originates from the Byzantine Generals Problem in computer science, where a group of generals must agree on a plan despite potential traitors among them.

### BIOS Boot Sequence
An automated tool for booting an EOS.IO network. It can be used to create a local test environment, a distributed network across multiple servers, or a fully operational EOS.IO network.

### Block Explorer
A tool for exploring the contents of a blockchain through a graphical user interface (GUI). See "eosq.app" for an example.

### Block Height
The block number in a specific blockchain. A block height of 1000 refers to the 1000th block in the chain.

### Block Producer
Block producers are teams distributed worldwide who create the blocks that form the EOS blockchain. They are elected by EOS token holders. The top 21 block producers create blocks, while a list of standby producers competes for votes to join the top 21. Another commonly used term is "supernode."

### Block Producer Agreement (regproducer)
The Block Producer Agreement is one of the supporting documents for the EOS Constitution. It outlines the rules and guidelines that block producer candidates must adhere to. It exists as a Ricardian contract on the blockchain and is signed when a candidate invokes the "regproducer" contract. The terms "Block Producer Agreement" and "regproducer" can be used interchangeably. It can be read [here](#).

### Block Rewards
Out of the 5% inflation on EOS, 1% goes to block rewards. From this 1%, 25% is paid per created block. Also known as "Bpay."

### Block.One
Block.One is the company that created the EOSIO software. Its CEO is Brendan Blumer, and its CTO is Daniel Larimer (also known by his online alias "Bytemaster"). Block.One conducted the largest and longest ICO in history, lasting 350 days and raising over $4 billion USD. They committed $1 billion USD to a venture capital fund to support technologies built on EOS.IO.

### Blockchain
A distributed database distinguished by its ability to manage a continuously growing list of records called blocks. Each block contains a timestamp and a link to the previous block. Blockchains are designed to preserve stored data and prevent tampering—once information is stored in a blockchain, it cannot be altered later.

### Borrow
The process of borrowing network/processing resources (CPU/NET) from the REX platform.

---

## C
### Child
In the permission structure of an EOS account, the owner permission is the highest authority, with all other permissions nested beneath it. Any permission derived from a parent permission is called a "child" permission. By default, an EOS account comes with the "active" permission as the child of the "owner" permission.

### Chintai
A decentralized resource exchange platform created by the block producer EOS42, with support from other block producers in the EOS mainnet community. Chintai allows users to lease their resources to borrowers at an agreed-upon interest rate.

### Cold Storage
When blockchain users refer to "cold storage," they mean storing private keys offline. This is a highly secure method since the keys are never exposed to the internet.

### Consensus
Consensus means universal agreement. Blockchains can differ in their consensus mechanisms. EOS.IO uses Delegated Proof of Stake (DPoS). Other common mechanisms include Proof of Work (PoW) and Proof of Stake (PoS).

### Constitution
EOS is described as a "governed blockchain." As such, it has a constitution, much like political jurisdictions. The constitution is a set of rules all EOS users agree to abide by as a condition of using the platform.

### CPU (Central Processing Unit)
On EOS, CPU represents processing time, a blockchain resource allocated through delegation. Every action requires a certain amount of CPU processing time, so to broadcast transactions on the EOS network, your account must have sufficient CPU staked.

---

## D
### Decentralized Autonomous Corporation (DAC)
A DAC is a decentralized autonomous corporation (or decentralized autonomous community). Similar to cooperatives, DACs are member-managed, autonomous entities that can operate independently. The entire business logic of a DAC is encoded in a smart contract on the blockchain. Also known as a Decentralized Autonomous Organization (DAO).

### Daniel Larimer
The CTO of Block.One, also known by his online alias "Bytemaster." He is renowned for creating both the BitShares and Steem blockchains before designing EOS.IO. Together, these two blockchains accounted for over half of all daily blockchain usage before the launch of the EOS mainnet. (Source: blocktivity.com)

### Decentralized Application (dApp)
A dApp is any application that runs on a decentralized network. The purest form of a dApp is one deployed on the network and operating without any centralized parties.

### Deferred Transaction
A deferred transaction is invoked within another transaction but does not execute in the original transaction. It resembles an inline action, with the only difference being the timing of execution.

### Delayed Transaction
A transaction with an active delay flag. The delay is defined in seconds.

### Delegate
Tokens on the EOS network can be in two states: delegated or undelegated. Delegating tokens allocates a share of network resources to the account that delegated them. You can delegate resources to your own account or another account using your tokens. (Also known as "stake.")

### Distributed Ledger Technology (DLT)
A replicated, shared, synchronized database distributed across multiple geographic locations without central administration. A relatively new technology, its first example was created by Satoshi Nakamoto and is known as Bitcoin—a chain of cryptographically linked transaction blocks.

### Delegated Proof of Stake (DPoS)
The consensus mechanism underlying EOS.IO. In this context, the network's credibility stems from the reputation and future incentives of block producers, encouraging them to serve the network faithfully and transparently. The consensus mechanism automatically provides incentives to maintain block producers' independence; if they act biased, they risk losing their positions. It would take collusion among at least 15 active block producers to undermine this mechanism's effectiveness and credibility. (In Proof of Work (PoW) networks like Bitcoin and Ethereum, a 51% hash rate is required for such an attack.)

---

### E
#### EOS Enhancement Proposal (EEP)  
A standard for proposing improvements to be developed by the community to create new standards for EOS.IO.

#### EOS  
The native token symbol on the EOS platform. Also commonly refers to the EOS mainnet.  
*(Network chain ID: aca376f206b8fc25a6ed44dbdc66547c36c6c33e3a119ffbeaef943642f0e906)*

#### EOSIO  
The software created by Block.One that powers the EOS mainnet and other networks using this platform.

#### EOS Alliance  
A self-formed nonprofit entity (also called "EOS Allies") that facilitates community dialogue about important EOS governance topics. It holds no authority over EOS and exists solely to serve the community.

#### EOS Go  
An independent media initiative founded by Kevin Wilcox, Johan "Bluejays" Kalin, and Jenny "TopKpop" to provide English-language news for the EOS community. Known for their weekly YouTube blogs, EOSRAD.io broadcasts, block producer candidate reports, and the forums.eosgo.io platform.  
*Acquired by a block producer team in October 2018.*

#### ERC-20  
Ethereum Request for Comment-20: The token standard for creating assets on Ethereum. The EOS initial coin offering (ICO) was conducted using ERC-20 tokens before the mainnet launch.

---

### F
#### Fiat Currency  
Government-issued currencies lacking intrinsic value, declared legal tender by regulation.

#### Finality  
Unlike other blockchains where users must wait for confirmations, EOS.IO achieves deterministic finality. Transactions behind the "last irreversible block" (LIB) are truly immutable and cannot be altered by chain reorganizations. This becomes critical with Inter-Blockchain Communication (IBC) protocols.

#### Fork  
A new blockchain created by copying the history of an existing chain and progressing independently.

#### Forum  
See: Referendum. The "eosio.forum" smart contract, created by EOS Canada, allows on-chain messaging. While versatile, it primarily serves the EOS mainnet's referendum system.

#### FUD (Fear, Uncertainty, Doubt)  
A common crypto term describing misinformation tactics used to stall progress by spreading baseless concerns.

---

### G
#### Genesis Block  
The first block in a blockchain. While forks share history with their parent chain, new platforms have unique genesis blocks. The EOS mainnet genesis block included the note:  
*"Never doubt that a small group of thoughtful, committed citizens can change the world; indeed, it's the only thing that ever has."*  
— eosacknowledgments.io

#### GitHub  
A code collaboration platform widely used for open-source projects like EOS.IO.

#### GoLang  
The Go programming language (developed by Google). EOS Canada created "eos-go" – a full Go library for EOS.IO development.

#### Governance  
The agreed-upon processes for maintaining fair and peaceful use of shared network resources.

---

### H
#### Hackathon  
Time-bound competitive events where developers collaborate on tech projects. Block.One hosts global hackathons to promote EOS.IO and dApp development.

#### Hash  
A fixed-length cryptographic fingerprint generated from input data using algorithms like SHA-256. Identical inputs always produce the same hash, enabling data verification.

#### Hash Rate  
The computational speed of mining operations (measured in hashes per second).

#### Hardware Key  
A physical device (typically USB) storing encrypted private keys. Allows cryptographic operations without exposing raw keys. If destroyed, the digital keys are permanently lost.

#### Block Header  
A section within each blockchain block containing metadata like:  
- Timestamp  
- Current block producer schedule  
- Last irreversible block number  
- Previous/current block IDs  

---

### I
#### Inter-Blockchain Communication (IBC)  
A future protocol for cross-chain interactions, enabling token transfers and parallel chain scaling.

#### Initial Coin Offering (ICO)  
A fundraising method where tokens are sold before network launch. Block.One's year-long EOS ICO raised over $4 billion – the largest in history.

#### IMEOS  
A Chinese media organization providing pre-launch EOS education to Mandarin-speaking communities.

#### Immutable  
The property of being unchangeable. Blockchain history becomes immutable through cryptographic chaining.

#### Inflation  
The EOS token issuance mechanism:  
- 5% annual inflation (adjustable, with plans to reduce to 1%)  
- 20% of inflation funds block producers and standby producers  
- 80% goes to the EOS.IO savings account  

#### Inline Action  
Smart contract-triggered actions executed within a single transaction.

#### IPFS (InterPlanetary File System)  
A decentralized storage protocol similar to BitTorrent. Block.One aims to integrate IPFS with EOS.IO for fully decentralized file storage.

---

### J
#### Jungle Testnet  
One of EOS's primary test networks.  
*Chain ID: 038f4b0fc8ff18a4f0842a8f0564611f6e96e8535901dd45e43ac8691a1c4dca*  
Resources: [GitHub](https://github.com) | [Block Explorer](https://jungle.bloks.io)

---

### K
#### KOREOS  
Korean media source providing EOS updates for Korean-speaking communities.

#### Kylin Testnet  
Another major EOS testnet operated by CryptoKylin.  
*Chain ID: 5fff1dae8dc8e2fc4d5b23b2c7665c97f9e9d8edf2b6485a86ba311c25639191*  
Resources: [Website](https://www.cryptokylin.io) | [Explorer](https://kylin.bloks.io)

---

### L
#### Launch  
The process of bootstrapping a blockchain network (synonym: "boot").

#### Leaky Bucket Algorithm  
Vote reward redistribution mechanism: Candidates earning <100 EOS/day from votes have their rewards redistributed to others above the threshold.

#### Last Irreversible Block (LIB)  
A block confirmed with 100% certainty, unaffected by chain reorganizations. Transactions beyond the LIB are permanently settled.

---

### M
#### Mainnet  
The primary EOS blockchain.  
*Chain ID: aca376f206b8fc25a6ed44dbdc66547c36c6c33e3a119ffbeaef943642f0e906*  

---




### M
#### Mapping  
During the EOS ERC-20 token distribution on Ethereum, users were required to register their public keys to map them to EOS mainnet accounts, assigning these keys to owner and active permissions on the new network.

#### Merkle Tree  
A cryptographic data structure used in EOS to link multiple transactions through hashes, ultimately connecting them to the genesis block. Provides efficient proof of transaction inclusion within a block.

#### Multi-signature (Multi-sig)  
Requires multiple cryptographic signatures (each from a different private key) to authorize an action. Enhances security by preventing single-point key compromises.

---

### N
#### Namespace  
Similar to ".com" or ".org" in web addresses, EOS allows namespace auctions for account suffixes (e.g., winning ".com" lets users create accounts ending with ".com"). Notable auctions included "eos.", "io.", and "com.".

#### Network (NET)  
A user resource representing blockchain throughput capacity. Delegating tokens secures proportional network bandwidth based on total delegated tokens.

#### Node  
Any computer/server running node software and connected to EOS's peer-to-peer (P2P) blockchain network.

---

### O
#### Open Source  
Per Article 7 of the EOS Constitution, all smart contracts must have publicly available source code for review, copying, and modification.

#### Oracle  
A system that feeds off-chain data to smart contracts (e.g., reporting basketball game scores for contract-based decisions).

#### Owner Permission  
The highest authority level in EOS account permissions. Can sign for all child permissions and restructure them. Default permissions are "owner" and "active".

---

### P
#### Permissions  
EOS.IO's account-based permission system allows customized authority structures (e.g., securing token transfers while allowing game interactions with limited keys).

#### Proof of Work (PoW)  
Consensus mechanism (used by Bitcoin) where miners compete to solve cryptographic puzzles. Increasing difficulty protects chain history.

#### Proof of Stake (PoS)  
Consensus mechanism distributing inflation rewards/transaction fees proportionally to token holders.

#### Private Key  
Cryptographic key authorizing blockchain actions under an account's permissions. Paired with a public key.

#### Public Key  
Publicly shareable key derived from a private key. Revealing it poses no security risk.

#### Proxy  
1) An account registered via `regproxy` that can receive delegated votes.  
2) Delegating voting power to another account without researching candidates.

---

### R
#### RAM  
Random Access Memory: A scarce EOS resource purchased (not staked) for fast data storage/retrieval.

#### Referendum  
EOS's on-chain voting system (via `eosio.forum` contract by EOS Canada) for community decision-making.

#### Refund  
After unstaking tokens, a 72-hour waiting period precedes refunds (shown as "pending refund" in explorers).

#### Registration  
ERC-20 EOS holders had to register public keys before mainnet launch to claim EOS mainnet accounts.

#### Resources  
EOS accounts manage three resources:  
- **RAM**: Persistent (bought/sold)  
- **CPU/NET**: Transient (renews ~24h)  

#### Resource Exchange (REX)  
A decentralized rental market for CPU/NET/RAM resources using Bancor-based distribution. Requires voting for ≥21 BPs or proxy voting.

#### Ricardian Contract  
Human-readable contract defining smart contract intent. Mandatory for all EOS smart contracts per Constitution.

---

### S
#### Smart Contract  
Self-executing contracts written in code.

#### Snapshot  
A recorded blockchain state used for airdrops or analyzing token holdings at specific times.

#### Stake  
1) Total EOS tokens owned  
2) Delegated tokens for resource access  

#### Staking  
The process of allocating EOS tokens to secure CPU/NET resources.

#### Staked  
The amount of EOS tokens currently allocated for resources.

#### Standby Producer  
Block producer candidates ranked:  
1) Top 21 (active producers)  
2) Earning ≥100 EOS/day from votes  
3) All other `regproducer` candidates  

#### Sudo  
From Linux's "superuser do". The `eosio.wrap` contract lets 15/21 BPs sign transactions on behalf of users.

#### Supernode  
Alternative term for block producer (common in other blockchain contexts).



### T
#### Transaction as Proof of Stake (TaPoS)  
A security mechanism ensuring transactions reference the latest blockchain state, preventing replay attacks where malicious actors might reuse old transactions despite account state changes.

#### Testnet  
A testing environment where developers trial smart contracts and applications. Block producers verify infrastructure functionality and test upgrades before mainnet deployment. Used for:  
- Simulating production networks  
- Stress-testing against attacks  
- Debugging unintended consequences  

#### Token  
The base unit of cryptocurrency. EOS tokens are divisible to 4 decimal places. Often used interchangeably with "coin."

#### Tokenomics  
The economic study of token systems, including:  
- Token movement dynamics  
- Currency creation/management  
- Network removal mechanisms  
Originated with Bitcoin and expanded with Ethereum's smart contracts.

#### Transaction  
A blockchain interaction containing one or multiple actions. On EOS, all on-chain operations (not just token transfers) are classified as transactions.

---

### U
#### User  
Any individual interacting with the EOS blockchain, either directly or through decentralized applications (dApps).

---

### V
#### Venture Capital (VC) Funding  
During EOS's ICO, Block.One raised ~$4 billion, allocating $1 billion to VC partnerships including:  
- Galaxy Digital  
- SVK Crypto  
- Tomorrow BC  
- FinLab  
- EOS Global  
*(Source: vc.eos.io)*

#### Vote  
A core governance mechanism in EOS.IO used for:  
- Electing block producers  
- Constitutional referendums  
- Worker Proposal System decisions  
- Council elections  

#### Vote Decay  
An incentive mechanism where voting power diminishes over time unless refreshed weekly. Prevents stale votes and maintains active block producer engagement. Users may:  
- Vote manually (≥1/week)  
- Delegate to auto-updating proxies  

#### Vote Pay (Vpay)  
From EOS's 5% inflation, 1% funds block producer rewards. 75% of this allocation distributes proportionally to candidates earning ≥100 EOS daily from votes. See also: *Leaky Bucket Algorithm*.

---

### W
#### Wallet  
Software storing private keys to authorize transactions. *Note:* Wallets don't "hold" tokens—they manage keys controlling on-chain token rights.

#### Whale  
An individual or wallet holding exceptionally large token quantities.

#### Worker Proposal System (WPS)  
A community-funded initiative supporting:  
- Network improvements  
- Community projects  
Funded through partial inflation.

---



