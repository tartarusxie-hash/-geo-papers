# GEO / AEO / AI Search 论文合集

> 当搜索的答案开始由 AI 生成，“如何被 AI 看见、引用和推荐”，就成了一个全新的研究领域。这个仓库，把这个领域迄今为止最重要的论文，系统地收集在了一起。

## 这是什么

这是一个面向 GEO（Generative Engine Optimization，生成式引擎优化）、AEO（Answer Engine Optimization，答案引擎优化）与 AI 搜索研究的**论文合集**：共收录 **106 篇**论文索引，其中 **88 篇**附有 PDF 原文，按 **10 个主题**分门别类存放；另外 18 篇因许可原因，仅收录元数据与原文链接。

无论你是刚开始关注 GEO 的产品经理、独立开发者、SEO / GEO 从业者，还是做 AI 搜索方向的研究者，都可以在这里按主题找到对应的代表性工作。

## 十个主题

1. **GEO 基础框架**——GEO 的概念起源、定义与综述，从奠基论文开始读。
2. **GEO 方法优化**——让内容更容易被生成式引擎选中、引用的具体方法。
3. **GEO 测量评估**——如何量化“被 AI 引用”：指标、基准与纵向追踪研究。
4. **AI 搜索实证**——对真实 AI 搜索产品的大规模实证研究，包括中文生成式搜索。
5. **AEO 理论整合**——SEO、GEO、AEO 之间的关系与统一框架。
6. **风险操纵**——对抗攻击、投毒与排名操纵，以及相应的防御研究。
7. **垂直多模态**——电商、多模态等垂直场景中的 GEO。
8. **AI 搜索架构与 Agentic Search**——搜索系统本身的架构，与智能体化搜索。
9. **RAG 检索优化**——检索增强生成中的检索方法改进。
10. **搜索评估治理**——评估方法、风险审计与治理框架。

每个主题的完整论文目录见下方「论文目录」，也可以直接打开对应的文件夹浏览。

## 推荐阅读路径

- **刚入门**：01_GEO基础框架 → 05_AEO理论整合
- **想动手做优化**：02_GEO方法优化 → 03_GEO测量评估
- **关心风险与合规**：06_风险操纵 → 10_搜索评估治理
- **做系统与工程**：08_AI搜索架构与AgenticSearch → 09_RAG检索优化

## 收录原则

- **来源可核**：每篇论文都记录了来源与原始链接，题名、年份、页数、来源集中在 `00_资料说明/论文清单.csv`，一篇一查。
- **原件不改**：PDF 保持原样，可用 `00_资料说明/checksums.sha256` 校验完整性。
- **尊重许可**：与来源仓库的处理一致——采用 arXiv 非独占分发许可的论文仅收录元数据与原文链接（共 18 篇），其余 88 篇收录 PDF 原文。
- **持续更新**：本合集会持续跟踪新发表的 GEO / AEO / AI 搜索论文，按同一套分类增补进来。

## 来源与许可

本合集的分类体系与目录元数据整理自 GEO Citation Lab contributors, "GEO Citation Lab", https://github.com/yaojingang/geo-citation-lab, CC BY 4.0，详见 [ATTRIBUTION.md](./ATTRIBUTION.md)。各论文 PDF 的权利归其原作者或出版方所有，本仓库仅作学术研究用途的整理与索引。

---

本目录收纳 GEO、AEO、AI Search、生成式搜索引擎优化与引用操纵相关论文资料。源资料来自 `GEO_AI搜索_AEO_论文合集`、2026-06-20 近 30 天新增论文调研，2026-07-21 新增的中文生成式搜索实证论文，以及 2026-10-25、2026-10-30 两次文献更新。当前包含 106 篇论文索引，其中 88 份 PDF 按主题保存在 10 个目录，18 篇通过原始来源阅读。

