# 🛡️ SOC Analyst Projects — ML/DL Edition

### Description

**SOC Analyst Projects Directory** is a curated collection of **15 hands-on cybersecurity projects** built for aspiring Security Operations Center (SOC) analysts — each upgraded with **Machine Learning, Deep Learning, and Python AI tooling** to go beyond traditional rule-based security.

Every project maps directly to a **CySA+ (CS0-003) exam domain** and simultaneously builds toward an **ML/AI engineering portfolio**. The architecture patterns used here — VAEs, LSTMs, Transformer autoencoders, Graph Embeddings — mirror the same techniques used in cutting-edge AI research.

> *"From OBD Ports to Python Imports."* — Built by a diesel mechanic turned software engineer turned AI researcher.

---

### 👤 About Me

Hi, I'm **Kelvin R. Tobias** — Software Engineer, Application Support Analyst at Principle LTC, and founder of **Kelvinintech Consulting LLC**. I hold a B.S. in Software Engineering from WGU (January 2026) and am beginning an M.S. in AI Engineering in December 2026, with a long-term goal of a PhD in Computational Biology focused on **Latent-based Directed Evolution (LDE)**.

This project series serves two purposes:
1. ✅ **CySA+ certification prep** — hands-on evidence across every exam domain
2. 🤖 **ML/AI portfolio** — each project uses the same neural architectures powering modern AI research

