---
permalink: /
title: "👋 About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<style>
  /* 控制 Experience 区块公司 logo 大小和对齐 */
  .exp-logo {
    height: 1.15em;            /* 略大于文字 */
    width: auto;
    vertical-align: -0.2em;    /* 与文字基线对齐微调 */
    margin-right: 6px;
  }
</style>

I am currently a final-year Master's student in Computer Technology at *Tsinghua University*, under the supervision of *Prof. Chun Yuan*. I obtained my Bachelor's degree in Computer Science and Technology from the *Yingcai Honors College at the University of Electronic Science and Technology of China* in 2023, where I was fortunate to be advised by *Prof. Xile Zhao*.  

I am currently working as a *Research Assistant* at *MMLab, The Chinese University of Hong Kong (CUHK)*, under the supervision of *Prof. Tianfan Xue*.

My research interests lie in *Computer Vision*, particularly in *image and video generation*.


[Email](mailto:zhuangjh23@mails.tsinghua.edu.cn) / [GitHub](https://github.com/zhuang2002)

---
# ✨ News
---
* <span style="font-size: smaller;">2025-09: One paper is accepted to [NeurIPS 2025](https://neurips.cc/)</span>
* <span style="font-size: smaller;">2025-04: Two papers are accepted to [SIGGRAPH 2025](https://www.siggraph.org/siggraph-events/conferences/)</span>
* <span style="font-size: smaller;">2024-12: One paper is accepted to [ICASSP 2025](https://2025.ieeeicassp.org/important-dates/)</span>
* <span style="font-size: smaller;">2024-07: One paper is accepted to [ECCV 2024](https://eccv.ecva.net/)</span>
* <span style="font-size: smaller;">2022-06: One paper is accepted to [ACM MM 2022](https://2022.acmmm.org/)</span>

---
# 🔬 Research
---
\* indicates equal contribution
<table style="width:100%;border:0px;border-spacing:0px;border-collapse:separate;margin-right:auto;margin-left:auto;"><tbody>	

<!--FlashVSR-->
<tr>
  <td style="padding:20px;width:30%;max-width:30%" align="center">
    <img style="width:100%;max-width:100%" src="https://zhuang2002.github.io/FlashVSR/flowchart.jpg" alt="dise">
  </td>
  <td width="75%" valign="center">
    <papertitle>FlashVSR: Towards Real-Time Diffusion-Based Streaming Video Super-Resolution</papertitle>
    <br>
    <b>Junhao Zhuang</b>, Shi Guo, Xin Cai, Xiaohui Li, Yihao Liu, Chun Yuan and Tianfan Xue
    <br>
    <em>arXiv preprint arXiv:2510.12747 2025</em>
    <br>
    <a href="https://arxiv.org/abs/2510.12747">[PDF]</a> 
    <a href="https://zhuang2002.github.io/FlashVSR/">[Project Page]</a>
    <a href="https://github.com/OpenImagingLab/FlashVSR">[Code]</a>
    <br>
    <p> FlashVSR is a streaming, one-step diffusion-based video super-resolution framework with block-sparse attention and a Tiny Conditional Decoder. It reaches ~17 FPS at 768×1408 on a single A100 GPU. A Locality-Constrained Attention design further improves generalization and perceptual quality on ultra-high-resolution videos.</p>
  </td>
</tr>	

<!--Cobra-->
<tr>
  <td style="padding:20px;width:30%;max-width:30%" align="center">
    <img style="width:100%;max-width:100%" src="../images/cobra.png" alt="dise">
  </td>
  <td width="75%" valign="center">
    <papertitle>Cobra: Efficient Line Art COlorization with BRoAder References</papertitle>
    <br>
    <b>Junhao Zhuang</b>, Lingen Li, Xuan Ju, Zhaoyang Zhang, Chun Yuan and Ying Shan
    <br>
    <em>ACM SIGGRAPH (<strong>SIGGRAPH</strong>), 2025</em>
    <br>
    <a href="https://arxiv.org/abs/2504.12240">[PDF]</a> 
    <a href="https://zhuang2002.github.io/Cobra/">[Project Page]</a>
    <a href="https://github.com/Zhuang2002/Cobra">[Code]</a>
    <br>
    <p> Cobra is a novel efficient long-context fine-grained ID preservation framework for line art colorization, achieving high precision, efficiency, and flexible usability for comic colorization. By effectively integrating extensive contextual references, it transforms black-and-white line art into vibrant illustrations.</p>
  </td>
</tr>	

<!--FlexiAct-->
<tr>
  <td style="padding:20px;width:30%;max-width:30%" align="center">
    <img style="width:100%;max-width:100%" src="../images/method.jpg" alt="dise">
  </td>
  <td width="75%" valign="center">
    <papertitle>FlexiAct: Towards Flexible Action Control in Heterogeneous Scenarios</papertitle>
    <br>
    Shiyi Zhang*, <b>Junhao Zhuang*</b>, Zhaoyang Zhang, Yansong Tang
    <br>
    <em>ACM SIGGRAPH (<strong>SIGGRAPH</strong>), 2025</em>
    <br>
    <a href="https://arxiv.org/abs/2505.03730">[PDF]</a> 
    <a href="https://shiyi-zh0408.github.io/projectpages/FlexiAct/">[Project Page]</a>
    <a href="https://github.com/shiyi-zh0408/FlexiAct">[Code]</a>
    <br>
    <p> We achieve action transfer in heterogeneous scenarios with varying spatial structures or cross-domain subjects.</p>
  </td>
</tr>	

<!--PowerPaint-->
<tr>
  <td style="padding:20px;width:30%;max-width:30%" align="center">
    <img style="width:100%;max-width:100%" src="../images/ppt.png" alt="dise">
  </td>
  <td width="75%" valign="center">
    <papertitle>A Task is Worth One Word: Learning with Task Prompts for High-Quality Versatile Image Inpainting</papertitle>
    <br>
    <b>Junhao Zhuang</b>, Yanhong Zeng, Wenran Liu, Chun Yuan, Kai Chen
    <br>
    <em>European Conference on Computer Vision (<strong>ECCV</strong>)</em>, 2024
    <br>
    <a href="https://arxiv.org/abs/2312.03594">[PDF]</a>
    <a href="https://powerpaint.github.io/">[Project Page]</a> 
    <a href="https://github.com/open-mmlab/PowerPaint">[Code]</a>
    <br>
    <p> PowerPaint is the first versatile image inpainting model that simultaneously achieves state-of-the-art results in various inpainting tasks such as text-guided object inpainting, context-aware image inpainting, shape-guided object inpainting with controllable shape-fitting, and outpainting.</p>
  </td>
</tr>	

<!--UConNet-->
<tr>
  <td style="padding:20px;width:30%;max-width:30%" align="center">
    <img style="width:100%;max-width:100%" src="../images/uconnet.png" alt="dise">
  </td>
  <td width="75%" valign="center">
    <papertitle>UConNet: Unsupervised controllable network for image and video deraining</papertitle>
    <br>
    <b>Junhao Zhuang</b>, Yisi Luo, Xile Zhao, Taixiang Jiang, Bichuan Guo
    <br>
    <em>ACM Multimedia Conference (<strong>ACM MM</strong>)</em>, 2022
    <br>
    <a href="https://dl.acm.org/doi/10.1145/3503161.3547772">[PDF]</a>
    <a href="https://github.com/zhuang2002/UConNet">[Code]</a> 
    <br>
    <p> We propose the UConNet for image and video deraining. Our UConNet learns a relationship between trade-off parameters of the loss function and weightings of feature maps. At the inference stage, the weightings can be adaptively controlled to handle different rain scenarios, resulting in high generalization abilities. Extensive experimental results validate the effectiveness, generalization abilities, and efficiency of UConNet. </p>
  </td>
</tr>	

<!--TextureDiffusion-->
<tr>
  <td style="padding:20px;width:30%;max-width:30%" align="center">
    <img style="width:100%;max-width:100%" src="../images/icassp.png" alt="dise">
  </td>
  <td width="75%" valign="center">
    <papertitle>TextureDiffusion: Target Prompt Disentangled Editing for Various Texture Transfer</papertitle>
    <br>
    Zihan Su, <b>Junhao Zhuang</b>, Chun Yuan
    <br>
    <em>International Conference on Acoustics, Speech, and Signal Processing (<strong>ICASSP</strong>), 2024, Oral</em>
    <br>
    <a href="https://arxiv.org/pdf/2409.09610">[PDF]</a>
    <a href="https://github.com/THU-CVML/TextureDiffusion">[Code]</a> 
    <br>
    <p> We proposed TextureDiffusion, a tuning-free image editing method applied to various texture transfer. </p>
  </td>
</tr>	

<!--ColorFlow-->
<tr>
  <td style="padding:20px;width:30%;max-width:30%" align="center">
    <img style="width:100%;max-width:100%" src="../images/colorflow.png" alt="dise">
  </td>
  <td width="75%" valign="center">
    <papertitle>ColorFlow: Retrieval-Augmented Image Sequence Colorization</papertitle>
    <br>
    <b>Junhao Zhuang*</b>, Xuan Ju*, Zhaoyang Zhang, Yong Liu, Shiyi Zhang, Chun Yuan, Ying Shan
    <br>
    <em>arXiv preprint arXiv:2412.11815, 2024</em>
    <br>
    <a href="https://arxiv.org/abs/2412.11815">[PDF]</a>
    <a href="https://zhuang2002.github.io/ColorFlow/">[Project Page]</a> 
    <a href="https://github.com/TencentARC/ColorFlow">[Code]</a>
    <br>
    <p> ColorFlow is the first model designed for fine-grained ID preservation in image sequence colorization, utilizing contextual information. Given a reference image pool, ColorFlow accurately generates colors for various elements in black and white image sequences, including the hair color and attire of characters, ensuring color consistency with the reference images.  </p>
  </td>
</tr>	

<!--Safe-Sora-->
<tr>
  <td style="padding:20px;width:30%;max-width:30%" align="center">
    <img style="width:100%;max-width:100%" src="../images/safesora.png" alt="dise">
  </td>
  <td width="75%" valign="center">
    <papertitle>Safe-Sora: Safe Text-to-Video Generation via Graphical Watermarking</papertitle>
    <br>
    Zihan Su, Xuerui Qiu, Hongbin Xu, Tangyu Jiang, <b>Junhao Zhuang</b>, Chun Yuan, Ming Li, Shengfeng He, Fei Richard Yu
    <br>
    <em>Neural Information Processing Systems (<strong>NeurIPS</strong>), 2025</em>
    <br>
    <a href="https://arxiv.org/pdf/2505.12667">[PDF]</a> 
    <a href="https://sugewud.github.io/Safe-Sora-project/">[Project Page]</a>
    <a href="https://github.com/Sugewud/Safe-Sora">[Code]</a>
    <br>
    <p> Safe-Sora: a framework for embedding graphical watermarks into video generation, achieving state-of-the-art quality, fidelity, and robustness through hierarchical adaptive matching and a 3D wavelet-enhanced Mamba architecture.</p>
  </td>
</tr>	

</tbody></table>

---

# 💼 Experience
---

- **Kuaishou / KlingAI** — *Research Intern*  
  Shenzhen, China · Sep 2025 – Present  
  ◦ Supervisor: [Xintao Wang](https://xinntao.github.io/) · Topics: Video Generation

- **Shanghai Artificial Intelligence Laboratory** — *Research Intern*  
  Shanghai, China · May 2025 – Sep 2025
  ◦ Supervisor: [Shi Guo](https://guoshi28.github.io/), [Tianfan Xue](https://tianfan.info/) · Topics: Video Super-Resolution, Diffusion Acceleration, Sparse Attention

- **Tencent, ARC Lab** — *Research Intern*  
  Shenzhen, China · May 2024 – Apr 2025
  ◦ Supervisors: [Zhaoyang Zhang](https://zzyfd.github.io/#/), [Ying Shan](https://scholar.google.com/citations?user=4oXBp9UAAAAJ&hl=en) · Topics: Comic Colorization, Video Generation, Diffusion Model

- **Shanghai Artificial Intelligence Laboratory** — *Research Intern*  
  Shanghai, China · Jul 2023 – Feb 2024  
  ◦ Supervisors: [Yanhong Zeng](https://zengyh1900.github.io/), [Kai Chen](https://scholar.google.com/citations?user=eGD0b7IAAAAJ&hl=en&oi=sra) · Topics: Image Inpainting, Image Editing, Diffusion Model

---

# 🌎 Visitor Map
<div style="display: flex; justify-content: center; margin: 20px 0;">
  <div style="width: 100px; height: 100px;">
    <script type="text/javascript" id="clstr_globe" src="//clustrmaps.com/globe.js?d=YcEGNdlapjfGw9-NBcj1CQW4sNbZoUSTRXAL3tOqhSM"></script>
  </div>
</div>
