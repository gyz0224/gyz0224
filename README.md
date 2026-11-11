<p align="center">
  <img src="./assets/portfolio-banner.svg" alt="Yang Gao — Research Portfolio" width="100%" />
</p>

<p align="center">
  <a href="https://doi.org/10.1145/3767308.3836197"><img src="https://img.shields.io/badge/ACM_MM-2026-2563eb?style=flat-square" alt="ACM MM 2026" /></a>
  <img src="https://img.shields.io/badge/Research-Computer_Vision-0f766e?style=flat-square" alt="Computer Vision" />
  <img src="https://img.shields.io/badge/Focus-Multimodal_AI-0e7490?style=flat-square" alt="Multimodal AI" />
  <a href="https://github.com/gyz0224"><img src="https://img.shields.io/badge/GitHub-gyz0224-181717?style=flat-square&logo=github" alt="GitHub" /></a>
</p>

<p align="center">
  <strong>M.S. Student in Artificial Intelligence · Henan University</strong><br />
  Computer Vision · Low-Level Vision · Multimodal Learning
</p>

---

## About

I am a graduate student in Artificial Intelligence at **Henan University**, working on low-level vision and multimodal learning. My research explores how **physical image-formation models** and **semantic representations** can complement each other for robust image restoration.

I am particularly interested in building reproducible vision systems, from unsupervised learning objectives and restoration architectures to multimodal model adaptation and evaluation.

- **Research:** Low-light image enhancement, image dehazing, unified image restoration, multimodal understanding.
- **Methodology:** Retinex theory, atmospheric scattering, semantic priors, self-supervised and unsupervised learning.
- **Current direction:** Vision-language model post-training under complex visual conditions.
- **Looking for:** Computer Vision / Multimodal AI research and algorithm internship opportunities.

## Research Interests

<p>
  <img src="https://img.shields.io/badge/Low--Level_Vision-Image_Restoration-155e75?style=flat-square" alt="Low-Level Vision" />
  <img src="https://img.shields.io/badge/Physics--Informed_Learning-Retinex_·_ASM-155e75?style=flat-square" alt="Physics-Informed Learning" />
  <img src="https://img.shields.io/badge/Vision--Language_Models-CLIP_·_VLM-155e75?style=flat-square" alt="Vision-Language Models" />
  <img src="https://img.shields.io/badge/Model_Post--Training-SFT_·_Preference_Optimization-155e75?style=flat-square" alt="Model Post-Training" />
</p>

## Selected Publication

**Bridging Physical and Semantic Knowledge: A Dual-Prior Driven Unsupervised Network for Low-Light Image Enhancement**

