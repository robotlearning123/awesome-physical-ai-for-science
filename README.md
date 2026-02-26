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
| [Accelerating discovery in natural science laboratories with AI and robotics](https://www.science.org/doi/10.1126/scirobotics.adv7932) | Science Robotics | 2025 | Perspectives & challenges |
| [The Rise of Self-Driving Labs](https://www.optica-opn.org/home/articles/volume_36/april_2025/features/the_rise_of_self-driving_labs/) | Optics & Photonics News | 2025 | Accessible overview of SDL field |
| [Will self-driving 'robot labs' replace biologists?](https://www.nature.com/articles/d41586-026-00453-8) | Nature News | 2026 | Debate on autonomous labs in biology |
| [A Comprehensive Survey of AI Scientists](https://github.com/tsinghua-fib-lab/Awesome-AI-Scientists) | Tsinghua | 2025 | Full pipeline AI scientist systems |
| [The rise of self-driving labs](https://www.nature.com/articles/s44160-022-00231-0) | Nature Synthesis | 2023 | Early perspective on SDL emergence |
| [Leading AI-driven drug discovery platforms: 2025 landscape](https://www.sciencedirect.com/science/article/abs/pii/S0031699725075118) | ScienceDirect | 2025 | Platform comparison for AI drug discovery |

## 🧪 Self-Driving Lab Systems

### Pioneering Systems

| System | Institution | Domain | Key Feature | Reference |
|--------|------------|--------|-------------|-----------|
| **OpenAI + Ginkgo Bioworks** | OpenAI / Ginkgo | Biology | 🔥 GPT-5 + cloud lab, 36k experiments, 40% cost reduction in cell-free protein synthesis | [bioRxiv 2026](https://www.biorxiv.org/content/10.64898/2026.02.05.703998v1) |
| **A-Lab** | LBNL Berkeley | Materials | Autonomous solid-state synthesis, 43 materials in 17 days | [Nature 2023](https://www.nature.com/articles/s41586-023-06734-w) |
| **Coscientist** | CMU | Chemistry | GPT-4 + robotic synthesis, palladium cross-coupling | [Nature 2023](https://www.nature.com/articles/s41586-023-06792-0) |
| **Mobile Robot Chemist** | U Liverpool | Chemistry | Autonomous mobile robots for exploratory synthesis | [Nature 2024](https://www.nature.com/articles/s41586-024-08173-7) |
| **ORGANA** | U Toronto | Chemistry | Franka robot + LLM planning | [Matter 2024](https://www.sciencedirect.com/science/article/abs/pii/S2590238524005423) |
| **Rainbow** | NC State / Multi-institution | Nanomaterials | Multi-robot SDL, parallelized nanocrystal synthesis | [Nature Comm 2025](https://www.nature.com/articles/s41467-025-63209-4) |
| **DOLPHIN** | Fudan / Shanghai AI Lab | General Science | LLM generates ideas → experiments → evaluation → iteration | [ACL 2025](https://arxiv.org/abs/2501.03916) |
| **AutoLabs** | Multi-institution | Chemistry | Cognitive multi-agent with self-correction | [arXiv 2025](https://arxiv.org/abs/2509.25651) |
| **SDL for Nanophotonics** | — | Photonics | Autonomous experimentation for spontaneous emission | [Nature Comm 2025](https://www.nature.com/articles/s41467-025-66916-0) |
| **SDL for Solid-State Lasers** | — | Materials/Photonics | Discovery of tunable organic emitters | [Nature Comm 2026](https://www.nature.com/articles/s41467-026-69233-2) |
| **AI Enzyme Engineering** | — | Biology | Generalized platform for autonomous enzyme engineering | [Nature Comm 2025](https://www.nature.com/articles/s41467-025-61209-y) |
| **Flow-Driven SDL** | — | Materials | 10× data intensification for materials discovery | [Nature Chem Eng 2025](https://www.nature.com/articles/s44286-025-00249-z) |

> ⚠️ **Note**: The A-Lab Nature 2023 paper received a [correction in January 2026](https://cen.acs.org/research-integrity/Nature-robot-chemist-paper-corrected/104/web/2026/01), with some questions remaining about the claimed new materials.

### Multi-Agent Scientific Systems

| System | Description | Year | Reference |
|--------|------------|------|-----------|
| **MARS** | 19 LLM agents + 16 tools, hierarchical architecture for materials discovery | 2026 | [Matter 2026](https://doi.org/10.1016/j.matt.2025.102577) / [phys.org](https://phys.org/news/2026-01-multi-agent-ai-robots-automate.html) |
| **Robin** | First AI to autonomously discover and validate novel therapeutic candidate (ripasudil for dAMD) | 2025 | [arXiv](https://arxiv.org/abs/2505.13400) / [FutureHouse](https://www.futurehouse.org/research-announcements/demonstrating-end-to-end-scientific-discovery-with-robin-a-multi-agent-system) |
| **ChemAgents** | Task Manager + Literature Reader + Experiment Designer + Computation Performer + Robot Operator | 2025 | [JACS 2025](https://pubs.acs.org/doi/10.1021/jacs.4c17738) |
| **Tippy** | Production-ready AI agents for DMTA cycle in drug discovery | 2025 | [arXiv](https://arxiv.org/abs/2507.09023) |
| **Aleks** | Multi-agent autonomous discovery in plant science | 2025 | [arXiv](https://arxiv.org/abs/2508.19383) |
| **VirSci** | Virtual scientists for Science of Science | 2025 | [ACL 2025](https://arxiv.org/abs/2410.09403) |
| **OriGene** | Virtual disease biologist for therapeutic target discovery | 2025 | [bioRxiv 2025](https://www.biorxiv.org/content/10.1101/2025.06.03.657658v1) |
| **Agent Laboratory** | Literature review → experiment → report writing pipeline | 2025 | [arXiv 2025](https://arxiv.org/abs/2501.04227) |

### End-to-End AI Scientist Systems

| System | Description | Achievement | Reference |
|--------|------------|-------------|-----------|
| **AI Scientist v1** | End-to-end automated research pipeline | ![Stars](https://img.shields.io/github/stars/SakanaAI/AI-Scientist?style=flat-square) | [Sakana AI 2024](https://github.com/SakanaAI/AI-Scientist) |
| **AI Scientist v2** | Workshop-level automated discovery | First AI-generated peer-reviewed paper (ICLR 2025 Workshop) | [arXiv 2025](https://arxiv.org/abs/2504.08066) |

> ⚠️ Independent [evaluation](https://arxiv.org/abs/2502.14297) (ACM SIGIR Forum 2025) found mixed results, noting some claims may be overstated.

## 🤖 Robotic Lab Platforms

### Hardware Platforms

| Platform | Institution | Description | Link |
|----------|------------|-------------|------|
| **MADSci** | Argonne National Lab | Modular Autonomous Discovery for Science toolkit | [AD-SDL](https://github.com/AD-SDL) |
| **LabClaw** | ![Stars](https://img.shields.io/github/stars/labclaw/labclaw?style=flat-square) | Open-source AI infrastructure for scientific labs — 5-layer architecture with self-evolving agents | [GitHub](https://github.com/labclaw/labclaw) |
| **Polybot** | Center for Nanoscale Materials | Self-driving lab for polymer science | [polybot-nexus](https://github.com/polybot-nexus) |
| **Opentrons Flex** | Opentrons | Open-source liquid handling robots | [Opentrons](https://github.com/Opentrons) |
| **Chemspeed** | Chemspeed | High-throughput automated synthesis | Commercial |
| **Mobile ALOHA** | Stanford | Bimanual mobile manipulation for labs | [GitHub](https://github.com/tonyzhaozh/aloha) |
| **ABB Robotics** | ABB | AI-driven collaborative robots for labs | [SLAS 2026 Demo](https://www.robotics247.com/article/slas-2026-abb-turns-ai-into-action-to-accelerate-the-future-of-lab-automation) |
| **Ginkgo Cloud Lab** | Ginkgo Bioworks | Remote automated wet lab (robots execute experiments) | [ginkgo.bio](https://www.ginkgo.bio/) |

### Orchestration Software

| Platform | Provider | Description | Link |
|----------|----------|-------------|------|
| **Cellario** | HighRes Biosolutions | 🔥 Agentic AI scheduling + orchestration for lab automation | [highres.com](https://www.highres.com/lab-orchestration) |
| **FlexPod** | HighRes | Configurable Lab Automation Platform | [highres.com](https://www.highres.com/) |
| **IvoryOS** | — | Drag-and-drop web interface for SDL workflow design | [Nature Comm 2025](https://www.nature.com/articles/s41467-025-60514-w) |
| **AlabOS** | — | Python reconfigurable workflow management for SDL | [RSC Digital Discovery 2024](https://pubs.rsc.org/en/content/articlehtml/2024/dd/d4dd00129j) |

> 🔥 **Breaking**: [HighRes + Opentrons partnership](https://www.businesswire.com/news/home/20260204914025/en/) (Feb 2026) — Industry's first AI Agent-to-Agent lab automation workflow

## 🧠 AI Agents for Scientific Discovery

### LLM-based Scientific Agents

| Agent | Focus | Key Innovation | Reference |
|-------|-------|---------------|-----------|
| **GPT-5 Lab Agent** | Biology | 🔥 Autonomous wet lab experiments via cloud lab, 36k experiments | [OpenAI 2026](https://openai.com/index/gpt-5-lowers-protein-synthesis-cost/) |
| **ChemCrow** | Chemistry | LLM + 18 chemistry tools integration | [arXiv 2023](https://arxiv.org/abs/2304.05376) |
| **SciAgents** | Materials | Graph reasoning + multi-agent for materials design | [arXiv 2024](https://arxiv.org/abs/2409.05556) |
| **Lang-PINN** | Physics | LLM builds Physics-Informed Neural Networks from natural language | [ICLR 2026](https://arxiv.org/abs/2510.05158) |
| **AI Scientist** | General | End-to-end automated research pipeline | [Sakana AI 2024](https://github.com/SakanaAI/AI-Scientist) |
| **OpenAI Deep Research** | General | Autonomous multi-step research agent | [OpenAI 2025](https://openai.com/index/introducing-deep-research/) |

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

### Neuroscience

| Platform | Type | Description |
|----------|------|-------------|
| **[DeepLabCut](https://github.com/DeepLabCut/DeepLabCut)** | Tool | Markerless multi-animal pose estimation |
| **[SLEAP](https://github.com/talmolab/sleap)** | Tool | Multi-animal pose tracking (top-down + bottom-up) |
| **[SpikeInterface](https://github.com/SpikeInterface/spikeinterface)** | Tool | Unified spike sorting framework (10+ backends) |
| **[Suite2p](https://github.com/MouseLand/suite2p)** | Tool | Two-photon calcium imaging pipeline |
| **[CaImAn](https://github.com/flatironinstitute/CaImAn)** | Tool | Calcium imaging analysis (CNMF, online) |
| **[MNE-Python](https://github.com/mne-tools/mne-python)** | Tool | MEG/EEG analysis |
| **[PyNWB](https://github.com/NeurodataWithoutBorders/pynwb)** | Standard | Neurodata Without Borders file I/O |
| **[NeuroConv](https://github.com/catalystneuro/neuroconv)** | Tool | 47+ formats → NWB conversion |
| **[Pynapple](https://github.com/pynapple-org/pynapple)** | Tool | Neural time series analysis |
| **[keypoint-MoSeq](https://github.com/dattalab/keypoint-moseq)** | Tool | Unsupervised behavioral syllable discovery |
| **[DataJoint](https://github.com/datajoint/datajoint-python)** | Platform | Scientific data pipeline management |
| **[DANDI Archive](https://dandiarchive.org/)** | Database | 790+ dandisets, open neuroscience data |
| **[Allen Brain Observatory](https://observatory.brain-map.org/)** | Database | Visual coding, connectivity atlas |
| **[OpenNeuro](https://openneuro.org/)** | Database | 1,800+ BIDS neuroimaging datasets |

## 🛠️ Software Frameworks & Tools

### Self-Driving Lab Software

| Tool | Stars | Description | Link |
|------|-------|-------------|------|
| **AI-Scientist** | ![Stars](https://img.shields.io/github/stars/SakanaAI/AI-Scientist?style=flat-square) | End-to-end automated research pipeline | [GitHub](https://github.com/SakanaAI/AI-Scientist) |
| **MADSci** | ![Stars](https://img.shields.io/github/stars/AD-SDL/MADSci?style=flat-square) | Modular framework for autonomous discovery | [GitHub](https://github.com/AD-SDL/MADSci) |
| **LabClaw** | ![Stars](https://img.shields.io/github/stars/labclaw/labclaw?style=flat-square) | Open-source AI infrastructure for scientific labs — 5-layer architecture with self-evolving agents | [GitHub](https://github.com/labclaw/labclaw) |
| **IvoryOS** | — | No-code web interface for SDL workflows | [Nature Comm 2025](https://www.nature.com/articles/s41467-025-60514-w) |
| **AlabOS** | — | Python reconfigurable SDL management | [Digital Discovery](https://pubs.rsc.org/en/content/articlehtml/2024/dd/d4dd00129j) |

### AI for Science Agent Platforms

| Platform | Provider | Description | Link |
|----------|----------|-------------|------|
| **Claude for Life Sciences** | Anthropic | MCP connectors + Agent Skills for life science research | [anthropic.com](https://www.anthropic.com/news/claude-for-life-sciences) |
| **Claude Scientific Skills** | K-Dense AI | 140+ ready-to-use scientific skills ![Stars](https://img.shields.io/github/stars/K-Dense-AI/claude-scientific-skills?style=flat-square) | [GitHub](https://github.com/K-Dense-AI/claude-scientific-skills) |
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
| [ORGANA: robotic assistant for automated chemistry](https://www.sciencedirect.com/science/article/abs/pii/S2590238524005423) | Matter | 2024 | Franka robot + LLM planning for autonomous chemistry |

### 🔬 Top Research — Closed-Loop & Active Learning

| Paper | Venue | Year | Key Result |
|-------|-------|------|------------|
| [Autonomous catalysis research with human–AI–robot collaboration](https://www.nature.com/articles/s41929-025-01430-6) | Nature Catalysis | 2025 | Human-AI-robot collaboration for catalyst discovery |
| [Autonomous closed-loop mechanistic investigation of molecular electrochemistry](https://www.nature.com/articles/s41467-024-47210-x) | Nature Communications | 2024 | Adaptive closed-loop workflow for electrochemical mechanism |
| [Closed-loop nanomaterials synthesis (AMPLE)](https://www.nature.com/articles/s44286-025-00291-x) | Nature Chemical Eng | 2025 | Gram-to-tonne scale, microreactors + ML + automation |
| [Science acceleration and accessibility with self-driving labs](https://www.nature.com/articles/s41467-025-59231-1) | Nature Communications | 2025 | Perspective on SDL accessibility & democratization |
| [SDL discovers principles for steering spontaneous emission](https://www.nature.com/articles/s41467-025-66916-0) | Nature Communications | 2025 | Autonomous experimentation in ultrafast nanophotonics |
| [Flow-driven data intensification for materials discovery](https://www.nature.com/articles/s44286-025-00249-z) | Nature Chemical Eng | 2025 | 10× data intensification for autonomous materials |

### 🔬 Top Research — LLM Agents in Labs

| Paper | Venue | Year | Key Result |
|-------|-------|------|------------|
| [LLM agents for automation of atomic force microscopy](https://www.nature.com/articles/s41467-025-64105-7) | Nature Communications | 2025 | AILA framework + AFMBench for evaluating LLM-driven AFM automation |
| [Automating quantum computing experiments with agent-based AI](https://www.cell.com/patterns/fulltext/S2666-3899(25)00220-X) | Cell Patterns | 2025 | LLM agent autonomously plans, executes & analyzes quantum experiments |
| [LIRA: Localization, inspection and reasoning for SDL](https://www.nature.com/articles/s42004-025-01770-1) | Communications Chemistry | 2025 | Vision + reasoning module for autonomous lab workflows |
| [LLMs in the scientific method: from hypothesis to discovery](https://www.nature.com/articles/s44387-025-00019-5) | npj Artificial Intelligence | 2025 | Comprehensive analysis of LLM roles across scientific method |
| [AI Scientist: Fully automated scientific discovery](https://arxiv.org/abs/2408.06292) | arXiv / Sakana AI | 2024 | End-to-end research pipeline |
| [Evaluating AI Scientist: Bold Claims, Mixed Results](https://arxiv.org/abs/2502.14297) | ACM SIGIR Forum | 2025 | Independent evaluation of AI Scientist capabilities |

### 🔬 Top Research — Safety, Infrastructure & Standards

| Paper | Venue | Year | Key Result |
|-------|-------|------|------------|
| [Steering towards safe self-driving laboratories](https://www.nature.com/articles/s41570-025-00747-x) | Nature Reviews Chemistry | 2025 | Safety framework for autonomous labs |
| [Self-driving labs for biotechnology](https://www.nature.com/articles/s43588-025-00885-8) | Nature Computational Sci | 2025 | When SDLs are (and aren't) applicable in biotech |
| [IvoryOS: interoperable web interface for SDL](https://www.nature.com/articles/s41467-025-60514-w) | Nature Communications | 2025 | No-code drag-and-drop SDL interface |
| [Transforming science labs into automated factories](https://www.science.org/doi/10.1126/scirobotics.adm6991) | Science Robotics | 2024 | Vision for lab-as-factory transformation |
| [Accelerating discovery with AI and robotics](https://www.science.org/doi/10.1126/scirobotics.adv7932) | Science Robotics | 2025 | Perspectives & challenges for lab AI+robotics |
| [Building an affordable self-driving lab](https://pubs.aip.org/aip/aml/article/3/4/046105/3369966) | APL Machine Learning | 2025 | IoT-based SDL for education (~$60 budget) |

### 🏥 Clinical / Biomedical AI

| Paper | Venue | Year |
|-------|-------|------|
| [AlphaFold 3: biomolecular interaction prediction](https://www.nature.com/articles/s41586-024-07487-w) | Nature | 2024 |
| [Med-PaLM: LLMs encode clinical knowledge](https://www.nature.com/articles/s41586-023-06291-2) | Nature | 2023 |
| [GatorTron: Large Clinical Language Model](https://www.nature.com/articles/s41746-022-00742-2) | npj Digital Medicine | 2022 |

## 📖 Books & Courses

- 📘 [Self-Driving Laboratories for Chemistry and Materials Science](https://pubs.acs.org/doi/10.1021/acs.chemrev.4c00055) — Chemical Reviews 2024
- 📘 [Building an Affordable Self-Driving Lab](https://pubs.aip.org/aip/aml/article/3/4/046105/3369966) — APL Machine Learning 2025 (IoT-based, ~$60)
- 🎓 [NVIDIA Deep Learning Institute](https://www.nvidia.com/en-us/training/) — GPU-accelerated training courses

## 🎯 Benchmarks & Datasets

| Benchmark | Domain | Description |
|-----------|--------|-------------|
| **FrontierScience** | General | OpenAI benchmark for AI scientific reasoning |
| **ScienceWorld** | General | Interactive text-based science experiments |
| **Materials Project** | Materials | 150k+ materials with computed properties |
| **AlphaFold DB** | Biology | 200M+ predicted protein structures |
| **PubChem** | Chemistry | 100M+ chemical compounds |
| **ChEMBL** | Drug Discovery | Bioactive molecules with drug-like properties |
| **[ScienceAgentBench](https://github.com/OSU-NLP-Group/ScienceAgentBench)** | General | 102-task benchmark for AI science agents (ICLR 2025) |

## 🌐 Communities & Events

- **[SLAS](https://www.slas.org/)** — Society for Lab Automation & Screening ([SLAS 2026 highlights](https://cen.acs.org/pharmaceuticals/drug-discovery/Humanoid-robots-lab-machines-attract/104/web/2026/02))
- **[Acceleration Consortium](https://acceleration.utoronto.ca/)** — University of Toronto, SDL research hub
- **[AD-SDL](https://github.com/AD-SDL)** — Argonne National Lab, Self-Driving Labs
- **[AI for Science Workshop](https://ai4sciencecommunity.github.io/)** — NeurIPS/ICML workshops

## 🔗 Related Awesome Lists

### AI for Science & Autonomous Research

| List | Stars | Focus | Active |
|------|-------|-------|--------|
| [awesome-ai-for-science](https://github.com/ai-boost/awesome-ai-for-science) | ![Stars](https://img.shields.io/github/stars/ai-boost/awesome-ai-for-science?style=flat-square) | Broadest AI+Science resource (tools, papers, datasets) | 2026 |
| [awesome-self-driving-labs](https://github.com/AccelerationConsortium/awesome-self-driving-labs) | ![Stars](https://img.shields.io/github/stars/AccelerationConsortium/awesome-self-driving-labs?style=flat-square) | Self-driving labs (chemistry/materials), BibTeX refs | 2025 |
| [Awesome-Self-Evolving-Agents](https://github.com/EvoAgentX/Awesome-Self-Evolving-Agents) | ![Stars](https://img.shields.io/github/stars/EvoAgentX/Awesome-Self-Evolving-Agents?style=flat-square) | Self-evolving agent architectures (survey companion) | 2025 |
| [Awesome-LLM-Scientific-Discovery](https://github.com/HKUST-KnowComp/Awesome-LLM-Scientific-Discovery) | ![Stars](https://img.shields.io/github/stars/HKUST-KnowComp/Awesome-LLM-Scientific-Discovery?style=flat-square) | 3-level autonomy framework (EMNLP 2025 survey) | 2025 |
| [Awesome-AI-Scientists](https://github.com/tsinghua-fib-lab/Awesome-AI-Scientists) | ![Stars](https://img.shields.io/github/stars/tsinghua-fib-lab/Awesome-AI-Scientists?style=flat-square) | Full-pipeline AI scientist systems (Tsinghua) | 2025 |
| [Awesome-AI-Scientist-Papers](https://github.com/openags/Awesome-AI-Scientist-Papers) | ![Stars](https://img.shields.io/github/stars/openags/Awesome-AI-Scientist-Papers?style=flat-square) | Robot scientist lineage: Ross King → AI Scientist | 2025 |
| [Awesome-Scientific-Language-Models](https://github.com/yuzhimanhua/Awesome-Scientific-Language-Models) | ![Stars](https://img.shields.io/github/stars/yuzhimanhua/Awesome-Scientific-Language-Models?style=flat-square) | 260+ domain-specific scientific LLMs catalogued | 2025 |
| [Awesome-Scientific-Datasets-and-LLMs](https://github.com/InternScience/Awesome-Scientific-Datasets-and-LLMs) | ![Stars](https://img.shields.io/github/stars/InternScience/Awesome-Scientific-Datasets-and-LLMs?style=flat-square) | Scientific datasets + LLM benchmarks | 2025 |

### Neuroscience

| List | Stars | Focus | Active |
|------|-------|-------|--------|
| [awesome-neuroscience](https://github.com/analyticalmonk/awesome-neuroscience) | ![Stars](https://img.shields.io/github/stars/analyticalmonk/awesome-neuroscience?style=flat-square) | Full-stack neuroscience tools (simulation → behavior) | 2024 |
| [awesome-neural-geometry](https://github.com/neurreps/awesome-neural-geometry) | ![Stars](https://img.shields.io/github/stars/neurreps/awesome-neural-geometry?style=flat-square) | Geometric deep learning + neuroscience | 2026 |
| [awesome-neurofm](https://github.com/mazabou/awesome-neurofm) | ![Stars](https://img.shields.io/github/stars/mazabou/awesome-neurofm?style=flat-square) | Neural foundation models (POYO, NDT2, POSSM) | 2025 |
| [ElectrophysiologySoftware](https://github.com/openlists/ElectrophysiologySoftware) | ![Stars](https://img.shields.io/github/stars/openlists/ElectrophysiologySoftware?style=flat-square) | EEG/MEG/ECoG/intracranial tools | 2025 |
| [awesome-janelia-software](https://github.com/JaneliaSciComp/awesome-janelia-software) | ![Stars](https://img.shields.io/github/stars/JaneliaSciComp/awesome-janelia-software?style=flat-square) | HHMI/Janelia research software | 2025 |

### Life Sciences & Biology

| List | Stars | Focus | Active |
|------|-------|-------|--------|
| [Awesome-Bioinformatics](https://github.com/danielecook/Awesome-Bioinformatics) | ![Stars](https://img.shields.io/github/stars/danielecook/Awesome-Bioinformatics?style=flat-square) | Bioinformatics CLI tools (200+) | 2025 |
| [awesome-single-cell](https://github.com/seandavi/awesome-single-cell) | ![Stars](https://img.shields.io/github/stars/seandavi/awesome-single-cell?style=flat-square) | Single-cell genomics (300+ tools) | 2026 |
| [papers_for_protein_design_using_DL](https://github.com/Peldom/papers_for_protein_design_using_DL) | ![Stars](https://img.shields.io/github/stars/Peldom/papers_for_protein_design_using_DL?style=flat-square) | 500+ protein design papers | 2026 |
| [awesome-computational-biology](https://github.com/inoue0426/awesome-computational-biology) | ![Stars](https://img.shields.io/github/stars/inoue0426/awesome-computational-biology?style=flat-square) | Computational biology databases + tools | 2026 |
| [awesome-bioie](https://github.com/caufieldjh/awesome-bioie) | ![Stars](https://img.shields.io/github/stars/caufieldjh/awesome-bioie?style=flat-square) | Biomedical NLP / information extraction | 2024 |
| [Awesome-LLM-Agents-Scientific-Discovery](https://github.com/zjlrock777/Awesome-LLM-Agents-Scientific-Discovery) | ![Stars](https://img.shields.io/github/stars/zjlrock777/Awesome-LLM-Agents-Scientific-Discovery?style=flat-square) | LLM agents in biomedical research | 2025 |

### Chemistry & Materials

| List | Stars | Focus | Active |
|------|-------|-------|--------|
| [awesome-python-chemistry](https://github.com/lmmentel/awesome-python-chemistry) | ![Stars](https://img.shields.io/github/stars/lmmentel/awesome-python-chemistry?style=flat-square) | Python chemistry packages (150+) | 2025 |
| [best-of-atomistic-machine-learning](https://github.com/JuDFTteam/best-of-atomistic-machine-learning) | ![Stars](https://img.shields.io/github/stars/JuDFTteam/best-of-atomistic-machine-learning?style=flat-square) | 510 projects, auto-ranked weekly | 2026 |
| [awesome-cheminformatics](https://github.com/hsiaoyi0504/awesome-cheminformatics) | ![Stars](https://img.shields.io/github/stars/hsiaoyi0504/awesome-cheminformatics?style=flat-square) | Cheminformatics tools | 2024 |
| [awesome-materials-informatics](https://github.com/tilde-lab/awesome-materials-informatics) | ![Stars](https://img.shields.io/github/stars/tilde-lab/awesome-materials-informatics?style=flat-square) | Materials databases + ML platforms | 2025 |
| [papers-for-molecular-design-using-DL](https://github.com/AspirinCode/papers-for-molecular-design-using-DL) | ![Stars](https://img.shields.io/github/stars/AspirinCode/papers-for-molecular-design-using-DL?style=flat-square) | 400+ molecular design papers | 2026 |
| [awesome-molecular-generation](https://github.com/amorehead/awesome-molecular-generation) | ![Stars](https://img.shields.io/github/stars/amorehead/awesome-molecular-generation?style=flat-square) | Generative molecular modeling (diffusion, flow) | 2025 |
| [awesome-isaac-gym](https://github.com/robotlearning123/awesome-isaac-gym) | ![Stars](https://img.shields.io/github/stars/robotlearning123/awesome-isaac-gym?style=flat-square) | NVIDIA Isaac Gym for robot learning & simulation | 2026 |

### Drug Discovery

| List | Stars | Focus | Active |
|------|-------|-------|--------|
| [awesome-drug-discovery](https://github.com/yboulaamane/awesome-drug-discovery) | ![Stars](https://img.shields.io/github/stars/yboulaamane/awesome-drug-discovery?style=flat-square) | Computational drug discovery tools | 2025 |
| [awesome-small-molecule-ml](https://github.com/benb111/awesome-small-molecule-ml) | ![Stars](https://img.shields.io/github/stars/benb111/awesome-small-molecule-ml?style=flat-square) | Small-molecule drug discovery ML | 2023 |
| [awesome-AI-based-protein-design](https://github.com/opendilab/awesome-AI-based-protein-design) | ![Stars](https://img.shields.io/github/stars/opendilab/awesome-AI-based-protein-design?style=flat-square) | AI protein design papers | 2024 |
| [awesome-ai-agent-papers](https://github.com/VoltAgent/awesome-ai-agent-papers) | ![Stars](https://img.shields.io/github/stars/VoltAgent/awesome-ai-agent-papers?style=flat-square) | AI agent papers (general) | 2026 |

---

## Contributing

Contributions welcome! Please read the [contribution guidelines](CONTRIBUTING.md) first.

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

---

**Maintained by [Cong](https://github.com/robotlearning123)** — Researcher in Physical AI for Science, Agentic Systems & Embodied Intelligence @ Harvard
