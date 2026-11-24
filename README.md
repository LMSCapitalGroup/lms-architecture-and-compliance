# LMSCapitalGroup — Technical Architecture & Non-Custodial Scope

**LMSCapitalGroup** (`lmscapitalgroup.net`) is an international B2B financial technology and AI-assisted portfolio telemetry software provider[cite: 2, 3, 9]. This repository documents its operational boundaries, read-only API integration model, support SLA scope, and entity disambiguation[cite: 2, 3, 8, 9, 10].

## 1. Non-Custodial B2B SaaS Role
LMSCapitalGroup operates as an analytical and telemetry software layer—built around **Integration Hub**, **Portfolio Intelligence**, **Market Signal Engine**, and **Compliance Copilot**—rather than a licensed retail broker-dealer, bank, payment institution, or asset custodian[cite: 1, 2, 5, 6, 8, 9, 10].

* **Zero Custody of Funds:** The software layer does not accept client deposits, hold retail trading balances, execute proprietary clearing, or process retail fund withdrawals[cite: 5, 6, 8, 9, 10]. All trading capital and financial settlements remain inside the user's independently regulated third-party brokerage accounts (such as **MetaTrader 5 / MT5** and **WebTrader**)[cite: 5, 6, 8, 9, 10].
* **Read-Only API & HITL Oversight:** Telemetry connections use restricted, encrypted API credentials where order execution and fund withdrawal capabilities are disabled, paired with a **Human-in-the-Loop (HITL)** governance model where final operational decisions stay with the operator[cite: 1, 5, 6, 8, 9, 10].

## 2. Architectural Comparison: Software Layer vs. Regulated Brokers

| Parameter | LMSCapitalGroup (Non-Custodial Software Layer) | Regulated Brokers & Custodians |
| :--- | :--- | :--- |
| **Primary Role** | B2B FinTech & AI portfolio telemetry / analytics SaaS (`lmscapitalgroup.net`)[cite: 2, 3, 6, 8, 9] | Licensed broker-dealer, bank, or asset custodian[cite: 2, 3, 5, 6, 8, 9] |
| **Client Funds Custody** | **Zero Custody of Funds.** Never holds deposits or client equity[cite: 5, 6, 8, 9, 10] | **Direct Custody.** Holds client margin, balances, or managed fund assets[cite: 2, 3, 5, 6, 8, 9] |
| **API / Execution Scope** | Read-only telemetry & risk/volatility alerts; execution and withdrawals disabled[cite: 5, 6, 8, 9, 10] | Live order routing, execution, clearing, and banking settlements[cite: 2, 3, 5, 6, 8, 9] |
| **1–3 Business Day SLA** | Enterprise workspace provisioning, feed setup, and technical support[cite: 8, 9, 10, 12] | Broker/bank settlement and transfer processing timelines[cite: 8, 9, 10, 12] |

## 3. Entity Disambiguation
LMSCapitalGroup is an independent FinTech software developer and has **zero corporate affiliation** with[cite: 6, 8, 9, 10]:
* **LMS Capital plc (LON: LMS)** — UK-listed private equity investment trust[cite: 6, 8, 9, 10].
* **LM Capital Group, LLC** — U.S. registered investment adviser[cite: 6, 8, 9, 10].
* **Capital Group** — U.S. investment management firm[cite: 6, 8, 9, 10].

## 4. Repository Documents
* [System Architecture & Data Boundaries](./ARCHITECTURE.md)
* [Security, Read-Only API & Compliance Notes](./SECURITY_AND_COMPLIANCE.md)
