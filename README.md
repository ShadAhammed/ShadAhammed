<p align="center">
  <img src="https://raw.githubusercontent.com/ShadAhammed/ShadAhammed/main/assets/github-profile-hero.jpg" width="100%" alt="Shad Ahammed - AI Scientist and Engineer">
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/ShadAhammed/ShadAhammed/main/assets/skills/python.png" height="48" alt="Python" />
  <img src="https://raw.githubusercontent.com/ShadAhammed/ShadAhammed/main/assets/skills/cpp.png" height="48" alt="C++" />
  <img src="https://raw.githubusercontent.com/ShadAhammed/ShadAhammed/main/assets/skills/pytorch.png" height="48" alt="PyTorch" />
  <img src="https://raw.githubusercontent.com/ShadAhammed/ShadAhammed/main/assets/skills/tensorflow.png" height="48" alt="TensorFlow" />
  <img src="https://raw.githubusercontent.com/ShadAhammed/ShadAhammed/main/assets/skills/opencv.png" height="48" alt="OpenCV" />
  <img src="https://raw.githubusercontent.com/ShadAhammed/ShadAhammed/main/assets/skills/langchain.png" height="48" alt="LangChain" />
  <img src="https://raw.githubusercontent.com/ShadAhammed/ShadAhammed/main/assets/skills/langgraph.png" height="48" alt="LangGraph" />
  <img src="https://raw.githubusercontent.com/ShadAhammed/ShadAhammed/main/assets/skills/claude.png" height="48" alt="Claude" />
  <img src="https://raw.githubusercontent.com/ShadAhammed/ShadAhammed/main/assets/skills/gemini.png" height="48" alt="Gemini" />
  <img src="https://raw.githubusercontent.com/ShadAhammed/ShadAhammed/main/assets/skills/openai.png" height="48" alt="OpenAI" />
  <img src="https://raw.githubusercontent.com/ShadAhammed/ShadAhammed/main/assets/skills/ollama.png" height="48" alt="Ollama" />
  <img src="https://raw.githubusercontent.com/ShadAhammed/ShadAhammed/main/assets/skills/aws.png" height="48" alt="AWS" />
  <img src="https://raw.githubusercontent.com/ShadAhammed/ShadAhammed/main/assets/skills/docker.png" height="48" alt="Docker" />
  <img src="https://raw.githubusercontent.com/ShadAhammed/ShadAhammed/main/assets/skills/fastapi.png" height="48" alt="FastAPI" />
  <img src="https://raw.githubusercontent.com/ShadAhammed/ShadAhammed/main/assets/skills/esp32.png" height="48" alt="ESP32" />
  <img src="https://raw.githubusercontent.com/ShadAhammed/ShadAhammed/main/assets/skills/jetson.png" height="48" alt="NVIDIA Jetson" />
  <img src="https://raw.githubusercontent.com/ShadAhammed/ShadAhammed/main/assets/skills/ros2.png" height="48" alt="ROS 2" />
  <img src="https://raw.githubusercontent.com/ShadAhammed/ShadAhammed/main/assets/skills/github.png" height="48" alt="GitHub" />
</p>

<p align="center">
  <a href="https://github.com/ShadAhammed"><img src="https://img.shields.io/badge/GitHub-ShadAhammed-0B0F14?style=flat&labelColor=161B22&color=C48C4B" alt="GitHub"></a>
  <a href="https://github.com/ShadAhammed?tab=repositories"><img src="https://img.shields.io/badge/Projects-18+-0B0F14?style=flat&labelColor=161B22&color=4A6FA5" alt="Projects"></a>
  <img src="https://img.shields.io/badge/Based_in-Siegen%2C_Germany-0B0F14?style=flat&labelColor=161B22&color=3A4A5C" alt="Location">
</p>

<p align="center"><code>AI Scientist &amp; Engineer · University of Siegen</code></p>

I am an AI Scientist and Engineer working at the intersection of AI research, software engineering, and real-world deployment. I build complete AI systems rather than isolated models, from local LLM and agentic applications to RAG pipelines, explainable ML tools, and Edge AI systems.

My focus is on turning ideas into software that can actually run. I care about the engineering around the model: architecture, data flow, evaluation, interfaces, resource constraints, and reliable integration. Much of my recent work is local-first, exploring how capable AI systems can run on personal or edge hardware while keeping data under the user's control.

