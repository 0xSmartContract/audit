# 🛡️ 0xSmartContract — Smart Contract Security Researcher

> **Independent security researcher** specializing in EVM smart contract auditing, with a track record across **118+ competitive audits and judging engagements** on Code4rena, Sherlock, and CodeHawks (Cyfrin). Focused on DeFi, account abstraction, cross-chain infrastructure, and protocol-level vulnerability discovery.

<p align="left">
  <a href="https://audits.sherlock.xyz/watson/0xsmartcontract">
    <img src="https://img.shields.io/badge/Sherlock-Watson-5C4EE5?style=for-the-badge" alt="Sherlock"/>
  </a>
  <a href="https://code4rena.com/@0xSmartContract">
    <img src="https://img.shields.io/badge/Code4rena-Warden-FF4500?style=for-the-badge" alt="Code4rena"/>
  </a>
  <a href="https://profiles.cyfrin.io/u/0xsmartcontract">
    <img src="https://img.shields.io/badge/CodeHawks-Hawk-00C2A8?style=for-the-badge" alt="CodeHawks"/>
  </a>
  <a href="https://twitter.com/0xSmartContract">
    <img src="https://img.shields.io/badge/Twitter-@0xSmartContract-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white" alt="Twitter"/>
  </a>
</p>

---

## 👋 About

I am a smart contract security researcher with deep expertise in **EVM internals, account abstraction (EIP-4337 / EIP-7702), MEV mechanics, and cross-chain bridge architecture**. My work combines hands-on offensive security — competing head-to-head with the world's top auditors in public contests — with a rigorous, low-level understanding of bytecode, opcode behavior, and protocol design.

Over the course of **100+ competitive audits**, I have surfaced **16 High** and **33 Medium** severity vulnerabilities across some of the most well-known protocols in the ecosystem, including **Nouns DAO, ENS, Chainlink CCIP, zkSync, EigenLayer, Blur, Maverick, and Art Gobblers**. I consistently rank inside the **top tier** of competitive fields, with **34 top-10 finishes** and **3 podium results**.

Beyond finding bugs, I also serve as a **Lead Judge on Sherlock**, evaluating and triaging submissions from other researchers — a role that reflects both the trust placed in my technical judgment and my commitment to raising the quality bar of the auditing ecosystem as a whole.

> 🧭 Smart Contracts · 📄 Code Review · 🤖 Crypto Automation · 📇 Auditing · ⚖️ Judging · 🐺 C4 Warden

---

## 📊 Track Record at a Glance

| Metric | Value |
| :--- | :---: |
| 🏆 **Total Engagements** | **118+** |
| 💰 **Total Awarded** | **~$75,400+** |
| 🔴 **High Severity Findings** | **16** |
| 🟡 **Medium Severity Findings** | **33** |
| ⚖️ **Judging Engagements** | **4** (incl. Lead Judge) |
| 🥇 **Podium Finishes (Top 3)** | **3** |
| 🔟 **Top-10 Finishes** | **34** |


---

## 🎖️ Career Highlights

A selection of standout results that demonstrate consistency against elite competitive fields:

| 🏅 Result | Contest | Platform | Notable Finding |
| :--- | :--- | :--- | :--- |
| 🥈 **Silver** | LooksRare Aggregator | Code4rena | Timelock bypass in stated governance flow |
| 🥉 **Bronze** | Blur Exchange | Code4rena | Owner can instantly drain all platform assets (High) |
| 🥉 **Bronze** | Sense | Sherlock | ERC4626 first-deposit share inflation exploit (High) |
| **#4** | Art Gobblers | Code4rena | Centralization risk around `RandProvider` (Medium) |
| **#5** | Maverick | Code4rena | Top-5 in a highly competitive AMM audit |
| **#5** | zkSync v2 / Era | Code4rena | Top-5 across two zkSync engagements |
| **#6** | Caviar | Code4rena | Top-6 NFT AMM result |
| **#6** | Canto Identity Protocol | Code4rena | Top-6 finish |
| ⚖️ **Lead Judge** | MagicSea / MakerDAO / Rumpel | Sherlock | Trusted to judge & triage competitive submissions |

---

