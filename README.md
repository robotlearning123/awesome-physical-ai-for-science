# Awesome Physical AI for Science 🧬🤖

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated collection of resources for **Physical AI for Science** — where robotics, laboratory automation, and AI agents converge to accelerate scientific discovery.

Physical AI for Science represents the integration of embodied intelligence (robots, automated instruments, sensors) with AI-driven decision-making to create autonomous or semi-autonomous scientific research systems. This includes self-driving laboratories, robotic experimentation, AI-guided experimental design, and multi-agent systems for scientific workflows.

**Key Themes:** Self-Driving Labs · Lab Automation · AI Agents for Science · Robotic Experimentation · Closed-Loop Discovery · Digital Workers for Research

---

## Contents

- [📋 Surveys & Reviews](#-surveys--reviews)
- [🧪 Self-Driving Lab Systems](#-self-driving-lab-systems)
- [🤖 Robotic Lab Platforms](#-robotic-lab-platforms)
- [🧠 AI Agents for Scientific Discovery](#-ai-agents-for-scientific-discovery)
- [🔬 Domain-Specific Platforms](#-domain-specific-platforms)
  - [Drug Discovery & Life Sciences](#drug-discovery--life-sciences)
  - [Materials Science](#materials-science)
  - [Chemistry](#chemistry)
  - [Biology & Genomics](#biology--genomics)
- [🛠️ Software Frameworks & Tools](#️-software-frameworks--tools)
- [🏢 Companies & Startups](#-companies--startups)
- [📚 Key Papers](#-key-papers)
- [📖 Books & Courses](#-books--courses)
- [🎯 Benchmarks & Datasets](#-benchmarks--datasets)
- [🌐 Communities & Events](#-communities--events)
- [🔗 Related Awesome Lists](#-related-awesome-lists)

---

## 📋 Surveys & Reviews

| Paper | Venue | Year | Highlights |
|-------|-------|------|------------|
| [Autonomous 'self-driving' laboratories: a review of technology and policy implications](https://royalsocietypublishing.org/rsos/article/12/7/250646) | Royal Society Open Science | 2025 | Comprehensive SDL review + policy framework |
| [Self-Driving Laboratories for Chemistry and Materials Science](https://pubs.acs.org/doi/10.1021/acs.chemrev.4c00055) | Chemical Reviews | 2024 | Definitive survey of SDLs |
| [AI, agentic models and lab automation for scientific discovery — the beginning of scAInce](https://www.frontiersin.org/journals/artificial-intelligence/articles/10.3389/frai.2025.1649155) | Frontiers in AI | 2025 | Agent AI + lab automation convergence |
| [Science acceleration and accessibility with self-driving labs](https://www.nature.com/articles/s41467-025-59231-1) | Nature Communications | 2025 | SDL accessibility & democratization |
| [Autonomous laboratories for accelerated materials discovery: a community survey](https://pubs.rsc.org/en/content/articlehtml/2024/dd/d4dd00059e) | Digital Discovery | 2024 | Community-driven practical insights |
| [The future of self-driving laboratories: from human in the loop interactive AI to gamification](https://pubs.rsc.org/en/content/articlehtml/2024/dd/d4dd00040d) | Digital Discovery | 2024 | Human-in-the-loop to full autonomy |
| [Accelerating discovery in natural science laboratories with AI and robotics](https://www.science.org/doi/10.1126/scirobotics.adv7932) | Science Robotics | 2024 | Perspectives & challenges |
| [A Comprehensive Survey of AI Scientists](https://github.com/tsinghua-fib-lab/Awesome-AI-Scientists) | Tsinghua | 2025 | Full pipeline AI scientist systems |

## 🧪 Self-Driving Lab Systems

### Pioneering Systems

| System | Institution | Domain | Key Feature | Reference |
|--------|------------|--------|-------------|-----------|
| **A-Lab** | LBNL Berkeley | Materials | Autonomous solid-state synthesis + ML recipe generation | [Nature 2023](https://www.nature.com/articles/s41586-023-06734-w) |
| **Rainbow** | Multi-institution | Nanomaterials | Multi-robot SDL, parallelized nanocrystal synthesis | 2025 |
| **DOLPHIN** | Fudan / Shanghai AI Lab | General Science | LLM generates ideas → experiments → evaluation → iteration | 2025 |
| **AutoLabs** | Multi-institution | Chemistry | Cognitive multi-agent with self-correction | [arXiv 2025](https://arxiv.org/abs/2509.25651) |
| **Coscientist** | CMU | Chemistry | GPT-4 + robotic synthesis, closed-loop reactions | [Nature 2023](https://www.nature.com/articles/s41586-023-06792-0) |

### Multi-Agent Scientific Systems

| System | Description | Year | Reference |
|--------|------------|------|-----------|
| **MARS** | 19 LLM agents + 16 tools, hierarchical architecture for materials discovery | 2026 | [phys.org](https://phys.org/news/2026-01-multi-agent-ai-robots-automate.html) |
| **Robin** | First AI to autonomously discover and validate novel therapeutic candidate | 2025 | [arXiv](https://arxiv.org/abs/2505.13400) |
| **ChemAgents** | Task Manager + Literature Reader + Experiment Designer + Computation Performer + Robot Operator | 2025 | ACS 2025 |
| **Tippy** | Production-ready AI agents for DMTA cycle in drug discovery | 2025 | [arXiv](https://arxiv.org/abs/2507.09023) |
| **Aleks** | Multi-agent autonomous discovery in plant science | 2025 | [arXiv](https://arxiv.org/abs/2508.19383) |

## 🤖 Robotic Lab Platforms

| Platform | Institution | Description | GitHub |
|----------|------------|-------------|--------|
| **MADSci** | Argonne National Lab | Modular Autonomous Discovery for Science toolkit | [AD-SDL](https://github.com/AD-SDL) |
| **Polybot** | Center for Nanoscale Materials | Self-driving lab for polymer science | [polybot-nexus](https://github.com/polybot-nexus) |
| **Opentrons** | Opentrons | Open-source liquid handling robots | [Opentrons](https://github.com/Opentrons) |
| **Chemspeed** | Chemspeed | High-throughput automated synthesis | Commercial |
| **Mobile ALOHA** | Stanford | Bimanual mobile manipulation for labs | [GitHub](https://github.com/tonyzhaozh/aloha) |

## 🧠 AI Agents for Scientific Discovery

### LLM-based Scientific Agents

| Agent | Focus | Key Innovation | Reference |
|-------|-------|---------------|-----------|
| **ChemCrow** | Chemistry | LLM + chemistry tools integration | [arXiv 2023](https://arxiv.org/abs/2304.05376) |
| **SciAgents** | Materials | Graph reasoning + multi-agent for materials design | 2024 |
| **Lang-PINN** | Physics | LLM builds Physics-Informed Neural Networks from natural language | ICLR 2026 |
| **AI Scientist** | General | End-to-end automated research pipeline | [Sakana AI 2024](https://github.com/SakanaAI/AI-Scientist) |
| **OpenAI Deep Research** | General | Autonomous multi-step research agent | OpenAI 2025 |

### Experiment Design & Active Learning

| Tool | Description | Reference |
|------|------------|-----------|
| **Bayesian Optimization** | Standard for adaptive experimental design in SDLs | Various |
| **SEEK** | Scientific Exploration with Expert Knowledge for scanning probe microscopy | Digital Discovery 2025 |
| **BOSS** | Bayesian Optimization Structure Search | 2024 |

## 🔬 Domain-Specific Platforms

### Drug Discovery & Life Sciences

| Platform | Type | Description |
|----------|------|-------------|
| **Insilico Medicine** | Company | AI-driven end-to-end drug discovery |
| **Owkin** | Company | Multimodal clinical AI + federated learning |
| **ConcertAI** | Company | Real-world data + agentic AI for oncology |
| **Hippocratic AI + Grove AI** | Company | Agentic AI for pharma R&D and clinical trials |
| **Causaly** | Company | Knowledge graph + AI for life sciences |
| **NVIDIA BioNeMo** | Framework | Generative AI for drug discovery |
| **AlphaFold 3** | Tool | Protein structure & interaction prediction |
| **OpenFold3** | Tool | Open-source AlphaFold3 reimplementation |
| **Boltz 2** | Tool | Open protein structure prediction |

### Materials Science

| Platform | Type | Description |
|----------|------|-------------|
| **A-Lab** | Lab | Autonomous materials synthesis (LBNL) |
| **NVIDIA PhysicsNeMo** | Framework | Open-source physics AI |
| **Materials Project** | Database | Open materials data + ML models |
| **AFLOW** | Database | Automatic FLOW for materials discovery |

### Chemistry

| Platform | Type | Description |
|----------|------|-------------|
| **RDKit** | Library | Open-source cheminformatics |
| **DeepChem** | Library | Deep learning for molecular ML |
| **IBM RXN** | Tool | AI-powered retrosynthesis |

### Biology & Genomics

| Platform | Type | Description |
|----------|------|-------------|
| **AlphaFold DB** | Database | 200M+ protein structures |
| **UniProt** | Database | Protein sequence and function |
| **Hugging Face Bio** | Hub | Bio ML models |

## 🛠️ Software Frameworks & Tools

### Self-Driving Lab Software

| Tool | Stars | Description | Link |
|------|-------|-------------|------|
| **MADSci** | 43⭐ | Modular framework for autonomous discovery | [GitHub](https://github.com/AD-SDL/MADSci) |
| **awesome-self-driving-labs** | 209⭐ | Curated SDL resource list | [GitHub](https://github.com/AccelerationConsortium/awesome-self-driving-labs) |
| **awesome-ai-for-science** | 1,246⭐ | Comprehensive AI4Science resources | [GitHub](https://github.com/ai-boost/awesome-ai-for-science) |

### AI for Science Agent Platforms

| Platform | Provider | Description | Link |
|----------|----------|-------------|------|
| **Claude for Life Sciences** | Anthropic | MCP connectors + Agent Skills for life science research | [anthropic.com](https://www.anthropic.com/news/claude-for-life-sciences) |
| **Claude Scientific Skills** | K-Dense AI | 140+ ready-to-use scientific skills (8.9k⭐) | [GitHub](https://github.com/K-Dense-AI/claude-scientific-skills) |
| **Google Vertex AI Agent Engine** | Google Cloud | Life science R&D agent framework | [Google Cloud](https://cloud.google.com/blog/topics/healthcare-life-sciences/agentic-ai-framework-in-life-sciences-for-rd) |
| **OpenAI Prism** | OpenAI | Free LaTeX workspace + GPT for researchers | [openai.com/science](https://openai.com/science/) |
| **Claude in Microsoft Foundry** | MS + Anthropic | Healthcare & life science agentic workflows | [microsoft.com](https://www.microsoft.com/en-us/industry/blog/healthcare/2026/01/11/bridging-the-gap-between-ai-and-medicine-claude-in-microsoft-foundry-advances-capabilities-for-healthcare-and-life-sciences-customers/) |

### MCP Servers for Life Sciences (Claude)

| MCP Server | Provider | Description | Auth Required |
|------------|----------|-------------|---------------|
| **PubMed** | NCBI/Anthropic | Search biomedical literature | None |
| **BioRender** | BioRender | Scientific illustrations & diagrams | Free account |
| **Synapse.org** | Sage Bionetworks | Collaborative research data management | Free account |
| **Scholar Gateway** | Wiley | Peer-reviewed scientific publications | Free account |
| **10x Genomics Cloud** | 10x Genomics | Single-cell & spatial analysis in natural language | Paid account |
| **Benchling** | Benchling | Lab notebooks, experiments, records | Enterprise |

### Scientific Skills (Claude Code / Agent Skills Standard)

> From [claude-scientific-skills](https://github.com/K-Dense-AI/claude-scientific-skills) — 140+ skills across:

| Category | Count | Examples |
|----------|-------|---------|
| **Scientific Databases** | 28+ | OpenAlex, PubMed, ChEMBL, UniProt, COSMIC, ClinVar, KEGG, PDB |
| **Python Packages** | 55+ | RDKit, Scanpy, BioPython, DeepChem, PyTorch Lightning |
| **Lab Integrations** | 15+ | Benchling, DNAnexus, LatchBio, OMERO, Protocols.io, Opentrons |
| **Analysis & Communication** | 30+ | Literature review, scientific writing, peer review, slides, posters |
| **Clinical & Research** | 10+ | Clinical decision support, treatment plans, hypothesis generation |
| **Bioinformatics Skills** | 4 | Single-cell RNA-seq QC, scvi-tools, Nextflow pipelines, Allotrope conversion |

### Multi-Agent Frameworks

| Tool | Description | Link |
|------|-------------|------|
| **LangGraph** | Multi-agent orchestration | [GitHub](https://github.com/langchain-ai/langgraph) |
| **CrewAI** | Role-based multi-agent framework | [GitHub](https://github.com/crewAIInc/crewAI) |
| **AutoGen** | Microsoft multi-agent conversations | [GitHub](https://github.com/microsoft/autogen) |
| **OpenClaw** | Hub-Node agent architecture | [GitHub](https://github.com/openclaw/openclaw) |

### Lab Automation & Robotics

| Tool | Description | Link |
|------|-------------|------|
| **SiLA 2** | Standardization in Lab Automation protocol | [sila-standard.com](https://sila-standard.com) |
| **AlabOS** | Python reconfigurable workflow management for SDL | [RSC Digital Discovery](https://pubs.rsc.org/en/content/articlehtml/2024/dd/d4dd00129j) |
| **Bluesky** | NSLS-II data acquisition framework | [blueskyproject.io](https://blueskyproject.io/) |
| **MuJoCo** | Physics simulation for robotics | [GitHub](https://github.com/google-deepmind/mujoco) |
| **Isaac Gym / Isaac Lab** | GPU-accelerated robot learning | [NVIDIA](https://developer.nvidia.com/isaac-gym) |

### Scientific Computing

| Tool | Description | Link |
|------|-------------|------|
| **FrontierScience** | Benchmark for AI scientific reasoning | [OpenAI](https://openai.com/index/frontierscience/) |
| **K-Dense Web** | Full AI co-scientist platform (200+ skills, cloud GPU) | [k-dense.ai](https://k-dense.ai) |

## 🏢 Companies & Startups

### Self-Driving Labs

| Company | Focus | Stage |
|---------|-------|-------|
| **Emerald Cloud Lab** | Remote-access automated lab | Growth |
| **Strateos** | Robotic cloud lab | Growth |
| **Culture Biosciences** | Automated bioreactors | Growth |
| **Arctoris** | Fully automated drug discovery lab | Growth |

### AI for Life Sciences

| Company | Focus | Stage |
|---------|-------|-------|
| **Insilico Medicine** | End-to-end AI drug discovery | Late |
| **Recursion** | AI + biology platform | Public |
| **Isomorphic Labs** | AlphaFold → drug design (Alphabet) | Growth |
| **Owkin** | Federated clinical AI | Growth |
| **Causaly** | Knowledge graph for life sciences | Growth |

### Lab Automation Hardware

| Company | Product | Focus |
|---------|---------|-------|
| **Opentrons** | OT-2/Flex | Affordable liquid handling |
| **Hamilton** | STAR/Vantage | High-end liquid handling |
| **Chemspeed** | SWING/iSynth | High-throughput synthesis |
| **Beckman Coulter** | Biomek | Life science automation |

## 📚 Key Papers

### Landmark Papers

1. **Coscientist** — "An Autonomous Agent for Scientific Discovery" — [Nature 2023](https://www.nature.com/articles/s41586-023-06792-0)
2. **A-Lab** — "An autonomous laboratory for the accelerated synthesis of novel materials" — [Nature 2023](https://www.nature.com/articles/s41586-023-06734-w)
3. **ChemCrow** — "Augmented LLM Chemistry Agent" — [arXiv 2023](https://arxiv.org/abs/2304.05376)
4. **Robin** — "A multi-agent system for automating scientific discovery" — [arXiv 2025](https://arxiv.org/abs/2505.13400)
5. **AI Scientist** — "Towards Fully Automated Open-Ended Scientific Discovery" — [Sakana AI 2024](https://arxiv.org/abs/2408.06292)
6. **Flow-Driven Data Intensification** — "Accelerate Autonomous Materials Discovery" — Nature Chemical Engineering 2025

### Clinical / Biomedical AI

1. **AlphaFold 3** — "Accurate structure prediction of biomolecular interactions" — [Nature 2024](https://www.nature.com/articles/s41586-024-07487-w)
2. **Med-PaLM** — "Large language models encode clinical knowledge" — Nature 2023
3. **GatorTron** — "A Large Clinical Language Model" — npj Digital Medicine 2022

## 📖 Books & Courses

- 📘 [Self-Driving Laboratories for Chemistry and Materials Science](https://pubs.acs.org/doi/10.1021/acs.chemrev.4c00055) — Chemical Reviews 2024 (comprehensive textbook-level review)
- 📘 [Autonomous Research](https://autonomous-research.org/) — Community resources
- 🎓 [AI for Science Bootcamp](https://www.nvidia.com/en-us/training/) — NVIDIA Deep Learning Institute

## 🎯 Benchmarks & Datasets

| Benchmark | Domain | Description |
|-----------|--------|-------------|
| **FrontierScience** | General | OpenAI benchmark for AI scientific reasoning |
| **ScienceWorld** | General | Interactive text-based science experiments |
| **Materials Project** | Materials | 150k+ materials with computed properties |
| **AlphaFold DB** | Biology | 200M+ predicted protein structures |
| **PubChem** | Chemistry | 100M+ chemical compounds |
| **ChEMBL** | Drug Discovery | Bioactive molecules with drug-like properties |

## 🌐 Communities & Events

- **[Acceleration Consortium](https://acceleration.utoronto.ca/)** — University of Toronto, SDL research hub
- **[AD-SDL](https://github.com/AD-SDL)** — Argonne National Lab, Self-Driving Labs
- **[AI for Science Workshop](https://ai4sciencecommunity.github.io/)** — NeurIPS/ICML workshops
- **[ORNL SDL Workshop](https://info.ornl.gov/sites/publications/Files/Pub227078.pdf)** — Oak Ridge National Lab

## 🔗 Related Awesome Lists

| List | Stars | Focus |
|------|-------|-------|
| [awesome-self-driving-labs](https://github.com/AccelerationConsortium/awesome-self-driving-labs) | 209⭐ | Self-driving labs (chemistry/materials) |
| [awesome-ai-for-science](https://github.com/ai-boost/awesome-ai-for-science) | 1,246⭐ | Broad AI for science |
| [awesome-isaac-gym](https://github.com/robotlearning123/awesome-isaac-gym) | 1,131⭐ | NVIDIA Isaac Gym for robot learning |
| [Awesome-AI-Scientists](https://github.com/tsinghua-fib-lab/Awesome-AI-Scientists) | 25⭐ | AI scientist survey |

---

## Contributing

Contributions welcome! Please read the [contribution guidelines](CONTRIBUTING.md) first.

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

---

**Maintained by [Cong](https://github.com/robotlearning123)** — Researcher in Physical AI for Science, Agentic Systems & Embodied Intelligence @ Harvard
