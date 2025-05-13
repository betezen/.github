# Betezen.Fun
**Perpetual Prediction Market for Country Performance**  
*Don't Bet, Trade Your Country's Future.*

<img src="assets/betezen.png" alt="Betezen Logo" width="400"/>

---

## 🧭 Overview
Betezen.Fun introduces a new type of prediction market: **perpetual, decentralized, and based on economic fundamentals**.
Users can trade tokenized representations of country performance — going long or short — based on indicators like inflation, GDP growth, stock indices, and exchange rates.
These contracts never expire, allowing positions to be held as long as desired.

Unlike traditional prediction markets where users bet on binary outcomes, 
Betezen.Fun quantifies macroeconomic predictions into tradable indices. 
For example, instead of predicting "Will interest rates rise?", traders can go 
long or short on a rate index that reflects central bank decisions. This turns 
policy speculation into an on-chain asset.

## 😵 Problem We Are Solving
- ⏳ Expiring prediction markets limit long-term forecasting.
- 💸 High liquidation risk on leveraged positions.
- 🧩 No financial product for directly trading macro trends of countries.
- 🌐 Prediction markets too focused on events, not economic fundamentals.

---

## 💡 Solution
We introduce Perpetual Country Positions, where traders can:
- 📈 Open long/short positions on countries based on real indicators.
- 🌀 Keep positions perpetually — no expiry.
- ⚖️ Avoid full liquidations — positions decay over time, not explode.
- 🤝 Trade with transparent funding fees and no centralized intermediaries.

---

## ⚙️ How It Works
1. CountryScore Calculation
   Based on CPI, GDP, Stock Index, Exchange Rate — hardcoded (PoC) or via oracle.
2. Position Contracts
   Users open long or short using openPosition(), and can set takeProfit/stopLoss.
3. Funding Fee Model
   Balances incentives between longs/shorts.
4. Profit/Loss Sharing
   All handled by smart contracts — no need to trust us.

---   

## ✨ Key Features
- 🔁 Perpetual Markets – Positions never expire.
- 📊 CountryScore – Derived from economic data.
- 🧠 Leverage Trading – Predict with 1x–5x impact.
- 🤖 On-Chain Settlement – All logic in Solana(SVM).
- 🧑‍🌾 Liquidity Provider Rewards – For market makers.
- 🔄 No Total Liquidation – Reduce risk, improve fairness.

---

## 🧪 Tech Stack
| Layer          | Stack / Tools                                           |
| -------------- | ------------------------------------------------------- |
| Frontend       | React.js, Tailwind CSS                                  |
| Wallet Auth    | Connect with Phantom Wallet                             |
| Smart Contract | **RUST** via Substrate Contracts pallet                 |
| Blockchain     | **Solana Ecosystem**                                    |
| Dev Tools      | cargo-contract, Substrate Playground, Phala Dev Tools   |
| Hosting        | Vercel, IPFS, Static Web Deployment                     |

---

## ⚙️ Smart Contracts on Polkadot
Our smart contracts are built using ink!, a Rust-based language designed specifically for the Polkadot ecosystem. Unlike traditional Ethereum-based contracts written in Solidity, ink! runs natively on the Substrate Contracts Pallet, enabling far more efficient execution in terms of speed and cost.

⚡ Why Polkadot + ink!
- Low to Zero Gas Fees
  On Polkadot, contract execution is significantly cheaper than on EVM-based chains. In some testnets or parachains, gas fees can be effectively zero, enabling more experimentation and frequent interaction without cost barriers.
  
- High Performance
  Contracts compiled from Rust into WebAssembly (Wasm) are inherently faster and safer. This means smart contracts on Polkadot are not only cheaper but also more performant, making them suitable for complex applications like perpetual prediction markets.

---

🎥 Demo Video
📽 Coming Soon – [Link to YouTube]

🖼 Presentation Slide
🧾 Figma Slides

🔗 Link
🌐 betezen.fun: [https://betezen.netlify.app/]

---

## 📚 References & Inspirations
Noise.xyz:
Inspired the idea of tokenizing non-price signals like attention.

Polymarket:
Demonstrated strong UX in decentralized betting.

---

🛠 How to Contribute

```bash
# 1. Fork this repo
# 2. Create a new branch
git checkout -b feature/your-feature

# 3. Make your changes
# 4. Push and open a PR
git push origin feature/your-feature
```

## Team
- **Ahmad Taufiq Harahap** – Project Manager([GitHub](https://github.com/AhmadTaufiq24))
- **Syahlevi Aldarna** – Frontend Dev([GitHub](https://github.com/syahlevi-aldarna))
- **Danuardi** – Backend Dev([GitHub](lihttps://github.com/Danuardi))

## Contact
- Email: betezen.fun@gmail.com
- Twitter: https://x.com/betezen_fun
