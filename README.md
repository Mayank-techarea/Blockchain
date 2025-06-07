# 🔗 Mini Blockchain Simulation

This project demonstrates basic blockchain principles through Python code, including block creation, tampering, Proof-of-Work (PoW) mining, and consensus mechanism simulations (PoW, PoS, DPoS).
---
## 📁 File Structure
- blockchain_simulation.py: Creates and links 3 simple blocks, simulates tampering.
- mining_simulation.py: Simulates mining with Proof-of-Work and nonce-based hashing.
- consensus_demo.py: Simulates and compares PoW, PoS, and DPoS consensus mechanisms.
## 1️⃣ blockchain_simulation.py
### 🧱 Features
- Creates a Block class with:
  - index, timestamp, data, previous_hash, hash, nonce
- Builds a 3-block chain
- Simulates data tampering on Block 1
- Shows how hash mismatch breaks the chain
python blockchain_simulation.py
# 💥 Mining Simulation (Proof of Work)

This Python script demonstrates a *Proof-of-Work (PoW)* mechanism by simulating mining of a block using a nonce and hash calculation.

---

## ⚙ How It Works

- A Block class is created with:
  - index: position of the block
  - timestamp: time of creation
  - data: stored data
  - previous_hash: hash of the previous block
  - nonce: number used to find a valid hash
  - hash: SHA-256 hash based on block content

- The mine_block(difficulty) function:
  - Increments nonce until the block's hash starts with a certain number of leading zeros (defined by difficulty)
  - This simulates the *mining* process and computational effort
## 🧪 Example Output

```text
# 🗳 Consensus Mechanism Simulation (PoW, PoS, DPoS)

This Python script simulates and compares three popular blockchain consensus mechanisms:

- 🧱 Proof of Work (PoW)
- 💰 Proof of Stake (PoS)
- 🗳 Delegated Proof of Stake (DPoS)

The goal is to understand how validators are selected in different systems using mock data.

---

## 🔁 What It Simulates

### 1️⃣ *Proof of Work (PoW)*

- Each miner has a power value.
- The miner with the *highest power* is selected.

```python
miner = {
    "miner_1": 50,
    "miner_2": 89,
    "miner_3": 42
}