- **Venue:** ACM Multimedia 2026 · Poster
- **Authors:** Yonghua Zhang, Yang Gao, Shuo Zhang, Ziqing Huang
- **Paper:** [ACM Digital Library](https://dl.acm.org/doi/10.1145/3767308.3836197) · [DOI: 10.1145/3767308.3836197](https://doi.org/10.1145/3767308.3836197)
- **Implementation:** [SPS-Net](https://github.com/gyz0224/SPS-Net)

<p align="center">
  <img src="https://raw.githubusercontent.com/gyz0224/SPS-Net/main/figs/SPS-Net.png" alt="SPS-Net architecture" width="88%" />
</p>
<p align="center"><sub>SPS-Net: Retinex-based physical priors and CLIP semantic representations for unsupervised low-light image enhancement.</sub></p>

## Featured Research Projects

<table>
  <tr>
    <td width="33%" valign="top">
      <h3>01 · SPS-Net</h3>
      <p><strong>Physical–Semantic Dual-Prior Low-Light Enhancement</strong></p>
      <p>An unsupervised low-light image enhancement network that integrates Retinex-based physical knowledge with semantic representations from a frozen CLIP encoder.</p>
      <p><strong>Key components</strong><br />PAFM · Illumination-Guided Attention · Semantic-Guided Attention</p>
      <p><a href="https://github.com/gyz0224/SPS-Net">Code</a> · <a href="https://doi.org/10.1145/3767308.3836197">Paper</a></p>
      <p><img src="https://img.shields.io/badge/ACM_MM-2026-2563eb?style=flat-square" alt="ACM MM 2026" /></p>
    </td>
    <td width="33%" valign="top">
      <h3>02 · Zero-Multi</h3>
      <p><strong>Zero-Reference Multi-Prior Image Enhancement</strong></p>
      <p>A multi-prior low-light enhancement framework exploring depth, semantic, and luminance cues, together with teacher–student distillation for lightweight prior transfer.</p>
      <p><strong>Key components</strong><br />Multi-Prior Guidance · Teacher–Student Distillation · Lightweight Student</p>
      <p><a href="https://github.com/gyz0224/Zero-Multi">Code</a> · <a href="https://github.com/gyz0224/Zero-Multi/blob/master/figs/Zero-Multi.pdf">Method Overview</a></p>
      <p><img src="https://img.shields.io/badge/Task-Low--Light_Enhancement-0f766e?style=flat-square" alt="Low-Light Enhancement" /></p>
    </td>
    <td width="33%" valign="top">
      <h3>03 · UniSPS</h3>
      <p><strong>Unified Unsupervised Image Restoration</strong></p>
      <p>A unified framework for low-light enhancement and image dehazing, sharing semantic representations while retaining task-specific physical models.</p>
      <p><strong>Key components</strong><br />Retinex Model · Atmospheric Scattering Model · Shared Semantics</p>
      <p><a href="https://github.com/gyz0224/UniSPS">Code</a> · <a href="https://github.com/gyz0224/UniSPS/blob/main/docs/TRAINING_PIPELINE.md">Training Pipeline</a></p>
      <p><img src="https://img.shields.io/badge/Task-Unified_Restoration-0f766e?style=flat-square" alt="Unified Restoration" /></p>
    </td>
  </tr>
</table>

## Additional Research & Engineering

| Project | Focus | Repository |
|:--|:--|:--|
| **SIMI Rebuild** | Modular bit-plane-based image enhancement and denoising framework, including enhancement, denoising, and joint training workflows. | [Code](https://github.com/gyz0224/SIMI_rebuild) |
| **SIMI Frequency** | Bit-plane and frequency-domain interaction studies for image restoration. | [Code](https://github.com/gyz0224/SIMI_rebuild_Freq) |
| **Self-DACE++** | Adaptive curve estimation for robust low-light image enhancement. | [Code](https://github.com/gyz0224/Self-DACEplusplus) |

## Multimodal Learning

**RobustVLM · Ongoing Research**

Exploring multimodal understanding under complex visual conditions, with an emphasis on:

- Multimodal data construction and quality control.
- Vision-language model supervised fine-tuning (SFT).
- Preference optimization and post-training.
- Consistent evaluation across challenging visual scenarios.

## Technical Stack

<p>
  <strong>Deep Learning & Vision</strong><br />
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" alt="PyTorch" />
  <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white" alt="OpenCV" />
  <img src="https://img.shields.io/badge/CUDA-76B900?style=flat-square&logo=nvidia&logoColor=white" alt="CUDA" />
  <img src="https://img.shields.io/badge/CLIP-412991?style=flat-square" alt="CLIP" />
  <img src="https://img.shields.io/badge/Transformers-FFD21E?style=flat-square&logo=huggingface&logoColor=black" alt="Transformers" />
</p>
<p>
  <strong>Development & Research Tools</strong><br />
  <img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black" alt="Linux" />
  <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" alt="Git" />
  <img src="https://img.shields.io/badge/LaTeX-008080?style=flat-square&logo=latex&logoColor=white" alt="LaTeX" />
  <img src="https://img.shields.io/badge/Hugging_Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black" alt="Hugging Face" />
</p>

## GitHub

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=gyz0224&show_icons=true&hide_border=true&rank_icon=github&theme=transparent" alt="GitHub statistics" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=gyz0224&layout=compact&langs_count=8&hide_border=true&theme=transparent" alt="Top languages" />
</p>
<p align="center">
  <img src="https://streak-stats.demolab.com?user=gyz0224&hide_border=true&theme=transparent" alt="GitHub contribution streak" />
</p>

---

<p align="center">
  <strong>Researching better visual perception through physical knowledge and multimodal intelligence.</strong><br />
  <a href="https://github.com/gyz0224">GitHub</a> ·
  <a href="https://doi.org/10.1145/3767308.3836197">ACM MM 2026 Paper</a>
</p>
