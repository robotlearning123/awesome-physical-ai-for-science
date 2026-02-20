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
| [From AI for Science to Agentic Science: A Survey on Autonomous Scientific Discovery](https://arxiv.org/abs/2508.14111) | arXiv | 2025 | Most comprehensive survey on agentic scientific discovery |
| [Autonomous 'self-driving' laboratories: a review of technology and policy implications](https://royalsocietypublishing.org/rsos/article/12/7/250646) | Royal Society Open Science | 2025 | Comprehensive SDL review + policy framework |
| [Self-Driving Laboratories for Chemistry and Materials Science](https://pubs.acs.org/doi/10.1021/acs.chemrev.4c00055) | Chemical Reviews | 2024 | Definitive survey of SDLs |
| [AI, agentic models and lab automation for scientific discovery — the beginning of scAInce](https://www.frontiersin.org/journals/artificial-intelligence/articles/10.3389/frai.2025.1649155) | Frontiers in AI | 2025 | Agent AI + lab automation convergence |
| [Science acceleration and accessibility with self-driving labs](https://www.nature.com/articles/s41467-025-59231-1) | Nature Communications | 2025 | SDL accessibility & democratization |
| [Autonomous laboratories for accelerated materials discovery: a community survey](https://pubs.rsc.org/en/content/articlehtml/2024/dd/d4dd00059e) | Digital Discovery | 2024 | Community-driven practical insights |
| [The future of self-driving laboratories: from human in the loop interactive AI to gamification](https://pubs.rsc.org/en/content/articlehtml/2024/dd/d4dd00040d) | Digital Discovery | 2024 | Human-in-the-loop to full autonomy |
| [Accelerating discovery in natural science laboratories with AI and robotics](https://www.science.org/doi/10.1126/scirobotics.adv7932) | Science Robotics | 2024 | Perspectives & challenges |
| [The Rise of Self-Driving Labs](https://www.optica-opn.org/home/articles/volume_36/april_2025/features/the_rise_of_self-driving_labs/) | Optics & Photonics News | 2025 | Accessible overview of SDL field |
| [Will self-driving 'robot labs' replace biologists?](https://www.nature.com/articles/d41586-026-00453-8) | Nature News | 2026 | Debate on autonomous labs in biology |
| [A Comprehensive Survey of AI Scientists](https://github.com/tsinghua-fib-lab/Awesome-AI-Scientists) | Tsinghua | 2025 | Full pipeline AI scientist systems |

## 🧪 Self-Driving Lab Systems

### Pioneering Systems

| System | Institution | Domain | Key Feature | Reference |
|--------|------------|--------|-------------|-----------|
| **OpenAI + Ginkgo Bioworks** | OpenAI / Ginkgo | Biology | 🔥 GPT-5 + cloud lab, 36k experiments, 40% cost reduction in cell-free protein synthesis | [bioRxiv 2026](https://www.biorxiv.org/content/10.64898/2026.02.05.703998v1) |
| **A-Lab** | LBNL Berkeley | Materials | Autonomous solid-state synthesis, 43 materials in 17 days | [Nature 2023](https://www.nature.com/articles/s41586-023-06734-w) |
| **Coscientist** | CMU | Chemistry | GPT-4 + robotic synthesis, palladium cross-coupling | [Nature 2023](https://www.nature.com/articles/s41586-023-06792-0) |
| **Mobile Robot Chemist** | U Liverpool | Chemistry | Autonomous mobile robots for exploratory synthesis | [Nature 2024](https://www.nature.com/articles/s41586-024-08173-7) |
| **ORGANA** | U Toronto | Chemistry | Franka robot + LLM planning | [Cell Reports Phys Sci 2024](https://doi.org/10.1016/j.xcrp.2024.101542) |
| **Rainbow** | Multi-institution | Nanomaterials | Multi-robot SDL, parallelized nanocrystal synthesis | 2025 |
| **DOLPHIN** | Fudan / Shanghai AI Lab | General Science | LLM generates ideas → experiments → evaluation → iteration | 2025 |
| **AutoLabs** | Multi-institution | Chemistry | Cognitive multi-agent with self-correction | [arXiv 2025](https://arxiv.org/abs/2509.25651) |
| **SDL for Nanophotonics** | — | Photonics | Autonomous experimentation for spontaneous emission | [Nature Comm 2025](https://www.nature.com/articles/s41467-025-66916-0) |
| **SDL for Solid-State Lasers** | — | Materials/Photonics | Discovery of tunable organic emitters | [Nature Comm 2026](https://www.nature.com/articles/s41467-025-61209-y) |
| **AI Enzyme Engineering** | — | Biology | Generalized platform for autonomous enzyme engineering | [Nature Comm 2025](https://www.nature.com/articles/s41467-025-61209-y) |
| **Flow-Driven SDL** | — | Materials | 10× data intensification for materials discovery | [Nature Chem Eng 2025](https://www.sciencedaily.com/releases/2025/07/250714052105.htm) |

> ⚠️ **Note**: The A-Lab Nature 2023 paper received a [correction in January 2026](https://cen.acs.org/research-integrity/Nature-robot-chemist-paper-corrected/104/web/2026/01), with some questions remaining about the claimed new materials.

### Multi-Agent Scientific Systems

| System | Description | Year | Reference |
|--------|------------|------|-----------|
| **MARS** | 19 LLM agents + 16 tools, hierarchical architecture for materials discovery | 2026 | [Matter 2026](https://doi.org/10.1016/j.matt.2025.102577) / [phys.org](https://phys.org/news/2026-01-multi-agent-ai-robots-automate.html) |
| **Robin** | First AI to autonomously discover and validate novel therapeutic candidate (ripasudil for dAMD) | 2025 | [arXiv](https://arxiv.org/abs/2505.13400) / [FutureHouse](https://www.futurehouse.org/research-announcements/demonstrating-end-to-end-scientific-discovery-with-robin-a-multi-agent-system) |
| **ChemAgents** | Task Manager + Literature Reader + Experiment Designer + Computation Performer + Robot Operator | 2025 | ACS 2025 |
| **Tippy** | Production-ready AI agents for DMTA cycle in drug discovery | 2025 | [arXiv](https://arxiv.org/abs/2507.09023) |
| **Aleks** | Multi-agent autonomous discovery in plant science | 2025 | [arXiv](https://arxiv.org/abs/2508.19383) |
| **VirSci** | Virtual scientists for Science of Science | 2025 | ACL 2025 |
| **OriGene** | Virtual disease biologist for therapeutic target discovery | 2025 | — |
| **Agent Laboratory** | Literature review → experiment → report writing pipeline | 2025 | Schmidgall et al. |

### End-to-End AI Scientist Systems

| System | Description | Achievement | Reference |
|--------|------------|-------------|-----------|
| **AI Scientist v1** | End-to-end automated research pipeline | 8.9k GitHub stars | [Sakana AI 2024](https://github.com/SakanaAI/AI-Scientist) |
| **AI Scientist v2** | Workshop-level automated discovery | First AI-generated peer-reviewed paper (ICLR 2025 Workshop) | Sakana AI 2025 |

> ⚠️ Independent [evaluation](https://arxiv.org/abs/2502.14297) (ACM SIGIR Forum 2025) found mixed results, noting some claims may be overstated.

## 🤖 Robotic Lab Platforms

### Hardware Platforms

| Platform | Institution | Description | Link |
|----------|------------|-------------|------|
| **MADSci** | Argonne National Lab | Modular Autonomous Discovery for Science toolkit | [AD-SDL](https://github.com/AD-SDL) |
| **Polybot** | Center for Nanoscale Materials | Self-driving lab for polymer science | [polybot-nexus](https://github.com/polybot-nexus) |
| **Opentrons Flex** | Opentrons | Open-source liquid handling robots | [Opentrons](https://github.com/Opentrons) |
| **Chemspeed** | Chemspeed | High-throughput automated synthesis | Commercial |
| **Mobile ALOHA** | Stanford | Bimanual mobile manipulation for labs | [GitHub](https://github.com/tonyzhaozh/aloha) |
| **ABB Robotics** | ABB | AI-driven collaborative robots for labs | [SLAS 2026 Demo](https://www.robotics247.com/article/slas-2026-abb-turns-ai-into-action-to-accelerate-the-future-of-lab-automation) |
| **Ginkgo Cloud Lab** | Ginkgo Bioworks | Remote automated wet lab (robots execute experiments) | [ginkgobioworks.com](https://www.ginkgobioworks.com/) |

### Orchestration Software

| Platform | Provider | Description | Link |
|----------|----------|-------------|------|
| **Cellario** | HighRes Biosolutions | 🔥 Agentic AI scheduling + orchestration for lab automation | [cellario.com](https://www.highresbio.com/cellario/) |
| **FlexPod** | HighRes | Configurable Lab Automation Platform | [highresbio.com](https://www.highresbio.com/) |
| **IvoryOS** | — | Drag-and-drop web interface for SDL workflow design | [Nature Comm 2025](https://www.nature.com/articles/s41467-025-60514-w) |
| **AlabOS** | — | Python reconfigurable workflow management for SDL | [RSC Digital Discovery 2024](https://pubs.rsc.org/en/content/articlehtml/2024/dd/d4dd00129j) |

> 🔥 **Breaking**: [HighRes + Opentrons partnership](https://www.businesswire.com/news/home/20260204914025/en/) (Feb 2026) — Industry's first AI Agent-to-Agent lab automation workflow

## 🧠 AI Agents for Scientific Discovery

### LLM-based Scientific Agents

| Agent | Focus | Key Innovation | Reference |
|-------|-------|---------------|-----------|
| **GPT-5 Lab Agent** | Biology | 🔥 Autonomous wet lab experiments via cloud lab, 36k experiments | [OpenAI 2026](https://openai.com/index/gpt-5-lowers-protein-synthesis-cost/) |
| **ChemCrow** | Chemistry | LLM + 18 chemistry tools integration | [arXiv 2023](https://arxiv.org/abs/2304.05376) |
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
| **Robin** (FutureHouse) | System | First autonomous therapeutic candidate discovery (ripasudil for dAMD) |
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
| **MARS** | System | Multi-agent robotic system for materials (SIAT, CAS) |
| **NVIDIA PhysicsNeMo** | Framework | Open-source physics AI |
| **Materials Project** | Database | Open materials data + ML models |
| **AFLOW** | Database | Automatic FLOW for materials discovery |

### Chemistry

| Platform | Type | Description |
|----------|------|-------------|
| **Coscientist** | System | GPT-4 autonomous chemistry lab |
| **RDKit** | Library | Open-source cheminformatics |
| **DeepChem** | Library | Deep learning for molecular ML |
| **IBM RXN** | Tool | AI-powered retrosynthesis |

### Biology & Genomics

| Platform | Type | Description |
|----------|------|-------------|
| **Ginkgo Cloud Lab** | Lab | GPT-5 autonomous protein synthesis |
| **AlphaFold DB** | Database | 200M+ protein structures |
| **UniProt** | Database | Protein sequence and function |
| **Hugging Face Bio** | Hub | Bio ML models |

## 🛠️ Software Frameworks & Tools

### Self-Driving Lab Software

| Tool | Stars | Description | Link |
|------|-------|-------------|------|
| **AI-Scientist** | 8.9k⭐ | End-to-end automated research pipeline | [GitHub](https://github.com/SakanaAI/AI-Scientist) |
| **awesome-ai-for-science** | 1,246⭐ | Comprehensive AI4Science resources | [GitHub](https://github.com/ai-boost/awesome-ai-for-science) |
| **awesome-self-driving-labs** | 209⭐ | Curated SDL resource list | [GitHub](https://github.com/AccelerationConsortium/awesome-self-driving-labs) |
| **MADSci** | 43⭐ | Modular framework for autonomous discovery | [GitHub](https://github.com/AD-SDL/MADSci) |
| **IvoryOS** | — | No-code web interface for SDL workflows | [Nature Comm 2025](https://www.nature.com/articles/s41467-025-60514-w) |
| **AlabOS** | — | Python reconfigurable SDL management | [Digital Discovery](https://pubs.rsc.org/en/content/articlehtml/2024/dd/d4dd00129j) |

### AI for Science Agent Platforms

| Platform | Provider | Description | Link |
|----------|----------|-------------|------|
| **Claude for Life Sciences** | Anthropic | MCP connectors + Agent Skills for life science research | [anthropic.com](https://www.anthropic.com/news/claude-for-life-sciences) |
| **Claude Scientific Skills** | K-Dense AI | 140+ ready-to-use scientific skills (8.9k⭐) | [GitHub](https://github.com/K-Dense-AI/claude-scientific-skills) |
| **Google Vertex AI Agent Engine** | Google Cloud | Life science R&D agent framework | [Google Cloud](https://cloud.google.com/blog/topics/healthcare-life-sciences/agentic-ai-framework-in-life-sciences-for-rd) |
| **OpenAI for Science** | OpenAI | Prism LaTeX + GPT-5 lab agent + FrontierScience | [openai.com/science](https://openai.com/science/) |
| **Claude in Microsoft Foundry** | MS + Anthropic | Healthcare & life science agentic workflows | [microsoft.com](https://www.microsoft.com/en-us/industry/blog/healthcare/2026/01/11/bridging-the-gap-between-ai-and-medicine-claude-in-microsoft-foundry-advances-capabilities-for-healthcare-and-life-sciences-customers/) |

### MCP Servers for Life Sciences

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

### Lab Automation Standards & Protocols

| Standard | Description | Link |
|----------|-------------|------|
| **SiLA 2** | Standardization in Lab Automation protocol | [sila-standard.com](https://sila-standard.com) |
| **Bluesky** | NSLS-II data acquisition framework | [blueskyproject.io](https://blueskyproject.io/) |
| **MuJoCo** | Physics simulation for robotics | [GitHub](https://github.com/google-deepmind/mujoco) |
| **Isaac Gym / Isaac Lab** | GPU-accelerated robot learning | [NVIDIA](https://developer.nvidia.com/isaac-gym) |

## 🏢 Companies & Startups

### Self-Driving Labs / Cloud Labs

| Company | Focus | Stage |
|---------|-------|-------|
| **Ginkgo Bioworks** | 🔥 Cloud lab + GPT-5 autonomous biology | Public (NYSE: DNA) |
| **Emerald Cloud Lab** | Remote-access automated lab | Growth |
| **Strateos** | Robotic cloud lab | Growth |
| **Culture Biosciences** | Automated bioreactors | Growth |
| **Arctoris** | Fully automated drug discovery lab | Growth |
| **SciSpot** | Self-driving lab platform for life sciences | Growth |

### AI for Life Sciences

| Company | Focus | Stage |
|---------|-------|-------|
| **FutureHouse** | Robin multi-agent scientific discovery | Growth |
| **Insilico Medicine** | End-to-end AI drug discovery | Late |
| **Recursion** | AI + biology platform | Public |
| **Isomorphic Labs** | AlphaFold → drug design (Alphabet) | Growth |
| **Owkin** | Federated clinical AI | Growth |
| **Causaly** | Knowledge graph for life sciences | Growth |

### Lab Automation Hardware & Software

| Company | Product | Focus |
|---------|---------|-------|
| **HighRes Biosolutions** | 🔥 Cellario + FlexPod | Agentic AI lab orchestration |
| **Opentrons** | OT-2/Flex | Affordable liquid handling |
| **Hamilton** | STAR/Vantage | High-end liquid handling |
| **Chemspeed** | SWING/iSynth | High-throughput synthesis |
| **Beckman Coulter** | Biomek | Life science automation |
| **ABB Robotics** | Collaborative robots | AI-driven lab automation |

## 📚 Key Papers

### 🔬 Top Research — Autonomous Lab Systems

| Paper | Venue | Year | Key Result |
|-------|-------|------|------------|
| [GPT-5-driven autonomous lab optimizes cell-free protein synthesis](https://www.biorxiv.org/content/10.64898/2026.02.05.703998v1) | bioRxiv | 2026 | 🔥 36k experiments, 40% cost reduction, minimal human intervention |
| [Knowledge-driven autonomous materials research (MARS)](https://doi.org/10.1016/j.matt.2025.102577) | Matter | 2026 | 19 LLM agents + 16 tools, closed-loop materials discovery |
| [An autonomous laboratory for accelerated synthesis (A-Lab)](https://www.nature.com/articles/s41586-023-06734-w) | Nature | 2023 | 43 materials in 17 days ([Correction 2026](https://cen.acs.org/research-integrity/Nature-robot-chemist-paper-corrected/104/web/2026/01)) |
| [Autonomous chemical research with LLMs (Coscientist)](https://www.nature.com/articles/s41586-023-06792-0) | Nature | 2023 | GPT-4 planned & executed palladium cross-coupling |
| [Autonomous mobile robot for exploratory chemistry](https://www.nature.com/articles/s41586-024-08173-7) | Nature | 2024 | Mobile robot navigating lab, performing synthesis autonomously |
| [Robin: multi-agent system for scientific discovery](https://arxiv.org/abs/2505.13400) | arXiv | 2025 | First AI to autonomously discover & validate therapeutic candidate (ripasudil) |
| [ORGANA: LLM + Franka robot for chemistry](https://doi.org/10.1016/j.xcrp.2024.101542) | Cell Reports Phys Sci | 2024 | Robot arm + LLM planning for autonomous chemistry |

### 🔬 Top Research — Closed-Loop & Active Learning

| Paper | Venue | Year | Key Result |
|-------|-------|------|------------|
| [Autonomous catalysis research with human–AI–robot collaboration](https://www.nature.com/articles/s41929-025-01430-6) | Nature Catalysis | 2025 | Human-AI-robot collaboration for catalyst discovery |
| [Autonomous closed-loop mechanistic investigation of molecular electrochemistry](https://www.nature.com/articles/s41467-024-47210-x) | Nature Communications | 2024 | Adaptive closed-loop workflow for electrochemical mechanism |
| [Closed-loop nanomaterials synthesis (AMPLE)](https://www.nature.com/articles/s44286-025-00291-x) | Nature Chemical Eng | 2025 | Gram-to-tonne scale, microreactors + ML + automation |
| [SDL for photochemical synthesis of plasmonic nanoparticles](https://www.nature.com/articles/s41467-025-59231-1) | Nature Communications | 2025 | Autonomous optimization of nanoparticle optical properties |
| [SDL discovers principles for steering spontaneous emission](https://www.nature.com/articles/s41467-025-66916-0) | Nature Communications | 2025 | Autonomous experimentation in ultrafast nanophotonics |
| [Flow-driven data intensification for materials discovery](https://www.sciencedaily.com/releases/2025/07/250714052105.htm) | Nature Chemical Eng | 2025 | 10× data intensification for autonomous materials |

### 🔬 Top Research — LLM Agents in Labs

| Paper | Venue | Year | Key Result |
|-------|-------|------|------------|
| [LLM agents for automation of atomic force microscopy](https://www.nature.com/articles/s41467-025-64105-7) | Nature Communications | 2025 | LLMs transforming SDL via autonomous AFM operation |
| [Automating quantum computing experiments with agent-based AI](https://www.cell.com/patterns/fulltext/S2666-3899(25)00220-X) | Cell Patterns | 2025 | LLM agent autonomously plans, executes & analyzes quantum experiments |
| [LIRA: Localization, inspection and reasoning for SDL](https://www.nature.com/articles/s42004-025-01770-1) | Communications Chemistry | 2025 | Vision + reasoning module for autonomous lab workflows |
| [LLMs in the scientific method: from hypothesis to discovery](https://www.nature.com/articles/s44387-025-00019-5) | npj Artificial Intelligence | 2025 | Comprehensive analysis of LLM roles across scientific method |
| [AI Scientist: Fully automated scientific discovery](https://arxiv.org/abs/2408.06292) | arXiv / Sakana AI | 2024 | End-to-end research pipeline (8.9k⭐) |
| [AI Scientist v2: Workshop-level discovery](https://arxiv.org/abs/2502.14297) | ICLR Workshop | 2025 | First AI-generated peer-reviewed paper |

### 🔬 Top Research — Safety, Infrastructure & Standards

| Paper | Venue | Year | Key Result |
|-------|-------|------|------------|
| [Steering towards safe self-driving laboratories](https://www.nature.com/articles/s41570-025-00747-x) | Nature Reviews Chemistry | 2025 | Safety framework for autonomous labs |
| [Self-driving labs for biotechnology](https://www.nature.com/articles/s43588-025-00885-8) | Nature Computational Sci | 2025 | When SDLs are (and aren't) applicable in biotech |
| [IvoryOS: interoperable web interface for SDL](https://www.nature.com/articles/s41467-025-60514-w) | Nature Communications | 2025 | No-code drag-and-drop SDL interface |
| [Transforming science labs into automated factories](https://www.science.org/doi/10.1126/scirobotics.adm6991) | Science Robotics | 2024 | Vision for lab-as-factory transformation |
| [Accelerating discovery with AI and robotics](https://www.science.org/doi/10.1126/scirobotics.adv7932) | Science Robotics | 2024 | Perspectives & challenges for lab AI+robotics |
| [Building an affordable self-driving lab](https://pubs.aip.org/aip/aml/article/3/4/046105/3369966) | APL Machine Learning | 2025 | IoT-based SDL for education ($300 budget) |

### 📊 Surveys & Meta-Analysis

| Paper | Venue | Year |
|-------|-------|------|
| [From AI for Science to Agentic Science](https://arxiv.org/abs/2508.14111) | arXiv | 2025 |
| [SDL for Chemistry & Materials](https://pubs.acs.org/doi/10.1021/acs.chemrev.4c00055) | Chemical Reviews | 2024 |
| [Autonomous SDL: Technology & Policy](https://royalsocietypublishing.org/rsos/article/12/7/250646) | Royal Society | 2025 |
| [Leading AI-driven drug discovery platforms: 2025 landscape](https://www.sciencedirect.com/science/article/abs/pii/S0031699925075118) | ScienceDirect | 2025 |
| [The rise of self-driving labs](https://www.nature.com/articles/s44160-022-00231-0) | Nature Synthesis | 2023 |

### 🏥 Clinical / Biomedical AI

| Paper | Venue | Year |
|-------|-------|------|
| [AlphaFold 3: biomolecular interaction prediction](https://www.nature.com/articles/s41586-024-07487-w) | Nature | 2024 |
| [Med-PaLM: LLMs encode clinical knowledge](https://www.nature.com/articles/s41586-023-06291-2) | Nature | 2023 |
| [GatorTron: Large Clinical Language Model](https://www.nature.com/articles/s41746-022-00742-2) | npj Digital Medicine | 2022 |

## 📖 Books & Courses

- 📘 [Self-Driving Laboratories for Chemistry and Materials Science](https://pubs.acs.org/doi/10.1021/acs.chemrev.4c00055) — Chemical Reviews 2024
- 📘 [Autonomous Research](https://autonomous-research.org/) — Community resources
- 📘 [Building an Affordable Self-Driving Lab](https://pubs.aip.org/aip/aml/article/3/4/046105/3369966) — APL Machine Learning 2025 (IoT-based education)
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

- **[SLAS](https://www.slas.org/)** — Society for Lab Automation & Screening ([SLAS 2026 highlights](https://cen.acs.org/pharmaceuticals/drug-discovery/Humanoid-robots-lab-machines-attract/104/web/2026/02))
- **[Acceleration Consortium](https://acceleration.utoronto.ca/)** — University of Toronto, SDL research hub
- **[AD-SDL](https://github.com/AD-SDL)** — Argonne National Lab, Self-Driving Labs
- **[AI for Science Workshop](https://ai4sciencecommunity.github.io/)** — NeurIPS/ICML workshops
- **[IROS 2025: AI Robot for Science Workshop](https://www.science.org/doi/10.1126/scirobotics.adv7932)** — Embodied AI for lab automation

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
