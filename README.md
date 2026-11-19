# AywaPay Multisender

Send USDT, BNB or any BEP-20 token to thousands of wallets in a few signatures, built on **BNB Smart Chain (BSC)** and compatible with other EVM networks.

App: https://multisender.aywapay.com

## Technology Stack

- **Blockchain**: BNB Smart Chain + EVM-compatible chains
- **Smart Contracts**: Solidity 0.8.19 (EVM "paris", optimizer on, 200 runs)
- **Frontend**: Next.js web app, installable on phones (PWA); wallets through browser extensions and WalletConnect
- **Development**: Hardhat

## Supported Networks

- **BNB Smart Chain Mainnet** (Chain ID: 56)

## Contract Addresses

| Network | Core Contract |
|---------|---------------|
| BNB Smart Chain Mainnet | [0x636E0a91Fff76a817af815fbb4551B8D007d0cc8](https://bscscan.com/address/0x636E0a91Fff76a817af815fbb4551B8D007d0cc8) |

AywaPay Multisender has no token of its own.

## Features

- Pay up to 200 wallets per transaction; long lists are split into batches
- Sign once: two approvals in your wallet, the page sends every batch and returns what is left (or sign each batch yourself)
- USDT, BNB or any BEP-20 token, from the sender's own wallet (non-custodial, no account)
- Every row checked before sending: wrong addresses, duplicates, missing amounts
- Total, network gas and service fee shown before signing; every batch links to BscScan
- Optional 24-hour, 7-day and 30-day passes to send without the service fee

## Security

Not audited by a third party yet. Tokens pass through the contract and reach every recipient in the same transaction; nothing stays in it afterwards.

## Links

- Website: https://aywapay.com
- X: https://x.com/AywaPay
- Telegram: https://t.me/aywapay
- Contact: support@aywapay.com

