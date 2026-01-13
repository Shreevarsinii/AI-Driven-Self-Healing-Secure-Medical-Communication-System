**🛡️ AI-Driven Self-Healing Secure Medical Communication System**

This project presents an AI-enabled secure healthcare communication system that dynamically encrypts medical data using AES-128 and automatically regenerates encryption keys when cyber intrusions are detected.

**The system integrates:**

• Medical data protection \\
• AI-based intrusion detection \\
• Dynamic encryption \\
• Self-healing secure communication \\
• Interactive cyber-medical dashboard

**🚀 Key Features**

Dynamic AES-128 encryption of medical data

ECDH-based shared secret generation

Key Derivation Function (KDF) for session keys

AI intrusion detection using CICIDS dataset

Automatic re-keying on attack detection

Self-healing secure channel

Real-time interactive dashboard

**🧠 System Workflow**

Medical Sensors / Dataset
→ Secure ECDH handshake
→ Shared master secret
→ Dynamic AES key generation
→ AES-128 encryption
→ Secure channel
→ AI intrusion detection
→ Attack → re-key + heal
→ AES decryption
→ Hospital dashboard

**📊 Datasets Used**

CICIDS2017 Network Intrusion Dataset

Synthetic Medical Monitoring Dataset

(Dataset links provided in /data/README.md)

⚙️ Tech Stack

Python

FastAPI

Streamlit

Scikit-learn

PyCryptodome

Pandas, NumPy

**Novelty**

“Our novelty is that AI does not only detect cyber-attacks. It directly controls encryption. When an intrusion happens, the system automatically changes the encryption keys and heals the secure channel without human intervention.
