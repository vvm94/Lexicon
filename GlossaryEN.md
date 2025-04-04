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

## Term Definitions

### A
#### <a id="action"></a>Action  
*[Definition from previous sections...]*

#### <a id="active-permission"></a>Active Permission  
*[Definition from previous sections...]*

[... continue with all other terms in alphabetical order ...]


Here is the English translation of the provided cryptocurrency and blockchain glossary focused on EOS:

---

# Glossary of Cryptocurrency and Blockchain Terms (EOS Specific)

This glossary is an attempt to better understand English blockchain terminology and provide Arabic alternatives that can be used when writing in Arabic without needing to include the English terms.

The glossary is incomplete and may contain flaws, which is why we invite everyone to participate in translation and suggest better alternatives. Contributors' names will be added to a dedicated page linked to the glossary.

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