## 🔬 Selected High-Severity Findings

Representative critical-impact vulnerabilities discovered across engagements:

- 🔴 **Blur Exchange** — A compromised or malicious owner could immediately steal all assets held on the platform.
- 🔴 **Redacted Cartel** — Asset drainage of the auto-compounding vault and share-price manipulation in `AutoPxGmx` / `AutoPxGlp`.
- 🔴 **Decent** — Missing minimum-gas checks across LayerZero messaging causing destination-chain execution failures; unrestricted Router address updates in `DcntEth`.
- 🔴 **LSD Network (Stakehouse)** — Cross-chain replay attack vector in `deployLPToken`.
- 🔴 **Nouns DAO** — Loss of veto power enabling a 51% governance attack.
- 🔴 **Nouns Builder** — Infinite loop in `Token::mint` when founder shares sum to 100.
- 🔴 **Sense** — ERC4626 first-deposit exploit breaking share accounting.
- 🔴 **NFTPort** — Missing reentrancy guard on the `mint` function.
- 🔴 **USSD** — Absent slippage protection in `UniV3SwapInput`; missing access control on rebalancer mint/burn.
- 🔴 **Ajna Protocol** — Reward loss when claiming against an underfunded contract.
- 🔴 **Curves** — Unauthorized access to the `setCurves` function.

---

## 🧠 Areas of Expertise

| Domain | Focus |
| :--- | :--- |
| **DeFi Protocols** | Lending, AMMs, stablecoins, vaults, yield strategies |
| **Account Abstraction** | EIP-4337 EntryPoint mechanics, EIP-7702 delegation |
| **Cross-Chain** | LayerZero, CCIP, bridge replay & messaging security |
| **MEV & Economic Attacks** | Slippage, oracle manipulation, share inflation, front-running |
| **EVM Internals** | Opcode/bytecode-level analysis, storage layout, reentrancy |
| **Governance** | Voting power, quorum, timelock & centralization risk |

---

## ⚖️ Judging  (Sherlock)

Selected to evaluate, triage, and rule on competitive audit submissions — including a **Lead Judge** appointment with a performance bonus.

| Date | Contest | Role | Result | Award |
| :--- | :--- | :--- | :---: | ---: |
| 2024-10 | Rumpel | Judge | 🥉 3rd | $37 |
| 2024-10 | MakerDAO | Judge | — | $207 |
| 2024-08 | MagicSea | Judge | 🥇 1st | $538 |
| 2024-08 | MagicSea | **Lead Judge** | +10% Bonus | $1,479 |

---

## 🗂️ Full Audit Portfolio

The complete list of competitive engagements across **Sherlock**, **Code4rena**, and **CodeHawks (Cyfrin)**, ordered by recency.

### 🟣 Sherlock · 🟠 Code4rena · 🟢 CodeHawks (Cyfrin) — Competitive Audits

