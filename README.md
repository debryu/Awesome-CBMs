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
<li><a href="#-awesome-workshops--talks">🛠️ Awesome Workshops & Talks</a></li>
<li><a href="#-awesome-metrics--benchmarks">📊 Awesome Metrics & Benchmarks</a></li>
<li><a href="#-awesome-datasets">💾 Awesome Datasets</a></li>
<li><a href="#-awesome-research-groups">👩‍🏫 Awesome Research Groups</a></li>
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
| [Interpretable Reward Modeling with Active Concept Bottlenecks](https://arxiv.org/pdf/2507.04695) <br> | ICML | 2025 | [Github](https://github.com/sonialagunac/cb-rm-workshop) |
| [Coarse-to-fine concept bottleneck models](https://proceedings.neurips.cc/paper_files/paper/2024/file/bdeab378efe6eb289714e2a5abc6ed42-Paper-Conference.pdf) <br> | NIPS | 2024 | [Github](https://github.com/konpanousis/Coarse-To-Fine-CBMs) |
| [Stochastic Concept Bottleneck Models](https://proceedings.neurips.cc/paper_files/paper/2024/file/5c7894ac8788555f1cecf536f1e0fd35-Paper-Conference.pdf) <br> | NIPS | 2024 | [Github](https://github.com/mvandenhi/SCBM) |
| [Contrastive pretraining for visual concept explanations of socioeconomic outcomes](https://openaccess.thecvf.com/content/CVPR2024W/EarthVision/papers/Obadic_Contrastive_Pretraining_for_Visual_Concept_Explanations_of_Socioeconomic_Outcomes_CVPRW_2024_paper.pdf) <br> | CVPR | 2024 | [Github](https://github.com/IvicaObadic/rnc-4-visual-concept-explanations) |
| [TREE-BASED LEAKAGE INSPECTION AND CONTROL IN CONCEPT BOTTLENECK MODELS](https://arxiv.org/pdf/2410.06352) <br> | - | 2024 | [Github](https://github.com/ai4ai-lab/mixed-cbm-with-trees) |
| [Concept-level Debugging of Part-Prototype Networks](https://arxiv.org/pdf/2205.15769) <br> | ICLR | 2023 | [Github](https://github.com/abonte/protopdebug) |
| [Probabilistic Concept Bottleneck Models](https://arxiv.org/pdf/2306.01574) <br> | ICML | 2023 | [Github](https://github.com/ejkim47/prob-cbm) |
| [Interpretable neural-symbolic concept reasoning](https://arxiv.org/pdf/2304.14068) <br> | ICML | 2023 | [Github](https://github.com/pietrobarbiero/pytorch_explain) |
| [Logic explained networks](https://arxiv.org/pdf/2108.05149) <br> | AI Elsevier | 2023 | [Github](https://github.com/pietrobarbiero/logic_explained_networks) |
| [Learning Bottleneck Concepts in Image Classification](https://arxiv.org/pdf/2304.10131) <br> | CVPR | 2023 | [Github](https://github.com/wbw520/BotCL) |
| [Sparse linear concept discovery models](https://openaccess.thecvf.com/content/ICCV2023W/CLVL/papers/Panousis_Sparse_Linear_Concept_Discovery_Models_ICCVW_2023_paper.pdf) <br> | ICCV-CLVL | 2023 | [Github](https://github.com/konpanousis/ConceptDiscoveryModels) |
| [Interactive Concept Bottleneck Models](https://ojs.aaai.org/index.php/AAAI/article/view/25736) <br> | AAAI | 2023 | - |
| [Addressing leakage in concept bottleneck models]([https://arxiv.org/pdf/2209.09056](https://proceedings.neurips.cc/paper_files/paper/2022/file/944ecf65a46feb578a43abfd5cddd960-Paper-Conference.pdf) <br> | NeurIPS | 2022 | [Github](https://github.com/dtak/addressing-leakage) |
| [Concept Embedding Models: Beyond the Accuracy-Explainability Trade-Off](https://arxiv.org/pdf/2209.09056) <br> | NeurIPS | 2022 | [Github](https://github.com/mateoespinosa/cem/) |
| [**GlanceNets: Interpretabile, Leak-proof Concept-based Models**](https://arxiv.org/pdf/2205.15612) <br> | NeurIPS | 2022 | [Github](https://github.com/ema-marconato/glancenet) |
| [Concept Bottleneck Model with Additional Unsupervised Concepts](https://arxiv.org/pdf/2202.01459) <br> | IEEE | 2022 | - |
| [Interpretable Image Classification with Differentiable Prototypes Assignment](https://arxiv.org/pdf/2112.02902) <br> | ECCV | 2022 | [Github](https://github.com/gmum/ProtoPool) |
| [Deformable ProtoPNet: An Interpretable Image Classifier Using Deformable Prototypes](https://arxiv.org/pdf/2111.15000) <br> | CVPR | 2022 | [Github](https://github.com/jdonnelly36/Deformable-ProtoPNet) |
| [A Framework for Learning Ante-hoc Explainable Models via Concepts](https://arxiv.org/pdf/2108.11761) <br> | CVPR | 2022 | - |
| [Post-hoc Concept Bottleneck Models](https://arxiv.org/pdf/2205.15480.pdf) <br> | ICLR | 2022 | [Github](https://github.com/mertyg/post-hoc-cbm) |
| [Entropy-based Logic Explanations of Neural Networks](https://arxiv.org/pdf/2106.06804) <br> | AAAI | 2022 | [Github](https://github.com/pietrobarbiero/entropy-lens) |
| [Attention-based interpretability with concept transformers](https://openreview.net/pdf?id=kAa9eDS0RdO) <br> | ICLR | 2021 | [Github](https://github.com/ibm/concept_transformer) |
| [SelfExplain: A Self-Explaining Architecture for Neural Text Classifiers](https://arxiv.org/pdf/2103.12279) <br> | - | 2021 | [Github](https://github.com/dheerajrajagopal/SelfExplain) |
| [ProtoPShare: Prototype Sharing for Interpretable Image Classification and Similarity Discovery](https://arxiv.org/pdf/2011.14340) <br> | ACM KDD | 2021 | [Github](https://github.com/gmum/ProtoPShare) |
| [**Concept Bottleneck Model**](https://proceedings.mlr.press/v119/koh20a) <br> | ICML | 2020 | [Github](https://github.com/yewsiang/ConceptBottleneck) |
| [Concept Whitening for Interpretable Image Recognition](https://arxiv.org/pdf/2002.01650) <br> | Nature MI | 2020 | [Github](https://github.com/zhiCHEN96/ConceptWhitening) |
| [Now you see me (cme): concept-based model extraction](https://arxiv.org/pdf/2010.13233) <br> | - | 2020 | [Github](https://github.com/dmitrykazhdan/CME) |
| [This Looks Like That: Deep Learning for Interpretable Image Recognition](https://arxiv.org/pdf/1806.10574) <br> | NIPS | 2019 | [Github](https://github.com/cfchen-duke/ProtoPNet) |
| [Interpretable Image Recognition with Hierarchical Prototypes](https://arxiv.org/pdf/1906.10651) <br> | AAAI | 2019 | [Github](https://github.com/peterbhase/interpretable-image) |
| [Towards Robust Interpretability with Self-Explaining Neural Networks](https://arxiv.org/pdf/1806.07538) <br> | NIPS | 2018 | [Github](https://github.com/AmanDaVinci/SENN?tab=readme-ov-file#documentation) |
| [Deep Learning for Case-Based Reasoning through Prototypes: A Neural Network that Explains Its Predictions](https://arxiv.org/pdf/1710.04806) <br> | AAAI | 2018 | [Github](https://github.com/OscarcarLi/PrototypeDL) |
| <br> |  |  | Github |

### 🤖 VLM-CBMs
The framework combines a Visual-Language model to generate concept annotations.
|  Title  |   Venue  |   Date   |   Code   |
|:--------|:--------:|:--------:|:--------:|
| [Improving ARDS Diagnosis Through Context-Aware Concept Bottleneck Models](https://arxiv.org/pdf/2508.09719) <br> |  |  | Github |
| [Locality-aware Concept Bottleneck Model](https://arxiv.org/pdf/2508.14562) <br> |  |  | Github |
| [DCBM: Data-Efficient Visual Concept Bottleneck Models](https://arxiv.org/pdf/2412.11576) <br> | ICML | 2025 | [Github](https://github.com/KathPra/DCBM) |
| [Discover-then-Name: Task-Agnostic Concept Bottlenecks via Automated Concept Discovery](https://arxiv.org/pdf/2407.14499) <br> | ECCV | 2024 | [Github](https://github.com/neuroexplicit-saar/Discover-then-Name) |
| [Incremental Residual Concept Bottleneck Models](https://arxiv.org/pdf/2404.08978) <br> | CVPR | 2024 | [Github](https://github.com/HelloSCM/Res-CBM) |
| [VLG-CBM: Training Concept Bottleneck Models with Vision-Language Guidance](https://arxiv.org/pdf/2408.01432) <br> | NeurIPS | 2024 | [Github](https://github.com/Trustworthy-ML-Lab/VLG-CBM) |
| [CLIP-QDA: An Explainable Concept Bottleneck Model](https://arxiv.org/pdf/2312.00110) <br> | TMLR | 2024 | - |
| [AdaCBM: An Adaptive Concept Bottleneck Model for Explainable and Accurate Diagnosis](https://arxiv.org/html/2408.02001v1) <br> | MICCAI | 2024 | [Github](https://github.com/AIML-MED/AdaCBM) |
| [Language in a Bottle: Language Model Guided Concept Bottlenecks for Interpretable Image Classification](https://arxiv.org/pdf/2211.11158.pdf) <br> | CVPR | 2023 | [Github](https://github.com/YueYANG1996/LaBo) |
| [Label Free Concept Bottleneck Models](https://arxiv.org/pdf/2304.06129.pdf) <br> | ICLR | 2023 | [Github](https://github.com/Trustworthy-ML-Lab/Label-free-CBM) |
| <br> |  |  | Github |



## 🔬 Discussions and Analysis
|  Title  |     Focus     |  Venue  |   Date   |   Code   |
|:--------|:-------------:|:-------:|:--------:|:--------:|
| [Enhancing Concept Localization in CLIP-based Concept Bottleneck Models](https://arxiv.org/pdf/2510.07115) <br> | Entanglement | - | 2025 | - |
| [SUB: Benchmarking CBM Generalization via Synthetic Attribute Substitutions](https://arxiv.org/pdf/2507.23784) <br> | Generalization | ICCV | 2025 | [Github](https://github.com/ExplainableML/sub) |
| [Measuring Leakage In Concept-Based Methods: An Information Theoretic Approach](https://arxiv.org/pdf/2504.09459) <br> | Leakage | ICLR | 2025 | - |
| [If Concept Bottlenecks are the Question, are Foundation Models the Answer?](https://arxiv.org/pdf/2504.19774) <br> | Concept Quality |  | 2025 | [Github](https://github.com/debryu/CQA) |
| [Concept Correlation and Its Effects on Concept-Based Models](https://openaccess.thecvf.com/content/WACV2023/papers/Heidemann_Concept_Correlation_and_Its_Effects_on_Concept-Based_Models_WACV_2023_paper.pdf) <br> | Entanglement | WACV | 2023 | - |
| [Overlooked Factors in Concept-based Explanations: Dataset Choice, Concept Learnability, and Human Capability](https://arxiv.org/pdf/2207.09615) <br> | Interpretability | CVPR | 2023 | [Github](https://github.com/princetonvisualai/OverlookedFactors) |
| [A closer look at the intervention procedure of concept bottleneck models](https://arxiv.org/pdf/2302.14260.pdf) <br> | Interventions | ICML | 2023 | [Github](https://github.com/ssbin4/Closer-Intervention-CBM) |
| [IS DISENTANGLEMENT ALL YOU NEED? COMPARING CONCEPT-BASED & DISENTANGLEMENT APPROACHES](https://arxiv.org/pdf/2104.06917) <br> | Entanglement | ICLR | 2021 | [Github](https://github.com/dmitrykazhdan/concept-based-xai) |
| [Do Concept Bottleneck Models learn as intended](https://arxiv.org/abs/2105.04289) <br> | Alignment | ICLR | 2021 | - |
| [Promises and Pitfalls of Black-Box Concept Learning Models](https://arxiv.org/pdf/2106.13314.pdf)  <br> | Entanglement, Leakage | - | 2021 | - |
| [ON COMPLETENESS-AWARE CONCEPT-BASED EXPLANATIONS IN DEEP NEURAL NETWORKS](https://arxiv.org/pdf/1910.07969) <br> | Completeness | NeurIPS | 2020 | [Github](https://github.com/chihkuanyeh/concept_exp) |



## 📖 Awesome Surveys
### Survey on Concept Based Models
- [Concept-based Explainable Artificial Intelligence: A Survey
](https://arxiv.org/pdf/2312.12936.pdf) 2023
- [A Comprehensive Survey on Self-Interpretable Neural Networks](https://arxiv.org/pdf/2501.15638) 2025


## 🛠️ Awesome Workshops & Talks

## 📊 Awesome Metrics & Benchmarks

## 💾 Awesome Datasets
- [SUB](https://huggingface.co/datasets/Jessica-bader/SUB)

## 👩‍🏫 Awesome Research Groups
