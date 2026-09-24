---
title: Microsoft Azure — Obsidian Learning Vault
---

# Microsoft Azure — A Beginner's Obsidian Learning Vault

> Learn cloud computing the hands-on way: a visual, interlinked knowledge base that takes you from **"what is the cloud?"** to confidently creating real Azure resources — no experience required.

This repository is a complete, beginner-friendly learning environment for **Microsoft Azure and cloud computing fundamentals**. Built as an Obsidian vault, every note links to the next — follow the graph and you'll naturally learn the full Azure story.

---

## Why learn from this repo?

- **Zero to hero structure** — mirrors the official Azure Fundamentals (AZ-900) syllabus in plain, simple language.
- **Real hands-on tutorials** — exact, step-by-step portal guides that capture every click and field value:
  - [Create a Virtual Machine in Azure](How%20To%20Create%20a%20VM%20in%20Azure%20Cloud/)
  - [Create a Storage Account in Azure Storage](How%20To%20Create%20a%20Storage%20Account%20in%20Azure%20Storage/)
  - [Estimate costs with the Azure Pricing Calculator](Azure%20pricing%20Calculator/)
- **Visual-first learning** — ~60 real screenshots make it easy to skim and to match what you see on screen.
- **Memorable analogies** — containers as portable "motor homes", encryption as a safe plus armored truck. Abstract cloud concepts become tangible.
- **Interlinked knowledge graph** — explore topics through wikilinks instead of reading one long linear document.
- **Covers the business side too** — pricing models, TCO, cost optimization, and migration strategies that most courses skip.

---

## Suggested learning path

Start anywhere, but this order mirrors how the vault was built:

| Step | Topic | What you'll learn |
|------|-------|-------------------|
| 1 | [Azure — Intro & Refresher](Azure/) | What is cloud computing? Why Azure? |
| 2 | [Cloud Services Types](Cloud%20Services%20Types/) | IaaS vs PaaS vs SaaS — the foundation of everything |
| 3 | [Benefits of cloud services](Benefits%20of%20cloud%20services/) | Scalability, reliability, predictability, availability |
| 4 | [Azure's Core Components](Azure's%20Core%20Components/) | Resources, resource groups, subscriptions, ARM |
| 5 | [Computing in Azure](Computing%20Services%20Overview%20in%20Azure/) | VMs, App Service, Functions, serverless |
| 6 | [Containers](Containers/) | Docker, Kubernetes, ACI, AKS, Container Apps |
| 7 | [Storage & Data](Data%20Processing%20in%20Azure/) | Blob storage, Data Lake, ETL, real-time processing |
| 8 | [AI & Machine Learning](AI%20&%20Machine%20Learning/) | Azure ML, Cognitive Services, Databricks |
| 9 | [Security & Compliance](Security%20and%20Compliance%20in%20Azure/) | RBAC, encryption, Key Vault, Sentinel |
| 10 | [Azure Economics](Azure%20Economics/) | Pricing, reservations, spot instances, TCO |
| 11 | [Migration to Azure](Migration%20to%20Azure/) | Lift-and-shift, rearchitect, Azure Site Recovery |

---

## Topics covered at a glance

```
├── ☁️ Azure basics — Intro, Refresher, cloud services types (IaaS/PaaS/SaaS)
├── 🧩 Core components — Resources, Resource Groups, Azure Resource Manager
├── 💻 Compute & Applications — VMs, App Service, Functions, Containers (ACI/AKS)
├── 💾 Storage & Data — Blob, Data Lake, ETL, batch vs real-time, Synapse
├── 🤖 AI & Big Data — Azure ML, Cognitive Services, Databricks, HDInsight
├── 🔐 Security — RBAC, Encryption, Key Vault, Sentinel, Network Security
├── 🧰 Management — Advisor, Monitor, Policy, Blueprints, Automation
├── 💰 Economics — Pricing calculator, TCO, Reservations, Hybrid Benefit
└── 🚚 Migration — Strategies, best practices, Site Recovery, DMS
```

> Tip: this is a visual map, not an exact tree — use the folder names to explore.

---

## Getting started

1. **Clone the repo**

   ```bash
   git clone https://github.com/amineelgardoum-rgb/Azure.git
   ```

2. **Open it as a vault**

   - Install **Obsidian** ([obsidian.md](https://obsidian.md)) — it's free.
   - Open Obsidian → *Open folder as vault* → select this folder.
   - The plugins (Graph view, Dataview, Kanban, Excalidraw) are already configured; grant plugin trust when prompted.

3. **Start your journey**

   - Press `Ctrl+G` to open the **Graph view** and watch every concept connect.
   - Click any `[[wikilink]]` to hop between related notes.
   - Follow the [suggested learning path](#suggested-learning-path) in order, or dive into any topic that grabs you.

4. **Do the hands-on labs** — the VM, storage account, and pricing calculator walkthroughs are the fastest way to make the concepts stick.

---

## Who is this for?

- **Absolute beginners** with no cloud experience who want a friendly, visual start.
- **Students** preparing for the **Microsoft Azure Fundamentals (AZ-900)** certification.
- **Any developer** wanting a quick, well-organized reference for Azure concepts and services.

---

## Planned improvements

The vault is evolving. Ideas on the roadmap:

- [ ] Link each topic to the official **Microsoft Learn** documentation
- [ ] Add practice questions and mini-quizzes per section
- [ ] Expand videos & interactive diagrams
- [ ] Add YAML frontmatter + tags for richer graph filtering

---

## Contribute

Found a stale step in a tutorial, or a concept you could explain better? Contributions are welcome — open an issue or submit a PR. Let's make learning Azure accessible to everyone.

## Acknowledgements

Built as a study vault alongside the Azure Fundamentals learning path. All screenshots are original captures from hands-on portal practice.