| Date | Contest | Platform | Award |
| :--- | :--- | :--- | ---: |
| 2024-02 | AI Arena | Code4rena | $216.02 |
| 2024-02 | HydraDX | Code4rena | $118.22 |
| 2024-01 | Decent | Code4rena | $186.33 |
| 2024-01 | Salty.IO | Code4rena | $39.34 |
| 2024-01 | Curves | Code4rena | $116.28 |
| 2023-12 | Ethereum Credit Guild | Code4rena | $892.68 |
| 2023-11 | Shell Protocol | Code4rena | $44.92 |
| 2023-11 | Panoptic | Code4rena | $479.29 |
| 2023-11 | Canto App-Specific Dollars & Bonding Curves | Code4rena | $288.91 |
| 2023-11 | Kelp DAO \| rsETH | Code4rena | $12.29 |
| 2023-10 | Party Protocol | Code4rena | $575.73 |
| 2023-10 | Ethena Labs | Code4rena | $88.73 |
| 2023-10 | The Wildcat Protocol | Code4rena | $412.50 |
| 2023-10 | Brahma | Code4rena | $14.47 |
| 2023-10 | ENS | Code4rena | $85.67 |
| 2023-09 | Maia DAO — Ulysses | Code4rena | $269.01 |
| 2023-08 | Dopex | Code4rena | $832.85 |
| 2023-08 | Shell Protocol | Code4rena | $441.46 |
| 2023-08 | veRWA | Code4rena | $47.92 |
| 2023-08 | Arbitrum Security Council Election System | Code4rena | $627.26 |
| 2023-08 | PoolTogether V5: Part Deux | Code4rena | $556.10 |
| 2023-08 | Tangible Caviar | Code4rena | $0.72 |
| 2023-08 | Good Entry | Code4rena | $158.78 |
| 2023-07 | Moonwell | Code4rena | $69.77 |
| 2023-07 | Amphora Protocol | Code4rena | $774.71 |
| 2023-07 | PoolTogether | Code4rena | $135.25 |
| 2023-07 | Tapioca DAO | Code4rena | $2,276.11 |
| 2023-07 | Basin | Code4rena | $303.89 |
| 2023-07 | Nouns DAO | Code4rena | $1,081.39 |
| 2023-07 | Beedle — Oracle-Free Perpetual Lending | CodeHawks | $171.69 |
| 2023-07 | Foundry DeFi Stablecoin | CodeHawks | — |
| 2023-06 | Canto | Code4rena | $348.84 |
| 2023-06 | Llama | Code4rena | $730.13 |
| 2023-06 | Stader Labs | Code4rena | $253.86 |
| 2023-05 | Maia DAO Ecosystem | Code4rena | $3,084.68 |
| 2023-05 | Chainlink CCIP & ARM Network | Code4rena | $59.42 |
| 2023-05 | USSD — Autonomous Secure Dollar | Sherlock | $0.00 |
| 2023-05 | Juicebox Buyback Delegate | Code4rena | $16.19 |
| 2023-05 | Venus Protocol Isolated Pools | Code4rena | $101.57 |
| 2023-05 | Ajna Protocol | Code4rena | $195.42 |
| 2023-04 | EigenLayer | Code4rena | $90.02 |
| 2023-04 | ENS | Code4rena | $637.07 |
| 2023-04 | Frankencoin | Code4rena | $43.63 |
| 2023-04 | Caviar Private Pools | Code4rena | $506.27 |
| 2023-04 | Rubicon v2 | Code4rena | $742.78 |
| 2023-03 | Gitcoin | Sherlock | $392.94 |
| 2023-03 | Asymmetry | Code4rena | $132.80 |
| 2023-03 | Canto Identity Subprotocols | Code4rena | $278.11 |
| 2023-03 | Polynomial Protocol | Code4rena | $103.46 |
| 2023-03 | zkSync Era System Contracts | Code4rena | $237.70 |
| 2023-03 | Neo Tokyo | Code4rena | $455.70 |
| 2023-03 | Wenwin | Code4rena | $251.21 |
| 2023-03 | Aragon Protocol | Code4rena | $774.31 |
| 2023-02 | Ethos Reserve | Code4rena | $764.26 |
| 2023-02 | Fair Funding (Alchemix & Unstoppable) | Sherlock | $107.05 |
| 2023-01 | Popcorn | Code4rena | $384.79 |
| 2023-01 | Canto Identity Protocol | Code4rena | $915.39 |
| 2023-01 | Numoen | Code4rena | $1,042.54 |
| 2023-01 | RabbitHole Quest Protocol | Code4rena | $230.95 |
| 2023-01 | Drips Protocol | Code4rena | $254.80 |
| 2023-01 | Timeswap | Code4rena | $1,678.01 |
| 2023-01 | Cooler | Sherlock | $0.30 |
| 2023-01 | OpenSea Seaport 1.2 | Code4rena | $310.43 |
| 2023-01 | Ondo Finance | Code4rena | $735.46 |
| 2023-01 | Reserve | Code4rena | $1,126.63 |
| 2023-01 | Astaria | Code4rena | $616.50 |
| 2023-01 | Biconomy — Smart Contract Wallet | Code4rena | $1,208.86 |
| 2022-12 | Papr | Code4rena | $394.79 |
| 2022-12 | GoGoPool | Code4rena | $1,198.27 |
| 2022-12 | Caviar | Code4rena | $1,222.80 |
| 2022-12 | Tigris Trade | Code4rena | $1,223.44 |
| 2022-12 | prePO | Code4rena | $840.61 |
| 2022-12 | Escher | Code4rena | $624.40 |
| 2022-12 | PoolTogether | Code4rena | $795.08 |
| 2022-12 | Maverick | Code4rena | $1,432.53 |
| 2022-11 | ParaSpace | Code4rena | $882.55 |
| 2022-11 | Canto | Code4rena | ₵758.10 |
| 2022-11 | Redacted Cartel | Code4rena | $1,058.24 |
| 2022-11 | Bull v Bear | Sherlock | $306.83 |
| 2022-11 | LSD Network — Stakehouse | Code4rena | $2,322.49 |
| 2022-11 | Blur Exchange | Code4rena | $1,193.90 |
| 2022-11 | LooksRare Aggregator | Code4rena | $5,205.96 |
| 2022-11 | SIZE | Code4rena | $73.96 |
| 2022-11 | Debt DAO | Code4rena | $691.09 |
| 2022-11 | Sense | Sherlock | $2,352.73 |
| 2022-10 | zkSync v2 | Code4rena | $2,102.32 |
| 2022-10 | Paladin — Warden Pledges | Code4rena | $391.01 |
| 2022-10 | Inverse Finance | Code4rena | $691.21 |
| 2022-10 | NFTPort | Sherlock | $1,324.75 |
| 2022-10 | Holograph | Code4rena | $771.29 |
| 2022-10 | 3xcalibur | Code4rena | $570.47 |
| 2022-10 | Juicebox | Code4rena | $367.96 |
| 2022-10 | Trader Joe v2 | Code4rena | $2,351.98 |
| 2022-10 | The Graph L2 Bridge | Code4rena | $1,054.18 |
| 2022-10 | Blur Exchange | Code4rena | $83.13 |
| 2022-09 | QuickSwap & StellaSwap | Code4rena | $466.16 |
| 2022-09 | Frax Ether Liquid Staking | Code4rena | $91.75 |
| 2022-09 | VTVL | Code4rena | $265.65 |
| 2022-09 | Art Gobblers | Code4rena | $6,785.46 |
| 2022-09 | Harpie | Sherlock | $121.37 |
| 2022-09 | Y2K Finance | Code4rena | $52.80 |
| 2022-09 | PartyDAO | Code4rena | $375.53 |
| 2022-09 | FEI & TRIBE Redemption | Code4rena | $33.58 |
| 2022-09 | Canto Dex Oracle | Code4rena | ₵210.46 |
| 2022-09 | Nouns Builder | Code4rena | $489.18 |
| 2022-08 | Olympus DAO | Code4rena | $248.18 |
| 2022-08 | Nouns DAO | Code4rena | $1,124.43 |
| 2022-08 | FIAT DAO veFDT | Code4rena | $15.00 |
| 2022-08 | Fraxlend (Frax Finance) | Code4rena | $108.73 |
| 2022-08 | Foundation Drop | Code4rena | $73.00 |
| 2022-08 | Mimo August 2022 | Code4rena | $40.74 |
| 2022-08 | Rigor Protocol | Code4rena | $62.38 |
| 2022-07 | Axelar Network v2 | Code4rena | $56.13 |
| 2022-07 | Golom | Code4rena | $129.83 |

---

## 🤝 Engagement

I am available for **private security reviews and protocol audits**. If you are building in DeFi, account abstraction, or cross-chain infrastructure and want a thorough, adversarial review before mainnet, let's talk.

- 🐦 **Twitter/X:** [@0xSmartContract](https://twitter.com/0xSmartContract)
- 💬 **Discord:** `0xSmartContract`
- 🐙 **GitHub:** [@0xSmartContract](https://github.com/0xSmartContract)
- 📊 **Sherlock:** [audits.sherlock.xyz/watson/0xsmartcontract](https://audits.sherlock.xyz/watson/0xsmartcontract)
- 🦅 **CodeHawks:** [profiles.cyfrin.io/u/0xsmartcontract](https://profiles.cyfrin.io/u/0xsmartcontract)

---

<p align="center"><i>Security is not a feature you add — it's an assumption you continually test.</i></p>
