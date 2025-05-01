# awesome-text-to-motion

<a href='https://zilize.github.io/awesome-text-to-motion/'>
  <img src='https://img.shields.io/badge/Project-Page-%23df5b46?style=flat&logo=Google%20chrome&logoColor=%23df5b46'  alt="project_page"/></a> 
<a href='https://zilize.github.io/awesome-text-to-motion/'>
  <img src='https://img.shields.io/badge/Interactive-Charts-%2346a5df?style=flat&logo=plotly&logoColor=white' alt="interactive_charts"/></a>
<a href='https://github.com/Zilize/awesome-text-to-motion/actions/workflows/static.yml'>
  <img src='https://img.shields.io/github/actions/workflow/status/zilize/awesome-text-to-motion/static.yml'  alt="workflow"/></a> 
<a href="https://zhuanlan.zhihu.com/p/1940481020941043393">
  <img src="https://img.shields.io/badge/知乎-文章-%23f5f5f5?style=flat&logo=Zhihu&logoColor=%23188de0" alt="知乎文章"/>
</a>

Text-driven human motion generation surveys, datasets and models, focusing on single-person scenarios without human-object/scene interaction.
Please refer to the [project page](https://zilize.github.io/awesome-text-to-motion/) for a better browsing experience with interactive visualizations and statistical charts.

<details>
<summary><b>Contribution Guide</b> (Click to expand)</summary>

---

We welcome contributions to make this repository more comprehensive and up-to-date! 

### How to Contribute

1. **Fork this repository** to your GitHub account
2. **Create a new branch** for your contribution
3. **Add your papers** following the guidelines below
4. **Submit a Pull Request** with a clear description of your changes

### Adding Papers

#### For Papers with arXiv IDs:
- **File**: `data/arxiv.csv`
- **Format**: Add a new row with the following columns:
  - `arxiv_id`: The arXiv ID (e.g., "2507.05419")
  - `survey`: "1" if it's a survey paper, "0" otherwise
  - `survey_abbr`: Abbreviation for survey papers (e.g., "Survey2507")
  - `model`: "1" if it's a model paper, "0" otherwise
  - `model_abbr`: Abbreviation for model papers (e.g., "MotionGen")
  - `dataset`: "1" if it's a dataset paper, "0" otherwise
  - `dataset_abbr`: Abbreviation for dataset papers (e.g., "MotionX")
  - `submission`: Conference/journal name (e.g., "CVPR")
  - `submission_year`: Year of submission (e.g., "2025")
  - `page`: Project page URL (if available)
  - `repo`: GitHub repository URL (if available)
  - `backbone_tags`: Comma-separated backbone tags (e.g., "Transformer, Diffusion")
  - `approach_tags`: Comma-separated approach tags (e.g., "Physical, Editing")

#### For Papers without arXiv IDs:
- **File**: `data/without-arxiv.json`
- **Format**: Add a new JSON object with the following structure:
```json
{
    "arxiv_id": "random-key-for-your-interest",
    "title": "Paper Title",
    "abstract": "Paper abstract...",
    "authors": ["Author 1", "Author 2"],
    "year": 2025,
    "month": 7,
    "url": "https://paper-url.com",
    "survey": false,
    "survey_abbr": "",
    "model": true,
    "model_abbr": "ModelName",
    "dataset": false,
    "dataset_abbr": "",
    "submission": "Conference",
    "submission_year": "2025",
    "page": "https://project-page.com",
    "repo": "https://github.com/user_name/repo",
    "backbone_tags": "Transformer, Diffusion",
    "approach_tags": "Physical, Editing"
}
```

Thank you for contributing to the awesome-text-to-motion collection! 🚀

---

</details>

## Contents

- [Surveys](#surveys)
- [Datasets](#datasets)
- [Models](#models)

## Surveys

- "Motion Generation: A Survey of Generative Approaches and Benchmarks". `arXiv(2025)` [[URL]](https://arxiv.org/abs/2507.05419)

- "Multimodal Generative AI with Autoregressive LLMs for Human Motion Understanding and Generation: A Way Forward". `arXiv(2025)` [[URL]](https://arxiv.org/abs/2506.03191)

- "Text-driven Motion Generation: Overview, Challenges and Directions". `arXiv(2025)` [[URL]](https://arxiv.org/abs/2505.09379)

- "Human Motion Generation: A Survey". `TPAMI(2023)` [[URL]](https://arxiv.org/abs/2307.10894)



## Datasets

- **UniMo4D**: "X-MoGen: Unified Motion Generation across Humans and Animals". `arXiv(2025)` [[URL]](https://arxiv.org/abs/2508.05162)

- **FineMotion**: "FineMotion: A Dataset and Benchmark with both Spatial and Temporal Annotation for Fine-grained Motion Generation and Editing". `arXiv(2025)` [[URL]](https://arxiv.org/abs/2507.19850) [[Code]](https://github.com/BizhuWu/FineMotion)

- **SnapMoGen**: "SnapMoGen: Human Motion Generation from Expressive Texts". `arXiv(2025)` [[URL]](https://arxiv.org/abs/2507.09122) [[Project Page]](https://snap-research.github.io/SnapMoGen/) [[Code]](https://github.com/snap-research/SnapMoGen)

- **MotionMillion**: "Go to Zero: Towards Zero-shot Motion Generation with Million-scale Data". `ICCV(2025)` [[URL]](https://arxiv.org/abs/2507.07095) [[Project Page]](https://vankouf.github.io/MotionMillion/) [[Code]](https://github.com/VankouF/MotionMillion-Codes)

- **HumanAttr**: "Generating Attribute-Aware Human Motions from Textual Prompt". `arXiv(2025)` [[URL]](https://arxiv.org/abs/2506.21912)

- **GBC-100K**: "From Motion to Behavior: Hierarchical Modeling of Humanoid Generative Behavior Control". `arXiv(2025)` [[URL]](https://arxiv.org/abs/2506.00043)

- **STANCE**: "Dynamic Motion Blending for Versatile Motion Editing". `CVPR(2025)` [[URL]](https://arxiv.org/abs/2503.20724) [[Project Page]](https://awfuact.github.io/motionrefit/) [[Code]](https://github.com/emptybulebox1/motionRefit/)

- **PerMo**: "PersonaBooth: Personalized Text-to-Motion Generation". `CVPR(2025)` [[URL]](https://arxiv.org/abs/2503.07390) [[Project Page]](https://boeun-kim.github.io/page-PersonaBooth/) [[Code]](https://github.com/Boeun-Kim/PersonaBooth)

- **TMD**: "Motion Anything: Any to Motion Generation". `arXiv(2025)` [[URL]](https://arxiv.org/abs/2503.06955) [[Project Page]](https://steve-zeyu-zhang.github.io/MotionAnything/)

- **Motion-X++**: "Motion-X++: A Large-Scale Multimodal 3D Whole-body Human Motion Dataset". `arXiv(2025)` [[URL]](https://arxiv.org/abs/2501.05098)

- **MotionFix**: "MotionFix: Text-Driven 3D Human Motion Editing". `SIGGRAPH Asia(2024)` [[URL]](https://arxiv.org/abs/2408.00712) [[Project Page]](https://motionfix.is.tue.mpg.de/) [[Code]](https://github.com/atnikos/motionfix)

- **HumanML3D-Extend**: "Infinite Motion: Extended Motion Generation via Long Text Instructions". `arXiv(2024)` [[URL]](https://arxiv.org/abs/2407.08443) [[Project Page]](https://shuochengzhai.github.io/Infinite-motion.github.io/)

- **MotionPercept**: "Aligning Human Motion Generation with Human Perceptions". `ICLR(2025)` [[URL]](https://arxiv.org/abs/2407.02272) [[Project Page]](https://motioncritic.github.io/) [[Code]](https://github.com/ou524u/MotionCritic)

- **PaM**: "MoDiPO: text-to-motion alignment via AI-feedback-driven Direct Preference Optimization". `arXiv(2024)` [[URL]](https://arxiv.org/abs/2405.03803)

- **HumanML3D++**: "You Think, You ACT: The New Task of Arbitrary Text to Motion Generation". `ICCV(2025)` [[URL]](https://arxiv.org/abs/2404.14745)

- **MotionVerse**: "Large Motion Model for Unified Multi-Modal Motion Generation". `arXiv(2024)` [[URL]](https://arxiv.org/abs/2404.01284) [[Project Page]](https://mingyuan-zhang.github.io/projects/LMM.html) [[Code]](https://github.com/mingyuan-zhang/LMM)

- **RICH-CAT**: "Contact-aware Human Motion Generation from Textual Descriptions". `arXiv(2024)` [[URL]](https://arxiv.org/abs/2403.15709) [[Project Page]](https://xymsh.github.io/RICH-CAT/)

- **FineHumanML3D**: "Motion Generation from Fine-grained Textual Descriptions". `LREC-COLING(2024)` [[URL]](https://arxiv.org/abs/2403.13518) [[Code]](https://github.com/KunhangL/finemotiondiffuse)

- **BlindWays**: "Text to Blind Motion". `NeurIPS(2024)` [[URL]](https://arxiv.org/abs/2412.05277) [[Project Page]](https://blindways.github.io/)

- **LaViMo**: "Text Motion Translator: A Bi-Directional Model for Enhanced 3D Human Motion Generation from Open-Vocabulary Descriptions". `ECCV(2024)` [[URL]](https://eccv.ecva.net/virtual/2024/poster/266)

- **Inter-MT2**: "A Unified Framework for Motion Reasoning and Generation in Human Interaction". `ICCV(2025)` [[URL]](https://arxiv.org/abs/2410.05628) [[Project Page]](https://vim-motion-language.github.io/)

- **MotionLib**: "Scaling Large Motion Models with Million-Level Human Motions". `ICML(2025)` [[URL]](https://arxiv.org/abs/2410.03311) [[Project Page]](https://beingbeyond.github.io/Being-M0/) [[Code]](https://github.com/BeingBeyond/Being-M0)

- **HumanML3D-synthesis**: "CLaM: An Open-Source Library for Performance Evaluation of Text-driven Human Motion Generation". `MM(24)` [[URL]](https://dl.acm.org/doi/10.1145/3664647.3685523) [[Code]](https://github.com/SheldongChen/CLaM/)

- **Limb-ET2M**: "Towards Emotion-enriched Text-to-Motion Generation via LLM-guided Limb-level Emotion Manipulating
". `MM(2024)` [[URL]](https://dl.acm.org/doi/10.1145/3664647.3681487) [[Code]](https://github.com/aekx/L3EM)

- **Motion-X**: "Motion-X: A Large-scale 3D Expressive Whole-body Human Motion Dataset". `NeurIPS(2023)` [[URL]](https://arxiv.org/abs/2307.00818) [[Project Page]](https://motion-x-dataset.github.io/) [[Code]](https://github.com/IDEA-Research/Motion-X)

- **HumanLong3D**: "AMD: Autoregressive Motion Diffusion". `AAAI(2024)` [[URL]](https://arxiv.org/abs/2305.09381) [[Code]](https://github.com/fluide1022/AMD)

- **HuMMan-MoGen**: "FineMoGen: Fine-Grained Spatio-Temporal Motion Generation and Editing". `NeurIPS(2023)` [[URL]](https://arxiv.org/abs/2312.15004) [[Project Page]](https://mingyuan-zhang.github.io/projects/FineMoGen.html) [[Code]](https://github.com/mingyuan-zhang/FineMoGen)

- **HumanML3D**: "Generating Diverse and Natural 3D Human Motions from Text". `CVPR(2022)` [[URL]](https://openaccess.thecvf.com/content/CVPR2022/papers/Guo_Generating_Diverse_and_Natural_3D_Human_Motions_From_Text_CVPR_2022_paper.pdf) [[Project Page]](https://ericguo5513.github.io/text-to-motion/) [[Code]](https://github.com/EricGuo5513/text-to-motion)

- **KIT**: "The KIT Motion-Language Dataset". `Big Data(2016)` [[URL]](https://arxiv.org/abs/1607.03827) [[Project Page]](https://motion-annotation.humanoids.kit.edu/dataset/)



## Models

- **X-MoGen**: "X-MoGen: Unified Motion Generation across Humans and Animals". `arXiv(2025)` [[URL]](https://arxiv.org/abs/2508.05162)

- **ReMoMask**: "ReMoMask: Retrieval-Augmented Masked Motion Generation". `arXiv(2025)` [[URL]](https://arxiv.org/abs/2508.02605) [[Project Page]](https://aigeeksgroup.github.io/ReMoMask/) [[Code]](https://github.com/AIGeeksGroup/ReMoMask)

- **SASI**: "Semantically Consistent Text-to-Motion with Unsupervised Styles". `SIGGRAPH(2025)` [[URL]](https://dl.acm.org/doi/10.1145/3721238.3730641) [[Project Page]](https://fivezerojun.github.io/stylization.github.io/)

- **MoMask++**: "SnapMoGen: Human Motion Generation from Expressive Texts". `arXiv(2025)` [[URL]](https://arxiv.org/abs/2507.09122) [[Project Page]](https://snap-research.github.io/SnapMoGen/) [[Code]](https://github.com/snap-research/SnapMoGen)

- **GotoZero**: "Go to Zero: Towards Zero-shot Motion Generation with Million-scale Data". `ICCV(2025)` [[URL]](https://arxiv.org/abs/2507.07095) [[Project Page]](https://vankouf.github.io/MotionMillion/) [[Code]](https://github.com/VankouF/MotionMillion-Codes)

- **MOST**: "MOST: Motion Diffusion Model for Rare Text via Temporal Clip Banzhaf Interaction". `arXiv(2025)` [[URL]](https://arxiv.org/abs/2507.06590)

- **MotionGPT3**: "MotionGPT3: Human Motion as a Second Modality". `arXiv(2025)` [[URL]](https://arxiv.org/abs/2506.24086) [[Project Page]](https://motiongpt3.github.io/) [[Code]](https://github.com/OpenMotionLab/MotionGPT3)

- **AttrMoGen**: "Generating Attribute-Aware Human Motions from Textual Prompt". `arXiv(2025)` [[URL]](https://arxiv.org/abs/2506.21912)

- **Motion-R1**: "Motion-R1: Chain-of-Thought Reasoning and Reinforcement Learning for Human Motion Generation". `arXiv(2025)` [[URL]](https://arxiv.org/abs/2506.10353) [[Project Page]](https://motion-r1.github.io/) [[Code]](https://github.com/GigaAI-Research/Motion-R1)

- **MOGO**: "MOGO: Residual Quantized Hierarchical Causal Transformer for High-Quality and Real-Time 3D Human Motion Generation". `arXiv(2025)` [[URL]](https://arxiv.org/abs/2506.05952)

- **ANT**: "ANT: Adaptive Neural Temporal-Aware Text-to-Motion Model". `arXiv(2025)` [[URL]](https://arxiv.org/abs/2506.02452) [[Code]](https://github.com/CCSCovenant/ANT)

- **PHYLOMAN**: "From Motion to Behavior: Hierarchical Modeling of Humanoid Generative Behavior Control". `arXiv(2025)` [[URL]](https://arxiv.org/abs/2506.00043)

- **ACMDM**: "Absolute Coordinates Make Motion Generation Easy". `arXiv(2025)` [[URL]](https://arxiv.org/abs/2505.19377) [[Project Page]](https://neu-vi.github.io/ACMDM/) [[Code]](https://github.com/neu-vi/ACMDM)

- **MoMADiff**: "Towards Robust and Controllable Text-to-Motion via Masked Autoregressive Diffusion". `MM(2025)` [[URL]](https://arxiv.org/abs/2505.11013) [[Code]](https://github.com/zzysteve/MoMADiff)

- **ReAlign**: "ReAlign: Bilingual Text-to-Motion Generation via Step-Aware Reward-Guided Alignment". `arXiv(2025)` [[URL]](https://arxiv.org/abs/2505.04974) [[Project Page]](https://wengwanjiang.github.io/ReAlign-page/)

- **GENMO**: "GENMO: A GENeralist Model for Human MOtion". `arXiv(2025)` [[URL]](https://arxiv.org/abs/2505.01425) [[Project Page]](https://research.nvidia.com/labs/dair/genmo/)

- **DSDFM**: "Deterministic-to-Stochastic Diverse Latent Feature Mapping for Human Motion Synthesis". `CVPR(2025)` [[URL]](https://arxiv.org/abs/2505.00998)

- **UniPhys**: "UniPhys: Unified Planner and Controller with Diffusion for Flexible Physics-Based Character Control". `ICCV(2025)` [[URL]](https://arxiv.org/abs/2504.12540) [[Project Page]](https://wuyan01.github.io/uniphys-project/)

- **Shape-Move**: "Shape My Moves: Text-Driven Shape-Aware Synthesis of Human Motions". `CVPR(2025)` [[URL]](https://arxiv.org/abs/2504.03639) [[Project Page]](https://shape-move.github.io/) [[Code]](https://github.com/shape-move/shape-move-public)

- **MG-MotionLLM**: "MG-MotionLLM: A Unified Framework for Motion Comprehension and Generation across Multiple Granularities". `CVPR(2025)` [[URL]](https://arxiv.org/abs/2504.02478) [[Code]](https://github.com/CVI-SZU/MG-MotionLLM)

- **FlowMotion**: "FlowMotion: Target-Predictive Conditional Flow Matching for Jitter-Reduced Text-Driven Human Motion Generation". `arXiv(2025)` [[URL]](https://arxiv.org/abs/2504.01338)

- **MixerMDM**: "MixerMDM: Learnable Composition of Human Motion Diffusion Models". `CVPR(2025)` [[URL]](https://arxiv.org/abs/2504.01019) [[Project Page]](https://pabloruizponce.com/papers/MixerMDM) [[Code]](https://github.com/pabloruizponce/MixerMDM)

- **ReMoGPT**: "ReMoGPT: Part-Level Retrieval-Augmented Motion-Language Models". `AAAI(2025)` [[URL]](https://ojs.aaai.org/index.php/AAAI/article/view/33044)

- **UniTMGE**: "UniTMGE: Uniform Text-Motion Generation and Editing Model via Diffusion". `WACV(2025)` [[URL]](https://ieeexplore.ieee.org/document/10943808)

- **MotionReFit**: "Dynamic Motion Blending for Versatile Motion Editing". `CVPR(2025)` [[URL]](https://arxiv.org/abs/2503.20724) [[Project Page]](https://awfuact.github.io/motionrefit/) [[Code]](https://github.com/emptybulebox1/motionRefit/)

- **LoRA-MDM**: "Dance Like a Chicken: Low-Rank Stylization for Human Motion Diffusion". `arXiv(2025)` [[URL]](https://arxiv.org/abs/2503.19557) [[Project Page]](https://haimsaw.github.io/LoRA-MDM/) [[Code]](https://github.com/haimsaw/LoRA-MDM)

- **HMU**: "Human Motion Unlearning". `arXiv(2025)` [[URL]](https://arxiv.org/abs/2503.18674) [[Project Page]](https://www.pinlab.org/hmu) [[Code]](https://github.com/edodema/human-motion-unlearning)

- **SimMotionEdit**: "SimMotionEdit: Text-Based Human Motion Editing with Motion Similarity Prediction". `CVPR(2025)` [[URL]](https://arxiv.org/abs/2503.18211) [[Project Page]](https://ideas.cs.purdue.edu/research/projects/sim-motion-edit/) [[Code]](https://github.com/lzhyu/SimMotionEdit)

- **MotionStreamer**: "MotionStreamer: Streaming Motion Generation via Diffusion-based Autoregressive Model in Causal Latent Space". `ICCV(2025)` [[URL]](https://arxiv.org/abs/2503.15451) [[Project Page]](https://zju3dv.github.io/MotionStreamer/) [[Code]](https://github.com/zju3dv/MotionStreamer/)

- **GenM3**: "GenM$^3$: Generative Pretrained Multi-path Motion Model for Text Conditional Human Motion Generation". `arXiv(2025)` [[URL]](https://arxiv.org/abs/2503.14919)

- **Kinesis**: "Reinforcement learning-based motion imitation for physiologically plausible musculoskeletal motor control". `arXiv(2025)` [[URL]](https://arxiv.org/abs/2503.14637) [[Code]](https://github.com/amathislab/Kinesis)

- **sMDM**: "Less is More: Improving Motion Diffusion Models with Sparse Keyframes". `arXiv(2025)` [[URL]](https://arxiv.org/abs/2503.13859)

- **SALAD**: "SALAD: Skeleton-aware Latent Diffusion for Text-driven Motion Generation and Editing". `CVPR(2025)` [[URL]](https://arxiv.org/abs/2503.13836) [[Project Page]](https://seokhyeonhong.github.io/projects/salad/) [[Code]](https://github.com/seokhyeonhong/salad)

- **PMG**: "Progressive Human Motion Generation Based on Text and Few Motion Frames". `TCSVT(2025)` [[URL]](https://arxiv.org/abs/2503.13300) [[Code]](https://github.com/qinghuannn/PMG)

- **PersonaBooth**: "PersonaBooth: Personalized Text-to-Motion Generation". `CVPR(2025)` [[URL]](https://arxiv.org/abs/2503.07390) [[Project Page]](https://boeun-kim.github.io/page-PersonaBooth/) [[Code]](https://github.com/Boeun-Kim/PersonaBooth)

- **MotionAnything**: "Motion Anything: Any to Motion Generation". `arXiv(2025)` [[URL]](https://arxiv.org/abs/2503.06955) [[Project Page]](https://steve-zeyu-zhang.github.io/MotionAnything/)

- **BioVAE**: "Biomechanics-Guided Residual Approach to Generalizable Human Motion Generation and Estimation". `arXiv(2025)` [[URL]](https://arxiv.org/abs/2503.06151)

- **MoMug**: "Unlocking Pretrained LLMs for Motion-Related Multimodal Generation: A Fine-Tuning Approach to Unify Diffusion and Next-Token Prediction". `arXiv(2025)` [[URL]](https://arxiv.org/abs/2503.06119)

- **Fg-T2M++**: "Fg-T2M++: LLMs-Augmented Fine-Grained Text Driven Human Motion Generation". `IJCV(2025)` [[URL]](https://arxiv.org/abs/2502.05534)

- **MotionLab**: "MotionLab: Unified Human Motion Generation and Editing via the Motion-Condition-Motion Paradigm". `ICCV(2025)` [[URL]](https://arxiv.org/abs/2502.02358) [[Project Page]](https://diouo.github.io/motionlab.github.io/) [[Code]](https://github.com/Diouo/MotionLab)

- **CASIM**: "CASIM: Composite Aware Semantic Injection for Text to Motion Generation". `arXiv(2025)` [[URL]](https://arxiv.org/abs/2502.02063) [[Project Page]](https://cjerry1243.github.io/casim_t2m/) [[Code]](https://github.com/cjerry1243/casim_t2m)

- **SPORT**: "SPORT: From Zero-shot Prompts to Real-time Motion Generation". `TVCG(2025)` [[URL]](https://ieeexplore.ieee.org/document/10891181/)

- **MotionPCM**: "MotionPCM: Real-Time Motion Synthesis with Phased Consistency Model". `arXiv(2025)` [[URL]](https://arxiv.org/abs/2501.19083)

- **Free-T2M**: "Free-T2M: Frequency Enhanced Text-to-Motion Diffusion Model With Consistency Loss". `arXiv(2025)` [[URL]](https://arxiv.org/abs/2501.18232)

- **FlexMotion**: "FlexMotion: Lightweight, Physics-Aware, and Controllable Human Motion Generation". `arXiv(2025)` [[URL]](https://arxiv.org/abs/2501.16778) [[Project Page]](https://openreview.net/forum?id=7652tHbbVE)

- **PackDiT**: "PackDiT: Joint Human Motion and Text Generation via Mutual Prompting". `arXiv(2025)` [[URL]](https://arxiv.org/abs/2501.16551)

- **MMDM**: "Text-driven Human Motion Generation with Motion Masked Diffusion Model". `arXiv(2024)` [[URL]](https://arxiv.org/abs/2409.19686)

- **EgoLM**: "EgoLM: Multi-Modal Language Model of Egocentric Motions". `CVPR(2025)` [[URL]](https://arxiv.org/abs/2409.18127) [[Project Page]](https://hongfz16.github.io/projects/EgoLM)

- **MoGenTS**: "MoGenTS: M