# Awesome Research Skills

> A curated collection of AI agent skills, tools, and repositories for scientific research across **neuroscience**, **brain-inspired intelligence**, **LLMs**, and **embodied intelligence**.

[![License: CC0-1.0](https://img.shields.io/badge/License-CC0_1.0-lightgrey.svg)](http://creativecommons.org/publicdomain/zero/1.0/)
[![Last Updated](https://img.shields.io/badge/Updated-2026--08--07-blue.svg)](https://github.com/)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)

## Why This Repo?

Thousands of AI agent skills are scattered across GitHub. A researcher working at the intersection of neuroscience and AI shouldn't have to dig through 85,000+ indexed skills to find the right tools. This repo curates high-quality, research-relevant skills and tools across four core domains, with metadata for each entry: stars, last update, skill count, and compatibility.

## Table of Contents

- [Neuroscience & Cognitive Science](#neuroscience--cognitive-science)
- [Brain-Inspired Intelligence & Neuromorphic Computing](#brain-inspired-intelligence--neuromorphic-computing)
- [LLM & AI Research Skills](#llm--ai-research-skills)
- [Embodied Intelligence & Robotics](#embodied-intelligence--robotics)
- [Cross-Domain Research Tools](#cross-domain-research-tools)
- [Awesome Lists & Resource Collections](#awesome-lists--resource-collections)
- [Refresh Guide](#refresh-guide)
- [Contributing](#contributing)

---

## Neuroscience & Cognitive Science

Skills and tools for neuroimaging, electrophysiology, neural data analysis, cognitive modeling, and brain simulation.

### Agent Skills (Installable)

| Repository | Skills | Stars | Description | Compatibility |
|---|---|---|---|---|
| [NeuroAIHub/awesome_cognitive_and_neuroscience_skills](https://github.com/NeuroAIHub/awesome_cognitive_and_neuroscience_skills) | 45 | — | AI-generated skills from academic papers covering fMRI preprocessing, EEG analysis, calcium imaging, drift-diffusion modeling, cognitive paradigm design, power analysis, and more. 13 categories including Cognitive Psychology, Neuroimaging, Electrophysiology, Cross-Domain Foundation. | Claude Code, Codex, OpenCode |
| [K-Dense-AI/scientific-agent-skills](https://github.com/K-Dense-AI/scientific-agent-skills) (neuro-relevant subset) | 158 total | 27.6k | Comprehensive scientific skills library — neuro-relevant skills include medical imaging (DICOM), clinical databases, and data visualization. 100+ scientific databases. | Cursor, Claude Code, Codex, Gemini CLI |

### Key Skills from NeuroAIHub

| Skill | Domain | Description |
|---|---|---|
| `fmri-preprocessing-pipeline-guide` | Neuroimaging | fMRI preprocessing pipeline (fMRIPrep, motion correction, normalization) |
| `fmri-glm-analysis-guide` | Neuroimaging | GLM analysis for task-based fMRI |
| `eeg-preprocessing-pipeline-guide` | Electrophysiology | EEG preprocessing (filtering, ICA, epoching) |
| `calcium-imaging-analysis-guide` | Electrophysiology | Calcium imaging pipeline (motion correction, ROI extraction, spike inference) |
| `drift-diffusion-model` | Cognitive Psychology | DDM selection, fitting, and evaluation for choice-RT data |
| `signal-detection-analysis` | Cognitive Psychology | SDT decision logic, formulas, and interpretation |
| `brain-connectivity-modeler` | Neuroimaging | Functional/effective connectivity: PPI, DCM, Granger causality, graph theory |
| `cognitive-paradigm-design` | Cognitive Psychology | Paradigm selection and parameterization for cognitive experiments |
| `cogsci-power-analysis` | Cross-Domain | Power analysis with effect size priors and sample size recommendations by modality |
| `cogsci-statistics` | Cross-Domain | Mixed models, corrections, Bayesian approaches, effect sizes |
| `cogsci-visualization` | Cross-Domain | Plot selection, color standards, publication formatting |
| `neural-population-analysis-guide` | Neural Coding | Neural population dynamics analysis |
| `act-r-model-builder` | Cognitive Modeling | ACT-R cognitive model construction |
| `bayesian-cognitive-model-builder` | Cognitive Modeling | Hierarchical Bayesian cognitive models with Stan/PyMC |
| `neuropsych-battery-selector` | Clinical Neuropsychology | Neuropsychological test battery selection |

### Awesome Lists & Tool Collections

| Repository | Stars | Description |
|---|---|---|
| [analyticalmonk/awesome-neuroscience](https://github.com/analyticalmonk/awesome-neuroscience) | — | Curated list of neuroscience libraries, software, and resources. Python (Nilearn, MNE-Python, Brian2, DIPY, PsychoPy, BindsNET), MATLAB (EEGLAB, FieldTrip, SPM, BrainStorm), C++ (Brayns). |
| [realamirhe/awesome-computational-neuro-science](https://github.com/realamirhe/awesome-computational-neuro-science) | — | CNS frameworks, libraries, software + pure Python SNN tutorial series. Includes Brian2, NEST, Nengo, BrainCog, BrainPy, Auryn, cuSNN, and more. |
| [awesomelistsio/awesome-neuroscience](https://github.com/awesomelistsio/awesome-neuroscience) | — | Tools, frameworks, datasets, educational resources, and community links for neuroscience. Covers Neural Data Analysis, Brain Simulation, Brain Imaging, BCIs, and Visualization. |

### Key Neuroscience Libraries (Frequently Referenced in Skills)

| Tool | Language | Description |
|---|---|---|
| [MNE-Python](https://github.com/mne-tools/mne-python) | Python | Processing time-resolved neural signals (EEG, MEG) |
| [Nilearn](https://github.com/nilearn/nilearn) | Python | Statistical learning on NeuroImaging data |
| [Brian2](https://github.com/brian-team/brian2) | Python | Simulator for spiking neural networks |
| [NEURON](https://github.com/neuronsimulator/nrn) | Python/C++ | Modeling individual neurons and networks |
| [PsychoPy](https://github.com/psychopy/psychopy) | Python | Running psychology and neuroscience experiments |
| [DIPY](https://github.com/dipy/dipy) | Python | Analysis of MR diffusion imaging |
| [CaImAn](https://github.com/flatironinstitute/CaImAn) | Python | Large-scale calcium imaging data analysis |
| [Suite2p](https://github.com/MouseLand/suite2p) | Python | Cell detection and signal extraction from two-photon calcium imaging |
| [DeepLabCut](https://github.com/DeepLabCut/DeepLabCut) | Python | Markerless pose estimation for animal behavior analysis |
| [AllenSDK](https://github.com/AllenInstitute/AllenSDK) | Python | Accessing Allen Brain Atlas data |
| [PyNWB](https://github.com/NeurodataWithoutBorders/pynwb) | Python | Reading/writing NWB neurophysiology data files |
| [fMRIPrep](https://github.com/nipreps/fmriprep) | Python | Robust preprocessing pipeline for fMRI data |

---

## Brain-Inspired Intelligence & Neuromorphic Computing

Skills and tools for spiking neural networks (SNNs), neuromorphic hardware, brain-inspired cognitive engines, and bio-inspired computation.

### Agent Skills & Frameworks

| Repository | Stars | Description |
|---|---|---|
| [open-neuromorphic/open-neuromorphic](https://github.com/open-neuromorphic/open-neuromorphic) | — | Global community for brain-inspired AI and hardware. Curated guides to SNN frameworks (ML, neuroscience, hybrid), event-based data utilities, and neuromorphic hardware. |
| [artiomn/awesome-neuromorphic](https://github.com/artiomn/awesome-neuromorphic) | — | Curated list of spiking/neuromorphic frameworks, ANN2SNN converters, robotic toolkits, datasets, and computational neuroscience software. |

### SNN Training Frameworks (ML-Oriented)

| Framework | Backend | Description |
|---|---|---|
| [SpikingJelly](https://github.com/fangwei123456/spikingjelly) | PyTorch | Open-source deep learning framework for SNNs (Chinese & English docs) |
| [snnTorch](https://github.com/jeshraghian/snntorch) | PyTorch | SNN training framework focused on gradient-based training |
| [BindsNET](https://github.com/BindsNET/bindsnet) | PyTorch | SNN simulation geared toward ML and reinforcement learning |
| [Norse](https://github.com/norse/norse) | PyTorch | Bio-inspired neural components — sparse, event-driven |
| [Sinabs](https://github.com/synsense/sinabs) | PyTorch | Spiking Convolutional Neural Networks (SCNNs) |
| [Rockpool](https://github.com/synsense/rockpool) | PyTorch/JAX | SNN library with GPU/TPU acceleration, deployable to neuromorphic hardware |
| [Spyx](https://github.com/kmheckel/spyx) | JAX/Haiku | Compact SNN package with JIT compilation for GPUs/TPUs |

### SNN Training Frameworks (Neuroscience-Oriented)

| Framework | Description |
|---|---|
| [Brian2](https://github.com/brian-team/brian2) | Clock-driven simulator for SNNs, designed for flexibility and ease of use |
| [NEST Simulator](https://github.com/nest/nest-simulator) | Simulator for large-scale spiking network models, focused on dynamics and structure |
| [NEURON](https://github.com/neuronsimulator/nrn) | Simulation environment for modeling neurons and networks with high biological detail |
| [NetPyNE](https://github.com/Neurosim-lab/netpyne) | Python package for developing biological neuronal networks using NEURON |

### Brain-Inspired Cognitive Engines

| Framework | Description |
|---|---|
| [BrainCog](https://github.com/BrainCog-X/Brain-Cog) | Brain-inspired cognitive intelligence engine for BIAI and brain simulation |
| [BrainPy](https://github.com/brainpy/BrainPy) | Integrative framework for computational neuroscience and brain-inspired computation (JAX/Numba JIT) |
| [Nengo](https://github.com/nengo/nengo) | Python package for building, testing, and deploying spiking neural networks |
| [NengoDL](https://github.com/nengo/nengo-dl) | Deep learning network simulator for spike-based neural networks |

### Neuromorphic Hardware & Platforms

| Platform | Description |
|---|---|
| [Intel LAVA](https://github.com/lava-nc/lava) | Software framework for neuromorphic computing from Intel (Loihi 2) |
| [HBP Neuromorphic Computing Platform](https://ebrains.eu/) | Part of EBRAINS research infrastructure (Human Brain Project) |
| BrainChip Akida | Commercial neuromorphic NPU |
| Intel Loihi 2 | Research neuromorphic chip |
| SynSense | Commercial neuromorphic intelligence (UZH/ETH spinoff) |

### ANN-to-SNN Converters & Event-Based Data

| Tool | Description |
|---|---|
| [snn_toolbox](https://github.com/deep-computing/snn_toolbox) | Transform rate-based ANNs into SNNs with various spike encodings |
| [Tonic](https://github.com/neuromorphs/tonic) | Download, manipulate, and load event-based/spike-based data (like PyTorch Vision for neuromorphic data) |
| [AEStream](https://github.com/aestream/aestream) | Parse and stream event-based DVS data to GPU/CPU/network |

---

## LLM & AI Research Skills

Skills, tools, and frameworks for AI-assisted research, automated experimentation, model training, and scientific writing.

### Comprehensive Skill Libraries

| Repository | Skills | Stars | Description | Compatibility |
|---|---|---|---|---|
| [anthropics/skills](https://github.com/anthropics/skills) | 17+ | 137k+ | Official Anthropic skills repository. Includes skill-creator, mcp-builder, webapp-testing, docx/pdf/pptx/xlsx, algorithmic-art, canvas-design, and more. Defines the SKILL.md standard. | Claude Code, Claude.ai |
| [K-Dense-AI/scientific-agent-skills](https://github.com/K-Dense-AI/scientific-agent-skills) | 158 | 27.6k | #1 Agent Skills library for science. 158 skills + 100+ databases covering biology, chemistry, medicine, drug discovery, ML, data visualization, lab automation, and scientific communication. | Cursor, Claude Code, Codex, Gemini CLI, Antigravity |
| [armstrongl/AI-research-SKILLs](https://github.com/armstrongl/AI-research-SKILLs) | 54/70 | — | AI research engineering skills: model architecture (LitGPT, Mamba, RWKV, NanoGPT), tokenization, fine-tuning, distributed training, inference, agents, RAG, multimodal. | Claude Code, Codex |
| [lhbzx1984/Light-skills](https://github.com/lhbzx1984/Light-skills) | 28 | — | Full-cycle Chinese research skills (28 skills + 9 knowledge bases). Covers literature review → data → idea → design → experiment → analysis → writing → figures → submission → revision. Anti-hallucination mechanisms. | Claude Code, Codex, OpenCode |
| [InternScience/Awesome-Scientific-Skills](https://github.com/InternScience/Awesome-Scientific-Skills) | — | 500+ | Curated collection of Agent Skills for scientific research from Shanghai AI Lab. Phase 1: link collection; Phase 2: unified directory; Phase 3: composition recipes. | Agent Skills standard |

### Automated Research Systems

| Repository | Stars | Description |
|---|---|---|
| [handsome-rich/Awesome-Auto-Research-Tools](https://github.com/handsome-rich/Awesome-Auto-Research-Tools) | — | Curated list of automated research projects. Covers autonomous research systems (AI-Scientist, RD-Agent, AutoResearchClaw), deep research, experiment execution, academic writing, and peer review. |
| [Karpathy/autoresearch](https://github.com/Karpathy/autoresearch) | — | Andrej Karpathy's minimal GPU research framework. External coding agents modify train.py per program.md, run 5-min nanochat experiments. |
| [SakanaAI/AI-Scientist](https://github.com/SakanaAI/AI-Scientist) | — | First fully automated open-ended scientific discovery system. Idea generation → coding → experiment → paper writing. |
| [microsoft/RD-Agent](https://github.com/microsoft/RD-Agent) | — | Microsoft's automated R&D pipeline — quant factor/model evolution, Kaggle automation, paper-to-code. MLE-bench top agent. |
| [OpenLAIR/dr-claw](https://github.com/OpenLAIR/dr-claw) | — | Super AI Lab with massive AI Doctors as Assistants. Best IDE for Research via AI Power. |
| [OpenRaiser/NanoResearch](https://github.com/OpenRaiser/NanoResearch) | — | Autonomous AI Research Assistant built on OpenClaw. |

### Research Workbenches & Assistants

| Repository | Stars | Description |
|---|---|---|
| [ai4s-research/open-science](https://github.com/ai4s-research/open-science) | — | Local-first, open-source AI research workbench for scientists. Open alternative to Claude Science. Tauri + MCP + agent skills. |
| [K-Dense-AI/K-Dense-BYOK](https://github.com/K-Dense-AI) | 908+ | Free desktop AI research assistant. 149 scientific skills, 326 workflow templates, 229 databases. Bring your own API keys. |
| [Galaxy-Dawn/Claude-Scholar](https://github.com/Galaxy-Dawn/Claude-Scholar) | 4.5k+ | Semi-automated research assistant for academic research and software development. Supports Claude Code, Codex CLI, Kimi Code CLI, OpenCode. |

### LLM Training & Engineering Skills (from armstrongl/AI-research-SKILLs)

| Category | Skills |
|---|---|
| Model Architecture | LitGPT, Mamba, RWKV, NanoGPT, Transformer |
| Tokenization | HuggingFace Tokenizers, SentencePiece |
| Fine-tuning | TRL (PPO/DPO), LoRA/QLoRA, PEFT |
| Data Processing | Datasets, tokenization pipelines, data cleaning |
| Distributed Training | Megatron-LM, DeepSpeed, FSDP |
| Inference | vLLM, TensorRT-LLM, llama.cpp |
| Agents | Tool use, ReAct, multi-agent orchestration |
| RAG | Vector databases, retrieval pipelines, chunking |
| MLOps | Model evaluation, benchmarking, deployment |

---

## Embodied Intelligence & Robotics

Skills, tools, simulators, and frameworks for embodied AI, robot learning, and physical AI.

### Agent Skills & Frameworks

| Repository | Stars | Description |
|---|---|---|
| [aichr/awesome-physical-ai](https://github.com/aichr/awesome-physical-ai) | — | Curated resources for Physical AI — where robotics, ML, and embodied intelligence converge. Foundation Models (VLA), 3D vision, datasets, benchmarks, simulators, edge AI, hardware. |
| [jonzamora/awesome-robot-learning-envs](https://github.com/jonzamora/awesome-robot-learning-envs) | — | List of robot learning environments for Deep RL, Imitation Learning, and Embodied AI. 30+ benchmarks with simulator/visualization info. |
| [gauti1311/awesome-robotics-libraries](https://github.com/gauti1311/awesome-robotics-libraries) | — | Curated list of robotics simulators and libraries. Covers simulators, dynamics, IK, ML, motion planning, SLAM, vision. |

### Foundation Models for Robotics (VLA)

| Model | Description |
|---|---|
| [NVIDIA GR00T](https://github.com/NVIDIA/GR00T) | Foundation model for humanoid robots |
| [Physical Intelligence π0](https://github.com/openpi/openpi) | VLA flow model with 10k+ hours robot data |
| [Octo](https://github.com/octo-models/octo) | Open-source diffusion policy with 800k episodes |
| [RT-2](https://robotics-transformer2.github.io/) | VLA model learning from web and robotics data |
| [PaLM-E](https://palm-e.github.io/) | Embodied multimodal language model |
| [LeRobot](https://github.com/huggingface/lerobot) | End-to-end robot learning framework by HuggingFace |

### Simulators

| Simulator | Physics Engine | Description |
|---|---|---|
| [NVIDIA Isaac Lab](https://github.com/isaac-sim/IsaacLab) | PhysX | GPU-accelerated robot learning, built on Isaac Sim |
| [Genesis](https://github.com/Genesis-Embodied-AI/Genesis) | Custom | Generative world for general-purpose robotics & embodied AI |
| [MuJoCo](https://github.com/google-deepmind/mujoco) | MuJoCo | Multi-Joint Dynamics with Contact (DeepMind) |
| [PyBullet](https://github.com/bulletphysics/bullet) | Bullet | Open-source physics simulation for robotics and DRL |
| [Habitat-Sim](https://github.com/facebookresearch/habitat-sim) | Bullet | High-performance 3D simulator for Embodied AI |
| [SAPIEN](https://github.com/haosulab/SAPIEN) | PhysX | Realistic physics simulation for articulated objects |
| [Gazebo](https://github.com/gazebosim/gz-sim) | ODE/Bullet/DART | Dynamic multi-robot simulator |
| [AI2-THOR](https://github.com/allenai/ai2thor) | Unity | Interaction, navigation, manipulation for household robots |
| [CoppeliaSim](https://www.coppeliarobotics.com/) | V-REP/Bullet | Virtual robot experimentation platform |
| [CARLA](https://github.com/carla-simulator/carla) | Unreal | Open-source simulator for autonomous driving |

### Robot Learning Benchmarks

| Benchmark | Simulator | Description |
|---|---|---|
| [DeepMind Control Suite](https://github.com/deepmind/dm_control) | MuJoCo | Continuous control benchmark |
| [Meta-World](https://github.com/Farama-Foundation/Metaworld) | MuJoCo | Multi-task manipulation |
| [RoboSuite](https://github.com/ARISE-Initiative/robosuite) | MuJoCo | Robot manipulation framework |
| [LIBERO](https://github.com/Lifelong-Robot-Learning/LIBERO) | MuJoCo | Benchmark for robot manipulation |
| [CALVIN](https://github.com/mees/calvin) | PyBullet | Long-horizon multi-task manipulation |
| [ManiSkill](https://github.com/haosulab/ManiSkill) | SAPIEN | GPU-parallelized manipulation benchmark |
| [HumanoidBench](https://github.com/carlosferrarof/HumanoidBench) | MuJoCo | Humanoid robot benchmark |

### Key Datasets

| Dataset | Description |
|---|---|
| [Open X-Embodiment](https://robotics-transformer-x.github.io/) | 1M+ trajectories, 80+ embodiments |
| [BridgeData V2](https://github.com/rail-berkeley/bridge_data_v2) | Large-scale manipulation from Berkeley |
| [DROID](https://github.com/droid-dataset/droid) | Large-scale in-the-wild robot manipulation dataset |

---

## Cross-Domain Research Tools

Tools and skills that span multiple research domains — from literature search to publication.

### Research Workflow Skills

| Repository | Stars | Description |
|---|---|---|
| [pikaqiu2333/Awesome-Vibe-Research](https://github.com/pikaqiu2333/Awesome-Vibe-Research) | — | Open, collaboratively-built repository for AI-assisted scientific research. Collects agents, skills, workflows, tools, and best practices across the full research lifecycle. 9-stage research process map. |
| [ai4s-research/awesome-ai-for-science](https://github.com/ai4s-research/awesome-ai-for-science) | — | Curated list of AI tools, libraries, papers, datasets, and frameworks for scientific discovery — physics, chemistry, biology, materials, and beyond. |
| [handsome-rich/Awesome-Auto-Research-Tools](https://github.com/handsome-rich/Awesome-Auto-Research-Tools) | — | Curated list of automated research open-source projects covering literature review, idea generation, experiment execution, paper writing, and peer review. |

### Literature Search & Management

| Tool | Description |
|---|---|
| [openags/paper-search-mcp](https://github.com/openags/paper-search-mcp) | MCP, CLI, Skills for searching and downloading academic papers from arXiv, PubMed, bioRxiv, etc. |
| [BioMCP](https://github.com/genomoncology/biomcp) | Biomedical MCP server unifying literature search across PubMed/Europe PMC, entity pivoting, Claude Code/Codex integration |
| [Semantic Scholar API](https://api.semanticscholar.org/) | Free academic paper search and citation graph API |

### Scientific Writing & Visualization

| Tool | Description |
|---|---|
| [anthropics/skills — pptx](https://github.com/anthropics/skills/tree/main/skills/pptx) | Create, edit, and analyze PowerPoint presentations |
| [anthropics/skills — docx](https://github.com/anthropics/skills/tree/main/skills/docx) | Word document creation, editing, tracked changes |
| [anthropics/skills — pdf](https://github.com/anthropics/skills/tree/main/skills/pdf) | PDF extraction, creation, merging, splitting, forms |
| [anthropics/skills — xlsx](https://github.com/anthropics/skills/tree/main/skills/xlsx) | Excel spreadsheets, formulas, data analysis, visualization |

### Statistics & Data Analysis

| Skill | Source | Description |
|---|---|---|
| `cogsci-statistics` | NeuroAIHub | Mixed models, corrections, Bayesian approaches, effect sizes |
| `scanpy` | K-Dense | Single-cell RNA-seq analysis |
| `pydeseq2` | K-Dense | Differential expression analysis |
| `database-lookup` | K-Dense | Unified access to 100+ scientific databases |

---

## Awesome Lists & Resource Collections

Meta-collections and awesome-lists that aggregate research tools across domains.

| Repository | Stars | Description |
|---|---|---|
| [pikaqiu2333/Awesome-Vibe-Research](https://github.com/pikaqiu2333/Awesome-Vibe-Research) | — | AI-assisted research: agents, skills, workflows, tools across 9 research stages |
| [ai4s-research/awesome-ai-for-science](https://github.com/ai4s-research/awesome-ai-for-science) | — | AI for Science: tools, libraries, papers, datasets, frameworks |
| [handsome-rich/Awesome-Auto-Research-Tools](https://github.com/handsome-rich/Awesome-Auto-Research-Tools) | — | Automated research: autonomous systems, deep research, experiment, writing, review |
| [analyticalmonk/awesome-neuroscience](https://github.com/analyticalmonk/awesome-neuroscience) | — | Neuroscience libraries, software, and resources |
| [realamirhe/awesome-computational-neuro-science](https://github.com/realamirhe/awesome-computational-neuro-science) | — | Computational neuroscience frameworks and SNN tutorials |
| [open-neuromorphic/open-neuromorphic](https://github.com/open-neuromorphic/open-neuromorphic) | — | Neuromorphic software frameworks and hardware |
| [aichr/awesome-physical-ai](https://github.com/aichr/awesome-physical-ai) | — | Physical AI: robotics, ML, embodied intelligence |
| [jonzamora/awesome-robot-learning-envs](https://github.com/jonzamora/awesome-robot-learning-envs) | — | Robot learning environments and benchmarks |
| [gauti1311/awesome-robotics-libraries](https://github.com/gauti1311/awesome-robotics-libraries) | — | Robotics simulators and libraries |
| [InternScience/Awesome-Scientific-Skills](https://github.com/InternScience/Awesome-Scientific-Skills) | 500+ | Curated Agent Skills for scientific research |

---

## Refresh Guide

This repository supports conversation-triggered refresh. When you say **"refresh"**, the following process runs:

1. **Search**: Scan GitHub, SkillsMP, ClaudSkills, and web for new research skills/repos in the four domains
2. **Deduplicate**: Check against existing entries to avoid duplicates
3. **Categorize**: Assign new entries to the appropriate domain section
4. **Update**: Modify README.md with new entries, update star counts and last-updated dates
5. **Commit**: Push changes with a descriptive commit message

### Manual Refresh

You can also trigger a refresh by running:

```bash
# The refresh is triggered via conversation with WorkBuddy
# Simply say "refresh" and the assistant will execute the full search-update-commit cycle
```

### Refresh Metadata

- **Last refreshed**: 2026-08-07
- **Refresh method**: Conversation-triggered (say "refresh" to WorkBuddy)
- **Search sources**: GitHub search, SkillsMP, ClaudSkills, WebSearch
- **Coverage**: Neuroscience, Brain-Inspired Intelligence, LLM/AI, Embodied Intelligence, Cross-Domain

---

## Contributing

Contributions are welcome! Please see [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

To add a new entry:
1. Check that it's not already listed
2. Determine the appropriate domain category
3. Add it to the relevant table with: repository link, stars, description, compatibility
4. Submit a pull request

### Criteria for Inclusion

- Directly relevant to neuroscience, brain-inspired intelligence, LLMs, or embodied intelligence research
- Open source with clear documentation
- Active maintenance (updated within the last 12 months preferred)
- For skill collections: follows the SKILL.md standard or equivalent

---

## License

[CC0 1.0 Universal](http://creativecommons.org/publicdomain/zero/1.0/) — Public Domain Dedication
