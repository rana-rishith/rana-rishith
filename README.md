<h1 align="center">Hey, I'm Rana 👋</h1>

<p align="center">
B.Tech Information Technology @ Manipal University Jaipur<br>
I train models at the intersection of vision and language — and I write about it too.
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/rana-rishith-musunuri/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a>
  <a href="mailto:ranarishith.24@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white"></a>
</p>

---

### 🔬 What I'm building

**🩻 Medical Image Captioning** — Frozen ViT-Base → projection MLP → Phi-2 (2.7B) with LoRA, trained in 5.5 hours on one RTX 5090. Evaluated on 500 ROCOv2 images:

| BLEU-1 | BLEU-2 | BLEU-3 | BLEU-4 | METEOR | ROUGE-L | CIDEr |
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| 0.1362 | 0.0733 | 0.0361 | 0.0187 | 0.0636 | 0.1638 | 0.1045 |

Beats DS@BioMed on every metric, edges Kaprov on METEOR, trails CS_Morgan. Written up for Springer LNCS as an efficiency result: one consumer GPU instead of a cluster. Also documents a mode-collapse failure mode, caught with a zeros-gap test that checks whether the model is really using the image.

**🧭 Failure Direction** — Speech enhancement fails two opposite ways: deletes the words, or leaves the noise. I built a reference-free index that tells the two apart and now use it to predict, from the noisy input alone, which failure a model will hit — even on unseen noise. Currently at the go/no-go gate before the prediction stage.

**🧠 GiWaLM** — 125M-parameter language model, pretrained from scratch on ~1B tokens with a custom 32K BPE tokenizer.

---

### 💼 Experience

**Ex-AI Intern, Wipro** — Data Analytics & AI team, working across the GCP stack: Vertex AI, BigQuery, and scalable ML pipelines. Picked up Time Series, RAG, and LLMOps along the way, plus a stack of Anthropic Claude certifications (Claude Code 101, MCP, Agent Skills, Subagents).

---

### 🛠️ Tech Stack

**💻 Languages**
<p align="left">
  <img src="https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white">
  <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white">
  <img src="https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white">
</p>

**🧠 AI • Deep Learning • NLP**
<p align="left">
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white">
  <img src="https://img.shields.io/badge/HuggingFace-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black">
  <img src="https://img.shields.io/badge/PEFT%2FLoRA-8A2BE2?style=for-the-badge&logo=pytorch&logoColor=white">
  <img src="https://img.shields.io/badge/RAG-FF6F00?style=for-the-badge&logo=databricks&logoColor=white">
  <img src="https://img.shields.io/badge/Computer_Vision-00A67E?style=for-the-badge&logo=opencv&logoColor=white">
</p>

**☁️ Cloud & MLOps**
<p align="left">
  <img src="https://img.shields.io/badge/Google_Cloud-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white">
  <img src="https://img.shields.io/badge/Vertex_AI-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white">
  <img src="https://img.shields.io/badge/BigQuery-669DF6?style=for-the-badge&logo=googlebigquery&logoColor=white">
  <img src="https://img.shields.io/badge/RunPod-6E56CF?style=for-the-badge&logo=runpod&logoColor=white">
</p>

**⚙️ Tools & Automation**
<p align="left">
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white">
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white">
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black">
  <img src="https://img.shields.io/badge/n8n-EA4B71?style=for-the-badge&logo=n8n&logoColor=white">
  <img src="https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white">
  <img src="https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white">
</p>

**🎨 Frontend**
<p align="left">
  <img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black">
</p>

**Where I spend my time:** multimodal LLMs, parameter-efficient fine-tuning, AI automation, computer vision, NLP.

---

### 📜 Certifications

<p align="left">
  <img src="https://img.shields.io/badge/Claude_Code_101-D97757?style=for-the-badge&logo=anthropic&logoColor=white">
  <img src="https://img.shields.io/badge/MCP-D97757?style=for-the-badge&logo=anthropic&logoColor=white">
  <img src="https://img.shields.io/badge/Agent_Skills-D97757?style=for-the-badge&logo=anthropic&logoColor=white">
  <img src="https://img.shields.io/badge/Subagents-D97757?style=for-the-badge&logo=anthropic&logoColor=white">
</p>

Anthropic certifications earned during my Wipro internship, alongside coursework in Time Series, RAG, and LLMOps.

---

### 📫 Open to

Research collaborations, technical internships, and AI engineering roles in deep learning and multimodal AI.

<p align="center">
📩 <a href="mailto:ranarishith.24@gmail.com">ranarishith.24@gmail.com</a> &nbsp;|&nbsp; 🔗 <a href="https://www.linkedin.com/in/rana-rishith-musunuri/">LinkedIn</a>
</p>
