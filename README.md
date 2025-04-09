
<div style="text-align: center;">
    <img src="./img/stablecoin.png" height=400 width=80%/>
</div>



# 🪙 Decentralized Stablecoin (DSC) Protocol

A decentralized, crypto-collateral-backed stablecoin system built using Solidity, Foundry, and Chainlink. The protocol allows users to mint a USD-pegged stablecoin using ETH and BTC as collateral, ensuring trustless, censorship-resistant value stability.


## ✨ Features

- 🏦 Mint/burn stablecoins (DSC) using ETH and BTC as collateral
- 🔐 Over-collateralization to ensure protocol solvency
- 📉 Automatic liquidation of unsafe positions
- 🔗 Real-time price feeds via Chainlink oracles
- 🧪 Built with Foundry for blazing-fast testing & development



## 🚀 Getting Started

### Prerequisites

- Foundry installed (`curl -L https://foundry.paradigm.xyz | bash`)
- Node.js (for front-end integration if applicable)
- Git, VSCode, MetaMask

### Clone & Build

```bash
git clone https://github.com/Monisha02045/Defi-StableCoin.git
cd defi-stablecoin
forge install
forge build
```

---

## 🧾 Contracts Overview

| Contract                      | Description |
|-------------------------------|-------------|
| `DSCEngin.sol`                | ERC20-compliant stablecoin contract |
| `DecentralizedStableCoin.sol` | Manages collateral deposits and DSC minting |
| `Oracle.sol`                  | Fetches price data using Chainlink |


---

## 🧪 Testing

```bash
forge test --coverage
```

Run unit tests  to ensure protocol robustness.

---

## 🔐 Security

- Uses Chainlink for tamper-proof oracles
- Built-in liquidation to maintain solvency
- Extensive test coverage
- (Optional) Audited with Slither and MythX

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---
