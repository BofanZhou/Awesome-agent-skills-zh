# Awesome Agent Skills（中文精选）

> 精选可用的 **AI Agent Skills**，按**用途**划分大类，以来源仓库（簇）为单位整体归类。中文介绍、保留英文术语。

![skills](https://img.shields.io/badge/skills-467-blue) ![repos](https://img.shields.io/badge/repos-26-green) ![stars](https://img.shields.io/badge/stars-913k-brightgreen) ![license](https://img.shields.io/badge/license-MIT-yellow) ![zh](https://img.shields.io/badge/lang-中文-orange)

## 收录标准

- 有可用的 `SKILL.md`，可被 Claude Code / Codex / pi 等 Agent 环境加载
- 有清晰的中文（或可理解英文）文档与触发说明
- 优先收录有维护迹象、stars 较高或经过实际验证的仓库
- 描述为中文意译，关键术语保留英文原文

<a id="toc"></a>
## 目录

1. **[官方出品 · Official](#01-official)**：Anthropic 官方技能 · Codex 生态工具
2. **[科研学术 · Research](#02-research)**：Nature 科研技能系列 · academic-research-skills 学术研究 · scientific-agent-skills 科学 Agent 技能库 · 数学建模竞赛工作流
3. **[公众号 · 中文内容创作](#03-wechat)**：wechat-skills 公众号写作 · wewrite 公众号全流程 · wechat-article-skills 公众号 AI 运营 · Humanizer-zh 去除 AI 痕迹
4. **[知识管理与检索](#04-knowledge)**：Obsidian 知识管理 · claude-obsidian 知识工作流 · anysearch 实时检索 · Agent-Reach 互联网能力路由
5. **[前端 · 设计与视觉](#05-frontend)**：garden-skills 设计创作集 · huashu-design 花叔设计 · taste-skill 品味设计 · ip-as-logo 个人 IP Logo · frontend-slides 网页演示 · guizang 横向翻页网页 PPT · html-slides 网页幻灯片
6. **[安全逆向 · Security](#06-security)**：reverse-skill 安全逆向
7. **[SEO 优化](#07-seo)**：claude-seo SEO 优化
8. **[个人 IP 打造](#08-ip)**：ip-strategist 个人 IP 策略师
9. **[工程流程与元技能](#09-engineering)**：Matt Pocock 技能集 · qiushi-skill 求是工作法
10. **[相关说明](#10-notes)**：收录口径与更新说明
11. **[相关项目](#11-related)**：同类合集仓库与技能市场

<a id="01-official"></a>
## 官方出品 · Official

> 官方维护的高质量 Agent Skills 仓库，稳定且面向生态。

### Anthropic 官方技能 ★171.9k

**来源仓库**：[https://github.com/anthropics/skills](https://github.com/anthropics/skills)  

Anthropic 官方公开的 Agent Skills：办公格式、视觉创作、扩展开发与元技能。

- **algorithmic-art** — 用 p5.js 以种子随机性（seeded randomness）创作算法艺术，支持交互式参数探索。
- **brand-guidelines** — 将 Anthropic 官方品牌色板与字体规范应用到各类产出物上。
- **canvas-design** — 以设计哲学为准则，创建精美的 .png / .pdf 视觉艺术作品。
- **claude-academy-guide** — 回答任何关于 Claude 产品用法的问题前先查此技能，推荐 Claude Academy 上匹配的课程与教程。
- **claude-api** — Claude API / Anthropic SDK 参考：模型 ID、定价、参数、streaming、tool use、MCP 等。
- **discernment-nudge** — 在给出可能被直接采纳的建议或成稿后，自动追加一道审慎性提醒，防止对输出照单全收。
- **doc-coauthoring** — 引导式文档共著（co-authoring）工作流：高效完成提案、技术规格、决策文档等结构化内容。
- **docx** — Word 文档全能处理：创建、读取、编辑与操作 .docx 文件。
- **frontend-design** — 构建新 UI 或重塑既有界面时，提供独特、有意图的视觉设计指导。
- **internal-comms** — 按统一格式撰写各类内部沟通文档：公告、产品更新、备忘录等。
- **mcp-builder** — 构建高质量 MCP（Model Context Protocol）服务器，让 LLM 与外部工具和数据交互。
- **pdf** — PDF 全能处理：读取、抽取、合并、拆分、表单填写与生成。
- **pptx** — 一切涉及 .pptx / .potx 的场景：读取、创建、编辑演示文稿。
- **skill-creator** — 创建新技能、改进现有技能，并通过评测度量技能表现。
- **slack-gif-creator** — 制作适配 Slack 的动图 GIF：内置尺寸与帧率约束、验证工具链。
- **theme-factory** — 给幻灯片、文档、报告、HTML 页面等产物批量套用主题的样式工具箱。
- **web-artifacts-builder** — 用现代前端栈构建精细的多组件 claude.ai HTML artifacts。
- **webapp-testing** — 用 Playwright 与本地 Web 应用交互并测试：点击、填表、截图、验证行为。
- **xlsx** — 电子表格为主的任何任务：读取、创建、编辑 .xlsx 等表格文件。

### Codex 生态工具

OpenAI Codex 环境配套技能：造技能、规则、子代理与宠物孵化。

- **create-rule** — 为 Codex 创建持久化的 AI 指导规则（rules），沉淀编码标准与约定。
- **create-skill** — 引导你为 Codex 编写高质量 Agent Skill：SKILL.md 结构、最佳实践与组织方式。
- **create-subagent** — 创建面向专门任务类型的自定义 subagent。
- **hatch-pet** — 从角色设定图创建、修复、验证、视觉 QA 并打包 Codex 兼容的 v2 动画宠物。
- **migrate-to-skills** — 把 Codex rules（.cursor/rules/*.mdc）与 slash commands 批量转换为 Agent Skills 格式。
- **shell** — 把 /shell 请求按字面执行为 shell 命令（仅在用户明确要求时使用）。
- **update-cursor-settings** — 修改 Codex / VSCode 用户 settings.json 设置。

[⬆ 返回目录](#toc)

<a id="02-research"></a>
## 科研学术 · Research

> 科研全流程：文献、写作、评审、科学计算与数学建模。

### Nature 科研技能系列 ★37.3k

**来源仓库**：[https://github.com/Yuan1z0825/nature-skills](https://github.com/Yuan1z0825/nature-skills)  

Nature 级科研流水线：检索、精读、引用、制图、统计、投稿、返修。

- **nature-academic-search** — 多源文献检索、引用核验，以及严格的独立他引（other-citation）审计。
- **nature-citation** — 按 Nature / CNS 标准，把长段落切分成可引用单元并为稿件添加严格引用。
- **nature-data** — 准备、审计或修订 Nature 级的数据可用性声明（Data Availability）、仓储计划与数据文件。
- **nature-downloader** — 合法获取学术全文：知网机构访问、英文 OA 检索、出版社公开渠道。
- **nature-experiment-log** — 标准化实验日志：直接上传图片 / 语音 / 文字，产出带 YAML frontmatter 的 Markdown，可选集成飞书与 Obsidian。
- **nature-figure** — 创建、修订、审计并导出 Nature 系期刊投稿级科研图表。
- **nature-literature-pipeline** — 全自动文献发现流水线：多源检索→六维评分→筛选，一步到位。
- **nature-paper-card** — 为单篇科学论文构建有据可查的深读 Paper Card（支持预印本 / PDF / DOI / arXiv）。
- **nature-paper-to-patent** — 把论文、学位报告、技术文档、源码、附图与发明人笔记转化为专利交底材料。
- **nature-paper2ppt** — 从科研论文构建完整的 Nature 风格中文答辩 PPTX。
- **nature-polishing** — 把学术文本润色、重构或翻译成简洁的 Nature 风英文，同时保留原意与立场。
- **nature-proposal-writer** — 提案先行的科研写作流水线（proposal-first pipeline），覆盖基金与开题场景。
- **nature-reader** — 构建全文中英对照、图表公式感知、有源可溯的精读 Markdown。
- **nature-ref-verifier** — 参考文献逐条多源交叉验证：逐字段比对作者、标题、年份、卷期、页码，输出结构化验证报告。
- **nature-response** — 起草、审计或修订 Nature 风格的返修信包：逐点回复审稿意见（point-by-point）。
- **nature-reviewer** — 以审稿人视角模拟 Nature 风格或通用的投稿前同行评审（pre-submission review）。
- **nature-shared** — Nature 技能族的内部共享参考支撑包，为其他 nature-* 技能提供公共资源。
- **nature-statistics** — 审计、修订或起草 Nature 级稿件的统计学报告部分。
- **nature-writing** — 从零起草、重构或规划 Nature 风格稿件章节与初次投稿材料。

### academic-research-skills 学术研究 ★43.9k

**来源仓库**：[https://github.com/Imbad0202/academic-research-skills](https://github.com/Imbad0202/academic-research-skills)  

学术研究全链路：论文写作管线、深度研究、评审与完整性检查。

- **academic-paper** — 12-agent 学术论文写作管线：11 种模式（full/plan/outline/revision 等）。
- **academic-paper-reviewer** — 多视角学术论文评审：动态审稿人角色，5 席轮转评审。
- **academic-pipeline** — 完整学术研究管线编排器：research→write→integrity check→review→finalize。
- **deep-research** — 通用深度研究 agent 团队：13-agent 严格学术研究管线。

### scientific-agent-skills 科学 Agent 技能库 ★35.5k

**来源仓库**：[https://github.com/K-Dense-AI/scientific-agent-skills](https://github.com/K-Dense-AI/scientific-agent-skills)  

163 个科学 Agent 技能：生信、量子、材料、统计、写作与评审。

- **adaptyv** — 用 Adaptyv Bio Foundry API/SDK 设计并提交蛋白质实验。
- **aeon** — 时间序列机器学习：分类、回归、预测与聚类（aeon）。
- **analytical-method-validation** — 按 ICH 等规范规划、执行并记录分析方法验证、确认与转移。
- **anndata** — 单细胞分析中带注释矩阵的数据结构（.h5ad 文件）。
- **arbor** — 自主改进真实产物（代码、训练配方、agent 框架、数据管线、提示词）的自动化优化技能。
- **arboreto** — 用可扩展算法（GRNBoost2 等）从基因表达数据推断基因调控网络。
- **astropy** — 天文学与天体物理核心 Python 库：单位、坐标、FITS 与数据工具。
- **autoskill** — 通过 screenpipe 观察屏幕，识别重复的研究工作流并自动匹配成技能。
- **benchling-integration** — Benchling Python SDK/REST API 集成：注册表实体、库存、ELN 条目与工作流。
- **bgpt-paper-search** — 检索科学论文并从全文研究中提取结构化实验数据。
- **bids** — 处理 BIDS（脑成像数据结构）数据集：组织神经影像、元数据与预处理。
- **biopython** — 综合分子生物学工具包：序列操作、FASTA/GenBank 解析、系统发育。
- **bioservices** — 40+ 生信服务的统一 Python 接口，查询多个数据库。
- **bulk-rnaseq** — 端到端 bulk RNA-seq 编排器：从 FASTQ 原始读数经 QC、比对到差异表达。
- **cellxgene-census** — 编程查询 CZ CELLxGENE Census 的版本化公共单细胞与空间转录组数据。
- **cirq** — Google 量子计算框架：面向 Google Quantum AI 硬件设计与运行噪声量子电路。
- **citation-management** — 学术引用管理：搜索 OpenAlex、PubMed、Google Scholar，生成规范引文。
- **clinical-decision-support** — 准备并校验仅限研究的临床决策支持评估、证据画像与队列设计。
- **clinical-reports** — 创建有安全边界的临床病例/诊断/治疗报告草稿并做本地确定性检查。
- **cobrapy** — 基于约束的代谢建模（COBRA）：FBA、FVA、基因敲除、通量采样、SBML 模型。
- **consciousness-council** — 对任何问题/决策/创意运行多视角 Mind Council 审慎讨论。
- **dask** — 大于内存的 pandas/NumPy 分布式计算，扩展实验与数据管线的算力。
- **database-lookup** — 带显式端点、过滤器、分页与来源证明的公共数据库 API 查询。
- **datamol** — RDKit 的 Pythonic 封装，简化接口与合理默认值，分子处理首选。
- **deepchem** — 分子机器学习：多种特征化器与预置数据集，属性预测（ADMET、毒性）。
- **deepspot-m** — 用 DeepSpot-M 从 H&E 组织学生成全转录组虚拟空间转录组。
- **deeptools** — NGS 分析工具包：BAM 转 bigWig、QC、热图/图谱与峰分析。
- **depmap** — 查询癌症依赖图谱（DepMap）：细胞系基因依赖评分（CRISPR/RNAi）。
- **dhdna-profiler** — 从任意文本提取认知模式与思维指纹。
- **diffdock** — DiffDock/DiffDock-L 分子对接：蛋白-小分子姿态预测。
- **dnanexus-integration** — 用 dx CLI/dxpy 在 DNAnexus 上构建并运行可复现的基因组学工作负载。
- **docx-sci** — 科学场景的 Word 文档读写处理（scientific-agent-skills 版本）。
- **esm** — ESM3/ESMC 蛋白语言模型：序列生成、结构预测与 Forge/Biohub 推理。
- **etetoolkit** — 系统发育与层级树的分析、比较、注释与可视化。
- **exa-search** — Exa 驱动的科学/技术内容网页搜索与抽取工具包。
- **experimental-design** — 在收集数据前设计实验与研究：选择设计、随机化、区组化与假设铺垫。
- **exploratory-data-analysis** — 对支持的科学文件做有界、本地的探索性分析。
- **flowio** — 读取、检查与写入流式细胞术标准（FCS）2.0/3.0/3.1 文件。
- **fluidsim** — 规划、配置、检查与重启有界 FluidSim 计算流体动力学仿真。
- **generate-image** — 通过 OpenRouter Image API 用 AI 模型生成/编辑图像（Gemini、Seedream 等）。
- **geniml** — 本地基因组区间工作流：校验 BED 与 universe 契约，区间代数与统计。
- **genomic-coordinates** — 转换基因组区间坐标约定，归一化并比较变异表示。
- **genomic-intelligence** — 用 Genomic Intelligence 直接从 DNA 序列预测调控特征、基因结构与表达。
- **geomaster** — 综合地学技能：遥感、GIS、空间分析与机器学习。
- **geopandas** — GeoPandas 工作流：GeoSeries/GeoDataFrame 操作与本地审计。
- **get-available-resources** — 检测主机资源：CPU、内存、磁盘、调度器、容器与加速器限制。
- **gget** — 快速 CLI/Python 查询 20+ 生信数据库（基因信息、BLAST 等）。
- **ginkgo-cloud-lab** — 在 Ginkgo Bioworks 云实验室提交并管理实验方案。
- **glycoengineering** — 分析与工程化蛋白质糖基化：扫描 N-糖基化位点与糖型工程。
- **gtars** — 本地基因组区间模型与集合代数：重叠、计数、共识与集合运算。
- **histolab** — 轻量 WSI 瓦片提取与预处理：基本切片处理、组织检测。
- **hugging-science** — 在生物学/化学/物理等科学领域做 AI/ML 工作时的 Hugging Face 工具链。
- **hypogenic** — 规划与审计 ChicagoHAI HypoGeniC/HypoRefine 的 LLM 辅助假设生成。
- **hypothesis-generation** — 构建有证据边界的科学问题、候选假设、竞争解释与因果推理。
- **imaging-data-commons** — 查询并下载 NCI 影像数据共享库的公共癌症影像数据。
- **infographics** — 用 Nano Banana Pro AI 制作专业信息图，智能迭代优化。
- **iso-standards-readiness** — 准备并结构审查 ISO 管理体系与实验室认可的就绪证据。
- **lab-hardware-cad** — 用 build123d 参数化设计实验室硬件并导出可制造 STL。
- **labarchive-integration** — 与 LabArchives ELN REST 与 Inventory API 安全集成。
- **lamindb** — LaminDB 生物数据集谱系原生湖仓：数据管理、查询与追踪。
- **latchbio-integration** — 用 Python SDK/CLI 在 Latch 上构建、注册、调试与运行生信工作流。
- **latex-posters** — 用 beamerposter/tikzposter/baposter 制作 LaTeX 科研海报。
- **liteparse** — 本地文档与 PDF 解析，返回带包围盒的空间文本。
- **literature-review** — 用多个学术数据库（PubMed、arXiv、bioRxiv 等）做系统性文献综述。
- **markdown-mermaid-writing** — 科学文档与 Mermaid 图表的综合写作技能。
- **market-research-reports** — 构建证据可溯的市场研究报告与假设驱动的市场规模测算。
- **markitdown** — 用 Microsoft MarkItDown 把异构文档与 URL 转成 Markdown。
- **matchms** — 处理、清洗、比较与搜索串联质谱（MS/MS 文件 I/O）。
- **matlab** — 构建、审查、迁移与安全规划 MATLAB / GNU Octave 数值工作流。
- **matplotlib** — 底层绘图库：精细控制出版级图表。
- **medchem** — 药物化学过滤器：Lipinski/Veber/CN 规则做化合物筛选。
- **modal** — Modal 无服务器云平台：按需运行 Python（含按需 GPU）。
- **molecular-dynamics** — 用 OpenMM/MDAnalysis 运行与分析分子动力学模拟。
- **molfeat** — 分子特征化（100+ 特征化器）：ECFP、MACCS、描述符、预训练模型。
- **ncats-arax** — 查询 NCATS Translator ARAX 生产 API：有界、带类型、来源丰富的单跳问答。
- **networkx** — 用 NetworkX 创建、分析与可视化复杂网络与图。
- **neurokit2** — 用 NeuroKit2 构建生理时间序列（ECG/EEG/EDA）的可复现研究流程。
- **neuropixels-analysis** — 用 SpikeInterface 端到端分析 Neuropixels 细胞外记录。
- **nextflow** — 端到端构建、运行与调试 Nextflow 数据管线与 nf-core 工作流。
- **omero-integration** — 用 omero-py 安全检查并自动化 OMERO.server 显微数据工作流。
- **onekgpd** — 查询千人基因组计划（3,202 例全基因组，GRCh38）数据集。
- **ontology-term-resolution** — 把自由文本科学标签解析为本体术语 ID 并校验既有 CURIEs。
- **open-notebook** — 自托管开源 NotebookLM 替代品：AI 研究与文档助手。
- **openpiv** — 用 OpenPIV 做粒子图像测速（PIV）分析，提取速度场。
- **opentrons-integration** — 编写、审查、迁移与排障 Opentrons Python Protocol API v2 协议。
- **optimize-for-gpu** — 在 NVIDIA 硬件上 GPU 加速科学 Python 并验证结果正确性。
- **pacsomatic** — nf-core/pacsomatic 配对肿瘤-正常工作流的操作工具包（BAM 输入）。
- **paper-lookup** — 搜索 11 个学术文献 API：论文、预印本、引用与开放获取全文。
- **paperclip** — 搜索与阅读生物医学全文论文、FDA/PMDA/EMA 监管文件与临床试验。
- **paperzilla** — 与 agent 讨论项目、推荐与规范论文（Paperzilla）。
- **parallel-web** — Parallel CLI：网页搜索、URL 抽取、深度研究与结构化数据富化。
- **pathml** — 本地计算病理学：载入与切片 WSI、组织检测与特征提取。
- **pathogen-variant-surveillance** — 通过 GenSpectrum LAPIS API 查询病原体基因组监测数据。
- **pathway-enrichment** — 对基因列表/排名数据做通路与基因集富集分析并解读。
- **pdf-sci** — 科学场景的 PDF 处理（scientific-agent-skills 版本）。
- **peer-review** — 起草有证据边界、建设性的同行评审与结构化稿件评估。
- **pennylane** — 硬件无关的量子机器学习框架，带自动微分。
- **phylogenetics** — 用 MAFFT/IQ-TREE 构建与分析系统发育树。
- **pi-agent** — 使用 Pi 终端编码 harness：安装、配置与在终端内编码。
- **pkpd-modeling** — 药代动力学与药效动力学建模与仿真（NCA、房室模型）。
- **polars** — 高性能 DataFrame 库：Python ETL、分析与 pandas 迁移。
- **polars-bio** — Polars 上的高性能基因组区间操作与生信文件 I/O。
- **pptx-posters** — 用无宏 PowerPoint 创建并审计可编辑的科学海报。
- **pptx-sci** — 科学场景的 PPTX 演示制作（scientific-agent-skills 版本）。
- **primekg** — 查询精准医学知识图谱（PrimeKG）：多尺度生物数据。
- **protocolsio-integration** — 读取、校验并安全导出 protocols.io 数据。
- **pufferlib** — PufferLib 强化学习环境、向量化、策略训练与版本感知指导。
- **pydeseq2** — 用 PyDESeq2 做 bulk RNA-seq 差异基因表达分析。
- **pydicom** — 用 pydicom 读取、检查、写入与安全预检本地 DICOM 数据。
- **pyhealth** — 用 PyHealth 构建临床/医疗深度学习管线（EHR/信号/影像）。
- **pylabrobot** — 开发与审查 PyLabRobot 实验室自动化资源与液体处理计划。
- **pymatgen** — 材料结构分析、校验、转换与计算材料数据处理。
- **pymc** — PyMC 贝叶斯建模：层级模型、MCMC(NUTS)、变分推断与 LOO 验证。
- **pymoo** — 多目标优化框架：NSGA-II/III、MOEA/D、Pareto 前沿与约束处理。
- **pyopenms** — 完整质谱分析平台：蛋白质组学与代谢组学工作流。
- **pysam** — Python/HTSlib 基因组文件读写：SAM/BAM/CRAM/VCF 查询过滤。
- **pytdc** — 通过 PyTDC 使用治疗学数据共享：注册表发现、获批药物与数据集。
- **pytorch-lightning** — PyTorch Lightning 深度学习框架：把 PyTorch 代码组织为模块化训练。
- **pyzotero** — 用 pyzotero 与 Zotero 文献库交互：检索、添加与整理条目。
- **qiskit** — 用 Qiskit 与 IBM Quantum Runtime 构建、仿真、转译与执行量子电路。
- **qutip** — 用 QuTiP 5 仿真与审计闭/开量子系统模型。
- **rdkit** — 化学信息学工具包：SMILES/SDF 解析、描述符、分子子结构搜索。
- **relsa-severity-assessment** — 实验室动物研究的严重度评估与人道终点预测。
- **research-grants** — 为 NSF/NIH/DOE/DARPA 等撰写有竞争力的科研基金提案。
- **research-lookup** — 为科学稿件/研究简报汇编当前学术证据。
- **rowan** — 云原生分子建模与药物化学工作流平台（Rowan，Python SDK）。
- **scanpy** — 标准单细胞 RNA-seq 分析管线：QC、归一化、降维（PCA/UMAP）与聚类。
- **scholar-evaluation** — 对学术作品做定性优先、证据可溯的发展性评审。
- **scientific-brainstorming** — 证据感知的科学头脑风暴：独立生成、结构化讨论与综合。
- **scientific-critical-thinking** — 评估科学主张与证据质量：实验设计效度、结论强度。
- **scientific-schematics** — 用 Nano Banana 2 AI 创建出版级科学示意图。
- **scientific-slides** — 为科研报告构建幻灯片与演示文稿。
- **scientific-visualization** — 用 Matplotlib/Seaborn 创建并审计真实、可访问、出版级科学图表。
- **scientific-writing** — 起草、修订与审计科学稿件：显式证据溯源与报告规范。
- **scikit-bio** — 生物数据工具包：序列分析、比对、系统发育树、多样性度量。
- **scikit-learn** — Python 机器学习：监督/无监督学习、交叉验证与模型选择。
- **scikit-survival** — 构建、评估与审计右删失/竞争风险生存分析工作流。
- **scvelo** — 用 scVelo 做 RNA 速率分析：从未剪接/剪接 mRNA 估计细胞状态转变。
- **scvi-tools** — 单细胞组学深度生成模型：概率批次校正、插补与整合。
- **seaborn** — 统计可视化：与 pandas 集成，快速探索分布与关系。
- **shap** — 用 SHAP 解释与审计机器学习预测。
- **simpy** — 用 SimPy 构建、检查、测试与分析基于进程的离散事件仿真。
- **stable-baselines3** — 生产级强化学习算法（PPO、SAC、DQN、TD3 等）。
- **statistical-analysis** — 研究数据的引导式统计分析：检验选择、假设检查、效应量。
- **statistical-power** — 研究规划的样本量与统计功效计算。
- **statsmodels** — Python 统计模型库：OLS、GLM、混合模型、时间序列。
- **sympy** — Python 精确符号数学：代数、微积分、方程求解与符号化简。
- **tamarind** — 访问 Tamarin 上的开源分子设计与结构生物学工具集合。
- **tiledbvcf** — 用 TileDB 高效存储与检索基因组变异数据（VCF/BCF 可扩展）。
- **timesfm-forecasting** — 用 Google TimesFM 基础模型做零样本时间序列预测。
- **torch-geometric** — PyTorch Geometric（PyG）图神经网络：节点/边/图分类。
- **torchdrug** — 构建与排障 TorchDrug 分子图工作流：属性预测、选择合成。
- **transformers** — Hugging Face Transformers：加载 Hub 模型、pipeline 推理、文本生成。
- **treatment-plans** — 格式化并结构校验临床决策后的本地治疗计划文档。
- **umap-learn** — 用 UMAP 做非线性降维：2D/3D 嵌入、聚类预处理。
- **uncertainty-and-units** — 用 pint 追踪物理单位并传播测量不确定度。
- **usfiscaldata** — 查询美国财政部财政数据 REST API（免 API key）。
- **vaex** — 处理超大表格数据集（数十亿行，超出内存）的分析。
- **venue-templates** — 用期刊/会议模板准备稿件、会议论文、海报与基金文档。
- **waypoint-bio** — 使用 Outpost Bio 的开源微生物组基础模型（Waypoint 检查点）。
- **what-if-oracle** — 运行结构化 What-If 情景分析：4-6 分支的可能性探索。
- **xlsx-sci** — 科学场景的 Excel 表格处理（scientific-agent-skills 版本）。
- **zarr-python** — 分块 N 维数组（Zarr-Python 3）：压缩数组、并行 I/O、S3/GCS 存储。

### 数学建模竞赛工作流 ★616

**来源仓库**：[https://github.com/zhnnky329/MathModeling-skills](https://github.com/zhnnky329/MathModeling-skills)  

数学建模竞赛全链路：拆题、选法、双语言建模、检验、写作、终审。

- **code-reviewer** — 检测已批准的建模代码是 Python 还是 MATLAB / 贝塔天元，并路由到对应的审查技能。
- **completeness-auditor** — 审计当前 lean / submission profile 所需的语义证据是否齐全，标出缺口。
- **consistency-auditor** — 对数学建模各产物做多媒介一致性检查，确保结论在不同文档间不打架。
- **data-auditor-cleaner** — 把赛题附件映射到子问题，审计并清洗原始数据，产出一份可复用的数据画像（data profile）。
- **decision-prompt-builder** — 在真正的建模判断点上生成一张紧凑的选择卡（choice card），供方法选择之前使用。
- **figure-table-planner** — 规划支撑论证所需的最小图表集合：诊断图、对比图、正文图与附录表。
- **final-method-explainer** — 为可提交的子问题构建权威的最终方法说明（final method explanation）。
- **math-figure-generator** — 从已存证的证据生成出版级数学建模图表，并做渲染校验。
- **matlab-code-reviewer** — 对照代码计划、数据契约与模型设定，审查、运行、调试 MATLAB / 贝塔天元建模代码。
- **matlab-model-code-generator** — 为人工批准的主方法生成最小可复现的 MATLAB 兼容代码并运行验证。
- **method-selector** — 为建模子问题构建紧凑的角色化候选方法短名单，并做风险筛查。
- **model-assumptions-builder** — 从问题框架中提取并持续维护全局假设与方法级建模假设。
- **model-code-analyzer** — 把人工批准的主方法与可用基线翻译成语言中立的最小实现方案。
- **modeler-decision-logger** — 把建模者的每个选择与理由忠实追加到规范化的 JSONL 决策日志。
- **paper-polisher** — 润色数模论文：语法、清晰度、公式一致性、hedging（模糊限制语）校准。
- **paper-section-writer** — 从已批准的求解包起草可提交的数模论文章节。
- **problem-classifier** — 按所需输出与结构给解析后的子问题分类，并暴露其中的歧义。
- **problem-parser** — 把数模赛题解析为目标、对象、数据、约束、输出与子问题的结构化框架。
- **python-code-reviewer** — 对照代码计划、数据契约与模型设定，审查、运行、调试已批准的 Python 建模代码。
- **python-model-code-generator** — 为人工批准的主方法与基线生成最小可复现的 Python 建模代码并运行。
- **quality-assurance-auditor** — 提交级最终审计：工作流完整性、证据质量与跨产物一致性的最后关卡。
- **reference-manager** — 数模论文的参考文献管理与核验：生成 BibTeX、检查格式与真实性。
- **related-paper-analyzer** — 收集分析相关论文、报告与参考方法，为方法选择提供不带抄袭风险的依据。
- **result-report-generator** — 汇总实验证据，对比主方法与可用基线，产出结构化结果报告。
- **robustness-checker** — 设计并执行风险定向的稳健性、灵敏度、误差与基线检验。
- **solution-package-builder** — 把最终方法、结果、稳健性与图表组装成可直接交付写作的 submission 包。
- **symbol-table-builder** — 从问题框架与活动方法维护一张全局数学符号与单位总表。
- **workflow-orchestrator** — 巡检数模工作区，评估各子问题的 lean / submission 门禁并推进整体状态。

[⬆ 返回目录](#toc)

<a id="03-wechat"></a>
## 公众号 · 中文内容创作

> 微信公众号从选题、写作、排版、配图到发布的完整创作工具。

### wechat-skills 公众号写作 ★157

**来源仓库**：[https://github.com/gainubi/wechat-skills](https://github.com/gainubi/wechat-skills)  

公众号写作套装：选题、文风 DNA、标题、初稿、配图与排版。

- **article-illustrator** — 为公众号文章生成可截图的扁平化解释配图 HTML 页面。
- **thesis-word-formatter** — 大学生毕业论文 Word 排版：收集学校模板与规范，整理目录、编号、参考文献与图表题注。
- **wechat-draft-writer** — 公众号初稿写作：基于参考资料、语音底稿与文风 DNA 生成高保真初稿。
- **wechat-style-profiler** — 为公众号作者梳理文风 DNA：从 3-10 篇文章建立复用风格画像（14 维分析、标点习惯、段落配方等）。
- **wechat-title-generator** — 公众号标题生成与评估：基于选题大纲生成 8 个标题候选并推荐最优。
- **wechat-topic-outline-planner** — 公众号选题与大纲策划：把粗点子转成 2-3 个高价值选题与主备两套大纲。
- **xiaoyuzhou-download** — 从小宇宙（xiaoyuzhoufm.com）下载播客单集音频。

### wewrite 公众号全流程 ★3.2k

**来源仓库**：[https://github.com/imraywang/wewrite](https://github.com/imraywang/wewrite)  

公众号内容全流程：从热点抓取到微信草稿箱的一条管道。

- **wewrite** — 微信公众号内容主入口：完成选题、素材、写作和审稿，并按需追加配图、排版或草稿箱发布，并分发风格设置、学习修改、数据复盘与多平台改写。
- **wewrite-learn** — WeWrite 自学习模块：从用户人工修改中学习写作偏好（playbook 飞轮）、导入范文建风格库、从公众号文章学习排版主题。
- **wewrite-publish** — WeWrite 排版发布模块：把 Markdown 做成微信预览，或推入公众号草稿箱；支持主题画廊与图片帖。
- **wewrite-review** — WeWrite 编辑审稿模块：核对任务、事实来源、观点与实用性，必要时直接改稿，通过编辑门槛才生成公众号成稿。
- **wewrite-rewrite** — WeWrite 多平台改写模块：把公众号文章内容级真改成其他平台版本（小红书图文笔记、抖音口播脚本）。
- **wewrite-stats** — WeWrite 数据复盘模块：拉取公众号阅读/分享/点赞数据，回填历史记录并给选题、标题、框架的调整建议。
- **wewrite-style** — WeWrite 风格设置模块：首次使用引导（onboard）+ 重设公众号写作风格配置（style.yaml）。
- **wewrite-topic** — WeWrite 选题模块：抓取全网热点 + 垂类高频需求 + 历史表现 + 搜索需求，生成 10 个评分排序的选题。
- **wewrite-visual** — WeWrite 视觉模块：为公众号文章生成封面与内文配图，或只交付提示词。
- **wewrite-write** — WeWrite 写作模块：选题明确后完成文章任务书、主张与证据、素材和初稿。

### wechat-article-skills 公众号 AI 运营 ★534

**来源仓库**：[https://github.com/aiworkskills/wechat-article-skills](https://github.com/aiworkskills/wechat-article-skills)  

微信公众号 AI 运营：选题、写稿、审稿、排版、配图、发布。

- **aws-wechat-article-assets** — 公众号业务资料库与预设包管理：业务资料按产品名组织在 .aws 预设包、主题包、品牌包中。
- **aws-wechat-article-formatting** — 公众号一键排版工具：Markdown 转微信后台可粘贴的 HTML，多主题、多字号、段落样式。
- **aws-wechat-article-images** — 公众号 AI 封面与配图生成：按标题与内容自动匹配画风，一稿多方案，多风格预设可复用。
- **aws-wechat-article-main** — 公众号运营一条龙：微信公众号全流程（选题→写稿→审稿→排版→配图→发布）的内容管线与 AIGC 工作流。
- **aws-wechat-article-publish** — 公众号发布：草稿箱、群发、图文推送与微信 API 自动化。
- **aws-wechat-article-review** — 公众号发布前合规审查：敏感词扫描、错别字检测、政治合规、平台规范校验，一次性输出修改清单。
- **aws-wechat-article-topics** — 公众号 AI 选题与标题生成：热点调研、选题策划、起标题、写摘要、系列排期。
- **aws-wechat-article-writing** — 公众号长文 AI 写作：从话题或提纲生成完整初稿，支持改写、续写、润色、开头结尾优化，可调 DeepSeek 等模型。
- **aws-wechat-sticker** — 公众号贴图与多图推送：从创意构思、AI 生图到公众号图片消息发布全流程，含九宫格自动排布、多图压缩、组图打包。

### Humanizer-zh 去除 AI 痕迹 ★16.1k

**来源仓库**：[https://github.com/op7418/Humanizer-zh](https://github.com/op7418/Humanizer-zh)  

去除文本中的 AI 痕迹，让输出更像人类书写。

- **humanizer-zh** — 去除文本中的 AI 生成痕迹，使其更自然、更像人类书写；基于维基百科「AI 写作特征」指南，检测并修复夸张比喻、套路化过渡等模式。

[⬆ 返回目录](#toc)

<a id="04-knowledge"></a>
## 知识管理与检索

> 把 Obsidian 变成第二大脑，并为 Agent 装上联网检索能力。

### Obsidian 知识管理 ★47.4k

**来源仓库**：[https://github.com/kepano/obsidian-skills](https://github.com/kepano/obsidian-skills)  

Obsidian 创始人出品：CLI、Markdown、Bases 与 JSON Canvas 知识管理。

- **defuddle** — 用 Defuddle CLI 剥离网页导航与杂讯，抽出干净的 Markdown 正文，大幅节省 token。
- **json-canvas** — 创建与编辑 JSON Canvas 画布文件（.canvas）：节点、边、分组与连线，常用于 Obsidian 白板。
- **obsidian-bases** — 创建与编辑 Obsidian Bases（.base 数据库视图）：views、filters、formulas 与 summaries。
- **obsidian-cli** — 通过 Obsidian CLI 读写笔记、任务与属性，支持插件开发、重载与 DOM 检查。
- **obsidian-markdown** — 编写 Obsidian 风味 Markdown：wikilinks、embeds、callouts、properties 等专属语法。

### claude-obsidian 知识工作流 ★13.6k

**来源仓库**：[https://github.com/AgriciDaniel/claude-obsidian](https://github.com/AgriciDaniel/claude-obsidian)  

自组织 AI 第二大脑：wiki 工作流、研究回环、推理与归档。

- **autoresearch** — 有界、带源的研究循环，起草带引用的档案并可选提出主张。
- **save** — 将用户选定的答案、决策、洞察或会话摘要存入 Obsidian 库。
- **think** — 应用 Fable 派生的 10 阶段 OBSERVE/LISTEN/THINK/CONNECT 推理流程。
- **wiki** — 初始化、采用并为独立 Obsidian 知识库路由工作（面向 wiki 工作流）。
- **wiki-cli** — 检测并使用官方 Obsidian CLI 做只读库访问。
- **wiki-fold** — 创建最近 Obsidian wiki 日志的有界、抽取式、结构幂等的汇总。
- **wiki-ingest** — 将来源材料纳入 Obsidian 库，并保留来源与声明追踪。
- **wiki-lint** — 对 Obsidian wiki 跑确定性的只读健康检查。
- **wiki-mode** — 读取或配置库归档方法论，并为待整理知识建议目标位置。
- **wiki-query** — 在不改动的情况下回答限定于库范围的 Obsidian wiki 问题。
- **wiki-retrieve** — 构建并查询库内 BM25 语境检索索引（可选多语言）。

### anysearch 实时检索 ★5.9k

**来源仓库**：[https://github.com/anysearch-ai/anysearch-skill](https://github.com/anysearch-ai/anysearch-skill)  

anysearch 统一实时搜索引擎：通用/垂直/批量搜索与全文抽取。

- **anysearch** — 实时搜索引擎：网页搜索、垂直领域搜索、并行批量搜索与 URL 内容抽取。

### Agent-Reach 互联网能力路由 ★76.0k

**来源仓库**：[https://github.com/Panniantong/Agent-Reach](https://github.com/Panniantong/Agent-Reach)  

互联网能力路由器：15 平台、多后端、零配置检索。

- **agent-reach** — Agent-Reach 互联网能力路由器：用户要求调研/搜索/查资料、或提到某个平台/分享 URL 时，用它从 15 个平台多渠道获取内容（小红书、推特、B站、Reddit、V2EX、LinkedIn、GitHub、YouTube、小宇宙、雪球、RSS 与任意网页）。多后端路由、6 渠道零配置。

[⬆ 返回目录](#toc)

<a id="05-frontend"></a>
## 前端 · 设计与视觉

> 网页幻灯片、设计出图与视觉品味：让 Agent 产出好看的界面与视觉。

### garden-skills 设计创作集 ★11.0k

**来源仓库**：[https://github.com/ConardLi/garden-skills](https://github.com/ConardLi/garden-skills)  

ConardLi 设计创作集：网页文章、视觉设计、知识检索与 AI 出图。

- **beautiful-article** — 把素材（URL / PDF / DOCX / Markdown / 截图）编辑设计成可离线打开与分享的单文件 HTML 网页文章。
- **gpt-image-2** — GPT Image 2 图像生成 / 编辑技能，支持 Garden 本地模式、Host-Native 等三种运行环境。
- **kb-retriever** — 本地知识库目录的检索问答助手：分层索引导航→学习处理方法→按文件类型渐进式检索。
- **web-design-engineer** — 构建或重设计浏览器渲染的精美视觉产物：页面、仪表盘、原型、幻灯片、动效与数据可视化。
- **web-video-presentation** — 把文章或口播稿做成点击驱动的 16:9 网页演示，看起来像视频，可选合成口播音频。

### huashu-design 花叔设计 ★23.6k

**来源仓库**：[https://github.com/alchaincyf/huashu-design](https://github.com/alchaincyf/huashu-design)  

花叔 Design：HTML 高保真原型、幻灯片、动画与专家评审。

- **huashu-design** — 花叔设计：用 HTML 做高保真原型、幻灯片、动画、可视化与专家评审，新设计先出三个方向供选。

### taste-skill 品味设计 ★81.1k

**来源仓库**：[https://github.com/Leonxlnx/taste-skill](https://github.com/Leonxlnx/taste-skill)  

Taste-Skill：给 AI 好品味，反 AI 味的视觉设计精修。

- **brandkit** — 高端品牌套件图生成：品牌规范板、logo 精修与物料。
- **design-taste-frontend** — 反 AI 味前端技能：落地页、作品集与改版，先读后设计。
- **design-taste-frontend-v1** — 初版 v1 taste-skill，为依赖其精确行为的旧项目保留。
- **full-output-enforcement** — 覆盖默认 LLM 截断行为，强制完整代码生成并禁用占位符。
- **gpt-taste** — 精英 UX/UI 与高级 GSAP 动效工程师，强制 Python 驱动的真随机化。
- **high-end-visual-design** — 教 AI 像高端代理一样设计：定义字体、间距、阴影与层次。
- **image-to-code** — 精英图片转代码技能：视觉重要任务先推理再生成。
- **imagegen-frontend-mobile** — 精英移动端 App 图像生成：高质量 app 原生屏幕概念。
- **imagegen-frontend-web** — 精英前端图像方向：生成转化友好的网站设计稿。
- **industrial-brutalist-ui** — 原始机械感界面：瑞士印刷排版 × 军事终端美学。
- **minimalist-ui** — 简洁编辑风界面：暖色单色、排版对比、平直曲线。
- **redesign-existing-projects** — 把既有网站/App 升级到高端品质：审计现状、定位问题。
- **stitch-design-taste** — 面向 Google Stitch 的语义设计系统，生成 agent 友好的 DESIGN.md。

### ip-as-logo 个人 IP Logo ★4.4k

**来源仓库**：[https://github.com/s1dashu/ip-as-logo-skill](https://github.com/s1dashu/ip-as-logo-skill)  

个人 IP 吉祥物 Logo：极简、圆润、轻新拟态。

- **ip-as-logo** — 生成极其简洁、可爱、拟人化的圆角方形角色图像（个人 IP 吉祥物 logo），轻微新拟态风格。

### frontend-slides 网页演示 ★28.2k

**来源仓库**：[https://github.com/zarazhangrui/frontend-slides](https://github.com/zarazhangrui/frontend-slides)  

前端幻灯片技能，构建精美网页演示。

- **frontend-slides** — 从零创建或从 PowerPoint 转换，生成动画丰富、令人惊艳的 HTML 演示文稿。

### guizang 横向翻页网页 PPT ★25.0k

**来源仓库**：[https://github.com/op7418/guizang-ppt-skill](https://github.com/op7418/guizang-ppt-skill)  

贵藏横向翻页网页 PPT：WebGL 背景、演讲者视图、数据大字报。

- **guizang-ppt-skill** — 生成横向翻页网页 PPT（单 HTML）：WebGL 背景、演讲者视图、观众屏同步、讲稿备注、数据大字报等模板。

### html-slides 网页幻灯片 ★75

**来源仓库**：[https://github.com/bluedusk/html-slides](https://github.com/bluedusk/html-slides)  

HTML 幻灯片与演讲者备注，支持多 Agent 环境。

- **html-slides** — 用 Claude/Codex/Copilot 的前端技能构建漂亮的 HTML 幻灯片与演讲者备注，可用 HTMLSlides App 演示。

[⬆ 返回目录](#toc)

<a id="06-security"></a>
## 安全逆向 · Security

> 逆向工程、授权渗透测试与安全研究。

### reverse-skill 安全逆向 ★29.7k

**来源仓库**：[https://github.com/zhaoxuya520/reverse-skill](https://github.com/zhaoxuya520/reverse-skill)  

安全逆向路由包：逆向、渗透、漏洞挖掘、取证、威胁狩猎。

- **api-security** — 授权的 REST/GraphQL/WebSocket/SOAP 接口安全评估。
- **apk-reverse** — CLI 环境 Android APK 逆向：解包、反编译、smali 修改、重打包与 Frida 动态 Hook。
- **attack-chain** — 授权多阶段攻击路径规划与编排。
- **binary-diff** — 跨版本符号迁移与二进制差分。
- **browser-automation** — 统一自动化入口：浏览器(Playwright)与 Windows 桌面自动化。
- **browser-extension-reverse** — Chrome/Firefox 扩展授权逆向工程。
- **case-review** — 审查一个 reverse-skill 案例包的 Scope 就绪度与证据链。
- **cloud-k8s** — 云、容器与 Kubernetes 安全评估。
- **code-audit** — 授权源码安全审查与 SAST 工作流（Semgrep/CodeQL 等）。
- **competition-ad-certificate-abuse** — CTF-sandbox 工作流下游子技能：AD CS 证书滥用 场景。
- **competition-agent-cloud** — CTF-sandbox 工作流下游子技能：AI-agent 云环境 场景。
- **competition-android-hooking** — CTF-sandbox 工作流下游子技能：Android 运行时 Hook 场景。
- **competition-browser-persistence** — CTF-sandbox 工作流下游子技能：浏览器持久化 场景。
- **competition-bundle-sourcemap-recovery** — CTF-sandbox 工作流下游子技能：源映射恢复 场景。
- **competition-cloud-metadata-path** — CTF-sandbox 工作流下游子技能：云元数据访问 场景。
- **competition-container-runtime** — CTF-sandbox 工作流下游子技能：容器运行时 场景。
- **competition-crypto-mobile** — CTF-sandbox 工作流下游子技能：加密/移动端 场景。
- **competition-custom-protocol-replay** — CTF-sandbox 工作流下游子技能：自定义协议重放 场景。
- **competition-dpapi-credential-chain** — CTF-sandbox 工作流下游子技能：DPAPI 凭证链 场景。
- **competition-file-parser-chain** — CTF-sandbox 工作流下游子技能：文件解析链 场景。
- **competition-firmware-layout** — CTF-sandbox 工作流下游子技能：固件布局 场景。
- **competition-forensic-timeline** — CTF-sandbox 工作流下游子技能：取证时间线 场景。
- **competition-graphql-rpc-drift** — CTF-sandbox 工作流下游子技能：GraphQL/RPC 漂移 场景。
- **competition-identity-windows** — CTF-sandbox 工作流下游子技能：Windows 身份 场景。
- **competition-ios-runtime** — CTF-sandbox 工作流下游子技能：iOS 运行时 场景。
- **competition-jwt-claim-confusion** — CTF-sandbox 工作流下游子技能：JWT/JWS 声明混淆 场景。
- **competition-k8s-control-plane** — CTF-sandbox 工作流下游子技能：Kubernetes 控制面 场景。
- **competition-kerberos-delegation** — CTF-sandbox 工作流下游子技能：Kerberos 委派 场景。
- **competition-kernel-container-escape** — CTF-sandbox 工作流下游子技能：内核/容器逃逸 场景。
- **competition-linux-credential-pivot** — CTF-sandbox 工作流下游子技能：Linux 凭证横向 场景。
- **competition-lsass-ticket-material** — CTF-sandbox 工作流下游子技能：LSASS 票据材料 场景。
- **competition-mailbox-abuse** — CTF-sandbox 工作流下游子技能：邮箱滥用 场景。
- **competition-malware-config** — CTF-sandbox 工作流下游子技能：恶意软件配置 场景。
- **competition-oauth-oidc-chain** — CTF-sandbox 工作流下游子技能：OAuth/OIDC 链 场景。
- **competition-pcap-protocol** — CTF-sandbox 工作流下游子技能：抓包协议 场景。
- **competition-prompt-injection** — CTF-sandbox 工作流下游子技能：prompt 注入 场景。
- **competition-queue-worker-drift** — CTF-sandbox 工作流下游子技能：队列/worker 漂移 场景。
- **competition-race-condition-state-drift** — CTF-sandbox 工作流下游子技能：竞态/状态漂移 场景。
- **competition-relay-coercion-chain** — CTF-sandbox 工作流下游子技能：强制认证中继链 场景。
- **competition-request-normalization-smuggling** — CTF-sandbox 工作流下游子技能：请求归一化走私 场景。
- **competition-reverse-pwn** — CTF-sandbox 工作流下游子技能：逆向利用 场景。
- **competition-runtime-routing** — CTF-sandbox 工作流下游子技能：路由绕过 场景。
- **competition-ssrf-metadata-pivot** — CTF-sandbox 工作流下游子技能：SSRF 元数据路径 场景。
- **competition-stego-media** — CTF-sandbox 工作流下游子技能：图片/音频隐写 场景。
- **competition-supply-chain** — CTF-sandbox 工作流下游子技能：CI/CD 供应链 场景。
- **competition-template-render-path** — CTF-sandbox 工作流下游子技能：SSR 模板渲染路径 场景。
- **competition-web-runtime** — CTF-sandbox 工作流下游子技能：CTF Web 运行时 场景。
- **competition-websocket-runtime** — CTF-sandbox 工作流下游子技能：WebSocket 运行时 场景。
- **competition-windows-pivot** — CTF-sandbox 工作流下游子技能：Windows 横向 场景。
- **competition-zip-archive** — CTF-sandbox 工作流下游子技能：ZIP/压缩包 场景。
- **ctf-sandbox** — CTF/AWD/靶场多类型编排的薄主入口。
- **ctf-sandbox-orchestrator** — CTF/AWD/靶场多类型编排的默认入口与主工作流。
- **database-security** — 数据库安全评估：PostgreSQL/MySQL/MSSQL/Mongo/Redis/memcached 等。
- **diagram-generator** — 从自然语言、笔记与代码生成、校验并渲染图表。
- **digital-forensics** — 数字取证：内存转储、磁盘时间线、PCAP 调查。
- **docs-generator** — 面向任务的技术文档（渐进式披露）。
- **dotnet-reverse** — .NET/C# 二进制逆向（CLR 托管程序、Sharp 工具）。
- **dsl-vm-reverse** — 逆向 JS 自定义 DSL/VM 解释器与非标准 WASM 类运行时。
- **edr-bypass-re** — 逆向 EDR/Defender/AV 实现 → 红队针对性绕过。
- **email-security** — 授权邮件安全审查：钓鱼分析、头认证、正文与链接检查。
- **firmware-pentest** — 固件/IoT 渗透链：逆向→提取→模拟→利用（OWASP FSTM）。
- **ghidra-reverse** — 用 Ghidra 做免费开源逆向（headless/GUI 反编译）。
- **go-rust-reverse** — 逆向剥离符号的 Go/Rust 二进制：运行时识别与函数重命名。
- **hardware-security** — 硬件与嵌入式接口安全研究：UART/JTAG 调试、芯片安全。
- **ida-reverse** — IDA Pro 逆向分析：二进制/PE/ELF/APK/DLL/SO 反编译与漏洞分析。
- **identity-federation** — 联邦身份系统评估：SAML/OIDC/OAuth2 联合。
- **js-reverse** — 配合 js-reverse-mcp 做前端 JS 逆向：签名定位、运行时采样与证据化输出。
- **llm-security** — LLM 应用与 AI Agent 安全评估（prompt injection 等）。
- **macos-reverse** — macOS 与 Mach-O 逆向：codesign、Obj-C/Swift 分析。
- **malware-analysis** — 疑似恶意软件分析（静态、动态与行为）。
- **mobile-reverse** — Android/iOS 应用逆向与安全测试。
- **ot-ics** — OT/ICS 安全评估：Purdue 分区、PLC/SCADA 暴露。
- **patch-diff-exploit** — N-day 补丁差分到利用：从补丁反推漏洞点、写 PoC。
- **pentest-tools** — 主动渗透测试工具链：信息收集、端口扫描、Web 渗透、SQL 注入等。
- **protocol-reverse** — 自定义二进制协议、Protobuf/gRPC、WebSocket 等的授权逆向。
- **pwn-chain** — 从逆向走到可用 Exploit 的全链路工程化方法。
- **radare2** — 用 radare2/r2 从命令行分析二进制。
- **radio-sdr** — 授权 RF/SDR 安全研究：信号识别、重放可行性与频谱分析。
- **reverse-engineering** — 通用反向工程技术：理解组件如何工作。
- **src-hunter** — 实战 SRC/众测/Bug bounty 漏洞挖掘工作流（5 阶段方法论）。
- **supply-chain-security** — 软件供应链安全：SBOM、SCA、CI/CD 管线。
- **thick-client** — 桌面胖客户端安全测试：本地存储、内存、网络与更新。
- **threat-hunting** — 蓝队威胁狩猎：Sigma/YARA 检测工程、SIEM 查询设计。
- **threat-intelligence** — 授权 OSINT 与网络威胁情报：IOC 富化、活动归因。
- **wifi-wireless** — 无线安全评估：Wi-Fi 抓包、WPA 握手分析。
- **windows-ad** — Active Directory 与 Windows 身份攻击：Kerberos、AD CS、委派。

[⬆ 返回目录](#toc)

<a id="07-seo"></a>
## SEO 优化

> 技术 SEO、内容优化与生成式引擎优化。

### claude-seo SEO 优化 ★15.4k

**来源仓库**：[https://github.com/AgriciDaniel/claude-seo](https://github.com/AgriciDaniel/claude-seo)  

通用 SEO：技术 SEO、E-E-A-T、Schema、GEO、本地 SEO。

- **seo** — 综合 SEO 分析：整站审计、单页优化、关键词研究与内容策略。
- **seo-audit** — 整站 SEO 审计，并行 subagent 爬取至多 500 页并检测各类问题。
- **seo-backlinks** — 反向链接分析：引荐域名、锚文本分布、毒性链接检测。
- **seo-cluster** — 基于 SERP 的语义主题聚类，用于内容架构规划与关键词分组。
- **seo-competitor-pages** — 生成 SEO 优化的竞品对比与替代页面（X vs Y 布局）。
- **seo-content** — 内容质量与 E-E-A-T 分析，含 AI 引用就绪度评估。
- **seo-content-brief** — 生成有竞争力的 SEO 内容简报：分段字数、竞品评分与引用建议。
- **seo-dataforseo** — 通过 DataForSEO MCP 服务获取实时 SEO 数据：SERP 分析与关键词研究。
- **seo-drift** — SEO 漂移监控：捕获关键要素基线、检测变更并追踪。
- **seo-ecommerce** — 电商 SEO：Google Shopping 可见度、亚马逊市场情报、价格与转化优化。
- **seo-flow** — FLOW 框架集成：证据驱动的 SEO（Find→Leverage→Optimize→Win）。
- **seo-geo** — 为 AI Overviews、ChatGPT 网页搜索、Perplexity 等做生成式引擎优化。
- **seo-google** — Google SEO API：Search Console、PageSpeed、站点地图等。
- **seo-hreflang** — Hreflang 与多语言 SEO 审计、校验与生成。
- **seo-image-gen** — SEO 素材的 AI 配图：OG 分享图、博客封面、schema 图片等。
- **seo-images** — 图片优化分析：alt 文本、文件大小、格式与性能。
- **seo-local** — 本地 SEO：Google 商家档案优化、NAP 一致性、外链与口碑。
- **seo-maps** — 地图情报：geo-grid 排名追踪、商家档案 API 审计。
- **seo-page** — 深度单页 SEO 分析：页面元素、内容质量与技术元数据。
- **seo-plan** — 新站或存量站的战略 SEO 规划：行业模板、竞品分析。
- **seo-programmatic** — 规模化程序化 SEO：从数据源批量生成页面的规划与分析。
- **seo-schema** — Schema.org 结构化数据检测、校验与生成（JSON-LD）。
- **seo-sitemap** — 分析既有 XML 站点地图或按行业模板生成新地图并校验。
- **seo-sxo** — 搜索体验优化：反向解读 Google SERP 以检测页面类型错配。
- **seo-technical** — 跨 9 类别的技术 SEO 审计：可抓取性、可索引性、安全、URL 结构等。

[⬆ 返回目录](#toc)

<a id="08-ip"></a>
## 个人 IP 打造

> 把 Agent 变成个人 IP 策略师，打造人设与内容。

### ip-strategist 个人 IP 策略师 ★150

**来源仓库**：[https://github.com/erduo1998-cell/ip-strategist](https://github.com/erduo1998-cell/ip-strategist)  

个人 IP 策略师：档案驱动的人设定位、内容支柱与脚本。

- **ip-strategist** — 档案驱动的个人 IP 打造陪跑教练：先建私人档案，再「诊-契-行-盘」闭环推进人设定位、内容支柱、找题判题改题与短视频脚本。

[⬆ 返回目录](#toc)

<a id="09-engineering"></a>
## 工程流程与元技能

> 任务流水线、测试驱动与拷问打磨的方法论技能。

### Matt Pocock 技能集 ★238.2k

**来源仓库**：[https://github.com/mattpocock/skills](https://github.com/mattpocock/skills)  

工程工作流：任务管线、测试驱动、代码审查、拷问打磨与规划。

- **ask-matt** — 不知道该用哪个技能时的路由器——问一句，它告诉你该走哪条技能路径（flow）。
- **claude-handoff** — 把当前对话移交给一个立即接手工作的全新后台 agent。
- **code-review** — 从固定基线（commit / branch / tag）出发，沿「规范符合度」与「需求符合度」两条轴并行审查代码变更。
- **codebase-design** — 深模块（deep module）设计的共享词汇表：改进模块接口、寻找深化机会、划定接缝位置。
- **diagnosing-bugs** — 疑难 bug 与性能回归的诊断闭环：症状→假设→二分定位→验证修复。
- **domain-modeling** — 构建并打磨项目的领域模型：讨论代码库术语、维护 CONTEXT.md 与 ADR。
- **git-guardrails-claude-code** — 配置 Claude Code hooks，拦截危险 git 操作（push、reset --hard、clean、branch -D 等）。
- **grill-me** — 一场毫不留情的访谈，把你的计划或设计磨利。
- **grill-with-docs** — 同样是无情拷问，但会同时沉淀 ADR 决策记录与术语表文档。
- **grilling** — 对计划、决策或想法穷追不舍地拷问，做压力测试。
- **handoff** — 把当前对话压缩成交接文档（handoff document），交给下一个 agent 无缝续办。
- **implement** — 依据一份 spec 或一组 tickets，实现一块具体的工作。
- **implement-spec** — 把一份规格说明（spec）忠实实现为代码。
- **improve-codebase-architecture** — 扫描代码库找出深化机会，产出可视化 HTML 报告，再逐项拷问确认是否采纳。
- **loop-me** — 就你想搭建的工作流规格，对「我」进行循环拷问，直到规格无懈可击。
- **migrate-to-shoehorn** — 把测试文件里的 as 类型断言迁移到 @total-typescript/shoehorn。
- **prototype** — 造一个一次性原型回答设计问题：验证状态模型是否成立、交互手感对不对。
- **research** — 针对问题调研高可信一手来源，并把结论沉淀为仓库内的 Markdown 研究笔记。
- **resolving-merge-conflicts** — 处理进行中的 git merge / rebase 冲突。
- **scaffold-exercises** — 创建可通过 lint 的课程练习目录结构：sections、problems、solutions、explainers。
- **setup-matt-pocock-skills** — 为本仓库配置工程技能集：issue tracker 选择、triage 标签体系与领域说明。
- **setup-pre-commit** — 配置 Husky pre-commit 钩子：lint-staged（Prettier）、类型检查与测试。
- **setup-ts-deep-modules** — 把 dependency-cruiser 接入 TypeScript 仓库，让每个 package 都成为深模块。
- **tdd** — 测试驱动开发（TDD）：红—绿—重构循环，先写测试再写实现。
- **teach** — 在当前工作区里教会用户一项新技能或概念，带学习记录与词汇表。
- **to-questionnaire** — 把你答不了的问题变成一份让别人填写的问卷（questionnaire）。
- **to-spec** — 把当前对话转成 spec 并发布到项目 issue tracker：不再追问，直接定稿。
- **to-tickets** — 把计划、spec 或当前对话拆解为一组 tracer-bullet 式 tickets，每张都声明验收口径。
- **triage** — 让 issue 与外部 PR 走过 triage 状态机：分类、核实、必要时拷问，最后写出 agent-ready brief。
- **wait-what** — 「停——刚才那条没说清。」重新陈述上一条消息，直到对方真的听懂。
- **wayfinder** — 把超出单次会话容量的巨大工程，规划成 issue tracker 上的共享决策 tickets 地图，逐张解决。
- **wizard** — 生成交互式 bash 向导，引导人逐步完成只有人能做的操作：配凭据、CI secrets、第三方后台设置。
- **writing-beats** — 写作 · exploit 阶段：把原料装配成一段节拍（beats）旅程，每个术语先夯实再使用。
- **writing-for-agents** — 面向 agent 的写作规范：如何编写 skills、AGENTS.md 与 CLAUDE.md。
- **writing-fragments** — 写作 · explore 阶段：开采原始片段，暂不做结构化。
- **writing-shape** — 写作 · exploit 阶段：把原料逐段塑造成文章。

### qiushi-skill 求是工作法 ★3.7k

**来源仓库**：[https://github.com/HughYau/qiushi-skill](https://github.com/HughYau/qiushi-skill)  

求是工作法：调查先行、抓主要矛盾、实践验证、持续推进。

- **arming-thought** — 在每次新顶层对话开始时调用，建立「实事求是」总原则并选用下游 skill。
- **concentrate-forces** — 多任务争夺资源时锁定主攻方向、停止分散用力。
- **contradiction-analysis** — 问题复杂、冲突因素多时厘清主要矛盾与优先级。
- **criticism-self-criticism** — 工作完成、收到批评或反复出错时做验收复盘与系统纠偏。
- **investigation-first** — 缺乏事实与一手信息时先调查再下判断（求是）。
- **mass-line** — 收集多方意见、整合成可执行方案并带回使用者验证。
- **overall-planning** — 多目标/多方利益冲突时做动态平衡与统筹。
- **practice-cognition** — 方案/假设经实践验证、试错迭代与复盘升级。
- **protracted-strategy** — 长期复杂、暂处劣势但不可放弃时的持久战策略。
- **spark-prairie-fire** — 资源极少、从零起步时的最小可行切入口与根据地建设。
- **workflows** — 需要多个思想武器协作时的标准化跨 skill 工作流组织。

[⬆ 返回目录](#toc)

<a id="10-notes"></a>
## 相关说明

- 数据来自对 26 个 GitHub 仓库的整理，共 467 个技能；stars 为整理时点数值。
- 本库按「用途」划分大类（官方出品 / 科研学术 / 公众号创作 / 知识管理 / 前端设计 / 安全逆向 / SEO / 个人 IP / 工程流程），每个来源仓库整簇归类，不拆散。
- 本库侧重「中文可读」：每条给出一句中文用途说明，英文原名保留便于检索上游。
- 欢迎补充新仓库：按上述收录标准，在对应大类追加簇并附来源仓库链接，发 PR。

[⬆ 返回目录](#toc)

<a id="11-related"></a>
## 相关项目

> 同类「Agent Skills 精选 / 合集」仓库与技能市场。本库的差异点：**中文可读** + **按用途整簇归类**，少而精、可快速上手，而非单纯堆数量。stars 为检索时点数值。

### 中文同类

- **[JackyST0/awesome-agent-skills](https://github.com/JackyST0/awesome-agent-skills)** — 中英双语精选合集，带网站版（jackyst0.github.io），覆盖 Cursor / Claude Code / Copilot 等平台。
- **[libukai/awesome-agent-skills](https://github.com/libukai/awesome-agent-skills)** — 中文偏「教学向」：快速入门、教程、资源与案例，辅助上手 Agent Skills。
- **[xstongxue/best-skills](https://github.com/xstongxue/best-skills)** — 中文通用高质量 skills 合集，可安装进 Cursor / Claude Code / Codex / OpenClaw 等。

### 英文同类

- **[VoltAgent/awesome-agent-skills](https://github.com/VoltAgent/awesome-agent-skills)**（约 33k★）— 目前该赛道体量最大的精选合集，1000+ 技能，兼容 Claude Code / Codex / Gemini CLI / Cursor。
- **[ComposioHQ/awesome-claude-skills](https://github.com/ComposioHQ/awesome-claude-skills)** — 公司运营的 Claude Skills 精选，按文档 / 开发 / 数据 / 营销等分类。
- **[awesome-skills.com](https://awesome-skills.com/)** — 网页形态合集，1030+ 技能带链接与描述。
- **[travisvn/awesome-claude-skills](https://github.com/travisvn/awesome-claude-skills)** · **[vivy-yi/awesome-skills](https://github.com/vivy-yi/awesome-skills)** · **[heilcheng/awesome-agent-skills](https://github.com/heilcheng/awesome-agent-skills)** · **[CommandCodeAI/agent-skills](https://github.com/commandcodeai/agent-skills)** — 社区维护的英文精选列表。

### 技能市场与官方

- **[SkillsMP（skillsmp.com/zh）](https://skillsmp.com/zh)** — 中文友好的技能商店，收录 3000+ 技能，主打安全审查，可搜索 / 安装。
- **[skills.sh](https://skills.sh)** · **[LobeHub](https://lobehub.com/skills)** · **[AugmentClaude](https://augmentclaude.com/)** · **[SkillsDirectory](https://www.skillsdirectory.com/)** · **[MCP Market](https://mcpmarket.com/)** · **[Agensi](https://www.agensi.io/)** — 各类 Agent Skills 市场，多数带安全扫描、安装与分发能力。
- **[anthropics/skills](https://github.com/anthropics/skills)** — Anthropic 官方 Agent Skills 仓库（见第 01 大类）；OpenAI Codex 生态技能亦是内容与权威标准来源。

[⬆ 返回目录](#toc)
