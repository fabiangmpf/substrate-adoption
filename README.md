# State of Substrate Adoption
*A list of projects publicly building with / for [Substrate]((https://github.com/paritytech/substrate))*

## Table of Contents
1. [Projects](#Projects)
2. [Tooling and Infrastructure](#Tooling-and-Infrastructure)
3. [Examples](#Examples)

## Projects

### AdEx

The Adex team implemented their protocol for decentralized digital advertising on Substrate. The protocol facilitates trading of advertising space/time, as well as the subsequent verification and proof that it actually occurred.

[Code](https://github.com/AdExNetwork/adex-protocol-substrate) | [Website](https://www.adex.network/)

### ChainX

ChainX is building a cross-chain digital asset management platform on top of the Substrate framework. 

[Code](https://github.com/chainx-org) | [Website](https://chainx.org/) | [Testnet](https://github.com/chainx-org/ChainX#testnet)

### Edgeware

Edgeware is a wasm-based smart contract platform with a focus on effective on-chain governance build on Substrate. It makes use of the SRML's *contracts* module. 

[Code](https://github.com/hicommonwealth) | [Team](https://commonwealth.im) | [Website](https://edgewa.re/) | [Testnet](https://polkascan.io/pre/edgeware-testnet/dashboard)

### Ethereum 2.0 Beacon Chain

Parity Technologies is building a Serenity / Ethereum 2.0 phase 0 full node implementation called 'Shasper' on top of the Substrate framework.

[Code](https://github.com/paritytech/polkadot) | [Team](https://www.parity.io/) | [Website](https://ethereum.org/) | [Testnet](https://github.com/paritytech/shasper/wiki/Shasper-Testnet-Plans)

### Horizon Games

Horizon Games is building a platform for blockchain-powered video games, as well as their own games on top of it. Substrate is used as the engine that executes the game logic and verifies results.   

[Code](https://github.com/horizon-games) | [Website](https://horizongames.net/)

### iExec

iExec is working on a decentralized blockchain-based cloud computing platform. The initial version is being build on Ethereum while the team is doing research into a Substrate-based solution. 

[Code](https://github.com/iExecBlockchainComputing/iexec-substrate-poc) | [Team](https://iex.ec/)

### Katalossos

Katallassos is an implementation of the [Algorithmic Contract Types Unified Standard (ACTUS)](https://www.actusfrf.org/about) into a specialized susbtrate-based blockchain. It's meant to become a new standard framework for originating and issuing financial instruments and financial services such as derivatives.

[Code](https://github.com/Trinkler/) | [Team](https://ipfs.io/ipns/trinkler.software/) | [Website](https://katallassos.com/)

### Kilt Protocol

The BOTLabs team is building the Kilt protocol on Substrate, a blockchain-based
protocol for self-sovereign identity.

[Code](https://github.com/KILTprotocol/) | [Team](https://botlabs.org/) | [Website](https://kilt.io/) 

 ### Ladder Network
 
Ladder Network is a solution enabling cross-chain value transfers build on the Substrate framework. 
 
[Code](https://github.com/laddernetwork/) | [Website](http://laddernetwork.io/) | [Testnet](https://telemetry.polkadot.io/#/Ladder%20Testnet%20v0.4.0)

### Plasm

Staked Technologies is building generalized Substrate runtime modules enabling developers to add Plasma functions to their Substrate-based chain.

[Code](https://github.com/stakedtechnologies) | [Team](https://staked.co.jp/)

### Polkadot Relay Chain

The first implementation of the Polkadot protocol is being built by Parity Technologies on the Substrate framework. Most of the current SRML modules in Substrate will be used in Polkadot. Furthermore, all chains being build on Substrate will be compatible with Polkadot, meaning they can plug into the Polkadot network as a native parachain.

[Code](https://github.com/paritytech/polkadot) | [Team](https://www.parity.io/) | [Website](https://polkadot.network/) | [Testnet](https://telemetry.polkadot.io/)

### Robonomics

Airalab is building blockchain infrastructure for cyber-physical systems integration into Smart Cities and Industry 4.0. The project 'Robonomics' is already running on Ethereum. The solution is now also being developed on Substrate with a plan to eventually integrating it into Polkadot.

[Code](https://github.com/airalab) | [Team](https://aira.life/en/) | [Website](https://robonomics.network/) | [Testnet](https://telemetry.polkadot.io/#/Robonomics)

### Starlog

Starlog is a Substrate-based blockchain, which stores metadata for IPFS. Data will be signed by the uploaders and include availability information, a price, a timestamp, a license, information about the uploaded file itself as well as the location/gateway of the initial upload.

[Code](https://github.com/PACTCare/Starlog)

### Totem Accounting

Totem is building an accounting soltuion on Substrate.

[Code](https://gitlab.com/totem-tech) | [Website](https://totemaccounting.com/)

### ZeroChain

Zerochain is a privacy-preserving blockchain build on Substrate. It is designed to get efficient zero-knowledge proving, reduce the on-chain storage cost and bring the flexibility for developing applications.

[Code](https://github.com/LayerXcom/zero-chain) | [Team](https://layerx.co.jp/)

## Tooling and Infrastructure 

### Chainhammer

Chainhammer is a performance benchmarking tools for blockchains. Support for Substrate is on it's way.

[Code](https://github.com/drandreaskrueger/chainhammer)

### Enzyme

BlockX Labs is building a browser extension wallet for Substrate & Polkadot.

[Code](https://github.com/blockxlabs/enzyme) | [Team](https://blockxlabs.com/) | [Website](https://getenzyme.dev/)

### Polkascan

Polkascan is a generalized open-source block explorer for any Substrate-based blockchain. 

[Code](https://github.com/polkascan) | [Website](https://polkascan.io/)

### Protos

Protos is building an open source node explorer.

[Code](https://github.com/protos-research/polkadot-node-explorer) | [Team](http://protosmanagement.com/)

### SpeckleOS

SpeckleOS is building a universal user interface for Substrate & Polkadot. This involves a browser extension wallet for the ecosystem. 

[Code](https://github.com/SpeckleOS) | [Website](https://www.speckleos.io/)

### substraTEE

substraTEE is an extension to Substrate, allowing to call a custom state transition function inside a Trusted Execution Environment (TEE), namely an Intel SGX enclave thereby providing confidentiality and integrity. The enclaves operate on an encrypted state which can be read and written only by a set of provisioned and remote-attested enclaves. substraTEE enables use cases demanding transaction privacy as well as atomic cross-chain transfers (bridges).

[Code](https://github.com/scs/substraTEE) | [Team](https://www.scs.ch/)

## Examples

### Substrate Collectables

Parity Technologies built a collectables blockchain - a chain that creates assets, and allows users to interact with and managing ownership of them. There is a self-paced workshop that walks you through the implementation.

[Code](https://github.com/shawntabrizi/substrate-collectables-workshop) | [Team](https://www.parity.io/)

### SunshineDAO

A fund coordination DAO built by Parity Technologies on Substrate, inspired by MolochDAO.

[Code](https://nuget.pkg.github.com/4meta5/SunshineDAO) | [Team](https://www.parity.io/)

### TCR DAppChain on Substrate

Parity Technolgies implemented a Token Curated Registry as a runtime in Substrate. There is a self-paced workshop that walks you through the implementation.

[Code](https://github.com/parity-samples/substrate-tcr) | [Team](https://www.parity.io/)

### UTXO on Substrate

Parity Technologies built an example implementation of an UTXO (Bitcoin-like) chain on Substrate. There is a self-paced workshop that walks you through the implementation.

[Code](https://github.com/nczhu/utxo-workshop) | [Team](https://www.parity.io/)

### Others

There are multiple smaller example implementations, like ERC20 and ERC721 runtimes, a Proof-of-Existence chain, a Websocket Listener and more that can be found in [Parity's Sample Repository](https://github.com/parity-samples).
