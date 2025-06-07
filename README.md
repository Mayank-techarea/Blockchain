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
