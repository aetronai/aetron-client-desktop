<h1 align="center">AETRON Wallet</h1>

<p align="center">
  Desktop wallet for the AETRON blockchain
  <br/>
  <a href="https://github.com/aetronai/aetron-client-desktop/releases/latest"><strong>Download Latest Release</strong></a>
</p>

<p align="center">
  <a href="https://github.com/aetronai/aetron-client-desktop/releases/latest">
    <img src="https://img.shields.io/github/v/release/aetronai/aetron-client-desktop?style=flat-square" alt="Latest Release">
  </a>
  <a href="https://github.com/aetronai/aetron-client-desktop/releases">
    <img src="https://img.shields.io/github/downloads/aetronai/aetron-client-desktop/total?style=flat-square" alt="Downloads">
  </a>
  <img src="https://img.shields.io/badge/platforms-macOS%20%7C%20Windows%20%7C%20Linux-blue?style=flat-square" alt="Platforms">
</p>

---

## About

AETRON Wallet is the official desktop client for the AETRON blockchain (Substrate-based). It provides a secure and user-friendly interface for managing AET tokens, staking, interacting with neuronets, and participating in the decentralized AI network.

All private keys are stored locally on your device in encrypted form. The wallet never transmits your keys or passwords to any external server.

## Features

### Wallet Management
- **Create wallets** with secure mnemonic phrase generation (12 or 24 words)
- **Import wallets** from mnemonic, private key, or keystore JSON file
- **Watch-only addresses** for monitoring without signing capability
- **Multiple wallets** with individual password protection and lock/unlock
- **QR code** for easy address sharing
- **Mnemonic export** with password verification

### Transfers
- Send and receive AET tokens
- Address book for frequently used contacts
- Real-time fee estimation
- Keep-alive mode to prevent accidental account depletion
- Transaction history with block explorer links

### Staking
- View stakes across all neuronets
- Add, increase, and remove stakes
- Move stakes between neuronets
- APY calculation and emission tracking
- Hotkey management (create, import, register on neuronets)

### Multisig Wallets
- Create multi-signature wallets with custom threshold
- Propose, approve, and cancel multisig transactions
- Real-time synchronization with on-chain multisig state
- Track pending approvals from all signatories

### Neuronets Explorer
- **Metagraph** — view all registered neurons (validators and miners)
- **Registration** — register new validators/miners, view registration costs
- **Distribution** — emission and stake distribution across neuronets
- **Miner Weights** — weight distribution and consensus data

### Liquidity
- Create and manage liquidity positions
- Configure price ranges
- Track earned fees (AET and QUANT)

### Security
- Private keys encrypted and stored locally only
- Process isolation — cryptographic operations run in a separate secure process
- Individual password per wallet
- Auto-lock with configurable timeout
- Password requirement on send (optional)
- Security event logging

### Other
- **Auto-updates** — the app checks for new versions and updates seamlessly
- **Network switching** — Mainnet, Testnet, or custom node
- **Address Book** — save and manage frequently used addresses

## Supported Platforms

| Platform | Format | Architecture |
|----------|--------|--------------|
| macOS    | `.dmg` | Universal (Apple Silicon + Intel) |
| Windows  | `.exe` (NSIS installer) | x64 |
| Linux    | `.AppImage` | x64 |

## Installation

1. Go to the [Releases](https://github.com/aetronai/aetron-client-desktop/releases/latest) page
2. Download the installer for your platform:
   - **macOS**: `AETRON-Wallet-x.x.x-universal.dmg`
   - **Windows**: `AETRON-Wallet-Setup-x.x.x.exe`
   - **Linux**: `AETRON-Wallet-x.x.x.AppImage`
3. Run the installer and follow the on-screen instructions

> **macOS users**: If you see a "damaged" or "unidentified developer" warning, right-click the app and select "Open", or go to System Settings > Privacy & Security and allow the app.

## Supported Languages

- English
- Russian (Русский)
- Chinese (中文)
- Spanish (Español)
- Portuguese (Português)
- German (Deutsch)
- French (Français)
- Turkish (Türkçe)

## Networks

| Network | Endpoint |
|---------|----------|
| Mainnet | `wss://entrypoint-mainnet.aetron.ai:443` |
| Testnet | `wss://entrypoint-test.aetron.ai:443` |

You can also connect to a local node at `ws://127.0.0.1:9944` or specify a custom endpoint.


## Feedback & Issues

Found a bug or have a feature request? Please open an issue on the [Issues](https://github.com/aetronai/aetron-client-desktop/issues) page.

## License

All rights reserved. This software is proprietary.
