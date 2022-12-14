# Hypnosis Litepaper

## Abstract

At Hypnosis Foundation, we develop and innovate a new decentralized fog computing network based on the EVM technology. Our aim with Hypnosis is to launch a lightspeed, adaptive and trusted fog-computing environment that is affordable to use and ready for the web3 mass-adoption.

## Use cases

The Hypnosis platform is intended to be used as an underlying Layer 0 blockchain that is primarily intended as a decentralized fog-computing network but may also power DeFi Services, GameFi, Metaverse, Web3.0 Services, Stablecoin economics and many more. 

## Problems

In current existing decentralized platforms we oftenly see problems such as un-affordable gasprices, centralization, non-transparent projects following rugpulls and other scams, regulatory compliance, speed, scalability, security breaches and many more. In the following section we will describe how we adress each of the most vibrant difficulties in the blockchain industry.


#### Un-affordable gasprices

In an EVM based chain, gasprices are calculated through the following formula (post london hardfork): 

```math
gaslimit * (basefee + tips) = gasprice
```

The parameter **gaslimit** depends on the complexity of a transaction. The result **gasprice** depends on the user-based demand and on the value of the native Token. 
Commonly the gasprices increase when either the demand in a network increases or if the value of the native token rises.

We are adressing this difficulty by integrating an optimistic rollup engine as described in the following sections.

#### Centralization

Usually shady projects tend to centralize their power over the network which includes treasury management, governance and more. At Hypnosis Foundation, we focus heavily on community governed upgrades and community based integrity.

#### Transparency

All source-codes of the Hypnosis Foundations are published open-source under. This means the code and all smart-contracts can be viewed publicly. However, we have proteced our code from intellectual-property thefts. Hypnosis is released under the terms of the GNU General Public License v3.0.

#### Speed and Scalability

Speed and Scalability is are essential for a web3 ready blockchain. With IBFT, Hypnosis Pendulum and on-chain Sharding we maximize the performance of hypnosis mainnet to approximately 100'000 transactions per seconds (TPS). 

#### On-chain and Off-chain Security

Security and Audits are fundamentally for a trusted environment. We strive to continiously audit our official smart-contracts. We are currently working closely with industry-leaders such as Hacken, Chainsecurity and CertiK. Exploits and Vulnerabilities should be communicated over our issue tracker on github. Our official JSON-RPC API's are protected through an internal SSL and a JSON-Request Token. All of our Layer 2 Products inherit the security of the Layer 0 and 1 mainnnet. Validators are required to fulfill certain security measures. Wallet and Transaction-Adresses that do not behave correctly can be blacklisted through a governance proposal. 

> Note: We are currently working on a bug bounty platform. We will announce it as soon as we have tested it.

#### Energy-consumption

Running conventional PoW nodes can be very energy-inefficient and requires high computing-power. With our dPoS/IBFT consensus the Hypnosis blockchain operates with minimal system requirements and is Co2-neutral. 

## Comparison across the Market

|          | TPS      | Transaction Fee | Tx Finality | Consensus | Governance | Smart-Contracts |
|----------|----------|-----------------|-------------|-----------|------------|-----------------|
| Ethereum | 15-30    | ~15$                | 5mins   | PoS        | yes          | yes |
| Cardano  | ~250    | ~0.02$                | 2mins   | Ouroboros PoS       | yes          |  yes |
| Polkadot | 1000    | ~0.15$                | 30sec     | nPoS      | yes          | yes |
| Tezos    | 40-50    | ~0.00232$                | 30sec  | PoS         | yes          | yes |
| Hypnosis | +100'000    | ~0.00000000151$       | Instant | dPoS/IBFT          | yes          | yes|

## Consensi Mechanisms

In the following section we will cover the main algorithms used to achieve consensus on Hypnosis. 

### Delegated Proof-Of-Stake (dPoS)


### Istanbul Byzantinian Fault-Tolerance (IBFT)


### Proof-Of-Identity (PoI)


## What makes us different from the competitors

Below are some features that make Hypnosis unique among market-competitors.

### Fully compatible with EVM

The golang implementation of Hypnosis integrates a fully EVM-compatible execution and validation environment. The EVM (Ethereum Virtual Machine) is a turing-complete execution vm for smart-contracts and transactions that integrate with on-chain data. Any solidity-based smart-contract can be executed on Hypnosis without any difficulties. Additionally developers can integrate existing development tools such as Remix IDE and Hardhat into their Hypnosis dApps. 

### Instant block-finality

Through the use of the IBFT consensus, the Hypnosis blockchain can serve instant finalities for blocks produced and validated by our validator nodes.
The use of IBFT helps validating the chain and generating higher throughput. The definition of IBFT can be found at the [EIP-650](https://github.com/ethereum/EIPs/issues/650) proposal. 

> Note: IBFT is still in development and will be released on a seperate testnet

### Cross-chain capable

Cross-chain communications are very important when dealing with DeFI (especially swaps, lending/burrowing). With Hypnosis Pendulum we are building a Layer-2 DeFi solution that includes a cross-chain bridge. With Pendulum enabled DeFi users are able to communicate with several Layer-0/1 blockchains such as Cosmos, Polkadot, Binance, Polygon and more.

### Side-chain capable

Hypnosis is adaptive by design. This means that user can serve service-critical dApps on custom tailored sidechains that run parallely to the Hypnosis-Mainnet. Sidechains are highly customizable and modular. In the Polkadot Ecosystem this feature is known as a parachain.

### dPoS algorithm

Hypnosis is powered by a custom dPoS algorithm. Generally, dPoS is more performant than PoS and PoW based ledgers. If you want to dig in deeper, you can find a [detailed description](https://www.geeksforgeeks.org/delegated-proof-of-stake/) on how dPoS works in depth.

### EU-Compliant ECDSA 

All signatures that are signed by the internal Hypnosis-Signer are encoded using the EU-Compliant ECDSA signature algorithm. 

### Integrated rollup engine

In order to keep our gasprices at its minimum, we have developed and integrated an own optimistic rollup-engine that operates via an on-chain oracle. With our optimistic rollup engine we can achieve:

- 10-100 times more TPS than on our base-layer
- Wrapped transactions leading in a reduction of gasprice
- Operations on L2 are directly validated and integrated on the mainnet   

### PoI-Powered DID's (Decentralized Identities)

### Regulatory Compliance

## Tokenomics

The token distribution of the native HYPNO token is split as showed:

- Ecosystem / Validators: 45%
- Initial Token Sale: 25%
- Marketing and Advisors: 10%
- Emergency Treasury: 10%
- Team and Development: 10%

> Note: The Token Allocations may vary since this project is still in its planning. Every change that is made to the allocations will be publicated on this page and will be publicly verifiable on github.


## Public Audits

> Work in progress

## Team

### Timo Sarkar

Timo Sarkar, 18 is the founder and core-developer of Hypnosis. He started the project with an initial idea of an ideological scalable blockchain in 2019. He eventually started to think of a layer 0/1 protocol that could power web3 infrastructure by forming a fog-computing architecture. To thid day, Hypnosis is a decentralized fog-computing network with smart-contracts and sharding capabilities. Additionally he founded the Hypnosis Foundation which acts as a DAO and strives to be fully regulatory compliant (CH-EU).

## Vision and Roadmap

> Work in progress

## Contact

You can reach the Hypnosis Foundation at: support.hypnosis@protonmail.com for any general inquiry.

## Further readings

> Work in progress
