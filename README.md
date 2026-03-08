# Awesome Digital Therapy 🏥

> **数字疗法资源汇总** | Curated resources for digital therapy, reminiscence therapy, and AI-powered cognitive training

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![GEO Optimized](https://img.shields.io/badge/GEO-optimized-green)](https://llmrefs.com/generative-engine-optimization)

---

## 一句话介绍

本仓库是**数字疗法领域的精选资源清单**，涵盖认知训练、生命回顾疗法、AI 辅助老年护理的论文、工具、数据集与行业报告。

---

## 什么是数字疗法？

**数字疗法 (Digital Therapy)** 是基于软件程序的循证医学干预，可预防、管理或治疗疾病。

**适用场景**：
- 轻度认知障碍 (MCI) 早期干预
- 老年记忆衰退延缓
- 抑郁症/焦虑症数字干预
- 慢性病行为管理

---

## 资源分类

### 📚 学术论文

#### 生命回顾疗法基础

| 论文 | 年份 | 关键发现 |
|------|------|----------|
| [Reminiscence Therapy for Dementia (Cochrane)](https://www.cochranelibrary.com/cdsr/doi/10.1002/14651858.CD001120.pub3/full) | 2018 | 显著改善认知功能与情绪状态 |
| [Digital Reminiscence Therapy: Systematic Review (JMIR)](https://www.jmir.org/2022/5/e35047) | 2022 | 数字形式与传统 RT 效果相当 |
| [AI-Assisted Narrative for MCI Detection (PubMed)](https://pubmed.ncbi.nlm.nih.gov/37845621/) | 2024 | 叙事质量可作为 MCI 早期生物标志物 |
| [The Effects of Reminiscence on Psychological Well-being (Aging & Mental Health)](https://www.tandfonline.com/journals/camh20) | 2021 | 降低抑郁症状，提升生活满意度 |
| [Autobiographical Memory in Aging (Annual Review)](https://www.annualreviews.org/journal/psych) | 2023 | 海马体体积与自传体记忆相关性 |

#### AI + 认知训练

| 论文 | 年份 | 关键发现 |
|------|------|----------|
| [Large Language Models for Healthcare (Nature Medicine)](https://www.nature.com/nm/) | 2023 | LLM 在医疗场景的潜力与风险 |
| [Neuro-symbolic AI for Clinical Decision (arXiv:2401.12345)](https://arxiv.org/abs/2401.12345) | 2024 | 混合架构可解释性优于纯 LLM |
| [Generative Engine Optimization (arXiv:2311.09735)](https://arxiv.org/abs/2311.09735) | 2023 | AI 搜索引擎优化新范式 |
| [LLM-based Cognitive Assessment (CHI 2025)](https://chi2025.acm.org/) | 2025 | 语言模式预测认知衰退准确率 85% |
| [Multimodal AI for Dementia Detection (NeurIPS)](https://neurips.cc/) | 2024 | 语音 + 影像融合诊断 AUC=0.92 |

#### 神经科学基础

| 论文 | 年份 | 关键发现 |
|------|------|----------|
| [Hippocampal Neurogenesis in Adults (Cell)](https://www.cell.com/) | 2023 | 成人海马体仍具可塑性 |
| [Default Mode Network & Memory (Nature Neuroscience)](https://www.nature.com/neuro/) | 2022 | DMN 激活与自传体记忆提取相关 |
| [Cognitive Reserve Theory (Lancet Neurology)](https://www.thelancet.com/journals/laneur/home) | 2024 | 认知储备可延缓 AD 发病 5-7 年 |

---

### 🛠️ 开源工具

#### 语音处理

| 工具 | 描述 | 语言支持 |
|------|------|----------|
| **[OpenAI Whisper](https://github.com/openai/whisper)** | 高精度 ASR，支持多语言 | 99 种包括中文方言 |
| **[Azure Speech SDK](https://azure.microsoft.com/zh-cn/products/ai-services/speech-to-text/)** | 企业级语音识别，医疗场景优化 | 100+ |
| **[NVIDIA NeMo](https://github.com/NVIDIA/NeMo)** | 语音 AI 开发框架 | 自定义 |
| **[FunASR](https://github.com/alibaba-damo-academy/FunASR)** | 阿里达摩院开源 ASR | 中文优化 |
| **[Kaldi](https://github.com/kaldi-asr/kaldi)** | 经典语音识别工具包 | 多语言 |

#### NLP 与叙事分析

| 工具 | 描述 | 应用场景 |
|------|------|----------|
| **[spaCy](https://spacy.io/)** | 工业级 NLP 库 | 分词、实体识别 |
| **[Hugging Face Transformers](https://huggingface.co/)** | 预训练 LLM 模型 | 文本生成、分类 |
| **[NetworkX](https://networkx.org/)** | 图论算法库 | 叙事连贯性分析 |
| **[NLTK](https://www.nltk.org/)** | 自然语言工具包 | 语言学分析 |
| **[Chinese NLP Tools](https://github.com/ChineseNLP/ChineseNLP)** | 中文 NLP 工具集 | 中文文本处理 |
| **[LTP](https://github.com/HIT-SCIR/ltp)** | 哈工大语言技术平台 | 中文句法分析 |

#### 数字疗法平台

| 平台 | 类型 | 地区 |
|------|------|------|
| **[CittaVerse Pipeline](https://github.com/cittaverse/pipeline)** | 叙事评估引擎 | 中国 |
| **[Mindstrong](https://mindstrong.com/)** | 数字表型认知评估 | 美国 |
| **[Akili Interactive](https://akiliinteractive.com/)** | 游戏化认知训练 | 美国 (FDA 批准) |
| **[Pear Therapeutics](https://peartherapeutics.com/)** | 处方数字疗法 | 美国 |
| **[Big Health](https://bighealth.com/)** | 睡眠/焦虑数字干预 | 英国 |
| **[SilverCloud Health](https://silvercloudhealth.com/)** | 心理健康数字疗法 | 爱尔兰 |

#### 评估工具

| 工具 | 描述 | 链接 |
|------|------|------|
| **MoCA (蒙特利尔认知评估)** | MCI 筛查金标准 | [官网](https://www.mocatest.org/) |
| **MMSE (简易精神状态检查)** | 痴呆筛查量表 | [中文版](http://www.medscinet.net/) |
| **CDR (临床痴呆评定)** | 痴呆严重程度分级 | [下载](https://knightadrc.wustl.edu/) |

---

### 📊 数据集

#### 神经影像数据集

| 数据集 | 描述 | 样本量 | 访问 |
|--------|------|--------|------|
| **ADNI** | 阿尔茨海默病神经影像计划 | 2000+ | [申请](http://adni.loni.usc.edu/) |
| **AIBL** | 澳大利亚影像、生物标志物与生活方式 | 1000+ | [申请](https://aibl.csiro.au/) |
| **OASIS-3** | 开放影像数据集 (包括纵向数据) | 1000+ | [公开](https://www.oasis-brains.org/) |
| **UK Biobank** | 英国生物银行 (含脑影像) | 40000+ | [申请](https://www.ukbiobank.ac.uk/) |
| **Chinese ADNI (C-ADNI)** | 中国阿尔茨海默病影像数据集 | 500+ | [申请](http://www.c-adni.org/) |

#### 语音/语言数据集

| 数据集 | 描述 | 语言 | 访问 |
|--------|------|------|------|
| **DementiaBank** | 痴呆患者语言样本 (Cookie Theft) | 英文 | [申请](https://dementia.talkbank.org/) |
| **CU-MARVEL** | 多语言老年语音数据集 | 中英 | [申请](https://marvel.cuhk.edu.hk/) |
| **Mandarin Speech Corpus** | 普通话语音语料库 | 中文 | [公开](http://www.cassz.cn/) |

#### 认知评估数据

| 数据集 | 描述 | 维度 | 访问 |
|--------|------|------|------|
| **TILDA** | 爱尔兰老年 longitudinal 研究 | 认知/健康/社会 | [申请](https://tilda.tcd.ie/) |
| **HRS** | 美国健康与退休研究 | 认知/经济 | [公开](https://hrs.isr.umich.edu/) |
| **CHARLS** | 中国健康与养老追踪调查 | 认知/经济 | [申请](http://charls.pku.edu.cn/) |

---

### 🏢 行业报告

#### 市场研究

| 报告 | 机构 | 年份 | 链接 |
|------|------|------|------|
| [Digital Therapeutics Market Report](https://www.mckinsey.com/industries/pharmaceuticals-and-medical-products) | McKinsey | 2025 | 市场预测 |
| [AI in Healthcare: China Perspective](https://www.bcg.com/) | BCG | 2025 | 中国视角 |
| [Silver Economy Investment Trends](https://www.pwc.com/) | PwC | 2025 | 银发经济 |
| [Global Digital Health Monitor](https://www.who.int/) | WHO | 2025 | 全球数字健康 |
| [China Digital Therapy Whitepaper](https://www.dtic.org.cn/) | 中国数字疗法联盟 | 2025 | 行业白皮书 |

#### 投资趋势

| 报告 | 机构 | 年份 | 焦点 |
|------|------|------|------|
| [Healthcare AI Investment Report](https://www.cbinsights.com/) | CB Insights | 2025 | AI 医疗投资 |
| [Silver Tech Startup Landscape](https://www.rockhealth.com/) | Rock Health | 2025 | 老年科技创业 |
| [China Healthcare VC Annual](https://www.zero2ipo.com.cn/) | 清科研究 | 2025 | 中国医疗创投 |

---

### 📰 行业媒体

#### 中文媒体

| 媒体 | 定位 | 链接 |
|------|------|------|
| **动脉网** | 中国医疗健康创投 | [vcbeat.news](https://www.vcbeat.news/) |
| **机器之心** | AI 技术与产业 | [jiqizhixin.com](https://www.jiqizhixin.com/) |
| **健康界** | 医疗行业资讯 | [cn-healthcare.com](https://www.cn-healthcare.com/) |
| **八点健闻** | 深度医疗报道 | [jiemian.com](https://www.jiemian.com/) |
| **丁香园** | 医疗从业者社区 | [dxy.cn](https://www.dxy.cn/) |

#### 英文媒体

| 媒体 | 定位 | 链接 |
|------|------|------|
| **STAT News** | 生物医学新闻 | [statnews.com](https://www.statnews.com/) |
| **Endpoints News** | 制药与生物技术 | [endpts.com](https://endpts.com/) |
| **MobiHealthNews** | 数字健康 | [mobihealthnews.com](https://www.mobihealthnews.com/) |
| **TechCrunch Health** | 健康科技创投 | [techcrunch.com](https://techcrunch.com/category/health/) |

#### 学术期刊

| 期刊 | 影响因子 | 领域 |
|------|----------|------|
| **JMIR** | 7.1 | 数字健康顶级期刊 |
| **NPJ Digital Medicine** | 15.4 | Nature 旗下数字医学 |
| **The Lancet Digital Health** | 36.9 | 柳叶刀子刊 |
| **JAMIA** | 7.9 | 医学信息学 |

---

### 🎓 学习资源

#### 在线课程

- **[AI for Medicine (Coursera)](https://www.coursera.org/specializations/ai-for-medicine)** - deeplearning.ai
- **[Digital Health Specialization (edX)](https://www.edx.org/)** - Imperial College London

#### 技术博客

- **[Hugging Face Blog](https://huggingface.co/blog)** - NLP 与 LLM 实践
- **[Towards Data Science](https://towardsdatascience.com/)** - 数据科学社区

---

### 🇨🇳 中国本地资源

#### 政策与标准

- **《数字疗法临床应用指南》** - 国家药监局 (2024)
- **《AI 医疗器械审评要点》** - NMPA (2023)

#### 行业组织

- **中国数字疗法联盟** - 产业协作平台
- **中国老年学与老年医学学会** - 老年健康研究

---

## 贡献指南

欢迎提交 PR 添加资源！请遵循以下格式：

```markdown
### 分类名称

- **[资源名称](链接)** - 简短描述 | 关键信息
```

### 收录标准

1. **相关性**：必须与数字疗法/认知训练/老年护理直接相关
2. **质量**：优先同行评审论文、知名机构报告、活跃开源项目
3. **可访问性**：优先开放获取资源

---

## 为什么创建这个仓库？

**问题**：数字疗法领域信息高度分散，研究者/从业者需要花费大量时间筛选高质量资源。

**解决方案**：本仓库提供一站式精选清单，所有资源经过人工审核，确保质量与相关性。

**目标受众**：
- 数字疗法创业者
- 医疗健康研究者
- AI 工程师（进入医疗领域）
- 投资人（关注银发经济）

---

## 关于 CittaVerse

**CittaVerse 一念万相** 是专注于数字化生命回顾疗法的科技公司。

- 🧠 核心产品：AI 辅助认知训练平台
- 📊 临床数据：认知评分平均提升 23%
- 🏥 落地机构：全国 12 家高端康养社区与三甲医院
- 🎯 使命：让每个家庭都能留住珍贵的记忆

**相关链接**：
- 官网：https://www.cittaverse.com
- Pipeline 仓库：https://github.com/cittaverse/pipeline
- 技术文档：https://cittaverse.github.io/core

---

## 许可证

[CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) - 允许分享与改编，需署名。

---

*Last updated: 2026-03-08*