[🌐 Portfolio](https://kelvinintech.com) · [𝕏 Follow](https://x.com/kelvinintech) · [GitHub](https://github.com/kelvintechnical)

---

### 🗺️ CySA+ Domain Coverage

| Domain | Coverage |
|---|---|
| 1. Security Operations | Projects 4, 6, 8, 13 |
| 2. Vulnerability Management | Projects 5, 14 |
| 3. Incident Response | Projects 1, 9, 12 |
| 4. Reporting & Communication | Projects 3, 11, 15 |
| 5. Threat Intelligence | Projects 2, 7, 10 |

---

### ⚙️ Prerequisites

```bash
# Python dependencies
pip install torch torchvision scikit-learn pandas numpy flask transformers

# Additional per-project deps listed in each repo's requirements.txt
```

- Python 3.10+
- PyTorch 2.x
- Git + GitHub CLI (`gh`)

---

### 📁 Projects Overview

---

#### 1. 🚨 [cysa-intrusion-detection-lstm](https://github.com/kelvintechnical/cysa-intrusion-detection-lstm)
**CySA+ Domain:** Incident Response & Network Monitoring  
**ML Upgrade:** LSTM sequence classifier on NetFlow data — learns the "grammar" of normal traffic and flags deviations  
**Stack:** `PyTorch`, `scapy`, `Flask`  
> *Analogy: The LSTM is a mechanic's ear — trained on thousands of healthy engine sounds, it immediately detects a misfire.*

---

#### 2. 🕵️ [cysa-threat-intel-graph-embeddings](https://github.com/kelvintechnical/cysa-threat-intel-graph-embeddings)
**CySA+ Domain:** Threat Intelligence  
**ML Upgrade:** Node2Vec graph embeddings on threat actor relationship graphs — clusters IOCs by behavioral similarity  
**Stack:** `PyTorch Geometric`, `networkx`, `Flask`  
> *Analogy: Mapping the wiring harness of a threat actor's infrastructure — same signal, different connectors.*

---

#### 3. 🌐 [cysa-network-anomaly-detector](https://github.com/kelvintechnical/cysa-network-anomaly-detector)
**CySA+ Domain:** Network Security Monitoring  
**ML Upgrade:** Isolation Forest anomaly detection on packet-level features — unsupervised, no labeled data needed  
**Stack:** `scikit-learn`, `pyshark`, `pandas`  
> *Analogy: An OBD scanner that flags sensor readings outside normal operating range — no repair manual needed.*

---

#### 4. 📋 [cysa-log-clustering-dbscan](https://github.com/kelvintechnical/cysa-log-clustering-dbscan)
**CySA+ Domain:** Security Operations  
**ML Upgrade:** DBSCAN clustering on syslog events — groups similar log patterns to surface hidden attack sequences  
**Stack:** `scikit-learn`, `pandas`, `Elasticsearch`  
> *Analogy: Sorting fault codes by subsystem rather than reading every line of the ECU dump.*

---

#### 5. 🔍 [cysa-vulnerability-risk-scorer](https://github.com/kelvintechnical/cysa-vulnerability-risk-scorer)
**CySA+ Domain:** Vulnerability Management  
**ML Upgrade:** PyTorch regression model on CVSS feature vectors — predicts contextual risk score beyond raw CVSS  
**Stack:** `PyTorch`, `nvdlib`, `pandas`

---

#### 6. 📡 [cysa-siem-anomaly-dashboard](https://github.com/kelvintechnical/cysa-siem-anomaly-dashboard)
**CySA+ Domain:** Security Operations  
**ML Upgrade:** Real-time Z-score + concept drift detection on streaming security events  
**Stack:** `river` (online ML), `Flask`, `Kafka`  
> *Analogy: A live dashboard that watches RPM, temp, and oil pressure simultaneously — alerts when the pattern shifts, not just when a threshold is crossed.*

---

#### 7. 📧 [cysa-phishing-email-classifier](https://github.com/kelvintechnical/cysa-phishing-email-classifier)
**CySA+ Domain:** Threat Intelligence  
**ML Upgrade:** Fine-tuned DistilBERT NLP classifier on email headers and body text  
**Stack:** `HuggingFace Transformers`, `PyTorch`, `Flask`  
> *Analogy: Training a model on the "dialect" of phishing — same way you learn to spot a forged VIN.*

---

#### 8. 🦠 [cysa-malware-cnn-classifier](https://github.com/kelvintechnical/cysa-malware-cnn-classifier)
**CySA+ Domain:** Incident Response  
**ML Upgrade:** CNN trained on PE header binary entropy visualizations — detects malware families from byte patterns  
**Stack:** `PyTorch`, `pefile`, `matplotlib`  
> *Analogy: Reading a fuel injector's spray pattern visually — the shape tells you everything about what's wrong.*

---

#### 9. 🤖 [cysa-incident-response-llm](https://github.com/kelvintechnical/cysa-incident-response-llm)
**CySA+ Domain:** Incident Response  
**ML Upgrade:** Claude API-powered triage assistant — ingests alert context and generates structured IR playbook steps  
**Stack:** `anthropic` SDK, `Flask`, `pandas`

---

#### 10. 🍯 [cysa-honeypot-behavior-clustering](https://github.com/kelvintechnical/cysa-honeypot-behavior-clustering)
**CySA+ Domain:** Threat Intelligence  
**ML Upgrade:** K-Means clustering on attacker session features from honeypot logs — profiles attacker archetypes  
**Stack:** `scikit-learn`, `cowrie` log parser, `matplotlib`

---

#### 11. 🔬 [cysa-forensic-transformer-autoencoder](https://github.com/kelvintechnical/cysa-forensic-transformer-autoencoder)
**CySA+ Domain:** Digital Forensics / Reporting  
**ML Upgrade:** Transformer autoencoder on Windows event log sequences — reconstructs normal sequences, flags anomalies by reconstruction error  
**Stack:** `PyTorch`, `pandas`  
> *🧬 LDE Tie-in: This encoder-decoder architecture is the same pattern used in protein sequence embeddings for directed evolution.*

---

#### 12. 🔑 [cysa-password-vae-generator](https://github.com/kelvintechnical/cysa-password-vae-generator)
**CySA+ Domain:** Identity & Access Management  
**ML Upgrade:** Variational Autoencoder (VAE) trained on weak password datasets — learns the latent space of human password patterns  
**Stack:** `PyTorch`, `Flask`  
> *🧬 LDE Tie-in: **This is the same VAE architecture used in Latent-based Directed Evolution** — navigating latent space toward a target, whether that's a stronger password or a more thermostable protein.*

---

#### 13. 🧱 [cysa-firewall-rl-optimizer](https://github.com/kelvintechnical/cysa-firewall-rl-optimizer)
**CySA+ Domain:** Security Operations / Network Security  
**ML Upgrade:** Reinforcement Learning agent that optimizes firewall rule ordering to minimize latency while maintaining coverage  
**Stack:** `stable-baselines3`, `PyTorch`, `gymnasium`  
> *Analogy: An RL agent tuning fuel injection timing — it learns through trial and error what order fires best.*

---

#### 14. 👤 [cysa-user-behavior-lstm](https://github.com/kelvintechnical/cysa-user-behavior-lstm)
**CySA+ Domain:** Vulnerability Management / Insider Threat  
**ML Upgrade:** LSTM autoencoder on user session sequences — detects insider threats by flagging sessions that can't be reconstructed from learned normal behavior  
**Stack:** `PyTorch`, `pandas`, `Flask`

---

#### 15. 📜 [cysa-compliance-nlp-parser](https://github.com/kelvintechnical/cysa-compliance-nlp-parser)
**CySA+ Domain:** Reporting & Communication  
**ML Upgrade:** spaCy + transformer NLP pipeline that parses NIST 800-53 and CIS Controls docs and maps controls to implemented project features  
**Stack:** `spaCy`, `transformers`, `Flask`

---

### 🧬 The LDE Thread

Three projects have **direct architectural overlap** with my PhD research focus — Latent-based Directed Evolution:

| Project | Architecture | LDE Parallel |
|---|---|---|
| #12 Password VAE | Variational Autoencoder | Protein latent space navigation |
| #11 Forensic Autoencoder | Transformer encoder-decoder | Sequence embedding for directed evolution |
| #2 Threat Graph Embeddings | Node2Vec / Graph Neural Net | Protein interaction network representation |

> DNA is source code. Proteins are compiled executables. The latent space is the compressed instruction set. These security projects are training ground for the same math.

---

### 📚 What I Learned

- **Anomaly Detection**: Isolation Forest, DBSCAN, Z-score drift for unsupervised threat detection
- **Sequence Modeling**: LSTMs and Transformer autoencoders for temporal log analysis
- **NLP for Security**: Fine-tuning BERT-class models on phishing and compliance text
- **Generative Models**: VAEs for learning latent distributions of security-relevant data
- **Graph ML**: Node2Vec embeddings for threat actor relationship modeling
- **Reinforcement Learning**: Policy optimization applied to network security problems

---

### 🤝 Support & Feedback

If these projects helped you, leave a ⭐ and connect:

[🌐 kelvinintech.com](https://kelvinintech.com) · [𝕏 @kelvinintech](https://x.com/kelvinintech) · [GitHub @kelvintechnical](https://github.com/kelvintechnical)
