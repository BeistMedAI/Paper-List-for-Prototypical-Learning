<div id = "top"></div>

<div align="center">

[![](https://capsule-render.vercel.app/api?type=waving&height=200&color=0:0F172A,65:4F46E5,100:22D3EE&text=🌟%20Paper%20List%20for%20Prototypical%20Learning&fontSize=30&fontAlign=50&fontAlignY=40&fontColor=FFFFFF&desc=%E2%80%94%20Junhao%20Jia&descAlign=90&descAlignY=60&descSize=20)](#top)

</div>

<p align="center">
  <a href="https://github.com/BeistMedAI/Paper-List-for-Prototypical-Learning">
    <img alt="Stars" src="https://img.shields.io/github/stars/BeistMedAI/Paper-List-for-Prototypical-Learning?style=flat-square&logo=github&label=Stars&labelColor=0F172A&color=4F46E5" />
  </a>
  <a href="https://github.com/BeistMedAI/Paper-List-for-Prototypical-Learning/forks">
    <img alt="Forks" src="https://img.shields.io/github/forks/BeistMedAI/Paper-List-for-Prototypical-Learning?style=flat-square&logo=github&label=Forks&labelColor=0F172A&color=4F46E5" />
  </a>
  <a href="https://github.com/BeistMedAI/Paper-List-for-Prototypical-Learning/issues">
    <img alt="Issues" src="https://img.shields.io/github/issues/BeistMedAI/Paper-List-for-Prototypical-Learning?style=flat-square&label=Issues&labelColor=0F172A&color=22D3EE" />
  </a>
  <a href="https://github.com/BeistMedAI/Paper-List-for-Prototypical-Learning/blob/main/LICENSE">
    <img alt="Code License" src="https://img.shields.io/github/license/BeistMedAI/Paper-List-for-Prototypical-Learning?style=flat-square&label=Code%20License&labelColor=0F172A&color=22D3EE" />
  </a>
  <a href="https://github.com/BeistMedAI/Paper-List-for-Prototypical-Learning/blob/main/LICENSE-DOCS">
    <img alt="Docs License" src="https://img.shields.io/badge/Docs%20License-CC%20BY%204.0-22D3EE?style=flat-square&labelColor=0F172A" />
  </a>
  <br/>
  <img alt="Last update" src="https://img.shields.io/badge/Last%20update-2025.08-4F46E5?style=flat-square&labelColor=0F172A" />
  <img alt="PRs Welcome" src="https://img.shields.io/badge/PRs-Welcome-22D3EE?style=flat-square&labelColor=0F172A" />
  <a href="https://awesome.re"><img alt="Awesome" src="https://awesome.re/badge-flat.svg" /></a>
</p>


**🦉 Contributors: [Junhao Jia (23' HDU Undergraduate)](https://github.com/BeistMedAI), [Yifei Sun (22' HDU-ITMO Undergraduate)](https://diaoquesang.github.io/), [Yunyou Liu (23' HDU Undergraduate)](https://github.com/Yunyou-Liu), [Huangwei Chen (22' HDU Undergraduate)](https://huangwei-chen.github.io/), [Shuo Jiang (23' HDU Undergraduate)](https://github.com/JSLiam94), [Huangxing Lin (24' XDU Undergraduate)](https://github.com/Zoraaster1207), [Ziyan Luo (23' HNU Undergraduate)](https://github.com/Zoraaster1207), [Hanwen Zheng (23' HDU Undergraduate)](https://github.com/Zhenghanwen-zhw), [Yuting Shi (23' HDU Undergraduate)](https://github.com/sytttttttt)**

**🎓 DeepWiki: [Generating GitHub Knowledge Base Documentation in One Click](https://deepwiki.com/BeistMedAI/Paper-List-for-Prototypical-Learning).**

**📦 Other resources: [1] [Paper-List-for-Medical-Anomaly-Detection](https://github.com/diaoquesang/Paper-List-for-Medical-Anomaly-Detection), [2] [Paper List for Medical Reasoning Large Language Models](https://github.com/HovChen/Paper-List-for-Medical-Reasoning-Large-Language-Models)**

### Welcome to join us by contacting: 23080631@hdu.edu.cn.

<div>
<p align="center">
  <a href="https://www.hdu.edu.cn/"><img src="logos/HDU.png" height="42" alt="HDU" /></a>&nbsp;&nbsp;
  <a href="https://www.zju.edu.cn/"><img src="logos/ZJU.png" height="42" alt="ZJU" /></a>&nbsp;&nbsp;
  <a href="https://www.xdu.edu.cn/"><img src="logos/XDU.png" height="42" alt="XDU" /></a>&nbsp;&nbsp;
  <a href="https://www.hnu.edu.cn/"><img src="logos/HNU.png" height="42" alt="HNU" /></a>&nbsp;&nbsp;
  <a href="https://en.itmo.ru/"><img src="logos/ITMO.jpg" height="42" alt="ITMO" /></a>&nbsp;&nbsp;
  <a href="https://en.cuhk.edu.hk/"><img src="logos/CUHK-SZ.png" height="42" alt="CUHK-SZ" /></a>&nbsp;&nbsp;
  <a href="https://www.sribd.cn/"><img src="logos/SRIBD.png" height="42" alt="SRIBD" /></a>
</p>

</div>
The list covers interpretable, prototype/part-based vision papers, organized by A–K taxonomy (multi-label). Medical Imaging (J) is further split into organ/modality/task subcategories.

### A–K 类别速览 · A–K at a glance
- [A. 奠基/通用 ProtoPNet 系与近亲 · Foundations & general prototype-part models](#s1)
- [B. Transformer/ViT 原型方法 · Prototype-based Transformers/ViTs](#s2)
- [C. 分层/树/超曲空间 · Hierarchies, trees, hyperbolic spaces](#s3)
- [D. 原型表示/匹配范式的扩展 · Extension of Prototypical Representation/Matching Paradigm](#s4)  
  ↳ [D1. 可形变/可逆/像素对齐](#s41) · [D2. 非参数/核/分布式原型](#s42) · [D3. 原型共享/分配/角色](#s43)
- [E. 语义/概念对齐（含多模态） · Semantic/concept alignment (incl. multimodal)](#s5)
- [F. 训练策略/后验构建/可编辑 · Training strategies, post-hoc, editable models](#s6)
- [G. 评测/基准/批判 · Evaluation, benchmarks, critiques](#s7)
- [H. 综述 · Surveys](#s8)
- [I. 任务维度 · Tasks (segmentation, keypoint, regression, UDA, MIL, multi-label)](#s9)
- [J. 医学影像 · Medical imaging](#s10)  
  ↳ [J1. Alzheimer’s (MRI)](#s101) · [J2. Tumor (MRI/mpMRI)](#s102) · [J3. Breast—Digital Mammography](#s103) · [J4. Chest—CXR/COVID-19](#s104)  
  ↳ [J5. Cephalometric/Dental X-ray](#s105) · [J6. Pathology—WSI/MIL](#s106) · [J7. Retina—Fundus](#s107) · [J8. Dermatology—Skin](#s108) · [J9. General/Multi-organ](#s109)
- [K. 粒度强化 · Patch/Part/Pixel](#s11)

## 🔎 Quick Start 
- 🧭 **Foundations**: This Looks Like That (NeurIPS 2019) → ProtoTree (CVPR 2021) → TesNet (ICCV 2021)
- 🧩 **Patch/Pixel Evidence**: PIP-Net (CVPR 2023) → PixPNet (WACV 2024)
- 🧠 **Transformer-based Prototypes**: ViT-NeT (ICML 2022) → ProtoPFormer (IJCAI 2024) → ProtoViT (NeurIPS 2024)
- 🌲 **Hierarchies / Hyperbolic**: Hierarchical Prototypes (AAAI 2019) → HAPPI (ICCVW 2025)
- 🏥 **Medical Imaging Track**: XProtoNet (CVPR 2021) → PAMIL (MICCAI 2024) → CIPL (TMI 2025)

> One-week onboarding? Read 1 paper + run 1 repo from each line above.

## 🧰 How to Use
- **By paradigm**: Need pixel-level evidence? See **K / D1**. Want a hierarchical reasoning chain? See **C**. Want ViT-coupled methods? Jump to **B**.
- **By task**: For segmentation / keypoint / MIL / UDA, see **I**. For medical imaging, use **J** and pick by organ/modality subcategory.
- **Code availability**: The :octocat: icon links to code. If it’s missing, the work is theory-oriented or not yet released.
- **Timeline**: For the latest trends, start with **2024–2025** items in **B / D / K**.

## 📒 Cheatsheet
- **Prototype / Part**: Reusable local evidence units aligned to image patches.
- **Support / Oppose**: Some methods allow prototypes to contribute positive or negative evidence, enabling defensible conclusions.
- **Activation spillover**: Prototype activations bleed into irrelevant regions → see pixel-aligned approaches such as PixPNet.
- **Hierarchical prototypes**: Multi-level explanations from parts → concepts → categories.

## ⚠️ Pitfalls
- **Latent similarity ≠ semantic similarity**: Always validate with pixel/region visualizations (see **G** for evaluation papers).
- **Prototype redundancy**: Separating supportive vs. trivial prototypes (e.g., ST-ProtoPNet) improves readability and discrimination.

## ✏️ Tips

- :octocat:: Code

- [🥰 : Star History](#s0)

## <div id = "s1"></div> A. Foundations & general prototype-part models 

- [[2019-NeurIPS]](https://proceedings.neurips.cc/paper/2019/file/adf7ee2dcf142b0e11888e72b43fcb75-Paper.pdf) **This looks like that: deep learning for interpretable image recognition** [:octocat:](https://github.com/jakesnell/prototypical-networks)
  - 简介（中文）: 开创“这像那”的原型-部件范式：学习若干原型部件，并以图像局部与原型的匹配作为决策证据，给出可视化的逐步解释。
  - Intro (EN): Foundational 'This Looks Like That' prototype-part paradigm: learns a set of prototypical parts and matches them to image patches to justify decisions.

<img width="1245" height="495" alt="image" src="https://github.com/user-attachments/assets/0d73a726-2e61-4ebd-9641-2d0a81ad4606" />

- [[2019-AAAI]](https://ojs.aaai.org/index.php/HCOMP/article/view/5265) **Interpretable Image Recognition with Hierarchical Prototypes** 
  - 简介（中文）: 在原型基础上引入层级结构（从部件到概念），让解释具备“由细到粗”的语义层次。
  - Intro (EN): Introduces hierarchical prototypes (from parts to concepts), enabling explanations at multiple semantic levels.
 
<img width="1406" height="1016" alt="image" src="https://github.com/user-attachments/assets/10355364-1222-4078-8dd3-8ca1822d08d4" />

- [[2021-ECML PKDD]](https://arxiv.org/pdf/2011.02863) **This looks like that, because... explaining prototypes for interpretable image recognition** [:octocat:](https://github.com/M-Nauta/Explaining_Prototypes)
  - 简介（中文）: 在原型识别（如 ProtoPNet）基础上，为每个原型自动量化颜色（色相）、形状、纹理、对比度与饱和度等因素的影响，生成可视化+数值的全局与局部解释，澄清“这像那”的相似性含义，并识别误导性与冗余原型。
  - Intro (EN): Builds on prototype-based recognition (e.g., ProtoPNet) by enriching visual prototypes with quantitative explanations—estimating how hue, shape, texture, contrast, and saturation influence each prototype—to produce global and local justifications that clarify “this looks like that,” and surface misleading or redundant prototypes.
 
<img width="1377" height="353" alt="image" src="https://github.com/user-attachments/assets/1593c4f6-1f33-44de-befb-712bed72cc86" />

- [[2021-ICCV]](https://openaccess.thecvf.com/content/ICCV2021/papers/Wang_Interpretable_Image_Recognition_by_Constructing_Transparent_Embedding_Space_ICCV_2021_paper.pdf) **Interpretable image recognition by constructing transparent embedding space** [:octocat:](https://github.com/JackeyWang96/TesNet)
  - 简介（中文）: 构建“透明嵌入空间”，使原型与特征维度更易于人解释，减少黑盒感。
  - Intro (EN): Builds a transparent embedding space to align features and prototypes with human-interpretable axes.
 
<img width="1290" height="506" alt="image" src="https://github.com/user-attachments/assets/3f71aab0-c6c9-4c5d-a8cf-afdede38cd53" />

- [[2021-ICMLW]](https://arxiv.org/pdf/2105.02968) **This looks like that... does it? shortcomings of latent space prototype interpretability in deep networks** [[other source]]([https://icml.cc/media/icml-2024/Slides/34227.pdf](https://icml.cc/virtual/2021/11382))
  - 简介（中文）: 指出潜在空间中的“相似性”未必等价于输入空间的语义相似，系统性分析原型解释的陷阱。
  - Intro (EN): Analyzes pitfalls: similarity in latent space may not reflect semantic similarity in input space; cautions for prototype interpretability.
 
<img width="2175" height="517" alt="image" src="https://github.com/user-attachments/assets/c1be777e-c8d2-4d00-9855-87704a0d4f70" />

- [[2022-ECCV]](https://arxiv.org/pdf/2112.02902) **Interpretable image classification with differentiable prototypes assignment** [:octocat:](https://github.com/gmum/ProtoPool)
  - 简介（中文）: 构建了 ProtoPool 模型，引入可共享原型库、可区分 (differentiable) 的原型与类别分配机制，并提出聚焦相似性（focal similarity）函数以凸显最具代表性的视觉部分，实现端到端正向推理、显著减少原型数量、提升可解释性与训练效率。该模型在 CUB‑200‑2011 和 Stanford Cars 数据集上以明显更少的原型取得了竞争性甚至优越的分类准确率，并通过理论分析与用户研究验证原型更具辨识性。 
  - Intro (EN): Presents ProtoPool, an interpretable prototype‑based image classification model that introduces a differentiable assignment of prototypes to classes, reuse of prototypes across classes, and a focal similarity function to emphasize salient features. It enables end‑to‑end positive reasoning, significantly reduces the number of prototypes, simplifies training (avoiding pruning stages), and achieves state‑of‑the‑art or competitive accuracy on CUB‑200‑2011 and Stanford Cars datasets. Theoretical analysis and user studies demonstrate that its prototypes are more distinctive and interpretable.
 
<img width="1234" height="619" alt="image" src="https://github.com/user-attachments/assets/ed18ef47-b3b1-4910-b36b-fc6f56e8edd1" />

- [[2022-ICPR]](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9956087&casa_token=mV6CJ9r3J_8AAAAA:11F0UeuihJi9QxN60t18atyV_XRbByfQ35jW-jqCF-8IGwsb83VsWKv7ZWamDQncH_zB-2My1w&tag=1) **Multi-grained interpre table network for image recognition** 
  - 简介（中文）: 提出了一种“多粒度可解释网络”（Multi‑Grained Interpretable Network for Image Recognition），通过将类组织成层级结构并分配多个粒度的标签，使用树状结构的分类器在粗粒度到细粒度的层次上逐步进行分类决策，并可为每一步提供可解释的决策路径。在 CUB‑200‑2011 与 Stanford Cars 等细粒度图像识别数据集上实现了具有竞争力的分类性能，同时对抗 FGSM 和 PGD 等对抗样本显示出更高的鲁棒性。
  - Intro (EN): Proposes a Multi‑Grained Interpretable Network for Image Recognition that organizes object classes into a hierarchical tree and assigns multi‑grained labels to training images. A tree‑structured classifier learns features at different granularity levels and makes predictions from coarse to fine, offering a clear decision pathway with explanations at each step. The method achieves competitive accuracy on fine‑grained datasets like CUB‑200‑2011 and Stanford Cars, and demonstrates improved robustness to adversarial attacks such as FGSM and PGD.
 
<img width="1540" height="761" alt="image" src="https://github.com/user-attachments/assets/56ed3a48-6583-4b2d-aa1e-d627f954ca3c" />

- [[2022-MICCAI]](https://arxiv.org/pdf/2209.12420) **Knowledge distillation to ensemble global and interpretable prototype-based mammogram classification models** 
  - 简介（中文）: 在乳腺X线分类中用蒸馏整合可解释原型与强表征，兼顾性能与可解释性。
  - Intro (EN): Uses knowledge distillation to combine interpretable prototypes with strong features for mammography classification.
 
<img width="1481" height="712" alt="image" src="https://github.com/user-attachments/assets/072a390d-9ace-435c-93e0-e2fc479ff024" />

- [[2022-NN]](https://www.sciencedirect.com/science/article/pii/S0893608022001125?casa_token=6wzHMFuphHYAAAAA:OWLadVlFDialP0WffRwHPUUYzpaDGI1mq-Pf0g7qsbj2GupKLPzQzQNOoKD187RbI-qme5pWXQ) **Think positive: An interpretable neural network for image recognition** [:octocat:](#)
  - 简介（中文）: 从“正向证据”角度构建可解释模型，强调支持性原型对决策的贡献。
  - Intro (EN): Focuses on positive evidence: emphasizes supporting prototypes as primary drivers of decisions.
 
<img width="1709" height="672" alt="image" src="https://github.com/user-attachments/assets/be0f430f-a835-4595-8b0e-a846ecf22229" />

- [[2023-ICCV]](https://openaccess.thecvf.com/content/ICCV2023/papers/Wang_Learning_Support_and_Trivial_Prototypes_for_Interpretable_Image_Classification_ICCV_2023_paper.pdf) **Learning Support and Trivial Prototypes for Interpretable Image Classification** [:octocat:](https://github.com/cwangrun/ST-ProtoPNet)
  - 简介（中文）: 区分‘支持性原型’与‘次要/冗余原型’，提升解释质量与判别力。
  - Intro (EN): Separates supportive vs. trivial prototypes to enhance explanation quality and discrimination.
 
<img width="792" height="377" alt="image" src="https://github.com/user-attachments/assets/d7c5ba01-3f48-4a15-b078-b19c04876e44" />

- [[2023-MICCAI]](https://arxiv.org/pdf/2310.15741) **Interpretable medical image classification using prototype learning and privileged information** 
  - 简介（中文）: 引入特权信息（训练期可见、测试期不可见）提升医学分类解释与性能。
  - Intro (EN): Leverages privileged information (available only at training) to enhance medical classification and interpretability.
 
<img width="1207" height="805" alt="image" src="https://github.com/user-attachments/assets/8ce558b9-c52a-4969-9121-8fabb06732a1" />

- [[2023-TCSVT]](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=10250992&casa_token=vyLb4XK3tAEAAAAA:LjaFmlFfW3DSSuW-ySMLrWeudKccSFdANQpSfsMtSh9ST5qiPdtCAqsPET8YKsIobenQpL0DFQ) **Transparent embedding space for interpretable image recognition** [:octocat:](https://github.com/JackeyWang96/TesNet)
  - 简介（中文）: 构建“透明嵌入空间”，使原型与特征维度更易于人解释，减少黑盒感。
  - Intro (EN): Builds a transparent embedding space to align features and prototypes with human-interpretable axes.
 
<img width="1445" height="606" alt="image" src="https://github.com/user-attachments/assets/c342600f-3aed-4e47-81b0-1493761769bf" />

- [[2025-ICLR]](https://openreview.net/forum?id=4sDicVEy6M) **What Do You See in Common？Learning Hierarchical Prototypes over Tree-of-Life to Discover Evolutionary Traits** [:octocat:](https://github.com/Imageomics/HComPNet)
  - 简介（中文）: 在原型基础上引入层级结构（从部件到概念），让解释具备“由细到粗”的语义层次。
  - Intro (EN): Introduces hierarchical prototypes (from parts to concepts), enabling explanations at multiple semantic levels.
 
<img width="1789" height="864" alt="image" src="https://github.com/user-attachments/assets/ed747977-4fee-4e04-9554-0efd815b28e9" />

- [[2025-ICLR_WD]](https://openreview.net/forum?id=HXwrppoSPc) **COMiX: Compositional explanations using prototypes** 
  - 简介（中文）: 用‘原型+组合’生成可组合解释，提升复杂场景的可解释性。
  - Intro (EN): Compositional explanations built from prototypes to handle complex scenes.
 
<img width="1263" height="702" alt="image" src="https://github.com/user-attachments/assets/d81eb193-1339-4ea6-8c77-602843166a32" />

- [[2025-PR]](https://www.sciencedirect.com/science/article/pii/S0031320324006526?casa_token=cwSd-BCRwpEAAAAA:pszMddU-YKWSOts3MzueNXcvt_DKqBOaBd2-3NWzLNZ2QRzq0cvc5mGKB16r7R_lFHGXGYVchg) **Characteristic discriminative prototype network with detailed interpretation for classification** 
  - 简介（中文）: 学习更具判别性的特征-原型，并提供细粒度决策分解。
  - Intro (EN): Learns more discriminative feature-prototype pairs with fine-grained decision breakdowns.
 
<img width="1229" height="523" alt="image" src="https://github.com/user-attachments/assets/1b47b3e5-60be-465d-9a00-e92488e151d6" />

## <div id = "s2"></div> B. Prototype-based Transformers/ViTs 

- [[2022-ICML]](https://proceedings.mlr.press/v162/kim22g/kim22g.pdf) **Vit-net: Interpretable vision transformers with neural tree decoder** [:octocat:](https://github.com/jumpsnack/ViT-NeT)
  - 简介（中文）: 把原型/树结构融入ViT，形成“Transformer特征+可解释树解码”的组合。
  - Intro (EN): Fuses ViT features with a tree decoder, marrying transformer representations with transparent prototype reasoning.

<img width="1543" height="599" alt="image" src="https://github.com/user-attachments/assets/a5233cd8-7d40-49df-b618-d4a15fffcb10" />
  
- [[2024-IJCAI]](https://www.ijcai.org/proceedings/2024/168) **ProtoPFormer: Concentrating on Prototypical Parts in Vision Transformers for Interpretable Image Recognitio** [:octocat:](https://github.com/zju-vipa/ProtoPFormer)
  - 简介（中文）: 在ViT上专注于原型化的局部部件，抑制背景干扰，提升解释聚焦度。
  - Intro (EN): Prototype-focused ViT that suppresses background distraction, sharpening attention on meaningful parts.
 
<img width="1200" height="480" alt="image" src="https://github.com/user-attachments/assets/8246c5d1-feb1-460b-8ec7-69961b19d9f3" />

- [[2024-ISBI]](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=10635182&casa_token=kEs0mPH5s5QAAAAA:lb-VTTALa7DeUJ8OXO3ZaivR2Wl-kAcNgxdB6HiQgmf0ggkDUnYTFEDyj5Nv8fL2F4ZRiURW4g) **Explainable transformer prototypes for medical diagnoses** [:octocat:](https://github.com/NUBagcilab/r2r_proto)
  - 简介（中文）: 基于Transformer的医学诊断原型，结合注意力与原型激活给出解释。
  - Intro (EN): Transformer-based medical diagnosis with prototype activations as clear visual rationales.
 
<img width="1850" height="598" alt="image" src="https://github.com/user-attachments/assets/7c55ddd1-458a-46ff-b367-32e969b00fa3" />

- [[2024-NeurIPS]](https://proceedings.neurips.cc/paper_files/paper/2024/file/48dfc849640344e2d58df0b5bb78c33b-Paper-Conference.pdf) **Interpretable Image Classification with Adaptive Prototype-based Vision Transformers** [:octocat:](https://github.com/Henrymachiyu/ProtoViT)
  - 简介（中文）: 在ViT中自适应地学习部件原型，并与注意力联动以提升可解释性。
  - Intro (EN): Learns adaptive part prototypes within ViTs and couples them with attention for better interpretability.
 
<img width="1478" height="912" alt="image" src="https://github.com/user-attachments/assets/fb2f39da-ea5c-4ce4-8a08-bafe1dccfdc5" />

- [[2025-JBHI_UR]](https://arxiv.org/pdf/2506.10669) **PiPViT: Patch-based Visual Interpretable Prototypes for Retinal Image Analysis** [:octocat:](https://github.com/marziehoghbaie/PiPViT)
  - 简介（中文）: 在眼底图像上把Patch原型与ViT结合，兼顾细粒度病变与全局结构。
  - Intro (EN): Combines patch prototypes and ViTs for retinal imaging to capture fine lesions and global structures.
 
<img width="2010" height="655" alt="image" src="https://github.com/user-attachments/assets/f04315b1-c792-4fc7-8968-be51d348aeee" />

- [[2025-ICASSP]](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=10890753&casa_token=CK3WkOK9TVsAAAAA:pBren1C90XkdKu7gUBnv5ReeSpxZ0zmhf2FeYqh-2t0gPXfpQPYsMb9onOdSyABmObSQkB_7dQ) **Prototypical Part Transformer for Interpretable Image Recognition**
  - 简介（中文）: 把部件原型与Transformer结构结合，统一表示学习与解释。
  - Intro (EN): Integrates part prototypes into a Transformer, unifying representation and explanation.
 
<img width="1275" height="417" alt="image" src="https://github.com/user-attachments/assets/0178283a-d91c-49a4-8657-85b17888c718" />

## <div id = "s3"></div> C. Hierarchies, trees, hyperbolic spaces 

- [[2019-AAAI]](https://ojs.aaai.org/index.php/HCOMP/article/view/5265) **Interpretable Image Recognition with Hierarchical Prototypes**
  - 简介（中文）: 在原型基础上引入层级结构（从部件到概念），让解释具备“由细到粗”的语义层次。
  - Intro (EN): Introduces hierarchical prototypes (from parts to concepts), enabling explanations at multiple semantic levels.
 
<img width="1406" height="1016" alt="image" src="https://github.com/user-attachments/assets/10355364-1222-4078-8dd3-8ca1822d08d4" />

- [[2021-CVPR]](https://openaccess.thecvf.com/content/CVPR2021/papers/Nauta_Neural_Prototype_Trees_for_Interpretable_Fine-Grained_Image_Recognition_CVPR_2021_paper.pdf) **Neural prototype trees for interpretable fine-grained image recognition** [:octocat:](https://github.com/M-Nauta/ProtoTree)
  - 简介（中文）: 把原型匹配与可解释的树模型结合，每个节点对应“像/不像”的证据，生成可追踪的决策路径。
  - Intro (EN): Combines prototype matching with decision trees; each node encodes supporting/opposing evidence for a transparent decision path.
 
<img width="1519" height="458" alt="image" src="https://github.com/user-attachments/assets/b3f1f407-970d-4b53-9ee0-e02632933fdb" />

- [[2022-ICML]](https://proceedings.mlr.press/v162/kim22g/kim22g.pdf) **Vit-net: Interpretable vision transformers with neural tree decoder** [:octocat:](https://github.com/jumpsnack/ViT-NeT)
  - 简介（中文）: 把原型/树结构融入ViT，形成“Transformer特征+可解释树解码”的组合。
  - Intro (EN): Fuses ViT features with a tree decoder, marrying transformer representations with transparent prototype reasoning.
 
<img width="1543" height="599" alt="image" src="https://github.com/user-attachments/assets/a5233cd8-7d40-49df-b618-d4a15fffcb10" />

- [[2023-JBHI]](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=10290723&casa_token=3ayrYdj6bekAAAAA:ND9zMo8PowTyi_hywubBzd7YzKCFIp4hlVR3PI6yDoVBye3j6SCoequKrnACUhRoPQp7H_cP3A) **Interpretable inference and classification of tissue types in histological colorectal cancer slides based on ensembles adaptive boosting prototype tree** 
  - 简介（中文）: 基于集成/Boosting的原型树，在病理切片上解释组织类型判别。
  - Intro (EN): Ensemble/boosted prototype trees for tissue classification on histology slides with transparent rules.
 
<img width="1413" height="981" alt="image" src="https://github.com/user-attachments/assets/272bef36-75bc-4ce0-9484-cb8f5f9b9856" />

- [[2025-ICCVW_BEW]](https://openreview.net/forum?id=PcF9Q51rF1&noteId=KSZAX91CoY) **HAPPI: Hyperbolic Hierarchical Part Prototypes for Image Recognition** 
  - 简介（中文）: 在超曲几何中学习层级原型，提升层次结构表达与相似度度量。
  - Intro (EN): Learns hierarchical prototypes in hyperbolic geometry to better encode tree-like relations.
 
<img width="1603" height="716" alt="image" src="https://github.com/user-attachments/assets/0c690ab4-4ffc-42a4-9d0d-024ea040a7f9" />

- [[2025-ICLR]](https://openreview.net/forum?id=4sDicVEy6M) **What Do You See in Common？Learning Hierarchical Prototypes over Tree-of-Life to Discover Evolutionary Traits** [:octocat:](https://github.com/Imageomics/HComPNet)
  - 简介（中文）: 在原型基础上引入层级结构（从部件到概念），让解释具备“由细到粗”的语义层次。
  - Intro (EN): Introduces hierarchical prototypes (from parts to concepts), enabling explanations at multiple semantic levels.
 
<img width="1518" height="735" alt="image" src="https://github.com/user-attachments/assets/e74f379c-8ebc-4ddb-8518-004f2ee27c34" />

- [[2025-JBHI]](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=10955117&casa_token=sTYYDiTd42cAAAAA:JU_OQVG1R0u18yid6HvEDCOri1b_7N7f89WZinPRn83aVnceKKjvB2ksF4GGPi_JciMq0B08EQ) **Progressive mining and dynamic distillation of hierarchical prototypes for disease classification and localisation** [:octocat:](https://github.com/cwangrun/HierProtoPNet)
  - 简介（中文）: 渐进挖掘与动态蒸馏层级原型，同时兼顾定位与分类。
  - Intro (EN): Progressive mining and dynamic distillation of hierarchical prototypes for joint localization/classification.
 
<img width="1667" height="431" alt="image" src="https://github.com/user-attachments/assets/548a094c-a241-46e2-b30a-85ef274613f4" />

## <div id = "s4"></div> D. Extension of Prototypical Representation/Matching Paradigm 

### <div id = "s41"></div> D1. Deformable, invertible, pixel-grounded 

- [[2022-CVPR]](https://openaccess.thecvf.com/content/CVPR2022/papers/Donnelly_Deformable_ProtoPNet_An_Interpretable_Image_Classifier_Using_Deformable_Prototypes_CVPR_2022_paper.pdf) **Deformable protopnet: An interpretable image classifier using deformable prototypes** [:octocat:](https://github.com/jdonnelly36/Deformable-ProtoPNet)
  - 简介（中文）: 允许原型发生形变与位移，以适应形态差异和姿态变化，同时保持‘部件—相似度’的可解释性。
  - Intro (EN): Allows prototypes to deform/translate to handle pose and morphology changes while preserving part-similarity explanations.
 
<img width="1258" height="295" alt="image" src="https://github.com/user-attachments/assets/79e4a8d7-7c97-41ac-ad10-2bfe52821dc3" />

- [[2023-CVPR]](https://openaccess.thecvf.com/content/CVPR2023/papers/Nauta_PIP-Net_Patch-Based_Intuitive_Prototypes_for_Interpretable_Image_Classification_CVPR_2023_paper.pdf) **Pip-net: Patch-based intuitive prototypes for interpretable image classification** [:octocat:](https://github.com/M-Nauta/PIPNet)
  - 简介（中文）: 以Patch为粒度学习直观原型，突出“局部贴片—概念”的对应关系，方便人工校验与纠错。
  - Intro (EN): Learns intuitive patch-level prototypes mapping local image patches to human-meaningful parts for easy auditing and correction.
 
<img width="1665" height="441" alt="image" src="https://github.com/user-attachments/assets/7f70f2fc-76c1-4ca1-9ab8-117b2acc0353" />

- [[2024-CEURW]](https://arxiv.org/pdf/2407.14277) **Patch-based Intuitive Multimodal Prototypes Network (PIMPNet) for Alzheimer's Disease classification** 
  - 简介（中文）: 面向医学影像场景、强调局部Patch/像素或可逆/可形变机制；通过将图像局部与学习到的原型匹配，给出‘这看起来像那’的直观证据。
  - Intro (EN): Medical imaging focus; Emphasizes patches/pixels, or deformable/invertible mechanisms. Matches image regions to learned prototypes to provide intuitive 'this looks like that' evidence.
 
<img width="1342" height="871" alt="image" src="https://github.com/user-attachments/assets/deb95825-bb48-4afe-92fb-330a670d5bbd" />

- [[2024-ECCV]](https://arxiv.org/pdf/2407.12200) **This Probably Looks Exactly Like That: An Invertible Prototypical Network** [:octocat:](https://github.com/craymichael/ProtoFlow)
  - 简介（中文）: 把原型网络做成可逆结构，便于从原型重构输入、检验可解释性。
  - Intro (EN): Makes prototype networks invertible to reconstruct inputs from prototypes and audit explanations.
 
<img width="1433" height="523" alt="image" src="https://github.com/user-attachments/assets/64819d67-7ed3-46c5-9f98-43d1bd2f2aa8" />

- [[2024-WACV]](https://openaccess.thecvf.com/content/WACV2024/papers/Carmichael_Pixel-Grounded_Prototypical_Part_Networks_WACV_2024_paper.pdf) **Pixel-grounded prototypical part networks** [:octocat:](https://github.com/merlresearch/PixPNet)
  - 简介（中文）: 将原型显式对齐到像素层级与实例轮廓，缓解‘激活外溢’问题。
  - Intro (EN): Aligns prototypes to pixels and instance contours, mitigating activation spillover.
 
<img width="1840" height="525" alt="image" src="https://github.com/user-attachments/assets/3140a92b-334a-4ecd-a2d5-a4bf16c2424c" />

- [[2025-JBHI_UR]](https://arxiv.org/pdf/2506.10669) **PiPViT: Patch-based Visual Interpretable Prototypes for Retinal Image Analysis** [:octocat:](https://github.com/marziehoghbaie/PiPViT)
  - 简介（中文）: 在眼底图像上把Patch原型与ViT结合，兼顾细粒度病变与全局结构。
  - Intro (EN): Combines patch prototypes and ViTs for retinal imaging to capture fine lesions and global structures.
 
<img width="2008" height="673" alt="image" src="https://github.com/user-attachments/assets/d97cd06c-8986-454b-b75e-61a001d1fd04" />

- [[2025-CVPRW]](https://openaccess.thecvf.com/content/CVPR2025W/TCV/papers/Singh_ProtoPatchNet_An_Interpretable_Patch-Based_Prototypical_Network_CVPRW_2025_paper.pdf) **ProtoPatchNet: An Interpretable Patch-Based Prototypical Network** 
  - 简介（中文）: 基于Patch的原型网络，强调可组合的局部证据与简洁的可视化。
  - Intro (EN): Patch-based prototypical network with composable local evidence and concise visualization.

<img width="1388" height="532" alt="image" src="https://github.com/user-attachments/assets/5c7f7211-3d6d-444b-b11e-f6af5556e916" />

### <div id = "s42"></div> D2. Non-parametric, kernels, distributions 

- [[2023-ICLR]](https://openreview.net/forum?id=lh-HRYxuoRr) **This Looks Like It Rather Than That: ProtoKNN For Similarity-Based Classifiers** 
  - 简介（中文）: 以近邻/非参数方式实现“这像哪一些”：减少训练时的参数化假设，强调基于库的相似实例证据。
  - Intro (EN): Non-parametric, nearest-neighbor flavored 'this looks like those' using stored exemplars instead of heavy parametrization.
 
<img width="1322" height="551" alt="image" src="https://github.com/user-attachments/assets/381fb53b-57b0-428b-9e7d-9eb7385d6bca" />

- [[2024-xAI]](https://arxiv.org/pdf/2404.14830) **CoProNN: Concept-Based Prototypical Nearest Neighbors for Explaining Vision Models** [:octocat:](https://github.com/TeodorChiaburu/beexplainable)
  - 简介（中文）: 以概念为中心的原型近邻方法：用可命名概念匹配相似样本。
  - Intro (EN): Concept-centric prototypical nearest neighbors that match samples via nameable concepts.
 
<img width="1471" height="850" alt="image" src="https://github.com/user-attachments/assets/1ae5bb64-c607-486a-bb1e-f2a55eb6e7a9" />

- [[2025-AAAI]](https://ojs.aaai.org/index.php/AAAI/article/view/34233) **A Robust Prototype-Based Network with Interpretable RBF Classifier Foundations** [:octocat:](https://github.com/si-cim/cbc-aaai-2025)
  - 简介（中文）: 以RBF为基础构建鲁棒原型分类器，连接核方法与可解释原型。
  - Intro (EN): Grounds prototype classifiers in RBF theory, linking kernel methods and interpretable prototypes.
 
<img width="781" height="324" alt="image" src="https://github.com/user-attachments/assets/f5680728-62e2-49f1-80c8-457d08ce5cb8" />

- [[2025-CVPR]](https://openaccess.thecvf.com/content/CVPR2025/papers/Zhu_Interpretable_Image_Classification_via_Non-parametric_Part_Prototype_Learning_CVPR_2025_paper.pdf) **Interpretable Image Classification via Non-parametric Part Prototype Learning** [:octocat:](https://github.com/zijizhu/proto-non-param)
  - 简介（中文）: 学习非参数的部件原型集合，减少强假设并提升可编辑性。
  - Intro (EN): Learns non-parametric sets of part prototypes, reducing assumptions and enhancing editability.
 
<img width="1389" height="776" alt="image" src="https://github.com/user-attachments/assets/5fdc93f5-d1dd-4b19-931c-db51a6ee8f39" />

- [[2025-TPAMI]](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=10982376&casa_token=O7jGkn0rrFgAAAAA:BbH8z9dUJQb0WVxUm3QaDXeqq7IOLlkG7lJQsQkIK7prWfl568yeeKCL7mLXFj9X4JGMWUPG5Q&tag=1) **Mixture of gaussian-distributed prototypes with generative modelling for interpretable and trustworthy image recognition** [:octocat:](https://github.com/cwangrun/MGProto)
  - 简介（中文）: 把原型建模为高斯混合并结合生成式建模，强化不确定性表达与可信度。
  - Intro (EN): Models prototypes as Gaussian mixtures and couples with generative modeling for uncertainty-aware trustworthiness.
<img width="1192" height="476" alt="image" src="https://github.com/user-attachments/assets/e330ea47-66a5-44db-89de-bb962efd87fc" />

### <div id = "s43"></div> D3. Sharing, assignment, prototype roles 

- [[2021-SIGKDD]](https://dl.acm.org/doi/pdf/10.1145/3447548.3467245) **Protopshare: Prototypical parts sharing for similarity discovery in interpretable image classification** [:octocat:](https://github.com/gmum/ProtoPShare)
  - 简介（中文）: 提出“原型部件共享”，在类别之间共享或迁移典型部件，提升样本效率与可解释性。
  - Intro (EN): Proposes prototypical part sharing across classes to improve sample efficiency and interpretability.
 
<img width="1202" height="457" alt="image" src="https://github.com/user-attachments/assets/af7694d4-5b2b-4cf1-b004-fde7600f93ef" />

- [[2022-ECCV]](https://arxiv.org/pdf/2112.02902) **Interpretable image classification with differentiable prototypes assignment** [:octocat:](https://github.com/gmum/ProtoPool)
  - 简介（中文）: 将原型分配建模为可微分过程，提升原型学习的可控性与可训练性。
  - Intro (EN): Formulates prototype assignment as a differentiable process to better control learning and consistency.
 
<img width="1234" height="624" alt="image" src="https://github.com/user-attachments/assets/071babe7-f04e-4c80-b7e9-b93e4c167b37" />

- [[2023-CVPR]](https://openaccess.thecvf.com/content/CVPR2023/papers/Nauta_PIP-Net_Patch-Based_Intuitive_Prototypes_for_Interpretable_Image_Classification_CVPR_2023_paper.pdf) **Pip-net: Patch-based intuitive prototypes for interpretable image classification** [:octocat:](https://github.com/M-Nauta/PIPNet)
  - 简介（中文）: 以Patch为粒度学习直观原型，突出“局部贴片—概念”的对应关系，方便人工校验与纠错。
  - Intro (EN): Learns intuitive patch-level prototypes mapping local image patches to human-meaningful parts for easy auditing and correction.
 
<img width="1667" height="434" alt="image" src="https://github.com/user-attachments/assets/3e112df4-91a0-439e-b243-54112f3ba452" />

- [[2023-ECAI]](https://arxiv.org/pdf/2307.10404) **Interpreting and correcting medical image classification with pip-net** [:octocat:](https://github.com/M-Nauta/PIPNet)
  - 简介（中文）: 以Patch为粒度学习直观原型，突出“局部贴片—概念”的对应关系，方便人工校验与纠错。
  - Intro (EN): Learns intuitive patch-level prototypes mapping local image patches to human-meaningful parts for easy auditing and correction.
 
<img width="1480" height="346" alt="image" src="https://github.com/user-attachments/assets/3a728c15-d479-412f-bad5-591b5527a4cb" />

- [[2023-ICCV]](https://openaccess.thecvf.com/content/ICCV2023/papers/Wang_Learning_Support_and_Trivial_Prototypes_for_Interpretable_Image_Classification_ICCV_2023_paper.pdf) **Learning Support and Trivial Prototypes for Interpretable Image Classification** [:octocat:](https://github.com/cwangrun/ST-ProtoPNet)
  - 简介（中文）: 区分‘支持性原型’与‘次要/冗余原型’，提升解释质量与判别力。
  - Intro (EN): Separates supportive vs. trivial prototypes to enhance explanation quality and discrimination.
 
<img width="811" height="387" alt="image" src="https://github.com/user-attachments/assets/f7f647b6-d203-48b3-a51a-03e9fdd20376" />

- [[2024-MICCAI]](https://arxiv.org/pdf/2403.18328) **Pipnet3d: Interpretable detection of alzheimer in mri scans** 
  - 简介（中文）: 以Patch为粒度学习直观原型，突出“局部贴片—概念”的对应关系，方便人工校验与纠错。
  - Intro (EN): Learns intuitive patch-level prototypes mapping local image patches to human-meaningful parts for easy auditing and correction.
<img width="1383" height="619" alt="image" src="https://github.com/user-attachments/assets/c460a5a1-5647-4fcc-85c6-eebb9da5db0c" />

## <div id = "s5"></div> E. Semantic/concept alignment (incl. multimodal) 

- [[2022-CVPR]](https://openaccess.thecvf.com/content/CVPR2022/papers/Keswani_Proto2Proto_Can_You_Recognize_the_Car_the_Way_I_Do_CVPR_2022_paper.pdf) **Proto2Proto: Can you recognize the car, the way I do?** [:octocat:](https://openaccess.thecvf.com/content/CVPR2022/papers/Keswani_Proto2Proto_Can_You_Recognize_the_Car_the_Way_I_Do_CVPR_2022_paper.pdf)
  - 简介（中文）: 让模型学会“像人一样”识别（以汽车为例）：将人类感知的部件/原型与网络原型对齐。
  - Intro (EN): Aligns human-perceived parts with learned prototypes (cars as example), making model evidence human-centric.
 
<img width="1720" height="629" alt="image" src="https://github.com/user-attachments/assets/59d27a7b-c69f-43f0-bf8e-250e407c6d16" />

- [[2023-ICLR]](https://openreview.net/forum?id=oiwXWPDTyNk) **Concept-level Debugging of Part-Prototype Networks** [:octocat:](https://github.com/abonte/protopdebug)
  - 简介（中文）: 在‘概念层’调试原型网络：发现并修复误导性概念，从而改善预测与解释。
  - Intro (EN): Debugs part-prototype networks at the concept level, fixing misleading concepts to improve both accuracy and explanations.
 
<img width="1435" height="479" alt="image" src="https://github.com/user-attachments/assets/08d1e8ae-3981-424a-9866-701dbe107d24" />

- [[2023-NeurIPS]](https://openreview.net/forum?id=dCAk9VlegR) **This looks like those: Illuminating prototypical concepts using multiple visualizations** [:octocat:](https://github.com/Henrymachiyu/This-looks-like-those_ProtoConcepts)
  - 简介（中文）: 用多种可视化方式呈现同一概念原型，帮助人类理解模型“看到”的语义。
  - Intro (EN): Shows multiple visualizations for the same prototypical concept to reveal what the model 'sees'.
 
<img width="1160" height="639" alt="image" src="https://github.com/user-attachments/assets/1fc0f967-4323-43bf-b358-d26be45c94b0" />

- [[2023-WACV]](https://openaccess.thecvf.com/content/WACV2023/papers/Sacha_ProtoSeg_Interpretable_Semantic_Segmentation_With_Prototypical_Parts_WACV_2023_paper.pdf) **Protoseg: Interpretable semantic segmentation with prototypical parts** [:octocat:](https://github.com/gmum/proto-segmentation)
  - 简介（中文）: 把‘部件原型’扩展到语义分割，像素级显示“这块区域像哪种原型”。
  - Intro (EN): Extends part-prototypes to semantic segmentation, grounding 'which region looks like which prototype' at pixel level.
 
<img width="1595" height="608" alt="image" src="https://github.com/user-attachments/assets/074b11c2-6ef4-40e5-8cb1-fff90f0225ad" />

- [[2024-AAAI]](https://ojs.aaai.org/index.php/AAAI/article/view/30109) **On the concept trustworthiness in concept bottleneck models** [:octocat:](https://github.com/hqhQAQ/ProtoCBM)
  - 简介（中文）: 讨论概念瓶颈模型的概念可信度，提醒概念误标或漂移的风险。
  - Intro (EN): Studies concept bottleneck trustworthiness, warning against mislabeled or drifting concepts.
 
<img width="1528" height="669" alt="image" src="https://github.com/user-attachments/assets/994ee032-7500-4cb9-b723-b741ffe73aaa" />

- [[2024-CIKM]](https://dl.acm.org/doi/pdf/10.1145/3627673.3679795) **Semantic prototypes: Enhancing transparency without black boxes** [:octocat:](https://github.com/ails-lab/Semantic-Prototypes)
  - 简介（中文）: 用语义化原型替代纯特征原型，增强人可读性与跨域泛化潜力。
  - Intro (EN): Replaces raw feature prototypes with semantic prototypes for readability and cross-domain generalization.
 
<img width="1204" height="400" alt="image" src="https://github.com/user-attachments/assets/ce7275cd-457a-4363-8d93-bd237827b95b" />

- [[2024-CVPR]](https://openaccess.thecvf.com/content/CVPR2024/papers/Wang_MCPNet_An_Interpretable_Classifier_via_Multi-Level_Concept_Prototypes_CVPR_2024_paper.pdf) **Mcpnet: An interpretable classifier via multi-level concept prototypes** [:octocat:](https://eddie221.github.io/MCPNet/)
  - 简介（中文）: 提出多层级概念原型（从部件到概念），在保持准确率的同时提升解释的层次性。
  - Intro (EN): Multi-level concept prototypes from parts to concepts, offering layered explanations without sacrificing accuracy.
 
<img width="1414" height="701" alt="image" src="https://github.com/user-attachments/assets/55df0d6c-5137-46bd-9955-75132da931c1" />

- [[2024-CVPRW]](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=10678010&casa_token=lqhBOsX5d7MAAAAA:4QCVH9ep9WEyQt9OMjfxH_vqrxKOKLN1qkZNhiIk1-wQ5dm_omZ-9f7EUI_wKshDgeooaAacgg) **Understanding the (extra-) ordinary: Validating deep model decisions with prototypical concept-based explanations** [:octocat:](https://github.com/maxdreyer/pcx)
  - 简介（中文）: 通过原型概念验证模型决策是否符合常识/领域知识，识别‘平凡/非平凡’证据。
  - Intro (EN): Validates whether decisions rely on ordinary vs. extra-ordinary prototypical concepts, aligning with domain knowledge.
 
<img width="731" height="722" alt="image" src="https://github.com/user-attachments/assets/b1cbb7ba-9b03-4402-aea0-faf98da074f6" />

- [[2024-MM]](https://openreview.net/forum?id=60Uyf4UumM) **Align2Concept: Language Guided Interpretable Image Recognition by Visual Prototype and Textual Concept Alignment** [:octocat:](https://openreview.net/forum?id=60Uyf4UumM)
  - 简介（中文）: 对齐视觉原型与文本概念，使解释从‘像哪块’上升到‘是什么概念’。
  - Intro (EN): Aligns visual prototypes with textual concepts, moving from 'where it looks like' to 'what concept it is'.
 
<img width="1508" height="611" alt="image" src="https://github.com/user-attachments/assets/dd620d7b-aeb6-436b-84db-0a287fba0019" />

- [[2024-NeurIPSW]](https://arxiv.org/pdf/2410.18705?) **Exploiting Interpretable Capabilities with Concept-Enhanced Diffusion and Prototype Networks** [:octocat:](https://github.com/acarballocastro/ConceptEnhanced)
  - 简介（中文）: 把扩散模型的概念能力与原型网络结合，探索更强的可解释生成+判别。
  - Intro (EN): Combines diffusion-model concepts with prototype networks for stronger interpretable generation+discrimination.
 
<img width="1321" height="728" alt="image" src="https://github.com/user-attachments/assets/3d25fd40-4351-45b5-afeb-1c1d5a33964c" />

- [[2024-plos]](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0311879) **An inherently interpretable deep learning model for local explanations using visual concepts** [:octocat:](https://github.com/mirzaahsan1986/CA_SoftNet)
  - 简介（中文）: 用人可理解的视觉概念构建局部解释，连接概念与证据区域。
  - Intro (EN): Uses human-understandable visual concepts to build local explanations linked to evidence regions.
 
<img width="1522" height="1047" alt="image" src="https://github.com/user-attachments/assets/a1fe5cdc-706f-409b-9bd2-f8e92e9e7406" />

- [[2024-TIP]](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=10684084&casa_token=o3YFdb-f9QMAAAAA:S3kJ7gaQ-9UCvVoVhArWgi_sNYy3UvdflQL8_wrNWh4Dx5CI9V_379RWNQKe5Nc_gNH_BwwoYg) **Learning transferable conceptual prototypes for interpretable unsupervised domain adaptation** [:octocat:](https://drive.google.com/file/d/1b1EHFghiF1ExD-Cn1HYg75VutfkXWp60/view?usp=sharing)
  - 简介（中文）: 学习可迁移/可跨域的概念原型，用于无监督域自适应与解释。
  - Intro (EN): Learns transferable conceptual prototypes for unsupervised domain adaptation with transparent reasoning.
 
<img width="1487" height="509" alt="image" src="https://github.com/user-attachments/assets/ffe2fe4a-7dd2-4010-81b7-b728e774b907" />

- [[2024-WACV]](https://openaccess.thecvf.com/content/WACV2024/papers/Wan_Interpretable_Object_Recognition_by_Semantic_Prototype_Analysis_WACV_2024_paper.pdf) **Interpretable object recognition by semantic prototype analysis** [:octocat:](https://github.com/WanQiyang/SPANet)
  - 简介（中文）: 以语义原型分析物体识别，把类别特征拆解为可命名的部件。
  - Intro (EN): Analyzes object recognition via semantic prototypes, decomposing categories into nameable parts.
 
<img width="1301" height="703" alt="image" src="https://github.com/user-attachments/assets/cc1210f9-b11f-49e5-8b83-3b63175cf3dd" />

- [[2024-xAI]](https://arxiv.org/pdf/2404.14830) **CoProNN: Concept-Based Prototypical Nearest Neighbors for Explaining Vision Models** [:octocat:](https://github.com/TeodorChiaburu/beexplainable)
  - 简介（中文）: 以概念为中心的原型近邻方法：用可命名概念匹配相似样本。
  - Intro (EN): Concept-centric prototypical nearest neighbors that match samples via nameable concepts.
 
<img width="1463" height="862" alt="image" src="https://github.com/user-attachments/assets/b7d45420-8f2a-4202-9aae-ff9655fe39eb" />

- [[2025-AAAI]](https://ojs.aaai.org/index.php/AAAI/article/view/32173) **ProtoArgNet: Interpretable Image Classification with Super-Prototypes and Argumentation** [:octocat:](https://github.com/H-Ayoobi/ProtoArgNet_AAAI)
  - 简介（中文）: 提出‘超原型+论证’机制，让不同原型提供支持/反驳证据，生成可辩护的结论。
  - Intro (EN): Introduces super-prototypes and argumentation: prototypes can support or refute a decision for defendable conclusions.
 
<img width="1461" height="465" alt="image" src="https://github.com/user-attachments/assets/40487c43-fe9e-44a6-a35a-56237cac08bb" />

- [[2025-TNNLS]](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=10966440&casa_token=GgRZS965NTIAAAAA:OpRKYiHPFe85mP-ZRcXEF7c_jN2g0d0h_ba4E4K1fj4jeD5KWluGnsYX5gFGPKMGm3YuB6RX2A) **TraNCE: Transformative Nonlinear Concept Explainer for CNNs** [:octocat:](https://github.com/daslimo/TrANCE)
  - 简介（中文）: 提出可变换的非线性概念解释器，与CNN结合提高概念层可解释性。
  - Intro (EN): A nonlinear, transformable concept explainer for CNNs to improve concept-level interpretability.
<img width="1536" height="832" alt="image" src="https://github.com/user-attachments/assets/0297883a-777a-435d-86aa-3f8a869e9e0a" />

## <div id = "s6"></div> F. Training strategies, post-hoc, editable models 

- [[2024-arXiv]](https://arxiv.org/pdf/2406.14675?) **This looks better than that: Better interpretable models with protopnext** 
  - 简介（中文）: 统一多个原型部件模块的改进与训练流程，便于复现与公平比较。
  - Intro (EN): Unifies improvements and training practices for prototype-part models to ease reproduction and fair comparison.
 
<img width="1109" height="772" alt="image" src="https://github.com/user-attachments/assets/be12cf8b-7ca4-4280-a285-c8a44677cf28" />

- [[2024-ICML]](https://openreview.net/pdf?id=MlzUD5CKvZ) **Improving Prototypical Visual Explanations with Reward Reweighing, Reselection, and Retraining** [:octocat:](https://github.com/aaron-jx-li/R3-ProtoPNet)[[other source]](https://icml.cc/media/icml-2024/Slides/34227.pdf)
  - 简介（中文）: 通过重加权/重选/再训练提升原型解释的可用性与一致性。
  - Intro (EN): Reweight, reselect, and retrain to improve the usability and stability of prototype explanations.
 
<img width="1872" height="901" alt="image" src="https://github.com/user-attachments/assets/4a23c458-dbc3-40c4-951c-8b5b710d8b25" />

- [[2024-ICML]](https://openreview.net/pdf?id=jhWSzTO0Jl) **Post-hoc Part-Prototype Networks** [[other source]](https://hkustsmartlab.github.io/2024/06/08/icml/)
  - 简介（中文）: 在黑盒模型之上后验构建‘部件-原型’解释层，无需重训主干。
  - Intro (EN): Builds a post-hoc part-prototype layer on top of a black-box model without retraining the backbone.
 
<img width="1362" height="1028" alt="image" src="https://github.com/user-attachments/assets/e06572f9-c909-4817-a6f6-2b9f9bf647c0" />

- [[2025-CVPR]](https://openaccess.thecvf.com/content/CVPR2025/papers/Donnelly_Rashomon_Sets_for_Prototypical-Part_Networks_Editing_Interpretable_Models_in_Real-Time_CVPR_2025_paper.pdf) **Rashomon sets for prototypical-part networks: Editing interpretable models in real-time** [:octocat:](https://github.com/jdonnelly36/proto-rset)
  - 简介（中文）: 刻画原型网络的‘拉绍蒙集合’，支持在等精度解空间内进行可控/实时编辑。
  - Intro (EN): Characterizes Rashomon sets for prototype networks, enabling controlled, real-time edits within equal-accuracy solutions.

<img width="779" height="439" alt="image" src="https://github.com/user-attachments/assets/03aca78c-3e4c-49f6-a2e4-e4b6c61e200b" />

## <div id = "s7"></div> G. Evaluation, benchmarks, critiques 

- [[2021-ICMLW]](https://arxiv.org/pdf/2105.02968) **This looks like that... does it? shortcomings of latent space prototype interpretability in deep networks** [[other source]]([https://icml.cc/media/icml-2024/Slides/34227.pdf](https://icml.cc/virtual/2021/11382))
  - 简介（中文）: 指出潜在空间中的“相似性”未必等价于输入空间的语义相似，系统性分析原型解释的陷阱。
  - Intro (EN): Analyzes pitfalls: similarity in latent space may not reflect semantic similarity in input space; cautions for prototype interpretability.
 
<img width="2175" height="517" alt="image" src="https://github.com/user-attachments/assets/c1be777e-c8d2-4d00-9855-87704a0d4f70" />

- [[2022-ECCV]](https://arxiv.org/pdf/2112.03184) **HIVE: Evaluating the human interpretability of visual explanations** [:octocat:](https://github.com/princetonvisualai/HIVE)[[]other source](https://princetonvisualai.github.io/HIVE/)
  - 简介（中文）: 从人类研究角度评测可解释性方法，提供更贴近人类认知的评估框架与指标。
  - Intro (EN): Human-grounded evaluation suite for interpretability, bringing cognitive validity to metrics.
 
<img width="1287" height="664" alt="image" src="https://github.com/user-attachments/assets/ccfe9962-58a8-425e-9790-c12f97132050" />

- [[2023-ICCV]](https://openaccess.thecvf.com/content/ICCV2023/papers/Huang_Evaluation_and_Improvement_of_Interpretability_for_Self-Explainable_Part-Prototype_Networks_ICCV_2023_paper.pdf) **Evaluation and improvement of interpretability for self-explainable part-prototype networks** [:octocat:](https://github.com/hqhQAQ/EvalProtoPNet)
  - 简介（中文）: 提出原型模型的量化评估与改进手段，关注原型质量、稳定性和可读性。
  - Intro (EN): Quantitatively evaluates and improves interpretability of self-explainable part-prototype networks.
 
<img width="1705" height="696" alt="image" src="https://github.com/user-attachments/assets/ea5c6cae-5136-4f4b-92ed-560d99533591" />

- [[2023-xAI]](https://arxiv.org/pdf/2307.14517) **The co-12 recipe for evaluating interpretable part-prototype image classifiers** 
  - 简介（中文）: 给出评测原型方法的一套‘配方’与协议，强调可复现、可量化的对比。
  - Intro (EN): Provides a reproducible 'recipe' to evaluate part-prototype methods with fair, quantitative comparisons.
 
<img width="1114" height="755" alt="image" src="https://github.com/user-attachments/assets/5dcfb888-7026-451c-9949-245632f75c50" />

- [[2024-AAAI]](https://ojs.aaai.org/index.php/AAAI/article/view/30154) **Interpretability benchmark for evaluating spatial misalignment of prototypical parts explanations** [:octocat:](https://github.com/gmum/interpretability-benchmark)
  - 简介（中文）: 提出空间错位评测基准：原型激活与真实部位不对齐的问题被量化并可比较。
  - Intro (EN): Benchmarks spatial misalignment where prototype activations fail to align with true evidence regions.
 
<img width="1506" height="755" alt="image" src="https://github.com/user-attachments/assets/ca707e67-fd7d-4267-8086-beb0f3336a3c" />

- [[2024-AAAI]](https://ojs.aaai.org/index.php/AAAI/article/view/30109) **On the concept trustworthiness in concept bottleneck models** [:octocat:](https://github.com/hqhQAQ/ProtoCBM)
  - 简介（中文）: 讨论概念瓶颈模型的概念可信度，提醒概念误标或漂移的风险。
  - Intro (EN): Studies concept bottleneck trustworthiness, warning against mislabeled or drifting concepts.
 
<img width="1455" height="647" alt="image" src="https://github.com/user-attachments/assets/071b6dbf-4257-40a4-b471-b8e3bef366d0" />

- [[2024-CVPRW]](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=10678010&casa_token=lqhBOsX5d7MAAAAA:4QCVH9ep9WEyQt9OMjfxH_vqrxKOKLN1qkZNhiIk1-wQ5dm_omZ-9f7EUI_wKshDgeooaAacgg) **Understanding the (extra-) ordinary: Validating deep model decisions with prototypical concept-based explanations** [:octocat:](https://github.com/maxdreyer/pcx)
  - 简介（中文）: 通过原型概念验证模型决策是否符合常识/领域知识，识别‘平凡/非平凡’证据。
  - Intro (EN): Validates whether decisions rely on ordinary vs. extra-ordinary prototypical concepts, aligning with domain knowledge.
 
<img width="1599" height="485" alt="image" src="https://github.com/user-attachments/assets/f3c4ca26-e7f2-4966-bc75-ecca9e619039" />

- [[2024-xAI]](https://arxiv.org/pdf/2404.09917?) **Evaluating the Explainability of Attributes and Prototypes for a Medical Classification Model** [:octocat:](https://github.com/XRad-Ulm/Proto-Caps)
  - 简介（中文）: 评估医疗模型中‘属性+原型’解释的可靠性与临床可用性。
  - Intro (EN): Evaluates the reliability and clinical utility of attribute+prototype explanations in medical models.
 
<img width="1004" height="742" alt="image" src="https://github.com/user-attachments/assets/9c2b9ca5-5178-479a-bf18-913580895bd2" />

- [[2024-xAI]](https://arxiv.org/pdf/2408.11401) **Revisiting FunnyBirds evaluation framework for prototypical parts networks** [:octocat:](https://github.com/hamer101/FunnyBirds_PrototypesRevisited)
  - 简介（中文）: 重审FunnyBirds框架，提示原型方法的评测陷阱与改进方向。
  - Intro (EN): Revisits the FunnyBirds framework to highlight pitfalls and fixes in prototype evaluation.

<img width="924" height="299" alt="image" src="https://github.com/user-attachments/assets/c2a48b79-174b-42d2-82df-7927ac82ef7e" />

## <div id = "s8"></div> H. Surveys 

- [[2024-biomedinformatics]](https://www.mdpi.com/2673-7426/4/4/115) **Part-Prototype Models in Medical Imaging Applications and Current Challenges** [:octocat:](#)
  - 简介（中文）: 医学影像原型方法综述，系统梳理应用、挑战与未来方向。
  - Intro (EN): Survey of prototype-based methods in medical imaging: applications, challenges, and future directions.
 
<img width="1465" height="587" alt="image" src="https://github.com/user-attachments/assets/a658d102-231a-413e-8524-70077f43928c" />

- [[2024-xAI]](https://arxiv.org/pdf/2403.20260) **Prototype-based interpretable breast cancer prediction models: Analysis and challenges** [:octocat:](https://github.com/ShreyasiPathak/multiinstance-learning-mammography)[:octocat:](https://github.com/ShreyasiPathak/prototype-based-breast-cancer-prediction)
  - 简介（中文）: 乳腺影像方向的原型方法综述与挑战梳理。
  - Intro (EN): Review and challenges in breast imaging with prototype-based models.
<img width="830" height="738" alt="image" src="https://github.com/user-attachments/assets/fe6c947a-e930-4deb-996a-2c9d5884c3c5" />

## <div id = "s9"></div> I. Tasks (segmentation, keypoint, regression, UDA, MIL, multi-label) 

- [[2021-SIGKDD]](https://dl.acm.org/doi/pdf/10.1145/3447548.3467245) **Protopshare: Prototypical parts sharing for similarity discovery in interpretable image classification** [:octocat:](https://github.com/gmum/ProtoPShare)
  - 简介（中文）: 提出“原型部件共享”，在类别之间共享或迁移典型部件，提升样本效率与可解释性。
  - Intro (EN): Proposes prototypical part sharing across classes to improve sample efficiency and interpretability.
 
<img width="1322" height="352" alt="image" src="https://github.com/user-attachments/assets/00adfde3-1b50-48e4-9a6b-60a402fce49f" />

- [[2022-MICCAI]](https://arxiv.org/pdf/2208.00457) **INSightR-Net: interpretable neural network for regression using similarity-based comparisons to prototypical examples** [:octocat:](https://github.com/lindehesse/INSightR-Net)
  - 简介（中文）: 基于相似度比较的可解释回归：用原型作为参照进行连续数值预测与解释。
  - Intro (EN): Similarity-based interpretable regression using prototypes as reference points for continuous predictions.
 
<img width="1382" height="641" alt="image" src="https://github.com/user-attachments/assets/6611a8a1-da2d-4644-afee-3690cbea92a2" />

- [[2023-CVPR]](https://openaccess.thecvf.com/content/ICCV2023/papers/Rymarczyk_ICICLE_Interpretable_Class_Incremental_Continual_Learning_ICCV_2023_paper.pdf) **Icicle: Interpretable class incremental continual learning** [:octocat:](https://github.com/gmum/ICICLE)
  - 简介（中文）: 面向增量学习的原型方法：在新类到来时保持旧类解释的一致性与稳定性。
  - Intro (EN): Prototype-based continual learning that maintains explanation consistency as new classes arrive.
 
<img width="1380" height="849" alt="image" src="https://github.com/user-attachments/assets/27d7a7c1-4b7d-4b7f-a4be-8f4412983427" />

- [[2023-ICLR]](https://openreview.net/forum?id=lh-HRYxuoRr) **This Looks Like It Rather Than That: ProtoKNN For Similarity-Based Classifiers** 
  - 简介（中文）: 以近邻/非参数方式实现“这像哪一些”：减少训练时的参数化假设，强调基于库的相似实例证据。
  - Intro (EN): Non-parametric, nearest-neighbor flavored 'this looks like those' using stored exemplars instead of heavy parametrization.
 
<img width="1302" height="578" alt="image" src="https://github.com/user-attachments/assets/45d2a3d4-e728-431a-a7e9-248d654ac4c3" />

- [[2023-WACV]](https://openaccess.thecvf.com/content/WACV2023/papers/Sacha_ProtoSeg_Interpretable_Semantic_Segmentation_With_Prototypical_Parts_WACV_2023_paper.pdf) **Protoseg: Interpretable semantic segmentation with prototypical parts** [:octocat:](https://github.com/gmum/proto-segmentation)
  - 简介（中文）: 把‘部件原型’扩展到语义分割，像素级显示“这块区域像哪种原型”。
  - Intro (EN): Extends part-prototypes to semantic segmentation, grounding 'which region looks like which prototype' at pixel level.
 
<img width="1577" height="597" alt="image" src="https://github.com/user-attachments/assets/e00a15d9-d421-439c-91d5-b42797f40c26" />

- [[2024-MICCAI]](https://arxiv.org/pdf/2406.12577) **Cephalometric Landmark Detection across Ages with Prototypical Network** [:octocat:](https://github.com/ShanghaiTech-IMPACT/CeLDA)
  - 简介（中文）: 面向头影测量的关键点检测，引入原型先验以提升跨年龄泛化。
  - Intro (EN): Keypoint localization for cephalometric analysis with prototype priors to generalize across ages.
 
<img width="1363" height="791" alt="image" src="https://github.com/user-attachments/assets/841a4c74-dd49-46cc-a2fb-767364af0328" />

- [[2024-MICCAI]](https://papers.miccai.org/miccai-2024/paper/1022_paper.pdf) **Pamil: Prototype attention-based multiple instance learning for whole slide image classification** [:octocat:](https://github.com/Jiashuai-Liu/PAMIL)
  - 简介（中文）: 在WSI多实例学习中引入‘原型注意力’，实现病理切片的弱监督可解释分类。
  - Intro (EN): Prototype attention for MIL on whole-slide images, enabling weakly supervised, interpretable pathology classification.
 
<img width="1312" height="583" alt="image" src="https://github.com/user-attachments/assets/9f56e1ac-1b2e-4693-8f12-e6edf834b4b4" />

- [[2024-TIP]](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=10684084&casa_token=o3YFdb-f9QMAAAAA:S3kJ7gaQ-9UCvVoVhArWgi_sNYy3UvdflQL8_wrNWh4Dx5CI9V_379RWNQKe5Nc_gNH_BwwoYg) **Learning transferable conceptual prototypes for interpretable unsupervised domain adaptation** [:octocat:](https://drive.google.com/file/d/1b1EHFghiF1ExD-Cn1HYg75VutfkXWp60/view?usp=sharing)
  - 简介（中文）: 学习可迁移/可跨域的概念原型，用于无监督域自适应与解释。
  - Intro (EN): Learns transferable conceptual prototypes for unsupervised domain adaptation with transparent reasoning.
 
<img width="1505" height="497" alt="image" src="https://github.com/user-attachments/assets/d1ad57d4-257a-4ac1-818f-01bbd9bba655" />

- [[2025-TMI]](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=10887396&casa_token=k4AqViOwfRMAAAAA:HMgKNev3t3lNTofW5OCWKhlzvyqv5Gg0JQaIV5iqu77j_iMDYr8Ng6cg2uIxYVS3xljVRjb8qA&tag=1) **Cross-and intra-image prototypical learning for multi-label disease diagnosis and interpretation** [:octocat:](https://github.com/cwangrun/CIPL)
  - 简介（中文）: 同时在图内/图间学习原型，支持多标签疾病诊断与解释。
  - Intro (EN): Learns prototypes within and across images to support multi-label diagnosis with explanations.
<img width="1328" height="618" alt="image" src="https://github.com/user-attachments/assets/aebb6e22-4d19-469b-98fd-db5fba698a41" />

## <div id = "s10"></div> J. Medical imaging 

### <div id = "s101"></div> J1. Brain — Alzheimer’s (MRI) 

- [[2024-MICCAI]](https://arxiv.org/pdf/2403.18328) **Pipnet3d: Interpretable detection of alzheimer in mri scans** 
  - 简介（中文）: 以Patch为粒度学习直观原型，突出“局部贴片—概念”的对应关系，方便人工校验与纠错。
  - Intro (EN): Learns intuitive patch-level prototypes mapping local image patches to human-meaningful parts for easy auditing and correction.
    
<img width="1026" height="458" alt="image" src="https://github.com/user-attachments/assets/c17e9ecc-2ddd-464a-aa7f-002f2845bf7f" />

### <div id = "s102"></div> J2. Brain — Tumor (MRI / mpMRI) 

- [[2024-MIDL]](https://proceedings.mlr.press/v227/wei24a/wei24a.pdf) **Mprotonet: A case-based interpretable model for brain tumor classification with 3d multi-parametric magnetic resonance imaging** [:octocat:](https://github.com/aywi/mprotonet)
  - 简介（中文）: 3D多参数MRI上的病例式原型模型，为脑肿瘤分类提供可解释证据。
  - Intro (EN): Case-based prototype model on 3D multi-parametric MRI for brain tumor classification.
  
<img width="1760" height="902" alt="image" src="https://github.com/user-attachments/assets/264db642-df25-418a-a918-b26e40d2ea31" />

### <div id = "s103"></div> J3. Breast — Digital Mammography 

- [[2021-NMI]](https://arxiv.org/pdf/2103.12308) **A case-based interpretable deep learning model for classification of mass lesions in digital mammography** [:octocat:](https://github.com/alinajadebarnett/iaiabl)
  - 简介（中文）: 在数字乳腺X线中构建病例式原型证据，辅助良恶性肿块分类并提供可视化解释。
  - Intro (EN): Case-based prototype evidence for digital mammography, assisting benign/malignant mass classification with visual rationale.
 
<img width="1258" height="447" alt="image" src="https://github.com/user-attachments/assets/bab2cb08-960d-45a9-8148-d6f9356a8bb1" />

- [[2024-CVPR Workshop]](https://openaccess.thecvf.com/content/CVPR2024W/DEF-AI-MIA/papers/Yang_FPN-IAIA-BL_A_Multi-Scale_Interpretable_Deep_Learning_Model_for_Classification_of_CVPRW_2024_paper.pdf) **FPN-IAIA-BL: A Multi-Scale Interpretable Deep Learning Model for Classification of Mass Margins in Digital Mammography** 
  - 简介（中文）: 在乳腺钼靶的‘肿块边缘’分类中引入多尺度原型，兼顾局部纹理与全局结构。
  - Intro (EN): Multi-scale prototype model for breast mass margin classification, capturing local texture and global structure.
    
<img width="1030" height="365" alt="image" src="https://github.com/user-attachments/assets/32da1ba6-136d-4861-9b41-0b0bbcf2ecad" />

### <div id = "s104"></div> J4. Chest — Chest X-ray (CXR/COVID-19) 

- [[2021-CVPR]](https://openaccess.thecvf.com/content/CVPR2021/papers/Kim_XProtoNet_Diagnosis_in_Chest_Radiography_With_Global_and_Local_Explanations_CVPR_2021_paper.pdf) **Xprotonet: diagnosis in chest radiography with global and local explanations** 
  - 简介（中文）: 面向胸部X光的原型网络：同时给出全局与局部的可视化证据，适配临床判读习惯。
  - Intro (EN): Prototype network for chest radiographs: delivers both global and local visual rationales aligned with clinical reading.
 
<img width="1273" height="497" alt="image" src="https://github.com/user-attachments/assets/801c78b4-35a5-4a84-9251-94e0f33229d1" />

- [[2021-IEEE Access]](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9448270) **An Interpretable Deep Learning Model for Covid-19 Detection With Chest X-Ray Images** 
  - 简介（中文）: 将原型式证据用于COVID-19胸片分类，展示病例式对照与可视化说明。
  - Intro (EN): Applies case-based prototype evidence to COVID-19 CXR classification with visual justifications.
    
<img width="1638" height="572" alt="image" src="https://github.com/user-attachments/assets/a443cf5f-20bf-4e1b-975a-396ba9cfda88" />

### <div id = "s105"></div> J5. Cephalometric / Dental X-ray (Keypoint) 

- [[2024-MICCAI]](https://arxiv.org/pdf/2406.12577) **Cephalometric Landmark Detection across Ages with Prototypical Network** [:octocat:](https://github.com/ShanghaiTech-IMPACT/CeLDA)
  - 简介（中文）: 面向头影测量的关键点检测，引入原型先验以提升跨年龄泛化。
  - Intro (EN): Keypoint localization for cephalometric analysis with prototype priors to generalize across ages.
 
<img width="1350" height="790" alt="image" src="https://github.com/user-attachments/assets/27ff2f1f-733b-4fea-8705-7743fcac9306" />

### <div id = "s106"></div> J6. Pathology — Whole Slide Images (WSI / MIL) 

- [[2023-JBHI]](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=10290723&casa_token=3ayrYdj6bekAAAAA:ND9zMo8PowTyi_hywubBzd7YzKCFIp4hlVR3PI6yDoVBye3j6SCoequKrnACUhRoPQp7H_cP3A) **Interpretable inference and classification of tissue types in histological colorectal cancer slides based on ensembles adaptive boosting prototype tree** 
  - 简介（中文）: 基于集成/Boosting的原型树，在病理切片上解释组织类型判别。
  - Intro (EN): Ensemble/boosted prototype trees for tissue classification on histology slides with transparent rules.
    
<img width="1414" height="992" alt="image" src="https://github.com/user-attachments/assets/85a1c314-6646-44b4-a0ac-6c14164a3770" />

### <div id = "s107"></div> J7. Retina — Fundus Imaging 

- [[2025-JBHI_UR]](https://arxiv.org/pdf/2506.10669) **PiPViT: Patch-based Visual Interpretable Prototypes for Retinal Image Analysis** [:octocat:](https://github.com/marziehoghbaie/PiPViT)
  - 简介（中文）: 在眼底图像上把Patch原型与ViT结合，兼顾细粒度病变与全局结构。
  - Intro (EN): Combines patch prototypes and ViTs for retinal imaging to capture fine lesions and global structures.
    
<img width="2029" height="672" alt="image" src="https://github.com/user-attachments/assets/1f8556e8-2a38-447c-b576-58b0be002d95" />

### <div id = "s108"></div> J8. Dermatology — Skin Lesions 

- [[2023-MICCAIW]](https://arxiv.org/pdf/2402.01410) **XAI for Skin Cancer Detection with Prototypes and Non-Expert Supervision** [:octocat:](https://github.com/MiguelC23/XAI-Skin-Cancer-Detection-A-Prototype-Based-Deep-Learning-Architecture-with-Non-Expert-Supervision)
  - 简介（中文）: 在皮肤病变分析中引入原型与非专家标注，探索低成本可解释诊断。
  - Intro (EN): Applies prototypes to skin lesion analysis with non-expert supervision to lower annotation cost.
  - 
<img width="1145" height="592" alt="image" src="https://github.com/user-attachments/assets/0fa79af0-ddff-4355-bb99-46ed491c9b42" />

### <div id = "s109"></div> J9. General / Multi-organ Frameworks (Medical) 

- [[2021-CCAI]](https://assets.pubpub.org/gzl17h3e/21624570427985.pdf) **Using ProtoPNet for Interpretable Alzheimer's Disease Classification**
  - 简介（中文）: 面向医学影像场景；通过将图像局部与学习到的原型匹配，给出‘这看起来像那’的直观证据。
  - Intro (EN): Medical imaging focus. Matches image regions to learned prototypes to provide intuitive 'this looks like that' evidence.
 
<img width="1056" height="583" alt="image" src="https://github.com/user-attachments/assets/99e9312c-8ad2-4fcd-982b-3a3e67829a8e" />

- [[2023-IPMI]](https://arxiv.org/pdf/2303.07125) **Don't panic: Prototypical additive neural network for interpretable classification of alzheimer's disease** [:octocat:](https://github.com/ai-med/PANIC)
  - 简介（中文）: 在AD诊断中提出加性原型结构，提供病例式证据并增强鲁棒性。
  - Intro (EN): Introduces an additive prototype architecture for AD diagnosis with case-based evidence and robustness.
 
<img width="1018" height="416" alt="image" src="https://github.com/user-attachments/assets/b43f02c3-3a3a-4470-a957-86ed92779689" />

- [[2023-TMI]](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=10225391&casa_token=4OiWhQrFMNAAAAAA:H1Mlkp0_Epb1XXxRVOgfKA2aUS9-Znn6z-Ki2qRb5dR56te1mXNQgzjOWNK2_kbUvtkA9KgC2w) **An Interpretable and Accurate Deep-Learning Diagnosis Framework Modeled With Fully and Semi-Supervised Reciprocal Learning** 
  - 简介（中文）: 提出全/半监督互惠学习框架，与原型证据结合以兼顾性能与可解释。
  - Intro (EN): Fully & semi-supervised reciprocal learning combined with prototype evidence for a balanced accuracy-interpretability tradeoff.
 
<img width="893" height="272" alt="image" src="https://github.com/user-attachments/assets/b69c4f8c-3020-4872-b831-e73c07602af9" />

- [[2024-arXiv]](https://arxiv.org/pdf/2404.08917?) **Maprotonet: A multi-scale attentive interpretable prototypical part network for 3d magnetic resonance imaging brain tumor classification** [:octocat:](https://github.com/TUAT-Novice/maprotonet)
  - 简介（中文）: 面向3D脑肿瘤MRI的多尺度注意力原型网络，给出体素/块级的病例式证据。
  - Intro (EN): Multi-scale attentive prototypical parts for 3D brain tumor MRI with case-based volumetric evidence.
 
<img width="1196" height="595" alt="image" src="https://github.com/user-attachments/assets/f7dacfa1-c1b8-4f50-a657-91c1b72f22ab" />

- [[2024-CEURW]](https://arxiv.org/pdf/2407.14277) **Patch-based Intuitive Multimodal Prototypes Network (PIMPNet) for Alzheimer's Disease classification** 
  - 简介（中文）: 面向医学影像场景、强调局部Patch/像素或可逆/可形变机制；通过将图像局部与学习到的原型匹配，给出‘这看起来像那’的直观证据。
  - Intro (EN): Medical imaging focus; Emphasizes patches/pixels, or deformable/invertible mechanisms. Matches image regions to learned prototypes to provide intuitive 'this looks like that' evidence.
 
<img width="1327" height="877" alt="image" src="https://github.com/user-attachments/assets/07cb35e1-b54f-476f-8871-025b291cfb01" />

- [[2025-JBHI]](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=10856378&casa_token=1z-wtqmro8kAAAAA:kIrMO-_DNuwAtVTtMmuFJzqVb1kvvx3JzLojqSi16xSCmoTfNpQjK43THD93A_VQjXYGAxt3ew) **FeaInfNet: Diagnosis of Medical Images with Feature-Driven Inference and Visual Explanations** [:octocat:](https://github.com/YTPLAB/FeaInfNet)
  - 简介（中文）: 以特征驱动推理结合可视化解释，用于多类医学诊断。
  - Intro (EN): Feature-driven inference with visual explanations for multi-class medical diagnosis.
 
<img width="1042" height="655" alt="image" src="https://github.com/user-attachments/assets/6035a02f-c9e7-43fa-930c-cd2c4a1a5cb4" />

- [[2025-TMI]](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=10887396&casa_token=k4AqViOwfRMAAAAA:HMgKNev3t3lNTofW5OCWKhlzvyqv5Gg0JQaIV5iqu77j_iMDYr8Ng6cg2uIxYVS3xljVRjb8qA&tag=1) **Cross-and intra-image prototypical learning for multi-label disease diagnosis and interpretation** [:octocat:](https://github.com/cwangrun/CIPL)
  - 简介（中文）: 同时在图内/图间学习原型，支持多标签疾病诊断与解释。
  - Intro (EN): Learns prototypes within and across images to support multi-label diagnosis with explanations.
    
<img width="1308" height="626" alt="image" src="https://github.com/user-attachments/assets/afd83cea-9819-48b6-a1d1-d6d4eea2f8c9" />

## <div id = "s11"></div> K. Patch/Part/Pixel 

- [[2021-SIGKDD]](https://dl.acm.org/doi/pdf/10.1145/3447548.3467245) **Protopshare: Prototypical parts sharing for similarity discovery in interpretable image classification** [:octocat:](https://github.com/gmum/ProtoPShare)
  - 简介（中文）: 提出“原型部件共享”，在类别之间共享或迁移典型部件，提升样本效率与可解释性。
  - Intro (EN): Proposes prototypical part sharing across classes to improve sample efficiency and interpretability.

<img width="1202" height="457" alt="image" src="https://github.com/user-attachments/assets/af7694d4-5b2b-4cf1-b004-fde7600f93ef" />

- [[2023-CVPR]](https://openaccess.thecvf.com/content/CVPR2023/papers/Nauta_PIP-Net_Patch-Based_Intuitive_Prototypes_for_Interpretable_Image_Classification_CVPR_2023_paper.pdf) **Pip-net: Patch-based intuitive prototypes for interpretable image classification** [:octocat:](https://github.com/M-Nauta/PIPNet)
  - 简介（中文）: 以Patch为粒度学习直观原型，突出“局部贴片—概念”的对应关系，方便人工校验与纠错。
  - Intro (EN): Learns intuitive patch-level prototypes mapping local image patches to human-meaningful parts for easy auditing and correction.

<img width="1665" height="441" alt="image" src="https://github.com/user-attachments/assets/7f70f2fc-76c1-4ca1-9ab8-117b2acc0353" />

- [[2023-ICCV]](https://openaccess.thecvf.com/content/ICCV2023/papers/Huang_Evaluation_and_Improvement_of_Interpretability_for_Self-Explainable_Part-Prototype_Networks_ICCV_2023_paper.pdf) **Evaluation and improvement of interpretability for self-explainable part-prototype networks** [:octocat:](https://github.com/hqhQAQ/EvalProtoPNet)
  - 简介（中文）: 提出原型模型的量化评估与改进手段，关注原型质量、稳定性和可读性。
  - Intro (EN): Quantitatively evaluates and improves interpretability of self-explainable part-prototype networks.

<img width="1705" height="696" alt="image" src="https://github.com/user-attachments/assets/ea5c6cae-5136-4f4b-92ed-560d99533591" />

- [[2023-ICLR]](https://openreview.net/forum?id=oiwXWPDTyNk) **Concept-level Debugging of Part-Prototype Networks** [:octocat:](https://github.com/abonte/protopdebug)
  - 简介（中文）: 在‘概念层’调试原型网络：发现并修复误导性概念，从而改善预测与解释。
  - Intro (EN): Debugs part-prototype networks at the concept level, fixing misleading concepts to improve both accuracy and explanations.

<img width="1435" height="479" alt="image" src="https://github.com/user-attachments/assets/08d1e8ae-3981-424a-9866-701dbe107d24" />

- [[2023-WACV]](https://openaccess.thecvf.com/content/WACV2023/papers/Sacha_ProtoSeg_Interpretable_Semantic_Segmentation_With_Prototypical_Parts_WACV_2023_paper.pdf) **Protoseg: Interpretable semantic segmentation with prototypical parts** [:octocat:](https://github.com/gmum/proto-segmentation)
  - 简介（中文）: 把‘部件原型’扩展到语义分割，像素级显示“这块区域像哪种原型”。
  - Intro (EN): Extends part-prototypes to semantic segmentation, grounding 'which region looks like which prototype' at pixel level.

<img width="1595" height="608" alt="image" src="https://github.com/user-attachments/assets/074b11c2-6ef4-40e5-8cb1-fff90f0225ad" />

- [[2023-xAI]](https://arxiv.org/pdf/2307.14517) **The co-12 recipe for evaluating interpretable part-prototype image classifiers** 
  - 简介（中文）: 给出评测原型方法的一套‘配方’与协议，强调可复现、可量化的对比。
  - Intro (EN): Provides a reproducible 'recipe' to evaluate part-prototype methods with fair, quantitative comparisons.

<img width="1114" height="755" alt="image" src="https://github.com/user-attachments/assets/5dcfb888-7026-451c-9949-245632f75c50" />

- [[2024-AAAI]](https://ojs.aaai.org/index.php/AAAI/article/view/30154) **Interpretability benchmark for evaluating spatial misalignment of prototypical parts explanations** [:octocat:](https://github.com/gmum/interpretability-benchmark)
  - 简介（中文）: 提出空间错位评测基准：原型激活与真实部位不对齐的问题被量化并可比较。
  - Intro (EN): Benchmarks spatial misalignment where prototype activations fail to align with true evidence regions.

<img width="1506" height="755" alt="image" src="https://github.com/user-attachments/assets/ca707e67-fd7d-4267-8086-beb0f3336a3c" />

- [[2024-arXiv]](https://arxiv.org/pdf/2404.08917?) **Maprotonet: A multi-scale attentive interpretable prototypical part network for 3d magnetic resonance imaging brain tumor classification** [:octocat:](https://github.com/TUAT-Novice/maprotonet)
  - 简介（中文）: 面向3D脑肿瘤MRI的多尺度注意力原型网络，给出体素/块级的病例式证据。
  - Intro (EN): Multi-scale attentive prototypical parts for 3D brain tumor MRI with case-based volumetric evidence.

<img width="1196" height="595" alt="image" src="https://github.com/user-attachments/assets/f7dacfa1-c1b8-4f50-a657-91c1b72f22ab" />

- [[2024-biomedinformatics]](https://www.mdpi.com/2673-7426/4/4/115) **Part-Prototype Models in Medical Imaging Applications and Current Challenges** [:octocat:](#)
  - 简介（中文）: 医学影像原型方法综述，系统梳理应用、挑战与未来方向。
  - Intro (EN): Survey of prototype-based methods in medical imaging: applications, challenges, and future directions.

<img width="1465" height="587" alt="image" src="https://github.com/user-attachments/assets/a658d102-231a-413e-8524-70077f43928c" />

- [[2024-CEURW]](https://arxiv.org/pdf/2407.14277) **Patch-based Intuitive Multimodal Prototypes Network (PIMPNet) for Alzheimer's Disease classification** 
  - 简介（中文）: 面向医学影像场景、强调局部Patch/像素或可逆/可形变机制；通过将图像局部与学习到的原型匹配，给出‘这看起来像那’的直观证据。
  - Intro (EN): Medical imaging focus; Emphasizes patches/pixels, or deformable/invertible mechanisms. Matches image regions to learned prototypes to provide intuitive 'this looks like that' evidence.

<img width="1342" height="871" alt="image" src="https://github.com/user-attachments/assets/deb95825-bb48-4afe-92fb-330a670d5bbd" />

- [[2024-ICML]](https://openreview.net/pdf?id=jhWSzTO0Jl) **Post-hoc Part-Prototype Networks** [[other source]](https://hkustsmartlab.github.io/2024/06/08/icml/)
  - 简介（中文）: 在黑盒模型之上后验构建‘部件-原型’解释层，无需重训主干。
  - Intro (EN): Builds a post-hoc part-prototype layer on top of a black-box model without retraining the backbone.

<img width="1362" height="1028" alt="image" src="https://github.com/user-attachments/assets/e06572f9-c909-4817-a6f6-2b9f9bf647c0" />

- [[2024-IJCAI]](https://www.ijcai.org/proceedings/2024/168) **ProtoPFormer: Concentrating on Prototypical Parts in Vision Transformers for Interpretable Image Recognitio** [:octocat:](https://github.com/zju-vipa/ProtoPFormer)
  - 简介（中文）: 在ViT上专注于原型化的局部部件，抑制背景干扰，提升解释聚焦度。
  - Intro (EN): Prototype-focused ViT that suppresses background distraction, sharpening attention on meaningful parts.

<img width="1200" height="480" alt="image" src="https://github.com/user-attachments/assets/8246c5d1-feb1-460b-8ec7-69961b19d9f3" />

- [[2024-WACV]](https://openaccess.thecvf.com/content/WACV2024/papers/Carmichael_Pixel-Grounded_Prototypical_Part_Networks_WACV_2024_paper.pdf) **Pixel-grounded prototypical part networks** [:octocat:](https://github.com/merlresearch/PixPNet)
  - 简介（中文）: 将原型显式对齐到像素层级与实例轮廓，缓解‘激活外溢’问题。
  - Intro (EN): Aligns prototypes to pixels and instance contours, mitigating activation spillover.

<img width="1840" height="525" alt="image" src="https://github.com/user-attachments/assets/3140a92b-334a-4ecd-a2d5-a4bf16c2424c" />

- [[2024-xAI]](https://arxiv.org/pdf/2408.11401) **Revisiting FunnyBirds evaluation framework for prototypical parts networks** [:octocat:](https://github.com/hamer101/FunnyBirds_PrototypesRevisited)
  - 简介（中文）: 重审FunnyBirds框架，提示原型方法的评测陷阱与改进方向。
  - Intro (EN): Revisits the FunnyBirds framework to highlight pitfalls and fixes in prototype evaluation.

<img width="924" height="299" alt="image" src="https://github.com/user-attachments/assets/c2a48b79-174b-42d2-82df-7927ac82ef7e" />

- [[2025-JBHI_UR]](https://arxiv.org/pdf/2506.10669) **PiPViT: Patch-based Visual Interpretable Prototypes for Retinal Image Analysis** [:octocat:](https://github.com/marziehoghbaie/PiPViT)
  - 简介（中文）: 在眼底图像上把Patch原型与ViT结合，兼顾细粒度病变与全局结构。
  - Intro (EN): Combines patch prototypes and ViTs for retinal imaging to capture fine lesions and global structures.

<img width="2029" height="672" alt="image" src="https://github.com/user-attachments/assets/1f8556e8-2a38-447c-b576-58b0be002d95" />

- [[2025-CVPR]](https://openaccess.thecvf.com/content/CVPR2025/papers/Zhu_Interpretable_Image_Classification_via_Non-parametric_Part_Prototype_Learning_CVPR_2025_paper.pdf) **Interpretable Image Classification via Non-parametric Part Prototype Learning** [:octocat:](https://github.com/zijizhu/proto-non-param)
  - 简介（中文）: 学习非参数的部件原型集合，减少强假设并提升可编辑性。
  - Intro (EN): Learns non-parametric sets of part prototypes, reducing assumptions and enhancing editability.

<img width="1389" height="776" alt="image" src="https://github.com/user-attachments/assets/5fdc93f5-d1dd-4b19-931c-db51a6ee8f39" />

- [[2025-CVPR]](https://openaccess.thecvf.com/content/CVPR2025/papers/Donnelly_Rashomon_Sets_for_Prototypical-Part_Networks_Editing_Interpretable_Models_in_Real-Time_CVPR_2025_paper.pdf) **Rashomon sets for prototypical-part networks: Editing interpretable models in real-time** [:octocat:](https://github.com/jdonnelly36/proto-rset)
  - 简介（中文）: 刻画原型网络的‘拉绍蒙集合’，支持在等精度解空间内进行可控/实时编辑。
  - Intro (EN): Characterizes Rashomon sets for prototype networks, enabling controlled, real-time edits within equal-accuracy solutions.

<img width="779" height="439" alt="image" src="https://github.com/user-attachments/assets/03aca78c-3e4c-49f6-a2e4-e4b6c61e200b" />

- [[2025-CVPRW]](https://openaccess.thecvf.com/content/CVPR2025W/TCV/papers/Singh_ProtoPatchNet_An_Interpretable_Patch-Based_Prototypical_Network_CVPRW_2025_paper.pdf) **ProtoPatchNet: An Interpretable Patch-Based Prototypical Network** 
  - 简介（中文）: 基于Patch的原型网络，强调可组合的局部证据与简洁的可视化。
  - Intro (EN): Patch-based prototypical network with composable local evidence and concise visualization.

<img width="1388" height="532" alt="image" src="https://github.com/user-attachments/assets/5c7f7211-3d6d-444b-b11e-f6af5556e916" />

- [[2025-ICASSP]](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=10890753&casa_token=CK3WkOK9TVsAAAAA:pBren1C90XkdKu7gUBnv5ReeSpxZ0zmhf2FeYqh-2t0gPXfpQPYsMb9onOdSyABmObSQkB_7dQ) **Prototypical Part Transformer for Interpretable Image Recognition**
  - 简介（中文）: 把部件原型与Transformer结构结合，统一表示学习与解释。
  - Intro (EN): Integrates part prototypes into a Transformer, unifying representation and explanation.

<img width="1275" height="417" alt="image" src="https://github.com/user-attachments/assets/0178283a-d91c-49a4-8657-85b17888c718" />

- [[2025-ICCVW_BEW]](https://openreview.net/forum?id=PcF9Q51rF1&noteId=KSZAX91CoY) **HAPPI: Hyperbolic Hierarchical Part Prototypes for Image Recognition** 
  - 简介（中文）: 在超曲几何中学习层级原型，提升层次结构表达与相似度度量。
  - Intro (EN): Learns hierarchical prototypes in hyperbolic geometry to better encode tree-like relations.

<img width="1603" height="716" alt="image" src="https://github.com/user-attachments/assets/0c690ab4-4ffc-42a4-9d0d-024ea040a7f9" />

- [[2025-ICLR]](https://openreview.net/forum?id=BM9qfolt6p) **LucidPPN: Unambiguous prototypical parts network for user-centric interpretable computer vision** [:octocat:](https://github.com/mateuszpach/LucidPPN)
  - 简介（中文）: 提出‘无歧义’原型部件学习，减少原型混淆并提高人类可读性。
  - Intro (EN): Targets unambiguous prototype parts to reduce confusion and improve human readability.

<img width="1137" height="847" alt="image" src="https://github.com/user-attachments/assets/76941c75-239b-46ad-a88b-27bb84481950" />

## 🙏 Acknowledgements
We thank the authors of the cited papers and the open-source community for their contributions.  
We also appreciate everyone who has submitted PRs and issues.  
This list is compiled for academic reference only; copyrights for the papers belong to their respective authors and publishers.

## 🤝 Contributing
PRs/Issues are welcome! Please follow this minimal schema:
```
- year: 2025
  venue: CVPR
  title: Interpretable Image Classification via Non-parametric Part Prototype Learning
  link_pdf: https://...
  link_code: https://github.com/...
  tags: [K, D2]        # A–K (multi-label), and J subcategories if applicable
  tasks: [classification, segmentation]
  modality: [natural, fundus, WSI]
  notes_en: One-line summary
```

## 💞 Citation

```
@misc{jia2025,
  author = {Jia, Junhao and Sun, Yifei and Liu, Yunyou and Chen, Huangwei and Jiang, Shuo and Lin, Huangxing and Luo, Ziyan and Zheng, Hanwen and Shi, Yuting},
  title = {Paper List for Prototypical Learning},
  year = {2025},
  publisher = {GitHub},
  journal = {GitHub repository},
  howpublished = {\url{https://github.com/BeistMedAI/Paper-List-for-Prototypical-Learning}}
}
```

  ## 🥰 Star History
<div id = "s0"></div>

[![Star History Chart](https://api.star-history.com/svg?repos=BeistMedAI/Paper-List-for-Prototypical-Learning&type=Timeline)](https://www.star-history.com/#BeistMedAI/Paper-List-for-Prototypical-Learning&Timeline)

[![](https://capsule-render.vercel.app/api?type=waving&height=200&color=0:0F172A,65:4F46E5,100:22D3EE&text=Back%20to%20Top&section=footer&fontSize=30&fontAlignY=65&fontColor=FFFFFF)](#top)