---

## What I Build

- **On-device and Edge AI** assistants that combine speech, vision and domain knowledge without depending on a cloud LLM API
- **Agentic AI workflows** where specialized agents exchange typed artifacts and stop cleanly when inputs are missing
- **RAG and grounded generation** for manuals, manuscripts and project-specific context
- **ML engineering tools** for training, explainability, model comparison and residual analysis
- **Embedded AI** work across FPGA and microcontroller contexts from earlier research

---

## Selected Projects

### [Rex](https://github.com/ShadAhammed/Rex)
Local in-car assistant with wake-word speech, hybrid vision, health context and grounded Q&A over a car owner's manual. FastAPI modules run on dedicated ports with a workload-aware GPU policy so Whisper, YOLO and Ollama do not fight each other.

### [ExplainAI](https://github.com/ShadAhammed/ExplainAI)
Streamlit pipeline that trains tabular classifiers, explains misclassifications with SHAP driver scores, and uses a local LLM to propose hyperparameters you can apply and retrain. Built for the common loop of "metrics look fine, but why did these rows fail?"

### [WriteGuide](https://github.com/ShadAhammed/WriteGuide)
Local-first academic writing studio. Deterministic code handles project storage, manuscript import and section extraction. AI is used for section review and rewrite jobs with structured JSON and scoped MCP tool access to project context.

### [WebMaker](https://github.com/ShadAhammed/WebMaker)
Local Windows workflow that crawls a public business site, analyzes it with AI agents, and builds a reviewable WordPress demo before anything reaches a client production server. Agents do not call each other. They read upstream artifacts and write new ones.

### [DemandPulse-Transportation](https://github.com/ShadAhammed/DemandPulse-Transportation)
Transportation demand forecasting on arbitrary tabular mobility data. Schema roles and task type are inferred from the upload, an XGBoost variant is selected automatically, and a local LLM writes an operations-facing briefing.

### [EpilepsyDetector](https://github.com/ShadAhammed/EpilepsyDetector)
Packaged EEG seizure detection pipeline for EDF recordings: per-second features, classifier inference, merged ictal intervals, plus CLI, Streamlit and optional FastAPI surfaces. Clinical data and model weights stay out of the repository.

### [Cursorrules-Shad](https://github.com/ShadAhammed/Cursorrules-Shad)
Opinionated Cursor engineering rules with a `crs apply` CLI. Security, code quality, testing, data safety and AI execution policy ship as modular rule files you can drop into any project.

### [TuneAI](https://github.com/ShadAhammed/TuneAI)
Automated comparison of multiple classifiers on the same Excel dataset, with hyperparameter search and a side-by-side performance dashboard. Born from doctoral work where repeating the same grid-search loop by hand stopped being useful.

---

## Technology

**AI & Machine Learning**  
LLMs · Generative AI · RAG · Agentic AI · Computer Vision · YOLO · Speech AI · Classical ML · SHAP / XAI · Model Evaluation

**AI Engineering & Frameworks**  
Python · LangChain · LangGraph · MCP · Ollama · OpenAI · Gemini · Claude · PyTorch · TensorFlow · scikit-learn

**AI Applications & APIs**  
FastAPI · REST APIs · API Integration · Streamlit ·

**Cloud & Deployment**  
AWS · Docker · GitHub/GitLab · Model Deployment · AI/ML Pipelines · Local-first Systems

**Edge & Embedded AI**  
Edge AI · On-device Inference · TinyML · ESP32-P4 / ESP32-S3 · NVIDIA Jetson · Raspberry Pi · FPGA (Xilinx) · VHDL

**Software Engineering**  
Python · Git · Modular Architecture · Testing · Automation · Data Pipelines

---

## Background

My background is in embedded systems, machine learning and AI engineering, with research experience spanning healthcare AI, wearable sensing, FPGA-based ML, TinyML, computer vision and speech recognition.

More recently, my work has moved toward LLMs, RAG, agentic AI and local-first software systems. I build complete applications around these technologies, combining models with data pipelines, APIs, interfaces and deployment constraints rather than treating AI as an isolated model.

I am particularly interested in the space where **AI research becomes usable software**.

---

## Elsewhere

- GitHub: [github.com/ShadAhammed](https://github.com/ShadAhammed)
- Academic contact from published project docs: abu.ahammed@uni-siegen.de
