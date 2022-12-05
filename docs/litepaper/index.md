# Hypnosis Litepaper

## Abstract

At Hypnosis Foundation, we develop and innovate a new decentralized smart-contract platform based on the EVM technology called Hypnosis. Our aim with Hypnosis is to launch a lightspeed, adaptive and interconnected blockchain that is ready for the web3 mass-adoption. 

## Use cases

The Hypnosis platform is intended to be used as an underlying Layer 0 blockchain that may power DeFi Services, GameFi, Metaverse, Web3.0 Services, Stablecoin economics and many more. 

## Problems

In current existing decentralized platforms we oftenly see problems such as un-affordable gasprices, centralization, non-transparent projects following rugpulls and other scams, regulatory compliance, speed, scalability, security breaches and many more. In the following section we will describe how we adress each of the most vibrant difficulties in the blockchain industry.


#### Un-affordable gasprices

In an EVM based chain, gasprices are calculated through the following formula (post london hardfork): 

```math
gaslimit * (basefee+ tips) = gasprice
```

The parameter **gaslimit** depends on the complexity of a transaction. The result **gasprice** depends on the user-based demand and on the value of the native Token. 
Commonly the gasprices increase when either the demand in a network increases or if the value of the native token rises.

We are adressing this difficulty by integrating an optimistic rollup engine as described in the following sections.

#### Centralization

Usually shady projects tend to centralize their power over the network which includes treasury management, governance and more. At Hypnosis Foundation, we focus heavily on community governed upgrades and community based integrity.

#### Transparency


#### Regulatory Compliance

#### Speed and Scalability

Speed and Scalability is are essential for a web3 ready blockchain. With IBFT, Hypnosis Pendulum and on-chain Sharding we maximize the performance of hypnosis mainnet to approximately 100'000 transactions per seconds (TPS). 

#### On-chain and Off-chain Security

#### Energy-consumption

### Comparison across the Market

## Consensi Mechanisms

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

## Public Audits

## Team

## Vision and Roadmap

## Contact

## Further readings
