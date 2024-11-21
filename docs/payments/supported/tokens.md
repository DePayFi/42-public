---
sidebar_position: 3
sidebar_label: Tokens
---

# Supported Tokens

Learn which tokens are supported by DePay and what requirements custom tokens need to fulfill.

## What tokens are supported?

DePay's permissionless, decentralized payment routing protocol technically supports all tokens fulfilling the requirements (see [requirements](#requirements)).

Please check [DePay's Website > About > Tokens](https://depay.com/tokens) in order to check which tokens are currently supported exactly.

## Requirements

In order for a token to be supported by DePay, that token needs to be a standard token, like ERC20, SPL etc..
Any customizations or additions to the token standard are not supported by DePay.

Additionally that token also needs to have:

  - a pair (liquidity pool) on a supported decentralized exchange (see [supported exchanges](/docs/payments/supported/exchanges))
  - a pair in either the native wrapped token of the respective blockchain (e.g. WETH on Ethereum, WMATIC on Polygon etc.) or a supported stable coin on the respective blockchain
  - with **at least USD 20k** in liquidity: USD 10k worth of base token e.g. WETH, WMATIC, USDC etc. + USD 10k worth of the token to be supported

