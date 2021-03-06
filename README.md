# Dollar Protocol

<p align="center">
  <img alt="DP Logo" src="./assets/pairNew.svg" width="440">
</p>

<p align="center">
  An ecosystem of synthetic assets (USDx, CNYx, TSLAx and more) powered by $SHARE
</p>

[![Home Page](https://img.shields.io/badge/homepage-view-red.svg)](https://dollarprotocol.com/)
[![Chat on Telegram](https://img.shields.io/badge/Chat%20on-Telegram-brightgreen.svg)](https://t.me/dollarprotocol) 
[![Email](https://img.shields.io/badge/send-email-blue.svg)](mailto:info@dollarprotocol.ccom)
[![Twitter Follow](https://img.shields.io/twitter/follow/dollarprotocol?label=follow%20%40dollarprotocol&style=social)](https://twitter.com/dollarprotocol)

# Main Contracts
* dollars.sol
* dollarsPolicy.sol
* orchestrator.sol
* seigniorageShares.sol

# Oracle Contracts
* decentralizedOracle.sol

# Mining
* SeigniorageMining.sol

## Origins
This dual token elastic money suppply protocol is an experiment to create a truly *good* money, a money owned by the people, not by governments.

We took inspiration from [Robert Sam's seigniorage shares paper](https://github.com/rmsams/stablecoins/blob/master/paper.pdf) and created a stable money that bifurcates speculators and regular users.

In this way, we preserve the stablecoin price AND the purchasing power of the wallet.

## Security
We ran internally a host of security tests, including Echidna, Manticore, Mythril OSS, Securify and Slither. The results of such reports are in the security folder.

## Ecosystem Addresses (V2)
* USDx: [0x2F6081E3552b1c86cE4479B80062A1ddA8EF23E3](http://etherscan.io/address/0x2F6081E3552b1c86cE4479B80062A1ddA8EF23E3)
* CNYx: [0x07f89875b1F142AbCba60FF1D7FCFb7Fe404d4ed](http://etherscan.io/address/0x07f89875b1F142AbCba60FF1D7FCFb7Fe404d4ed)
* DollarPolicy: [0x452a3F4A4E8E81B619d88c2B44Bd160ce8B4fc03](http://etherscan.io/address/0x452a3F4A4E8E81B619d88c2B44Bd160ce8B4fc03)
* CNYxPolicy: [0xD7b6C3eBCD8C7701CDdB2544CA68118BFceCE8E2](http://etherscan.io/address/0xD7b6C3eBCD8C7701CDdB2544CA68118BFceCE8E2)
* Orchestrator: [0xb3D027CbF33695fA651412e4eD1Cb299cF1cF068](http://etherscan.io/address/0xb3D027CbF33695fA651412e4eD1Cb299cF1cF068)
* CNYxOrchestrator: [0x3ccbBEd50134283a7FD2EE62456c8526b2B33DD5](http://etherscan.io/address/0x3ccbBEd50134283a7FD2EE62456c8526b2B33DD5)
* SeigniorageShares: [0x39795344CBCc76cC3Fb94B9D1b15C23c2070C66D](http://etherscan.io/address/0x39795344CBCc76cC3Fb94B9D1b15C23c2070C66D)
* Decentralized Oracle SHR-USDx: [0xbA20E267D061997b3e1CCBcd6843ef3e6626dCCd](http://etherscan.io/address/0xbA20E267D061997b3e1CCBcd6843ef3e6626dCCd)
* Decentralized Oracle ETH-USDx: [0x51f729D292f8cc6A0E1D4936fA1F4B5AaE1cFeEE](http://etherscan.io/address/0x51f729D292f8cc6A0E1D4936fA1F4B5AaE1cFeEE)
* Decentralized Oracle ETH-USDC: [0x905C1036C12DF0e1701629979D7305bBB35D802b](http://etherscan.io/address/0x905C1036C12DF0e1701629979D7305bBB35D802b)
* Decentralized Oracle xBOND-ETH [0xb2bc8e996331ee37ddac7050acafbec6109dd429](http://etherscan.io/address/0xb2bc8e996331ee37ddac7050acafbec6109dd429)
* Decentralized Oracle CNYx-USDC [0xDa5e43bff8908b38AA271CDC192cafdcC28a5713](http://etherscan.io/address/0xDa5e43bff8908b38AA271CDC192cafdcC28a5713)
* USDxPoolReward [0x145B9340D4Db4042350F51CfAE982a5004416867](http://etherscan.io/address/0x145B9340D4Db4042350F51CfAE982a5004416867)
* CNYxPoolReward [0xD7b6C3eBCD8C7701CDdB2544CA68118BFceCE8E2](http://etherscan.io/address/0xD7b6C3eBCD8C7701CDdB2544CA68118BFceCE8E2)
* xBond [0xa8f8dC37f3aB1F2357eC1B6345e02798b4124DCD](http://etherscan.io/address/0xa8f8dC37f3aB1F2357eC1B6345e02798b4124DCD)
* Seigniorage Governor Alpha [0x59f83d677898f7E0D68ECb225395D41FB190cb35](http://etherscan.io/address/0x59f83d677898f7E0D68ECb225395D41FB190cb35)
* Dollar Timelock [0xf4a4534a9A049E5B3B6701e71b276b8a11F09139](http://etherscan.io/address/0xf4a4534a9A049E5B3B6701e71b276b8a11F09139)

* Liquidity Mining Reserve for future - Multisig: [0x01b6e2C30B27b3D2E15595E89F2115B139Eaf597](http://etherscan.io/address/0x01b6e2C30B27b3D2E15595E89F2115B139Eaf597)
* Liquidity Mining Contract for UniswapV2 SHARE-ETH: [0x305fFCF8C97D2BF51A4c270e2B20850De90AbF3A](http://etherscan.io/address/0x305fFCF8C97D2BF51A4c270e2B20850De90AbF3A)

## Deprecated Pools
* Liquidity Mining Contract for UniswapV2 ETH-USD: [0xC122C726D5F9975e87D710dFc021CbA6cDe8b718](http://etherscan.io/address/0xC122C726D5F9975e87D710dFc021CbA6cDe8b718)
* Liquidity Mining Contract for UniswapV2 YFI-USD: [0xE439285C0951Ca640FaBd83E5d992Bf343839B06](http://etherscan.io/address/0xE439285C0951Ca640FaBd83E5d992Bf343839B06)
* Liquidity Mining Contract for Mooniswap yCRV-USD: [0x38140A4b11a11dC6b5189FBbCF4af6eF7Dcc68C6](http://etherscan.io/address/0x38140A4b11a11dC6b5189FBbCF4af6eF7Dcc68C6)
* Liquidity Mining Contract for UniswapV2 USDT-USD: [0xc03d9f95edf22082729beec4b4b2567cf7046d94](http://etherscan.io/address/0xc03d9f95edf22082729beec4b4b2567cf7046d94)
* Liquidity Mining Contract for UniswapV2 USDC-USD: [0xb9ce76bc1b157eace940f06bd51c808d94b62fe4](http://etherscan.io/address/0xb9ce76bc1b157eace940f06bd51c808d94b62fe4)
* Liquidity Mining Contract for UniswapV2 DAI-USD: [0xeabc3ecf578d6fef1614bf69d233c19f68de912d](http://etherscan.io/address/0xeabc3ecf578d6fef1614bf69d233c19f68de912d)
* Liquidity Mining Contract for UniswapV2 AMPL-USD: [0xda68752f7bab60b1539694419003d91728d53732](http://etherscan.io/address/0xda68752f7bab60b1539694419003d91728d53732)
* Liquidity Mining Contract for UniswapV2 MKR-USD: [0x1b2e74e0bc2aede133769ab3b5bc7b9bd14df0ed](http://etherscan.io/address/0x1b2e74e0bc2aede133769ab3b5bc7b9bd14df0ed)
* Liquidity Mining Contract for UniswapV2 COMP-USD: [0x48e39B5bb84558a53f9ce206c2B6Da56C33f2aEe](http://etherscan.io/address/0x48e39B5bb84558a53f9ce206c2B6Da56C33f2aEe)
* Liquidity Mining Contract for UniswapV2 LINK-USD: [0x24bed893c46dba8693215b7cb8da426b0111c6aa](http://etherscan.io/address/0x24bed893c46dba8693215b7cb8da426b0111c6aa)


To learn more about the project, please visit [https://dollarprotocol.com](https://dollarprotocol.com)
