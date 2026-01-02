# Hi there :) I'm Dongkon (DK) Lee

Neuroengineering + applied ML systems — I build closed-loop pipelines that turn neural signals into actionable feedback, and ship software tools around them.

**Current focus:** brain–computer interfaces, in-vitro electrophysiology + MEA workflows, RL/3D vision for connectomics QA, and agentic LLM systems for clinical decision support.

---

## 🧠 Neuroengineering / Research
- **Fu Lab (Bio-Electronics, Princeton)** — automated **closed-loop training** for in-vitro networks with **HD-MEA** + BrainDance  
  - Replaced manual stimulation protocols with real-time orchestration → **80% lower experimental latency**
  - Built low-level signal processing pipeline → **+25% neural signal fidelity**
- **Seung Lab (Connectomics, Princeton Neuroscience Institute)** — RL for 3D segmentation error correction  
  - Cut manual tracing review → **90% reduction** using Deep-Q / PPO pipeline  
  - Generated large-scale imitation learning data via multi-instance **Neuroglancer** orchestration  
  - Improved generalization → **+50%** with LR scheduling + 3D augmentation

---

## 🚀 Cool things I’ve built
- **[PeerPear](https://github.com/smkim0508/PeerPear)** — centralized, LLM-powered group pairing platform for student organizations  
  - Matches “bigs/littles” or mentors/mentees by collecting preferences and running an LLM-assisted grouping + compatibility workflow, then gives orgs a single dashboard to manage pairings and exports  
  - Live demo: https://peerpear.vercel.app/
- **[PeriMind](https://perimind.ai/) ([GitHub](https://github.com/decaylee13/perimind))** — multi-agent AI assistant for intra-operative anesthesiology support  
  - Ingests perioperative patient context and clinical guidelines to generate structured assessments and anesthesia/treatment recommendations via an orchestrated multi-agent workflow  
  - Deployed clinical reasoning system → **95% accuracy** and **~2.1s latency**  
  - Reduced GPU memory **35%** + inference time **45%** via quantization/pruning
- **[PUnC Verilog Processor](https://github.com/decaylee13/verilog-punc-processor)** — synthesizable 16-bit LC3-style stored-program CPU for FPGA deployment  
  - Implemented full fetch–decode–execute control with modular datapath + control unit in Verilog (unpipelined for reliability)  
  - Built 128-entry memory (async read / sync write) and an 8-register (R0–R7) register file with condition codes (N/Z/P) and subroutine support (R7)  
  - Supports core LC3 instruction subset: arithmetic (ADD/AND), memory ops (LD/LDI/LDR/LEA/ST/...), control flow (BR/JMP/JSR/RET), and HALT
- **[LLM_Proofreading_Agent](https://github.com/decaylee13/LLM_Proofreading_Agent)** — benchmarking LLM proofreading performance through NeuroGlancer-style workflows
- **Wafer Defect Segmentation (Kulite Semiconductors)**  
  - Fine-tuned **SAM + YOLO** on 10k+ images → **96% mIoU**  
  - Optimized YOLO inference pipeline → **+80% throughput**  
  - Automated **100GB+** preprocessing pipeline with AWS S3/EC2 + Python


---

## 🤝 Connect
- Website: https://decaylee13.github.io/
- Email: dl2635@princeton.edu
