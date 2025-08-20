<a name="readme-head"></a>
<h1 align="center"> Awesome collection of all Concept Based Models <a href="https://github.com/debryu/Awesome-CBMs"><img src="figures/awesome.svg" alt="Awesome" width="120"></a></h1> 
<p align="center">
    ✨<b> Curated collection of papers and resources on latest advances of Concept based models.</b> ✨
</p>

<details open>
<summary>🗂️ <font size="4"><b>Table of Contents</b></font></summary>
<ol>
<li><a href="#-cbm-frameworks">📖 CBM Framework Papers</a></li>
  <ul>
    <li><a href="#cbms">👨‍⚕️ CBMs</a></li>
    <li><a href="#-vlm-cbms">🤖 VLM-CBMs</a></li>
  </ul>
<li><a href="#-discussions-and-analysis">🔬 Discussions and Analysis Papers</a></li>
<li><a href="#-awesome-surveys">📖 Awesome Surveys</a></li>
<li><a href="#-awesome-workshops--talks">👩‍🏫 Awesome Workshops & Talks</a></li>
<li><a href="#-awesome-metrics--benchmarks">📊 Awesome Metrics & Benchmarks</a></li>
<li><a href="#-awesome-datasets">💾 Awesome Datasets</a></li>
</ol>
</details>

<p align="center">
    🚧🚧🚧 <b>THIS IS UNDER CONSTRUCTION</b>🚧🚧🚧
</p>
<p align="center">
    Do not hesitate to submit a pull request if you want to add a reference or any correction!
</p>

