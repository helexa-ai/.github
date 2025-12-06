<img width="1280" height="640" alt="image" src="https://github.com/user-attachments/assets/c714d506-c121-48a9-88b9-da5e58aae0f1" />

# 🌐 Helexa — The Distributed AI Mesh

**Helexa** is an open, decentralized AI compute network that connects independent
operators into a global inference mesh. Nodes host models, portals collect user
payments, and the Helexa mesh routes requests intelligently based on demand,
capacity, and economics.

Helexa turns GPU operators into AI providers — without central control, without
cloud lock-in, and without a single point of failure.

> **AI as a self-organising helix. Globally distributed. Open to everyone.**

---

## 🚀 What Helexa Enables

### **🧠 Distributed AI Serving**
Any operator can contribute GPU resources by running **labman** and **portman**.
Nodes collaborate through a secure p2p overlay and serve inference requests
routed through the mesh.

### **📡 OpenAI-Compatible Gateways**
Operators may run public-facing endpoints. Users interact via standard OpenAI
APIs while Helexa handles routing and load-balancing across the mesh.

### **💰 A Fair, Transparent Economic Layer**
Front-End Portals (FEPs) accept user payments (crypto, stablecoins, fiat), issue
signed receipts, and settle payouts to providers in their chosen currency.

### **⚡ Autonomous Hosting Decisions**
Each labman node decides which models to keep warm based on peer-derived demand,
global supply signals, local economics, and operator policy.

### **🔐 Strong Privacy & Security**
Requests route over encrypted peer-to-peer links. Node identities use modern
signature schemes. There is no central database or cloud dependency.

---

## 🔧 Core Components

### **labman**
Mesh node + local orchestrator:
- p2p networking (peer discovery, gossip, routing)
- hosting decisions (load/unload models)
- economic logic (receipt verification, payout claims)
- gateway support (OpenAI HTTP endpoints)

### **portman**
High-performance model runtime:
- wraps model backends (llama.cpp, vLLM, etc.)
- receives hosting instructions from labman
- streams inference tokens back to requestors

### **Front-End Portals (FEPs)**
User-facing services:
- manage API keys and user balances  
- accept deposits and payments  
- generate signed receipts for provider payouts  
- coordinate with gateway labman nodes  

### **Helexa Mesh Protocol**
Specification defining:
- p2p message envelopes  
- proxying of OpenAI requests  
- gossip (peers, capabilities, market signals)  
- receipt transport  
- hosting decision primitives  

---

## 🧬 Why “Helexa”?

The name reflects the structure of the network:

- **Helix** — a self-organising, evolving structure  
- **Network** — the global mesh of independent operators  
- **Ecosystem** — a growing community aligned around open, distributed AI  

Helexa forms a living, spiraling infrastructure where intelligence emerges
from many contributors.

---

## 📚 Documentation (WIP)

Project documentation will soon be published at:

- **https://helexa.ai** — Introduction, vision, public overview  
- **https://helexa.io** — Developer docs, APIs, operator guides  
- **https://helexa.net** — Mesh endpoints, registry, operator listings  

As the ecosystem grows, we will maintain:
- FAQ
- Operator manuals
- Portal integration guides
- Mesh protocol reference
- Economics specification

---

## 🤝 Contributing

Helexa is an open ecosystem. Contributions are welcome in:

- p2p networking  
- model hosting  
- economics & receipts  
- protocol design  
- backend integrations  
- UI/UX for portals and dashboards  
- documentation & community building  

To get started:

1. Explore the repositories under this organization.  
2. Read the architecture and protocol documents.  
3. Join discussions via Issues and Pull Requests.  
4. Engage with the community as it forms around the project.

---

## 🗺️ Roadmap (High-Level)

### **MVP**
- basic p2p mesh  
- single provider node + gateway node  
- OpenAI-compatible request proxying  
- portman hosting control  
- mock FEP issuing signed receipts  

### **v0.1**
- multi-provider routing  
- demand-based hosting decisions  
- receipt storage + claim workflow  
- operator configuration system  
- public welcome site & documentation  

### **v0.2**
- real payment integrations (USDC / Stripe)  
- provider exposure limits & risk controls  
- operator dashboards  
- mesh bootstrap registry  
- authentication & identity hardening  

### **v1.0**
- multi-currency support  
- ecosystem of portals  
- governance model  
- incentivised distribution of public models  
- multi-region redundancy and stability guarantees  

---

## 🧑‍💻 License & Governance

Helexa is an open, collaborative project. Licensing, governance, and foundation
structure will be published as the community grows and stabilizes. Our goal is
to preserve:

- operator autonomy  
- economic fairness  
- protocol openness  
- security and resilience  

---

## 🌟 Join the Mesh

Helexa is building the world’s first **decentralised AI organism** — a global
helix of compute, intelligence, and incentive alignment.

Whether you're:
- a GPU operator  
- a researcher  
- a portal builder  
- or an open-source contributor  

…there is a place for you in the Helexa ecosystem.

**Welcome to the mesh.**
