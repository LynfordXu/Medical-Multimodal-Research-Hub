# Medical Multimodal Research Hub

MICCAI & ISBI 2025–2026 医学多模态研究专题索引 · Workshop / Tutorial / Challenge

本文件包括专题与研究方向分级。报告人主页、Slides 将在后续补充。

**范围：** MICCAI / ISBI 2025–2026；共 **69** 条候选专题（A **31**、B **33**、C **5**）。这是筛选后的研究资源清单，不是会议的全部活动。

## 分级标准

|  等级   | 含义                                                                   |
| :---: | :------------------------------------------------------------------- |
| **A** | 核心跨模态：异质模态的融合、对齐、联合推理或生成，如影像–文本、影像–临床数据、病理–组学，以及 MRI/PET/CT 跨成像模态生成。 |
| **B** | 明确相关：专题实质涉及多模态但不全部围绕它；或研究 PET/CT、MRI 多序列、不同成像方案的联合/统一建模。             |
| **C** | 方法关联：主要是单模态跨域、同模态图像合成、通用模型或工具，对多模态研究存在方法迁移价值。                        |

**边界：** MRI→CT 等跨成像模态生成属于跨模态建模，但不等同于多源信息融合；MRI 多序列、多期相 CT、不同采集域的联合建模，也不自动等同于异质信息融合。等级仅表示专题与医学多模态研究方向的相关程度，不代表专题质量、论文质量或资源完整度。

## 研究方向

| 主线              | 关注内容                                        |
| --------------- | ------------------------------------------- |
| 医学视觉语言 / 报告生成   | 影像—文本对齐、医学 VLM/MLLM、报告生成与定位                 |
| 影像 + 临床数据       | 影像与 EHR、表格、纵向随访信息的融合                        |
| 病理 + 组学 / 放射影像  | WSI、分子数据、空间组学与放射影像整合                        |
| 多影像 / 多序列建模     | PET/CT、MRI 多序列、多期相及不同采集域的联合/统一建模；需与异质信息融合区分 |
| 生成、合成与跨模态转换     | 扩散/生成建模、影像合成、跨模态生成                          |
| 基础模型、Agent 与可信性 | 医学基础模型、智能体、适配、评估与推理可靠性                      |
| 临床专科应用          | 牙科、手术、眼科等具体场景中的多源数据理解                       |

## 专题目录

表内专题名称优先链接至专题独立主页；无独立主页时，链接会议官方目录、正式论文集或其他可核验的官方/原始资料。“研究线索 / 判定依据”一列均依据当前可获取的公开资料逐条复核。

### MICCAI 2025（24 条）