## 📖 CBM Frameworks
### CBMs
Standard CBM framework where the data is annotated by a human expert.
|  Title  |   Venue  |   Date   |   Code   |
|:--------|:--------:|:--------:|:--------:|
| [TREE-BASED LEAKAGE INSPECTION AND CONTROL IN CONCEPT BOTTLENECK MODELS](https://arxiv.org/pdf/2410.06352) <br> | - | 2024 | [Github](https://github.com/ai4ai-lab/mixed-cbm-with-trees) |
| [Probabilistic Concept Bottleneck Models](https://arxiv.org/pdf/2306.01574) <br> | ICML | 2023 | [Github](https://github.com/ejkim47/prob-cbm) |
| [Interpretable neural-symbolic concept reasoning](https://arxiv.org/pdf/2304.14068) <br> | ICML | 2023 | [Github](https://github.com/pietrobarbiero/pytorch_explain) |
| [Logic explained networks](https://arxiv.org/pdf/2108.05149) <br> | AI Elsevier | 2023 | [Github](https://github.com/pietrobarbiero/logic_explained_networks) |
| [Interactive Concept Bottleneck Models](https://ojs.aaai.org/index.php/AAAI/article/view/25736) <br> | AAAI | 2023 | - |
| [Concept Embedding Models: Beyond the Accuracy-Explainability Trade-Off](https://arxiv.org/pdf/2209.09056) <br> | NeurIPS | 2022 | [Github](https://github.com/mateoespinosa/cem/) |
| [**GlanceNets: Interpretabile, Leak-proof Concept-based Models**](https://arxiv.org/pdf/2205.15612) <br> | NeurIPS | 2022 | [Github](https://github.com/ema-marconato/glancenet) |
| [Post-hoc Concept Bottleneck Models](https://arxiv.org/pdf/2205.15480.pdf) <br> | ICLR | 2022 | [Github](https://github.com/mertyg/post-hoc-cbm) |
| [Entropy-based Logic Explanations of Neural Networks](https://arxiv.org/pdf/2106.06804) <br> | AAAI | 2022 | [Github](https://github.com/pietrobarbiero/entropy-lens) |
| [Attention-based interpretability with concept transformers](https://openreview.net/pdf?id=kAa9eDS0RdO) <br> | ICLR | 2021 | [Github](https://github.com/ibm/concept_transformer) |
| [**Concept Bottleneck Model**](https://proceedings.mlr.press/v119/koh20a) <br> | ICML | 2020 | [Github](https://github.com/yewsiang/ConceptBottleneck) |
| [Concept Whitening for Interpretable Image Recognition](https://arxiv.org/pdf/2002.01650) <br> | Nature MI | 2020 | [Github](https://github.com/zhiCHEN96/ConceptWhitening) |
| [Now you see me (cme): concept-based model extraction](https://arxiv.org/pdf/2010.13233) <br> | - | 2020 | [Github](https://github.com/dmitrykazhdan/CME) |
| <br> |  |  | Github |

### 🤖 VLM-CBMs
The framework combines a Visual-Language model to generate concept annotations.
|  Title  |   Venue  |   Date   |   Code   |
|:--------|:--------:|:--------:|:--------:|
| [DCBM: Data-Efficient Visual Concept Bottleneck Models](https://arxiv.org/pdf/2412.11576) <br> | ICML | 2025 | [Github](https://github.com/KathPra/DCBM) |
| [Discover-then-Name: Task-Agnostic Concept Bottlenecks via Automated Concept Discovery](https://arxiv.org/pdf/2407.14499) <br> | ECCV | 2024 | [Github](https://github.com/neuroexplicit-saar/Discover-then-Name) |
| [Incremental Residual Concept Bottleneck Models](https://arxiv.org/pdf/2404.08978) <br> | CVPR | 2024 | [Github](https://github.com/HelloSCM/Res-CBM) |
| [VLG-CBM: Training Concept Bottleneck Models with Vision-Language Guidance](https://arxiv.org/pdf/2408.01432) <br> | NeurIPS | 2024 | [Github](https://github.com/Trustworthy-ML-Lab/VLG-CBM) |
| [CLIP-QDA: An Explainable Concept Bottleneck Model](https://arxiv.org/pdf/2312.00110) <br> | TMLR | 2024 | - |
| [Language in a Bottle: Language Model Guided Concept Bottlenecks for Interpretable Image Classification](https://arxiv.org/pdf/2211.11158.pdf) <br> | CVPR | 2023 | [Github](https://github.com/YueYANG1996/LaBo) |
| [Label Free Concept Bottleneck Models](https://arxiv.org/pdf/2304.06129.pdf) <br> | ICLR | 2023 | [Github](https://github.com/Trustworthy-ML-Lab/Label-free-CBM) |
| <br> |  |  | Github |



## 🔬 Discussions and Analysis
|  Title  |     Focus     |  Venue  |   Date   |   Code   |
|:--------|:-------------:|:-------:|:--------:|:--------:|
| [If Concept Bottlenecks are the Question, are Foundation Models the Answer?](https://arxiv.org/pdf/2504.19774) <br> | Concept Quality |  | 2025 | [Github](https://github.com/debryu/CQA) |
| [Overlooked Factors in Concept-based Explanations: Dataset Choice, Concept Learnability, and Human Capability](https://arxiv.org/pdf/2207.09615) <br> | Interpretability | CVPR | 2023 | Github |
| [A closer look at the intervention procedure of concept bottleneck models](https://arxiv.org/pdf/2302.14260.pdf) <br> | Interventions | ICML | 2023 | [Github](https://github.com/ssbin4/Closer-Intervention-CBM) |
| [IS DISENTANGLEMENT ALL YOU NEED? COMPARING CONCEPT-BASED & DISENTANGLEMENT APPROACHES](https://arxiv.org/pdf/2104.06917) <br> | Entanglement | ICLR | 2021 | [Github](https://github.com/dmitrykazhdan/concept-based-xai) |
| [Do Concept Bottleneck Models learn as intended](https://arxiv.org/abs/2105.04289) <br> | Alignment | ICLR | 2021 | - |
| [Promises and Pitfalls of Black-Box Concept Learning Models](https://arxiv.org/pdf/2106.13314.pdf)  <br> | Entanglement, Leakage | - | 2021 | - |
| [ON COMPLETENESS-AWARE CONCEPT-BASED EXPLANATIONS IN DEEP NEURAL NETWORKS](https://arxiv.org/pdf/1910.07969) <br> | Completeness | NeurIPS | 2020 | [Github](https://github.com/chihkuanyeh/concept_exp) |
| <br> |  |  |  | Github |


## 📖 Awesome Surveys
### Survey on Concept Based Models
- [Title](link) + year
- [Concept-based Explainable Artificial Intelligence: A Survey
](https://arxiv.org/pdf/2312.12936.pdf) 2023
- [A Comprehensive Survey on Self-Interpretable Neural Networks](https://arxiv.org/pdf/2501.15638) 2025


## 👩‍🏫 Awesome Workshops & Talks
- [title](link) [Workshop/Talk] + detail + venue + year

## 📊 Awesome Metrics & Benchmarks

## 💾 Awesome Datasets
