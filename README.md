<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=28&duration=3000&pause=800&color=D97757&center=true&vCenter=true&width=640&lines=Hey%2C+I'm+Rana+%F0%9F%91%8B;I+teach+models+to+read+X-rays.;I+train+LLMs+from+scratch.;I+measure+how+models+fail." alt="Typing intro" />

**B.Tech IT @ Manipal University Jaipur** · vision + language · one GPU at a time

<a href="https://www.linkedin.com/in/rana-rishith-musunuri/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a>
<a href="mailto:ranarishith.24@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white"></a>
<img src="https://komarev.com/ghpvc/?username=rana-rishith&style=for-the-badge&color=D97757&label=Profile+views">

</div>

---

```python
rana = {
    "studying":  "B.Tech Information Technology, MUJ",
    "building":  ["multimodal LLMs", "LMs from scratch", "failure analysis for speech models"],
    "favorite":  "getting cluster-level results out of a single consumer GPU",
    "next":      "MS in AI/ML, Fall 2028",
}
```

---

## 🔬 What I'm building

### 🩻 [Medical Image Captioning](https://github.com/rana-rishith/medical-image-captioning)
> **A radiology captioner trained in 5.5 hours on one RTX 5090.**

Frozen ViT-Base → projection MLP → Phi-2 (2.7B) with LoRA. On 500 ROCOv2 test images:

| BLEU-1 | BLEU-2 | BLEU-3 | BLEU-4 | METEOR | ROUGE-L | CIDEr |
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| 0.1362 | 0.0733 | 0.0361 | 0.0187 | 0.0636 | 0.1638 | 0.1045 |

- Beats DS@BioMed on every metric, edges Kaprov on METEOR, trails CS_Morgan
- Written up for **Springer LNCS** as an efficiency result: one consumer GPU instead of a cluster
- Catches its own mode collapse with a **zeros-gap test**: swap the image for zeros and check whether the captions change. If they don't, the model was never looking.

### 🧭 Failure Direction
> **Speech enhancement fails in two opposite ways. I built a way to tell which one is coming.**

A model either deletes the words or leaves the noise in. My reference-free index separates the two, and I'm now using it to predict the failure from the noisy input alone, including noise types the model never saw. Currently at the go/no-go gate before the prediction stage.

### 🧠 GiWaLM
> **A 125M-parameter language model, built from the tokenizer up.**

Pretrained from scratch on ~1B tokens with a custom 32K BPE tokenizer. No pretrained weights, no shortcuts.

### 🌱 Open source: [EleutherAI lm-evaluation-harness](https://github.com/EleutherAI/lm-evaluation-harness)
Working on [#2256](https://github.com/EleutherAI/lm-evaluation-harness/issues/2256): making the chrF metric configurable.

---

## 💼 Experience

**AI Intern · Wipro** (Data Analytics & AI)
Worked across the GCP stack: Vertex AI, BigQuery, and ML pipelines. Picked up time series, RAG, and LLMOps along the way.

---

## 🛠️ Tech Stack

<p align="left">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white">
  <img src="https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white">
  <img src="https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white">
  <img src="https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white">
  <img src="https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white">
</p>
<p align="left">
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white">
  <img src="https://img.shields.io/badge/HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black">
  <img src="https://img.shields.io/badge/PEFT%2FLoRA-8A2BE2?style=flat-square&logo=pytorch&logoColor=white">
  <img src="https://img.shields.io/badge/RAG-FF6F00?style=flat-square">
  <img src="https://img.shields.io/badge/Computer_Vision-00A67E?style=flat-square&logo=opencv&logoColor=white">
</p>
<p align="left">
  <img src="https://img.shields.io/badge/Google_Cloud-4285F4?style=flat-square&logo=googlecloud&logoColor=white">
  <img src="https://img.shields.io/badge/Vertex_AI-4285F4?style=flat-square&logo=googlecloud&logoColor=white">
  <img src="https://img.shields.io/badge/BigQuery-669DF6?style=flat-square&logo=googlebigquery&logoColor=white">
  <img src="https://img.shields.io/badge/RunPod-6E56CF?style=flat-square">
  <img src="https://img.shields.io/badge/Kaggle-20BEFF?style=flat-square&logo=kaggle&logoColor=white">
</p>
<p align="left">
  <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white">
  <img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black">
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white">
  <img src="https://img.shields.io/badge/n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white">
  <img src="https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white">
  <img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black">
</p>

**📜 Anthropic certified:** Claude Code 101 · MCP · Agent Skills · Subagents

---

## 📊 GitHub

<div align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=rana-rishith&show_icons=true&hide_border=true&title_color=D97757&icon_color=D97757&bg_color=0d1117&text_color=c9d1d9">
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=rana-rishith&layout=compact&hide_border=true&title_color=D97757&bg_color=0d1117&text_color=c9d1d9">
</div>

---

<div align="center">

### 📫 Let's talk

Open to research collaborations, internships, and AI engineering roles in deep learning and multimodal AI.
If you work on vision-language models or evaluation, I'd like to hear from you.

📩 [ranarishith.24@gmail.com](mailto:ranarishith.24@gmail.com) · 🔗 [LinkedIn](https://www.linkedin.com/in/rana-rishith-musunuri/)

</div>