|  等级   | 类型        | 专题（入口）                                                                                                                                                                                  | 研究线索 / 判定依据                                |
| :---: | :-------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :----------------------------------------- |
| **A** | Tutorial  | [From Foundational to Multimodal Models for Medical Imaging (FMLLM)](https://sites.google.com/view/miccai-2025-tutorial)                                                                | 教程明确系统讲授医学 VLM、MLLM、影像与文本/知识图谱融合           |
| **A** | Workshop  | [COMputational PAthologY and multimodaL data Workshop](https://www.compayl.com/)                                                                                                        | 专题核心为计算病理与语言、组学、放射影像等多源数据整合                |
| **A** | Workshop  | [Learning with Longitudinal Medical Images and Data (LMID)](https://ldtm-miccai.github.io/lmid2025/)                                                                                    | 纵向 CT/MR/PET + 报告/EHR/LLM；含多模态时序预测与疾病进展建模  |
| **A** | Workshop  | [Multimodal Large Language Models in Clinical Practice](https://clinicalmllms.github.io/)                                                                                               | Workshop 直接聚焦临床多模态大语言模型及其影像、文本、DNA 输入      |
| **A** | Workshop  | [Multimodal Learning for Clinical Decision Support (ML-CDS)](https://sites.google.com/view/ml-cdsmiccai2025/home)                                                                       | 官方目标即医学影像、临床文本、组学等数据的多模态融合及决策支持            |
| **A** | Workshop  | [ODIN2025 - Oral and Dental Image aNalysis Workshop](https://odin-workshops.org/2025/)                                                                                                  | CBCT + IOS 为主；含跨模态配准/集成与 3D 牙科多结构学习        |
| **A** | Challenge | [Challenge for Vision-Language Modeling in 3D Medical Imaging](https://vlm3dchallenge.com/)                                                                                             | 面向 3D 医学影像与语言共同建模                          |
| **A** | Challenge | [Combining HIstology, Medical Imaging (Radiology), and molEcular Data for Medical pRognosis and diAgnosis.](https://chimera.grand-challenge.org/)                                       | 研究对象即组织学、放射影像与分子数据的联合分析                    |
| **A** | Challenge | [HEad and neCK TumOR (HECKTOR) Lesion Segmentation, Diagnosis and Prognosis using Multimodal Data](https://hecktor25.grand-challenge.org/)                                              | PET、CT 与临床信息服务于分割、诊断和预后任务                  |
| **A** | Challenge | [Multimodal survival and recurrence prediction in head and neck oncology](https://hancock.research.fau.eu/challenge)                                                                    | 挑战核心为头颈肿瘤多源数据生存与复发预测                       |
| **A** | Challenge | [REport Generation of pathology using Pan-Asia Giga-pixel WSIs](https://reg2025.grand-challenge.org/)                                                                                   | WSI → 病理文本报告生成是核心任务                        |
| **A** | Challenge | [SynthRAD2025: Synthesizing computed tomography for radiotherapy](https://synthrad2025.grand-challenge.org/)                                                                            | MRI/CBCT → 合成 CT，是明确的跨成像模态生成任务             |
| **A** | Challenge | [UNICORN Lighthouse Challenge: Unified beNchmark for Imaging in COmputational pathology, Radiology and Natural language](https://unicorn.grand-challenge.org/)                          | 统一评测病理、放射影像、自然语言上的多模态基础模型                  |
| **B** | Tutorial  | [Generative Models for Synthesizing Medical Images (GenAI-Medical)](https://sites.google.com/stanford.edu/genai-medical/home)                                                           | MRI/CT 等医学图像生成；含多模态/跨模态合成与临床评估             |
| **B** | Workshop  | [Emerging LLM/LMM Applications in Medical Imaging (ELAMI)](https://link.springer.com/book/10.1007/978-3-032-07502-4)                                                                    | 涵盖 LLM 与 LMM；有图文工作，但并非全部是多模态               |
| **B** | Workshop  | [Workshop on Digital Twin for Healthcare](https://digitaltwinforhealthcare.com/workshops/2025/)                                                                                         | 影像 + 生理信号 + 基因组/传感器 + 计算仿真；面向多模态数字孪生       |
| **B** | Challenge | [Automated Lesion Segmentation in Whole-Body PET/CT and Longitudinal CT](https://autopet-iv.grand-challenge.org/)                                                                       | PET/CT 联合成像与纵向 CT 分为不同赛题，非全赛题跨模态融合         |
| **B** | Challenge | [Foundation-Model-Driven Parkinson's Disease Auto Diagnosis Challenge](https://ruijin-imit.github.io/challenges/PDCADxFoundation-MICCAI2025/)                                           | T1WI + QSM + NM-MRI；多参数 MRI 融合用于分割与 PD 诊断  |
| **B** | Challenge | [Liver Lesion Segmentation in Non-Contrast CT: Triphasic-Aided, Multi-Center, and Multi-Vendor Challenge](https://www.synapse.org/Synapse:syn65878273)                                  | 三期 CT 辅助非增强 CT 分割，属于同类影像多期相应用              |
| **B** | Challenge | [Multiple Sclerosis Spinal Cord Lesion Detection from MultiSequence MRIs](https://portal.fli-iam.irisa.fr/ms-multi-spine/)                                                              | 跨多序列 MRI 做脊髓病变检测，不等同影像+文本等异质融合             |
| **B** | Workshop  | [3rd Workshop on Foundation Models for General Medical AI](https://link.springer.com/book/10.1007/978-3-032-07845-2)                                                                    | 医学图像 + 文本/VLM；含跨模态蒸馏、报告生成与单模态基础模型          |
| **B** | Workshop  | [Agentic AI for Medicine](https://link.springer.com/book/10.1007/978-3-032-06004-4)                                                                                                     | 医学影像 + LLM/智能体；含多模态影像分析、报告与 CT 流程自动化（部分论文） |
| **B** | Workshop  | [Fifth MICCAI workshop on Deep Generative Models for Medical Image Computing and Computer Assisted Intervention (DGM4MICCAI)](https://link.springer.com/book/10.1007/978-3-032-05472-2) | 医学图像生成 + 文本/报告条件；含文生图、报告引导与 VLM 生成（部分论文）   |
| **C** | Challenge | [Pancreatic Tumor Segmentation in Therapeutic and DIagnostic MRI](https://panther.grand-challenge.org/)                                                                                 | 诊断 MRI 与 MR-Linac 分成分割评测域，主目标是跨域泛化         |

### MICCAI 2026（37 条）

|  等级   | 类型        | 专题（入口）                                                                                                                                                                                                       | 研究线索 / 判定依据                                         |
| :---: | :-------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :-------------------------------------------------- |
| **A** | Tutorial  | [Multimodal Foundational Models for BioMedical Imaging](https://sites.google.com/view/miccai-2026-tutorial)                                                                                                  | 课程涵盖 VLM、医学 MLLM、图像与文本生成及相应评测                       |
| **A** | Workshop  | [14th Workshop on Multimodal Learning for Clinical Decision Support](https://sites.google.com/view/ml-cds-miccai-2026/)                                                                                      | 明确讨论医学多模态数据和跨尺度融合以支持临床决策                            |
| **A** | Workshop  | [Computational Pathology and Multimodal Data Workshop](https://www.compayl.com/)                                                                                                                             | 计算病理与放射影像、语言及组学整合为专题主旨                              |
| **A** | Workshop  | [Medical Imaging Analysis for Spatial Omics](https://sites.google.com/view/miso2026)                                                                                                                         | 医学影像计算与空间组学的协同是专题核心                                 |
| **A** | Workshop  | [Multimodal Learning with Medical Tabular Data](https://multitab-miccai-2026.github.io/)                                                                                                                     | 明确研究表格/EHR/组学数据与医学影像的融合、缺失和泛化                       |
| **A** | Workshop  | [Oral and Dental Image aNalysis](https://odin-workshops.org/2026/schedule/)                                                                                                                                  | CBCT + IOS + 2D 影像/照片 + 报告；含跨模态融合、配准与报告生成           |
| **A** | Challenge | [A Benchmark for Vision-Language Models in Head CT Reporting](https://headline.ccibonn.ai/)                                                                                                                  | CT 影像与自然语言报告共同构成 VLM 评测任务                           |
| **A** | Challenge | [Benchmarking Medical Multimodal Large Language Models](https://medreason26.github.io/)                                                                                                                      | 医学影像 + 问题/上下文进行跨模态视觉问答及推理                           |
| **A** | Challenge | [Big Cross-Modal Attenuation Correction Challenge](https://bic-mac-challenge.github.io/)                                                                                                                     | MRI、PET、Topogram 联合生成伪 CT，明确融合未对齐信息                 |
| **A** | Challenge | [Combining HIstology, Medical imaging and molEcular data for medical pRognosis and diAgnosis Agent](https://chimera-agent.grand-challenge.org/)                                                              | 组织学、放射影像、分子数据联合诊断/预后与智能体推理                          |
| **A** | Challenge | [Fusion for Intelligent Decision-support in Ophthalmology](https://syntheseyes.com/blog/miccai-challenge-2026/)                                                                                              | 术中眼底显微镜图像与 iOCT 的融合定位/跨模态配准                         |
| **A** | Challenge | [Grounding Free-Text Findings to 3D CT Segmentations](https://rexrank.ai/ReXGroundingCT/challenge.html)                                                                                                      | 自由文本病灶描述与 3D CT 区域进行细粒度关联                           |
| **A** | Challenge | [HEad and neCK TumOR Lesion Segmentation, Staging and Prognosis using Multimodal Data](https://hecktor26.grand-challenge.org/)                                                                               | PET+CT+临床信息联合完成分割、分期和预后                             |
| **A** | Challenge | [Multimodal Text Report Generation for Oral and Dental Image Analysis](https://odin-workshops.org/)                                                                                                          | 3D 口腔影像/扫描与文本报告联合生成                                 |
| **A** | Challenge | [Pathologist Reasoning-Guided Report Generation Challenge](https://reg2026.grand-challenge.org/)                                                                                                             | 病理图像、病理医生推理与报告文本生成形成图文任务                            |
| **A** | Challenge | [Vision-Language Modeling in 3D Medical Imaging](https://vlm3dchallenge.com/)                                                                                                                                | 3D 医学影像与文本联合的视觉语言建模                                 |
| **B** | Tutorial  | [Clinical Pathology for AI Researchers: Diagnostic Reasoning, Regulatory Realities, & Multimodal Decision-Making](https://www.compayl.com/tutorial)                                                          | 含病理、放射影像、组学临床联合推理，但教程主要覆盖临床流程与监管                    |
| **B** | Workshop  | [1st Workshop on Stable Adaptation and Faithful Evaluation of Reasoning in Medical Foundation Models](https://safer-workshop.github.io/)                                                                     | 医学影像 + 临床多模态 + VLM；聚焦安全适配、证据 grounding 与可信推理        |
| **B** | Workshop  | [Continual Learning in Medical Multimodal-Vision](https://climem.github.io/CLiMeM/index.html)                                                                                                                | 持续学习是主轴；多模态视觉为重点应用方向之一                              |
| **B** | Workshop  | [Deep Generative Models for Medical Image Computing and Computer Assisted Intervention](https://dgm4miccai.github.io/)                                                                                       | MRI/CT/CBCT/超声/病理等；含跨模态合成、转换与多模态生成                  |
| **B** | Workshop  | [Efficient Medical AI Workshop](https://sites.google.com/view/ema2026)                                                                                                                                       | 医学影像 + LLM/VLM/基础模型；含高效多模态学习与模型适配                   |
| **B** | Workshop  | [Emerging LLM/LMM Applications in Medical Imaging](https://hula-ai.github.io/miccai-elami-2026/#/)                                                                                                           | 同时涉及 LLM、LMM 和单模态医学影像应用，属于较广论坛                      |
| **B** | Workshop  | [International Workshop on Digital Twin for Healthcare 2026](https://digitaltwinforhealthcare.com/workshops/2026)                                                                                            | 影像 + 生理信号 + 基因组/传感器 + 计算模型；多模态数字孪生与临床转化             |
| **B** | Workshop  | [Mechanistic Interpretability for Medical Foundation Models](https://mi4medfm.github.io/2026/)                                                                                                               | 医学基础模型 + 多模态/VLM；聚焦内部机制、幻觉/偏差与可信输出解释                |
| **B** | Challenge | [Annotated Multi-Phase Liver Imaging For Artificial Intelligence](https://www.codabench.org/competitions/14290/)                                                                                             | 多期肝脏影像分析，属同类成像多期相建模                                 |
| **B** | Challenge | [Automated Lesion Segmentation in Whole-Body PET/CT](https://autopet-v.grand-challenge.org/)                                                                                                                 | PET/CT 多成像信息用于病灶分割，主要目标是分割评测                        |
| **B** | Challenge | [Mitral Valve Anatomy Analysis Using Multimodal Imaging Data](https://mwm2026.github.io/mvaa)                                                                                                                | CT、3D TEE 与手术视频是三个模态任务，当前主要按任务独立分割                  |
| **B** | Challenge | [Multimodal Vessel-Specific Intracranial Aneurysm Classification and Segmentation Challenge](http://topaneu-26.grand-challenge.org/)                                                                         | CTA 或 MRA 作为可选输入进行一致评测，并非要求配对融合                     |
| **B** | Challenge | [Transformative Research and Efficient AI Technologies for Multimodal Management of Tuberculosis](https://treat-mmtb.mi2rl.co/)                                                                              | Task 2 为胸片+临床元数据融合，Task 1 为胸片单模态分割                  |
| **B** | Challenge | [Universal Multi-Sequence, Multi-Center and Multi-View CMR Segmentation and Quantification Challenge](https://mwm2026.github.io/cmr-multi)                                                                   | 多序列、多中心、多视图 CMR 统一建模；属同类成像多输入                       |
| **B** | Challenge | [Universal Ultrasound Image & Video Analysis Challenge: Multi-Organ Classification and Segmentation Across B-mode and Contrast-Enhanced Ultrasound](https://uusivc2026-sudo.github.io/uusivc2026.github.io/) | 融合多种超声成像形式和视频做跨器官/任务通用模型，未要求同患者跨模态配对                |
| **B** | Workshop  | [11th International Workshop on Simulation and Synthesis in Medical Imaging](https://2026.sashimiworkshop.org/)                                                                                              | 医学图像生成 + 跨模态转换；含 CBCT→CT、Histology→HiP-CT、多模态 MRI 等 |
| **B** | Workshop  | [2nd Agentic AI for Medicine](https://agentic-ai-for-medicine.github.io/agentic-ai-for-medicine/)                                                                                                            | 胸片/医学影像 + 智能体/VLM；含多模态 Agentic RL、VQA 与视觉证据推理       |
| **B** | Workshop  | [4th Workshop on Foundation Models for General Medical AI](https://www.miccai2026.org/en/workshops.asp)                                                                                                      | 医学图像 + VLM/文本；含报告生成、医学文档 VQA 与多模态拓扑建模               |
| **C** | Workshop  | [MICCAI Student Board Second Workshop on Empowering MEdical information computing and Research through early-career Guidance and Expertise](https://miccaimsb.github.io/emerge/)                             | 医学影像 + EHR/文本/EEG 等；含多模态 VQA、生成学习与多源融合（部分论文）        |
| **C** | Challenge | [A Generalizable Cross-Field MRI Translation and Harmonization Challenge](https://mrixfields.chihucloud.com/2026/)                                                                                           | 不同磁场强度的 MRI 生成与校正，主要研究同一模态的域转移                      |
| **C** | Challenge | [Synthesizing Virtual Contrast-Enhancement in Breast MRI](https://mama-research.github.io/mama-synth.html)                                                                                                   | 乳腺 MRI 增强前 → 增强后同模态图像合成                             |

### ISBI 2025（3 条）

| 等级 | 类型 | 专题（入口） | 研究线索 / 判定依据 |
|:--:|:--|:--|:--|
| **A** | Workshop | [Foundation AI Models in Biomedical Imaging (FAIBI)](https://hazratali.github.io/faibi2025/) | 独立官网明确以医学影像、EHR、报告等多模态基础模型为重心 |
| **B** | Workshop | [Open-source MONAI: Next-Generation Capabilities for Biomedical Imaging AI](https://biomedicalimaging.org/2025/workshops/) | 介绍 MONAI 生态、生成模型和 VLM；多模态只是课程模块之一 |
| **C** | Tutorial | [MHub.ai – Making AI in Medical Imaging simple and Reproducible](https://biomedicalimaging.org/2025/tutorials/) | MHub 主体是多格式医学模型容器、复现和部署；非融合学习专题 |

### ISBI 2026（5 条）

|  等级   | 类型        | 专题（入口）                                                                                                                                                | 研究线索 / 判定依据                    |
| :---: | :-------- | :---------------------------------------------------------------------------------------------------------------------------------------------------- | :----------------------------- |
| **A** | Workshop  | [The 2nd Workshop on Foundation AI models in Biomedical Imaging (FAIBI)](https://biomedicalimaging.org/2026/workshops-2/)                             | 官方摘要明确以医学影像、EHR、报告等多模态基础模型为重点  |
| **B** | Workshop  | [Exploring Foundation Models in Medical Image Analysis: Applications, Challenges, and Uncertainties](https://biomedicalimaging.org/2026/workshops-2/) | 通用医学基础模型为主，多模态编码/报告生成是部分讨论内容   |
| **B** | Workshop  | [Large Models Meet Surgical Data Science](https://sites.google.com/view/lm-surg/)                                                                     | 涵盖术前影像、术中信号、机器人运动和 EHR，但专题主旨更宽 |
| **B** | Workshop  | [Pediatric Brain Data Analysis](https://pediatricbrainanalysis.github.io/)                                                                            | 纳入影像+EHR/组学研究主题，但活动整体是儿科脑研究    |
| **B** | Challenge | [Multi-modal Ulcerative Colitis Grading in Endoscopy](https://endouc-cv.github.io/)                                                                   | 涉及内镜图像分级与图像–文本生成，但整体以疾病分级为主    |

## 官方活动目录

| 会议 | Workshop | Tutorial | Challenge |
|:--|:--|:--|:--|
| MICCAI 2025 | [官方目录](https://conferences.miccai.org/2025/en/workshops.asp) | [官方目录](https://conferences.miccai.org/2025/en/tutorials.asp) | [官方目录](https://conferences.miccai.org/2025/en/challenges.asp) |
| MICCAI 2026 | [官方目录](https://conferences.miccai.org/2026/en/workshops.asp) | [官方目录](https://conferences.miccai.org/2026/en/tutorials.asp) | [官方目录](https://conferences.miccai.org/2026/en/challenges.asp) |
| ISBI 2025 | [官方目录](https://biomedicalimaging.org/2025/workshops/) | [官方目录](https://biomedicalimaging.org/2025/tutorials/) | [官方目录](https://biomedicalimaging.org/2025/challenges/) |
| ISBI 2026 | [官方目录](https://biomedicalimaging.org/2026/workshops-2/) | [官方目录](https://biomedicalimaging.org/2026/tutorials-2/) | [官方目录](https://biomedicalimaging.org/2026/challenges/) |

## 使用与核验说明

- 一个 Workshop 中出现个别跨模态论文，并不意味着该专题整体以多模态为核心；同一主题下的 Workshop、Tutorial 与 Challenge 如为独立活动，则分别保留。
- 个别条目目前仅有会议官方目录、专题简介或标题级证据，尚未完整核查全部议程与论文；相关性分级可随新增一手资料进一步调整。
- 完整日程、讲者主页、Slides、视频及其他状态信息计划移至独立附录，本表仅保留专题入口、分级及核心判定依据。