原仓库在线导航页：[https://yaojingang.github.io/geo-citation-lab/02-geo-aeo-ai-search-papers/](https://yaojingang.github.io/geo-citation-lab/02-geo-aeo-ai-search-papers/)

## 分类概览

| 分类 | 主题 | 论文数 | 仓库 PDF 数 |
| --- | --- | ---: | ---: |
| [01_GEO基础框架](./01_GEO基础框架/) | GEO 基础框架 | 6 | 6 |
| [02_GEO方法优化](./02_GEO方法优化/) | GEO 方法优化 | 14 | 12 |
| [03_GEO测量评估](./03_GEO测量评估/) | GEO 测量评估 | 21 | 17 |
| [04_AI搜索实证](./04_AI搜索实证/) | AI 搜索实证 | 11 | 9 |
| [05_AEO理论整合](./05_AEO理论整合/) | AEO 理论整合 | 6 | 6 |
| [06_风险操纵](./06_风险操纵/) | 风险、操纵与对抗 | 23 | 19 |
| [07_垂直多模态](./07_垂直多模态/) | 垂直场景与多模态 | 8 | 5 |
| [08_AI搜索架构与AgenticSearch](./08_AI搜索架构与AgenticSearch/) | AI 搜索架构与 Agentic Search | 7 | 5 |
| [09_RAG检索优化](./09_RAG检索优化/) | RAG 检索优化 | 4 | 3 |
| [10_搜索评估治理](./10_搜索评估治理/) | 搜索评估与治理 | 6 | 6 |
| 合计 | | 106 | 88 |

## 资料说明

- [`00_资料说明/论文清单.csv`](./00_资料说明/论文清单.csv)：论文清单，包含论文题名、年份、页数、文件大小、来源 URL 和备注。文件名为空时，导航页直接打开原站 PDF。
- [`00_资料说明/GEO_AI搜索_AEO_论文整理说明.docx`](./00_资料说明/GEO_AI搜索_AEO_论文整理说明.docx)：原始整理说明。源目录中存在两份相同内容的说明文件，本仓库按 SHA-256 去重保留一份。
- [`00_资料说明/checksums.sha256`](./00_资料说明/checksums.sha256)：本目录导入文件的 SHA-256 校验清单。
- 2026-06-20 新增批次：从近 30 天调研报告中核对 13 篇主表论文和 1 篇延伸阅读，其中 `Dynamics of Adversarial Attacks on Large Language Model-Based Search Engines`、`Don’t Measure Once: Reliable AI Search Visibility Requires Repeated Trials and Structure-Aware Metrics` 已在原 41 篇中，实际新增 12 篇 PDF。
- 2026-07-21 新增：`What Do Chinese-Language Generative Search Engines Cite and Surface? A Large-Scale Empirical Study`，收录至 `04_AI搜索实证`。

- 2026-10-25 新增收录 16 篇：11 篇在 2026-07-21 后首次提交，5 篇为遗漏补录；本轮检索发现的最新首次提交日期为 2026-10-10。
- 2026-10-30 新增收录 36 篇：11 篇为 2026-10-10 后首次提交的新论文，25 篇为遗漏补录；其中 23 篇按 Creative Commons 类许可收录 PDF，13 篇为 arXiv 非独占分发许可、仅收录元数据与原站链接。本轮的更新记录与收录来源见 `00_资料说明/2026-10-30_更新记录.md` 与 `00_资料说明/2026-10-30_收录与来源.json`。
- [本轮更新记录](./00_资料说明/2026-10-25_GEO论文更新记录.md)记录范围、阅读建议和证据边界；[收录与来源](./00_资料说明/2026-10-25_收录与来源.json)记录作者、版本、原始许可、路径和 SHA-256。
- 本轮 11 份公开 PDF 保留各自的 Creative Commons 许可；5 篇采用 arXiv 非独占分发许可的论文仅发布元数据与原站链接。本地阅读副本放在 `本地阅读_2026-10-25/`，不提交至 GitHub。论文原件保持原样，权利归原作者或出版方。

## 论文目录

### 01_GEO基础框架 GEO 基础框架

| 文件 | 论文题名 | 年份 | 来源 |
| --- | --- | --- | --- |
| [01_GEO基础框架_GEO_Generative_Engine_Optimization.pdf](./01_GEO基础框架/01_GEO基础框架_GEO_Generative_Engine_Optimization.pdf) | GEO: Generative Engine Optimization | 2023/2024 | arXiv, KDD 2024 |
| [01_GEO基础框架_GEO_in_Digital_Repositories.pdf](./01_GEO基础框架/01_GEO基础框架_GEO_in_Digital_Repositories.pdf) | Generative Engine Optimization in Digital Repositories: Optimizing Visibility for Generative AI | 2025 | Infonomy |
| [01_GEO基础框架_How_to_Dominate_AI_Search.pdf](./01_GEO基础框架/01_GEO基础框架_How_to_Dominate_AI_Search.pdf) | Generative Engine Optimization: How to Dominate AI Search | 2025 | arXiv |
| [01_GEO基础框架_Navigating_the_Shift_Web_Search_vs_Generative_AI_Response.pdf](./01_GEO基础框架/01_GEO基础框架_Navigating_the_Shift_Web_Search_vs_Generative_AI_Response.pdf) | Navigating the Shift: A Comparative Analysis of Web Search and Generative AI Response Generation | 2026 | arXiv |
| [01_GEO基础框架_Critical_Survey_GEO_2023_2026.pdf](./01_GEO基础框架/01_GEO基础框架_Critical_Survey_GEO_2023_2026.pdf) | Optimizing Visibility in Generative Engines: A Critical Survey of Generative Engine Optimization (2023-2026) | 2026 | arXiv v1，2026-10-25 收录 |
| [01_GEO基础框架_Beyond_Retrieval_Modeling_Confidence_Decay_and_Deterministic_Agentic_Platforms_in_Generative_Engine_Optimization.pdf](./01_GEO基础框架/01_GEO基础框架_Beyond_Retrieval_Modeling_Confidence_Decay_and_Deterministic_Agentic_Platforms_in_Generative_Engine_Optimization.pdf) | Beyond Retrieval: Modeling Confidence Decay and Deterministic Agentic Platforms in Generative Engine Optimization | 2026 | arXiv，2026-10-30 收录 |

### 02_GEO方法优化 GEO 方法优化

| 文件 | 论文题名 | 年份 | 来源 |
| --- | --- | --- | --- |
| [02_GEO方法优化_Beyond_Keywords_Content_Centric_Agents_GSEO.pdf](./02_GEO方法优化/02_GEO方法优化_Beyond_Keywords_Content_Centric_Agents_GSEO.pdf) | Beyond Keywords: Driving Generative Search Engine Optimization with Content-Centric Agents | 2025 | arXiv |
| [02_GEO方法优化_Beyond_SEO_Transformer_Content_Optimisation.pdf](./02_GEO方法优化/02_GEO方法优化_Beyond_SEO_Transformer_Content_Optimisation.pdf) | Beyond SEO: A Transformer-Based Approach for Reinventing Web Content Optimisation | 2025 | arXiv mirror |
| [02_GEO方法优化_IF_GEO_Conflict_Aware_Instruction_Fusion.pdf](./02_GEO方法优化/02_GEO方法优化_IF_GEO_Conflict_Aware_Instruction_Fusion.pdf) | IF-GEO: Conflict-Aware Instruction Fusion for Multi-Query Generative Engine Optimization | 2026 | arXiv |
| [02_GEO方法优化_Role_Augmented_Intent_Driven_GSEO.pdf](./02_GEO方法优化/02_GEO方法优化_Role_Augmented_Intent_Driven_GSEO.pdf) | Role-Augmented Intent-Driven Generative Search Engine Optimization | 2025 | arXiv |
| [02_GEO方法优化_Think_Before_Writing_Feature_Level_Optimization.pdf](./02_GEO方法优化/02_GEO方法优化_Think_Before_Writing_Feature_Level_Optimization.pdf) | Think Before Writing: Feature-Level Optimization for Generative Engine Optimization | 2026 | arXiv |
| [02_GEO方法优化_What_Generative_Search_Engines_Like.pdf](./02_GEO方法优化/02_GEO方法优化_What_Generative_Search_Engines_Like.pdf) | What Generative Search Engines Like: Explaining and Optimizing Website Visibility in Generative Search | 2025 | arXiv |
| [02_GEO方法优化_White_Hat_Search_Engine_Optimization_using_LLMs.pdf](./02_GEO方法优化/02_GEO方法优化_White_Hat_Search_Engine_Optimization_using_LLMs.pdf) | White Hat Search Engine Optimization using Large Language Models | 2025 | arXiv |
| [02_GEO方法优化_Query_Implied_GEO.pdf](./02_GEO方法优化/02_GEO方法优化_Query_Implied_GEO.pdf) | Query Implied Generative Engine Optimization | 2026 | arXiv v1，2026-10-25 收录 |
| [02_GEO方法优化_Agent2UCB_Agentic_GEO.pdf](./02_GEO方法优化/02_GEO方法优化_Agent2UCB_Agentic_GEO.pdf) | Agent2UCB: Agentic System for Generative Engine Optimization | 2026 | arXiv v1，2026-10-25 收录 |
| [原站 PDF](https://arxiv.org/pdf/2608.27631v1) | Beyond the Vacuum: Combinatorial Strategy Selection for Competitor-Aware Generative Engine Optimization | 2026 | arXiv v1，2026-10-25 收录 |
| [02_GEO方法优化_AgenticGEO_Self_Evolving_System.pdf](./02_GEO方法优化/02_GEO方法优化_AgenticGEO_Self_Evolving_System.pdf) | AgenticGEO: A Self-Evolving Agentic System for Generative Engine Optimization | 2026 | arXiv v1，2026-10-25 收录 |
| [原站 PDF](https://arxiv.org/pdf/2604.19516v1) | From Experience to Skill: Multi-Agent Generative Engine Optimization via Reusable Strategy Learning | 2026 | arXiv v1，2026-10-25 收录 |
| [02_GEO方法优化_Diagnosing_and_Repairing_Citation_Failures_in_Generative_Engine_Optimization.pdf](./02_GEO方法优化/02_GEO方法优化_Diagnosing_and_Repairing_Citation_Failures_in_Generative_Engine_Optimization.pdf) | Diagnosing and Repairing Citation Failures in Generative Engine Optimization | 2026 | arXiv，2026-10-30 收录 |
| [02_GEO方法优化_Gap_Detection_Mitigating_Homogenization_through_Demand_and_Defensibility.pdf](./02_GEO方法优化/02_GEO方法优化_Gap_Detection_Mitigating_Homogenization_through_Demand_and_Defensibility.pdf) | Gap Detection: Mitigating Homogenization through Demand and Defensibility | 2026 | arXiv，2026-10-30 收录 |

### 03_GEO测量评估 GEO 测量评估

| 文件 | 论文题名 | 年份 | 来源 |
| --- | --- | --- | --- |
| [03_GEO测量评估_AI_Answer_Engine_Citation_Behavior_GEO16.pdf](./03_GEO测量评估/03_GEO测量评估_AI_Answer_Engine_Citation_Behavior_GEO16.pdf) | AI Answer Engine Citation Behavior: A Longitudinal Study of GEO in 16 Generative Engines | 2025 | arXiv |
| [03_GEO测量评估_C_SEO_Bench_Does_Conversational_SEO_Work.pdf](./03_GEO测量评估/03_GEO测量评估_C_SEO_Bench_Does_Conversational_SEO_Work.pdf) | C-SEO Bench: Does Conversational SEO Work? | 2025 | arXiv, NeurIPS Datasets and Benchmarks |
| [03_GEO测量评估_Dont_Measure_Once_AI_Search_Visibility.pdf](./03_GEO测量评估/03_GEO测量评估_Dont_Measure_Once_AI_Search_Visibility.pdf) | Don’t Measure Once: Reliable AI Search Visibility Requires Repeated Trials and Structure-Aware Metrics | 2026 | arXiv |
| [03_GEO测量评估_AEO_Natural_Experiment_ChatGPT_Referral_Traffic.pdf](./03_GEO测量评估/03_GEO测量评估_AEO_Natural_Experiment_ChatGPT_Referral_Traffic.pdf) | Disentangling Answer Engine Optimization from Platform Growth: A Log-Based Natural Experiment on ChatGPT Referral Traffic | 2026 | arXiv |
| [03_GEO测量评估_From_Citation_Selection_to_Citation_Absorption.pdf](./03_GEO测量评估/03_GEO测量评估_From_Citation_Selection_to_Citation_Absorption.pdf) | From Citation Selection to Citation Absorption: Understanding Source Influence in LLM-Generated Answers | 2026 | arXiv |
| [03_GEO测量评估_GEO_at_Scale_Brand_Visibility_AI_Search_Engines.pdf](./03_GEO测量评估/03_GEO测量评估_GEO_at_Scale_Brand_Visibility_AI_Search_Engines.pdf) | Generative Engine Optimization at Scale: Measuring Brand Visibility Across AI Search Engines | 2026 | arXiv |
| [03_GEO测量评估_SAGEO_Arena_Realistic_Environment.pdf](./03_GEO测量评估/03_GEO测量评估_SAGEO_Arena_Realistic_Environment.pdf) | SAGEO: A Search Arena for Generative Engine Optimization in a Realistic Environment | 2026 | arXiv |
| [03_GEO测量评估_Structural_Feature_Engineering_for_GEO.pdf](./03_GEO测量评估/03_GEO测量评估_Structural_Feature_Engineering_for_GEO.pdf) | Structural Feature Engineering for Generative Engine Optimization | 2026 | arXiv |
| [03_GEO测量评估_Conversational_Capture_Trajectory_Level_GEO.pdf](./03_GEO测量评估/03_GEO测量评估_Conversational_Capture_Trajectory_Level_GEO.pdf) | Conversational Capture: A Trajectory-Level Framework for Evaluating Generative Engine Optimization in Multi-turn Human-Agent Interaction | 2026 | arXiv v1，2026-10-25 收录 |
| [原站 PDF](https://arxiv.org/pdf/2608.30023v1) | Demand-Side Measurement for Generative Engine Optimization: Constructing and Validating a Million-Persona, Intent-Annotated Buyer Corpus | 2026 | arXiv v1，2026-10-25 收录 |
| [原站 PDF](https://arxiv.org/pdf/2609.07559v1) | Scoring Without the Engine: Validating a Deterministic, Manipulation-Resistant Content Score for Generative Engines, End to End | 2026 | arXiv v1，2026-10-25 收录 |
| [原站 PDF](https://arxiv.org/pdf/2609.22655v1) | Scoring With the Engine: Retrieval Exposure, Cross-Engine Divergence, and the Limits of Engine-Agnostic GEO Scores | 2026 | arXiv v1，2026-10-25 收录 |
| [03_GEO测量评估_Generative_Marketing_Mix_Modeling.pdf](./03_GEO测量评估/03_GEO测量评估_Generative_Marketing_Mix_Modeling.pdf) | Generative Marketing Mix Modeling: A Causal Inference Framework Linking GEO and GEM to Business Impact | 2026 | arXiv v1，2026-10-25 收录 |
| [03_GEO测量评估_Quantifying_Uncertainty_in_AI_Visibility_A_Statistical_Framework_for_Generative_Search_Measurement.pdf](./03_GEO测量评估/03_GEO测量评估_Quantifying_Uncertainty_in_AI_Visibility_A_Statistical_Framework_for_Generative_Search_Measurement.pdf) | Quantifying Uncertainty in AI Visibility: A Statistical Framework for Generative Search Measurement | 2026 | arXiv，2026-10-30 收录 |
| [03_GEO测量评估_What_Gets_Cited_Competitive_GEO_in_AI_Answer_Engines.pdf](./03_GEO测量评估/03_GEO测量评估_What_Gets_Cited_Competitive_GEO_in_AI_Answer_Engines.pdf) | What Gets Cited: Competitive GEO in AI Answer Engines | 2026 | arXiv，2026-10-30 收录 |
| [03_GEO测量评估_Incumbent_Advantage_Brand_Bias_and_Cognitive_Manipulation_Dynamics_in_LLM_Recommendation_Systems.pdf](./03_GEO测量评估/03_GEO测量评估_Incumbent_Advantage_Brand_Bias_and_Cognitive_Manipulation_Dynamics_in_LLM_Recommendation_Systems.pdf) | Incumbent Advantage: Brand Bias and Cognitive Manipulation Dynamics in LLM Recommendation Systems | 2026 | arXiv，2026-10-30 收录 |
| [03_GEO测量评估_Measuring_GEO_Visibility_Prompt_Corpora_Define_the_Answer_Market.pdf](./03_GEO测量评估/03_GEO测量评估_Measuring_GEO_Visibility_Prompt_Corpora_Define_the_Answer_Market.pdf) | Measuring GEO Visibility: Prompt Corpora Define the Answer Market | 2026 | arXiv，2026-10-30 收录 |
| [03_GEO测量评估_VoteGEO_Bench_Measuring_the_Impact_of_Generative_Engine_Optimization_on_Electoral_Visibility.pdf](./03_GEO测量评估/03_GEO测量评估_VoteGEO_Bench_Measuring_the_Impact_of_Generative_Engine_Optimization_on_Electoral_Visibility.pdf) | VoteGEO-Bench: Measuring the Impact of Generative Engine Optimization on Electoral Visibility | 2026 | arXiv，2026-10-30 收录 |
| [03_GEO测量评估_Location_Location_Generation_Where_You_Ask_Matters_for_Generative_Engine_Optimization.pdf](./03_GEO测量评估/03_GEO测量评估_Location_Location_Generation_Where_You_Ask_Matters_for_Generative_Engine_Optimization.pdf) | Location, Location, Generation: Where You Ask Matters for Generative Engine Optimization | 2026 | arXiv，2026-10-30 收录 |
| [03_GEO测量评估_Humanitys_Last_Choice_A_Common_Evaluation_Standard_for_Generative_Engine_Optimization.pdf](./03_GEO测量评估/03_GEO测量评估_Humanitys_Last_Choice_A_Common_Evaluation_Standard_for_Generative_Engine_Optimization.pdf) | Humanity's Last Choice: A Common Evaluation Standard for Generative Engine Optimization | 2026 | arXiv，2026-10-30 收录 |
| [原站 PDF](https://arxiv.org/pdf/2610.38090) | Predicting What Answer Engines Cite: Open Decision Models, Rerankers and a Distilled 4B Student on Ten Engines under Controlled Retrieval | 2026 | arXiv，2026-10-30 收录 |

### 04_AI搜索实证 AI 搜索实证

| 文件 | 论文题名 | 年份 | 来源 |
| --- | --- | --- | --- |
| [04_AI搜索实证_A_Survey_of_Generative_Search_and_Recommendation.pdf](./04_AI搜索实证/04_AI搜索实证_A_Survey_of_Generative_Search_and_Recommendation.pdf) | A Survey of Generative Search and Recommendation in the Era of Large Language Models | 2024/2025 | Generative Search and Recommendation |
| [04_AI搜索实证_Characterizing_Web_Search_in_Generative_AI_Age.pdf](./04_AI搜索实证/04_AI搜索实证_Characterizing_Web_Search_in_Generative_AI_Age.pdf) | Characterizing Web Search in the Age of Generative AI | 2026 | arXiv |
| [04_AI搜索实证_Chinese_Language_Generative_Search_Engines_Citation_Study.pdf](./04_AI搜索实证/04_AI搜索实证_Chinese_Language_Generative_Search_Engines_Citation_Study.pdf) | What Do Chinese-Language Generative Search Engines Cite and Surface? A Large-Scale Empirical Study | 2026 | arXiv |
| [04_AI搜索实证_How_Generative_AI_Disrupts_Search_Google_AI_Overviews.pdf](./04_AI搜索实证/04_AI搜索实证_How_Generative_AI_Disrupts_Search_Google_AI_Overviews.pdf) | How Generative AI Disrupts Search: Consumer Behavior, Website Traffic, and the Impact of Google AI Overviews | 2026 | ACM SIGIR 2026 author PDF |
| [04_AI搜索实证_NExT_Search_User_Feedback_Ecosystem.pdf](./04_AI搜索实证/04_AI搜索实证_NExT_Search_User_Feedback_Ecosystem.pdf) | NExT-Search: Rebuilding User Feedback Ecosystem for Generative AI Search | 2025 | arXiv |
| [04_AI搜索实证_What_Evidence_Do_Language_Models_Find_Convincing.pdf](./04_AI搜索实证/04_AI搜索实证_What_Evidence_Do_Language_Models_Find_Convincing.pdf) | What Evidence Do Language Models Find Convincing? | 2024 | arXiv |
| [04_AI搜索实证_What_Drives_AI_Citations.pdf](./04_AI搜索实证/04_AI搜索实证_What_Drives_AI_Citations.pdf) | What Drives AI Citations? Content, Retrieval and Model Knowledge in Generative Engine Optimization (GEO) | 2026 | arXiv v1，2026-10-25 收录 |
| [原站 PDF](https://arxiv.org/pdf/2601.00869) | Cultural Encoding in Large Language Models: The Existence Gap in AI-Mediated Brand Discovery | 2025 | arXiv，2026-10-30 收录 |
| [04_AI搜索实证_The_Discovery_Gap_How_Product_Hunt_Startups_Vanish_in_LLM_Organic_Discovery_Queries.pdf](./04_AI搜索实证/04_AI搜索实证_The_Discovery_Gap_How_Product_Hunt_Startups_Vanish_in_LLM_Organic_Discovery_Queries.pdf) | The Discovery Gap: How Product Hunt Startups Vanish in LLM Organic Discovery Queries | 2026 | arXiv，2026-10-30 收录 |
| [04_AI搜索实证_How_Generative_AI_Disrupts_Search_An_Empirical_Study_of_Google_Search_Gemini_and_AI_Overviews.pdf](./04_AI搜索实证/04_AI搜索实证_How_Generative_AI_Disrupts_Search_An_Empirical_Study_of_Google_Search_Gemini_and_AI_Overviews.pdf) | How Generative AI Disrupts Search: An Empirical Study of Google Search, Gemini, and AI Overviews | 2026 | arXiv，2026-10-30 收录 |
| [原站 PDF](https://arxiv.org/pdf/2610.15382) | Understanding ChatGPT Citations: Evidence from Production Web Search Across Model Generations | 2026 | arXiv，2026-10-30 收录 |

### 05_AEO理论整合 AEO 理论整合

| 文件 | 论文题名 | 年份 | 来源 |
| --- | --- | --- | --- |
| [05_AEO理论整合_From_SEO_to_AEO_Generative_AI_Search_Visibility.pdf](./05_AEO理论整合/05_AEO理论整合_From_SEO_to_AEO_Generative_AI_Search_Visibility.pdf) | From SEO to Answer Engine Optimization (AEO): Generative AI and the Transformation of Search Visibility | 2025 | ResearchGate chapter PDF |
| [05_AEO理论整合_Integrated_Framework_for_SEO_GEO_AEO.pdf](./05_AEO理论整合/05_AEO理论整合_Integrated_Framework_for_SEO_GEO_AEO.pdf) | Optimizing for the Artificial Intelligence-Driven Search Era: An Integrated Framework for SEO, GEO, and AEO | 2025 | IJSREM |
| [05_AEO理论整合_Smart_Search_Optimization_SEO_AEO_GEO.pdf](./05_AEO理论整合/05_AEO理论整合_Smart_Search_Optimization_SEO_AEO_GEO.pdf) | Smart Search Optimization: A Theoretical Framework Integrating SEO, AEO and GEO in the Era of Generative AI | 2025 | Loro Journal |
| [05_AEO理论整合_Transition_from_SEO_to_GEO_AEO_AIO_Digital_Marketing.pdf](./05_AEO理论整合/05_AEO理论整合_Transition_from_SEO_to_GEO_AEO_AIO_Digital_Marketing.pdf) | How the Transition from SEO to GEO, AEO, and AIO is Impacting Digital Marketing Strategies | 2025 | IJCRT |
| [05_AEO理论整合_Zero_Click_Search_and_Answer_Engines_Literature_Review.pdf](./05_AEO理论整合/05_AEO理论整合_Zero_Click_Search_and_Answer_Engines_Literature_Review.pdf) | Zero-Click Search and Answer Engines: A Literature Review on SEO Transformation in Digital Marketing | 2025/2026 | JIEM |
| [05_AEO理论整合_AX_is_the_New_AEO.pdf](./05_AEO理论整合/05_AEO理论整合_AX_is_the_New_AEO.pdf) | AX is the New AEO | 2026 | arXiv，2026-10-30 收录 |

### 06_风险操纵 风险、操纵与对抗

| 文件 | 论文题名 | 年份 | 来源 |
| --- | --- | --- | --- |
| [06_风险操纵_Adversarial_SEO_for_LLMs.pdf](./06_风险操纵/06_风险操纵_Adversarial_SEO_for_LLMs.pdf) | Adversarial Search Engine Optimization for Large Language Models | 2024 | arXiv |
| [06_风险操纵_CONFLICTBANK_Knowledge_Conflicts_in_LLMs.pdf](./06_风险操纵/06_风险操纵_CONFLICTBANK_Knowledge_Conflicts_in_LLMs.pdf) | CONFLICTBANK: A Benchmark for Evaluating the Influence of Knowledge Conflicts in LLMs | 2024 | OpenReview |
| [06_风险操纵_Dynamics_of_Adversarial_Attacks_on_LLM_Search_Engines.pdf](./06_风险操纵/06_风险操纵_Dynamics_of_Adversarial_Attacks_on_LLM_Search_Engines.pdf) | Dynamics of Adversarial Attacks on Large Language Model-Based Search Engines | 2025 | arXiv |
| [06_风险操纵_GASLITEing_the_Retrieval.pdf](./06_风险操纵/06_风险操纵_GASLITEing_the_Retrieval.pdf) | GASLITEing the Retrieval: Exploring Vulnerabilities in Dense Embedding-Based Search | 2024/2025 | OpenReview |
| [06_风险操纵_Manipulating_LLMs_to_Increase_Product_Visibility.pdf](./06_风险操纵/06_风险操纵_Manipulating_LLMs_to_Increase_Product_Visibility.pdf) | Manipulating Large Language Models to Increase Product Visibility | 2024 | arXiv |
| [06_风险操纵_Persistent_Pre_Training_Poisoning_of_LLMs.pdf](./06_风险操纵/06_风险操纵_Persistent_Pre_Training_Poisoning_of_LLMs.pdf) | Persistent Pre-Training Poisoning of LLMs | 2024 | arXiv |
| [06_风险操纵_PoisonArena_Competing_Poisoning_Attacks_in_RAG.pdf](./06_风险操纵/06_风险操纵_PoisonArena_Competing_Poisoning_Attacks_in_RAG.pdf) | PoisonArena: Uncovering Competing Poisoning Attacks in Retrieval-Augmented Generation | 2025 | arXiv |
| [06_风险操纵_Ranking_Manipulation_for_Conversational_Search_Engines.pdf](./06_风险操纵/06_风险操纵_Ranking_Manipulation_for_Conversational_Search_Engines.pdf) | Ranking Manipulation for Conversational Search Engines | 2024 | arXiv |
| [06_风险操纵_StealthRank_LLM_Ranking_Manipulation.pdf](./06_风险操纵/06_风险操纵_StealthRank_LLM_Ranking_Manipulation.pdf) | StealthRank: LLM Ranking Manipulation via Stealthy Prompt Optimization | 2025 | arXiv |
| [06_风险操纵_Unveiling_Resilience_of_LLM_Enhanced_Search.pdf](./06_风险操纵/06_风险操纵_Unveiling_Resilience_of_LLM_Enhanced_Search.pdf) | Unveiling the Resilience of LLM-Enhanced Search Engines Against Adversarial Attacks | 2026 | arXiv |
| [06_风险操纵_SafeGEO_Recommendation_Agent_Risks.pdf](./06_风险操纵/06_风险操纵_SafeGEO_Recommendation_Agent_Risks.pdf) | SafeGEO: Understanding Generative Engine Optimization Risks in Recommendation Agents | 2026 | arXiv v2，2026-10-25 收录 |
| [06_风险操纵_GEO_Defender_Malicious_Optimization.pdf](./06_风险操纵/06_风险操纵_GEO_Defender_Malicious_Optimization.pdf) | When Optimization Becomes Manipulation: Defending Generative Search against Malicious Generative Engine Optimization | 2026 | arXiv v1，2026-10-25 收录 |
| [06_风险操纵_Controlling_Output_Rankings_in_LLM_Based_Search_via_Generative_Engine_Optimization.pdf](./06_风险操纵/06_风险操纵_Controlling_Output_Rankings_in_LLM_Based_Search_via_Generative_Engine_Optimization.pdf) | Controlling Output Rankings in LLM-Based Search via Generative Engine Optimization | 2026 | arXiv，2026-10-30 收录 |
| [06_风险操纵_SCI_Defense_Detecting_Persuasion_Structured_Manipulation_of_LLM_Based_Ranking_in_Generative_Engines.pdf](./06_风险操纵/06_风险操纵_SCI_Defense_Detecting_Persuasion_Structured_Manipulation_of_LLM_Based_Ranking_in_Generative_Engines.pdf) | SCI-Defense: Detecting Persuasion-Structured Manipulation of LLM-Based Ranking in Generative Engines | 2026 | arXiv，2026-10-30 收录 |
| [原站 PDF](https://arxiv.org/pdf/2605.29107) | GEO-Bench: Benchmarking Ranking Manipulation in Generative Engine Optimization | 2026 | arXiv，2026-10-30 收录 |
| [原站 PDF](https://arxiv.org/pdf/2606.13610) | One Polluted Page Is Enough: Evaluating Web Content Pollution in LLM Recommenders | 2026 | arXiv，2026-10-30 收录 |
| [06_风险操纵_GPE_Evaluating_Robust_Evidence_Aggregation_for_Fact_Verification_under_Controllable_GEO_Style_Poisoning.pdf](./06_风险操纵/06_风险操纵_GPE_Evaluating_Robust_Evidence_Aggregation_for_Fact_Verification_under_Controllable_GEO_Style_Poisoning.pdf) | GPE: Evaluating Robust Evidence Aggregation for Fact Verification under Controllable GEO-Style Poisoning | 2026 | arXiv，2026-10-30 收录 |
| [06_风险操纵_GEO_Flag_Detecting_and_Measuring_GEO_Optimized_Web_Content.pdf](./06_风险操纵/06_风险操纵_GEO_Flag_Detecting_and_Measuring_GEO_Optimized_Web_Content.pdf) | GEO-Flag: Detecting and Measuring GEO-Optimized Web Content | 2026 | arXiv，2026-10-30 收录 |
| [原站 PDF](https://arxiv.org/pdf/2609.02316) | Counter-GEO-Bench: Evaluating Defenses Against Information-Distorting Generative Engine Optimization | 2026 | arXiv，2026-10-30 收录 |
| [原站 PDF](https://arxiv.org/pdf/2609.06027) | Evaluating Deep-Search Agents under Hierarchical Web Evidence Poisoning | 2026 | arXiv，2026-10-30 收录 |
| [06_风险操纵_From_Public_Posts_to_AI_Search_Citations_Measuring_the_Fragility_of_AI_Search.pdf](./06_风险操纵/06_风险操纵_From_Public_Posts_to_AI_Search_Citations_Measuring_the_Fragility_of_AI_Search.pdf) | From Public Posts to AI-Search Citations: Measuring the Fragility of AI Search | 2026 | arXiv，2026-10-30 收录 |
| [06_风险操纵_A_Cues_Hidden_Price_Auditing_Seller_Influence_on_AI_Shoppers.pdf](./06_风险操纵/06_风险操纵_A_Cues_Hidden_Price_Auditing_Seller_Influence_on_AI_Shoppers.pdf) | A Cue's Hidden Price: Auditing Seller Influence on AI Shoppers | 2026 | arXiv，2026-10-30 收录 |
| [06_风险操纵_Toolflation_Seller_Agents_Distort_Tool_Markets_Through_Spontaneous_Generative_Engine_Optimization.pdf](./06_风险操纵/06_风险操纵_Toolflation_Seller_Agents_Distort_Tool_Markets_Through_Spontaneous_Generative_Engine_Optimization.pdf) | Toolflation: Seller Agents Distort Tool Markets Through Spontaneous Generative Engine Optimization | 2026 | arXiv，2026-10-30 收录 |

### 07_垂直多模态 垂直场景与多模态

| 文件 | 论文题名 | 年份 | 来源 |
| --- | --- | --- | --- |
| [07_垂直多模态_Caption_Injection_Generative_Search_Engine.pdf](./07_垂直多模态/07_垂直多模态_Caption_Injection_Generative_Search_Engine.pdf) | Caption Injection for Optimization in Generative Search Engines | 2025 | arXiv |
| [07_垂直多模态_E_GEO_Ecommerce_Testbed.pdf](./07_垂直多模态/07_垂直多模态_E_GEO_Ecommerce_Testbed.pdf) | E-GEO: A Testbed for Generative Engine Optimization in E-Commerce | 2025 | arXiv |
| [07_垂直多模态_Multimodal_GEO_VLM_Rankers.pdf](./07_垂直多模态/07_垂直多模态_Multimodal_GEO_VLM_Rankers.pdf) | Multimodal Generative Engine Optimization: Rank Manipulation for Vision-Language Model Rankers | 2026 | ResearchGate paper PDF |
| [07_垂直多模态_Pinterest_GEO_VLM_Agent_Framework.pdf](./07_垂直多模态/07_垂直多模态_Pinterest_GEO_VLM_Agent_Framework.pdf) | Generative Engine Optimization: A VLM and Agent Framework for Pinterest Acquisition Growth | 2026 | arXiv |
| [07_垂直多模态_Style_and_Semantic_Effects_Generative_Search_Engine.pdf](./07_垂直多模态/07_垂直多模态_Style_and_Semantic_Effects_Generative_Search_Engine.pdf) | When Content is Goliath and Algorithm is David: The Style and Semantic Effects of Generative Search Engine | 2025 | ResearchGate paper PDF |
| [原站 PDF](https://arxiv.org/pdf/2603.12282) | Algorithmic Trust and Compliance: Benchmarking Brand Notability for UK iGaming Entities in Generative Search Engines | 2026 | arXiv，2026-10-30 收录 |
| [原站 PDF](https://arxiv.org/pdf/2606.16344) | Whose hotel does the AI recommend? An algorithm audit of reputation signals in LLM-assisted hotel selection | 2026 | arXiv，2026-10-30 收录 |
| [原站 PDF](https://arxiv.org/pdf/2607.12056) | Designing Agent-Ready Websites for AI Web Agents: A Framework for Machine Readability, Actionability, and Decision Reliability | 2026 | arXiv，2026-10-30 收录 |

### 08_AI搜索架构与AgenticSearch AI 搜索架构与 Agentic Search

| 文件 | 论文题名 | 年份 | 来源 |
| --- | --- | --- | --- |
| [08_AI搜索架构与AgenticSearch_Decoupled_Search_Grounding_LLM_Agents.pdf](./08_AI搜索架构与AgenticSearch/08_AI搜索架构与AgenticSearch_Decoupled_Search_Grounding_LLM_Agents.pdf) | Decoupling Search from Reasoning: A Vendor-Agnostic Grounding Architecture for LLM Agents | 2026 | arXiv |
| [08_AI搜索架构与AgenticSearch_Diverse_Query_Initialization_Agentic_Search.pdf](./08_AI搜索架构与AgenticSearch/08_AI搜索架构与AgenticSearch_Diverse_Query_Initialization_Agentic_Search.pdf) | Beyond Parallel Sampling: Diverse Query Initialization for Agentic Search | 2026 | arXiv |
| [08_AI搜索架构与AgenticSearch_ScholarQuest_Agentic_Academic_Paper_Search.pdf](./08_AI搜索架构与AgenticSearch/08_AI搜索架构与AgenticSearch_ScholarQuest_Agentic_Academic_Paper_Search.pdf) | ScholarQuest: A Taxonomy-Guided Benchmark for Agentic Academic Paper Search in Open Literature Environments | 2026 | arXiv |
| [08_AI搜索架构与AgenticSearch_Streaming_Tool_Use_in_RAG.pdf](./08_AI搜索架构与AgenticSearch/08_AI搜索架构与AgenticSearch_Streaming_Tool_Use_in_RAG.pdf) | When Does Streaming Tool Use Help? Characterizing Tool-Intent Stabilization in Streaming Retrieval-Augmented Generation | 2026 | arXiv |
| [原站 PDF](https://arxiv.org/pdf/2605.12887) | EcoGEO: Trajectory-Aware Evidence Ecosystems for Web-Enabled LLM Search Agents | 2026 | arXiv，2026-10-30 收录 |
| [08_AI搜索架构与AgenticSearch_ACARE_Agent_Context_Aware_Reranker_for_Iterative_Search.pdf](./08_AI搜索架构与AgenticSearch/08_AI搜索架构与AgenticSearch_ACARE_Agent_Context_Aware_Reranker_for_Iterative_Search.pdf) | ACARE: Agent-Context-Aware Reranker for Iterative Search | 2026 | arXiv，2026-10-30 收录 |
| [原站 PDF](https://arxiv.org/pdf/2610.36134) | When Connectivity Misleads: Guiding Agentic Search with Contrastive Evidence Paths | 2026 | arXiv，2026-10-30 收录 |

### 09_RAG检索优化 RAG 检索优化

| 文件 | 论文题名 | 年份 | 来源 |
| --- | --- | --- | --- |
| [09_RAG检索优化_MCompassRAG_Topic_Metadata_Semantic_Compass.pdf](./09_RAG检索优化/09_RAG检索优化_MCompassRAG_Topic_Metadata_Semantic_Compass.pdf) | MCompassRAG: Topic Metadata as a Semantic Compass for Paragraph-Level Retrieval | 2026 | arXiv |
| [09_RAG检索优化_SCAR_Semantic_Continuity_Aware_Retrieval.pdf](./09_RAG检索优化/09_RAG检索优化_SCAR_Semantic_Continuity_Aware_Retrieval.pdf) | SCAR: Semantic Continuity-Aware Retrieval for Efficient Context Expansion in RAG | 2026 | arXiv |
| [09_RAG检索优化_SproutRAG_Attention_Guided_Tree_Search.pdf](./09_RAG检索优化/09_RAG检索优化_SproutRAG_Attention_Guided_Tree_Search.pdf) | SproutRAG: Attention-Guided Tree Search with Progressive Embeddings for Long-Document RAG | 2026 | arXiv |
| [原站 PDF](https://arxiv.org/pdf/2610.37080) | Tessera: Structure-Completed Evidence Units for Web Retrieval-Augmented Generation | 2026 | arXiv，2026-10-30 收录 |

### 10_搜索评估治理 搜索评估与治理

| 文件 | 论文题名 | 年份 | 来源 |
| --- | --- | --- | --- |
| [10_搜索评估治理_App_Store_Ranking_LLM_Generated_Judgments.pdf](./10_搜索评估治理/10_搜索评估治理_App_Store_Ranking_LLM_Generated_Judgments.pdf) | Scaling Search Relevance: Augmenting App Store Ranking with LLM-Generated Judgments | 2026 | arXiv |
| [10_搜索评估治理_SAGE_Scalable_AI_Governance_Evaluation.pdf](./10_搜索评估治理/10_搜索评估治理_SAGE_Scalable_AI_Governance_Evaluation.pdf) | SAGE: Scalable AI Governance & Evaluation | 2026 | arXiv |
| [10_搜索评估治理_Claim_Gated_Source_Risk_Auditing.pdf](./10_搜索评估治理/10_搜索评估治理_Claim_Gated_Source_Risk_Auditing.pdf) | Claim-Gated Source-Risk Auditing for Generative Search | 2026 | arXiv v2，2026-10-25 收录 |
| [10_搜索评估治理_GEO_Risks_Concentration_Disclosure.pdf](./10_搜索评估治理/10_搜索评估治理_GEO_Risks_Concentration_Disclosure.pdf) | Position: Generative Engine Optimization Creates Underexamined Risks, Governance Must Target Concentration, Disclosure, and Academic Blind Spots | 2026 | arXiv v1，2026-10-25 收录 |
| [10_搜索评估治理_Mechanism_Design_for_Generative_Engines_From_Exploitation_toward_Win_Win_Outcomes.pdf](./10_搜索评估治理/10_搜索评估治理_Mechanism_Design_for_Generative_Engines_From_Exploitation_toward_Win_Win_Outcomes.pdf) | Mechanism Design for Generative Engines: From Exploitation toward Win-Win Outcomes | 2026 | arXiv，2026-10-30 收录 |
| [10_搜索评估治理_CHASE_How_Content_Ecosystems_Are_Reshaped_When_Ranking_Is_the_Only_Target.pdf](./10_搜索评估治理/10_搜索评估治理_CHASE_How_Content_Ecosystems_Are_Reshaped_When_Ranking_Is_the_Only_Target.pdf) | CHASE: How Content Ecosystems Are Reshaped When Ranking Is the Only Target | 2026 | arXiv，2026-10-30 收录 |
