# 🌍 Transparent Disaster Relief on the Blockchain

A decentralized platform to bring **trust, speed, and accountability** to global disaster relief efforts. With this system, donations flow directly to verified aid organizations, and contributors can **track funds in real time**, earn **reputation tokens**, and participate in governance to ensure funds are spent responsibly.

---

## ✨ Features

💸 **Transparent Donations** – Direct funds to verified aid pools with full on-chain traceability
🏦 **Donation Pools** – Create and manage pooled funds for specific disasters (e.g., Earthquake, Flood)
✅ **Verified NGOs** – Only trusted relief organizations can withdraw funds
🏅 **Reputation Tokens** – Donors earn non-transferable reputation tokens (soulbound) for contributions
🗳 **Community Governance** – Token holders vote on NGO approvals and pool allocations
🔍 **Auditable Withdrawals** – Every fund release is linked to NGO reports and stored immutably
🎯 **Contributor Rewards** – Long-term donors get special governance privileges

---

## 🛠 How It Works

**For Donors**

1. Pick a disaster relief pool (e.g., Earthquake Fund 2025)
2. Send your STX donation into the pool
3. Earn **Reputation Tokens** (soulbound, not tradable)
4. Track how funds are allocated transparently

**For NGOs**

1. Apply for verification (requires governance approval)
2. Once verified, request withdrawals from disaster pools
3. Submit proof-of-aid reports on-chain (linked to fund releases)

**For the Community**

* Use **Governance Contract** to vote on:

  * Approving NGOs
  * Adjusting pool allocation rules
  * Introducing new disaster pools

---

## 🧩 Smart Contracts Overview

1. **Donation-Pool**

   * Create and manage pools for specific disasters
   * Accept donations in STX
   * Track donor balances

2. **NGO-Registry**

   * Store and verify trusted NGOs
   * Only verified NGOs can withdraw funds

3. **Governance**

   * DAO-style contract for voting on NGO approvals and policies
   * Weighted voting with Reputation Tokens

4. **Reputation-Token (Soulbound)**

   * Non-transferable token earned by donors
   * Used for governance participation

5. **Withdrawal-Requests**

   * NGOs submit withdrawal requests tied to specific pools
   * Community governance approves/rejects requests

6. **Proof-of-Aid**

   * NGOs submit immutable reports after withdrawals
   * Linked to transaction ID for public auditing

7. **Treasury**

   * Manages overall platform funds and distribution rules

8. **Disaster-Registry**

   * Catalog of active disasters and associated donation pools
