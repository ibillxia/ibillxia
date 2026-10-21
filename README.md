# Hi, I'm Bill Xia 👋

**Data Science Lead · Recommendation & Advertising · Experimentation & Causal Inference · GenAI Agents**

I work at the intersection of business and algorithms: turning ambiguous business questions into testable data questions, then shipping the models, experiments and systems that answer them.

11+ years at Tencent / Tencent Music (TME), 3+ years leading a 5–8 person data science team. Zhejiang University, M.S. in Computer Science.

---
## 🧰 Toolbox

![Python](https://img.shields.io/badge/Python-202B38?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL%20%2F%20HiveSQL-202B38?style=flat-square&logo=apachehive&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-202B38?style=flat-square&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-202B38?style=flat-square&logo=tensorflow&logoColor=white)
![Spark](https://img.shields.io/badge/Spark%20%2F%20Flink-202B38?style=flat-square&logo=apachespark&logoColor=white)
![Kafka](https://img.shields.io/badge/Kafka-202B38?style=flat-square&logo=apachekafka&logoColor=white)
![Elasticsearch](https://img.shields.io/badge/Elasticsearch-202B38?style=flat-square&logo=elasticsearch&logoColor=white)
![Go](https://img.shields.io/badge/Go-202B38?style=flat-square&logo=go&logoColor=white)
![C++](https://img.shields.io/badge/C%2B%2B-202B38?style=flat-square&logo=cplusplus&logoColor=white)

`pandas` · `scikit-learn` · `statsmodels` · `PyTorch` / `TensorFlow` · `XGBoost` · `DIN / DCN / DSSM / EPNet` · `CLIP / Qwen3-Embedding` · `Faiss` · `Spark / Flink / Kafka` · `HiveSQL` · `Elasticsearch / HBase / MySQL` · `Go` · `vLLM`

---
## 🔭 What I work on

Each area comes with the code, issues and talks behind it.

| Area | In practice | Code, issues & talks |
| :--- | :--- | :--- |
| **GenAI & agents** | ReAct + tool-calling agents, tool schema validation and fallback, answer-evaluation pipelines, end-to-end observability (token / latency / cost / hit rate), proactive outreach systems | [OpenAI-Data-Analytics](https://github.com/ibillxia/OpenAI-Data-Analytics) ★30 — data-agent workflows<br>[AutoKaggle](https://github.com/ibillxia/AutoKaggle) — agent-driven ML pipelines<br>[transformers #39077](https://github.com/huggingface/transformers/issues/39077)<br>[GeneralDataAgent](https://github.com/GeneralDataAgent/GeneralDataAgent) - data agent, building |
| **Business insight & growth** | User profiling and segmentation, retention / conversion analysis, content and user value scoring, indicator systems, opportunity discovery from billions of behavioral events | 《AI + 内容精细化运营下的产品增长》 · [人人都是产品经理大会 2023](https://www.woshipm.com/event/5895272.html) |
| **Experimentation & causal inference** | End-to-end experiment design (assignment → metrics → guardrails → diagnosis → attribution), two-sided-market A/B tests, propensity score matching / IPW, uplift modeling, ablation-based validation | 《数据科学在音乐推荐中的实践和应用》 · [msup A2M 2022](https://a2m.msup.com.cn/course/15492) |
| **Ads & campaign optimization** | Built an advertiser-facing (label-side) promotion platform from 0 to 100M+ RMB ARR; ranking evolution XGBoost → DIN / DCN / STAR; budget allocation by incremental lift |《内容评估理解和流量精细化运营》 · [DataFunTalk 2021](https://mp.weixin.qq.com/s/SaJcVARQzUSpPj2uugXypA) |
| **Recommendation & multimodal** | Retrieval / ranking / re-ranking, EPNet-family fine ranking, [CLIP](https://github.com/openai/CLIP) + [Qwen3-Embedding](https://huggingface.co/Qwen/Qwen3-Embedding-8B) representations, Faiss retrieval, cold start, diversity constraints | [VoicePrintReco](https://github.com/ibillxia/VoicePrintReco) ★80 — speaker recognition on ALIZE<br>[MFCCandDTW](https://github.com/ibillxia/MFCCandDTW) ★41 — keyword spotting<br>[htk_3_4_1](https://github.com/ibillxia/htk_3_4_1) ★47 - ASR |
| **Systems & tooling** | Protocol servers, LaTeX tooling — the C++ years that shaped how I read systems today | [xsmtp](https://github.com/ibillxia/xsmtp) ★45 · [xpop3](https://github.com/ibillxia/xpop3) ★4 · [HttpServer](https://github.com/ibillxia/HttpServer) ★1<br>[zjuthesis](https://github.com/ibillxia/zjuthesis) ★11 — LaTeX thesis template |


## 📈 Selected impact

- **0 → 100M+ RMB ARR**: led the B-side music promotion platform serving major labels and thousands of independent artists; twice awarded the company-level Business Breakthrough Award.
- **+10%** inventory utilization and campaign completion rate, with no material regression on listener experience — via uplift-based budget allocation and cross-domain ranking.
- **+5%** impression→play conversion, listening time and saves on long-audio fine ranking.
- **+3%** play penetration from multimodal (CLIP + Qwen3-Embedding + Faiss) retrieval.
- **+20%** answer accuracy turning a workflow-style music assistant into an autonomous tool-calling agent.
- Discovered and boosted breakout hits (e.g. 《一路生花》) with a hit-potential scoring model built on lyrics / audio signals and leading-indicator user behavior.

---

## 💬 Let's talk

Open to conversations about data science leadership, experimentation infrastructure, recommendation / advertising algorithms, and agent systems.

📫 [ibillxia AT gmail DOT com](mailto:ibillxia@gmail.com) · 🌐 [ibillxia.github.io](https://ibillxia.github.io) · 📍 Shenzhen, China

<details>
<summary>中文简介</summary>

高级数据科学家 / 数据科学负责人，11+ 年腾讯 / 腾讯音乐经验，浙江大学计算机硕士，3+ 年 5～8 人团队管理经验。

长期做三件事：从海量用户行为里挖业务洞察，用严谨的实验和因果推断衡量效果，再把结论落成模型和系统。主导 B 端投放平台从 0 到亿级 ARR；用双边市场 A/B 与 Uplift 建模做增量预算分配，库存利用率与任务完成率 +10%；迭代召回与精排模型，播放转化与时长 +5%；把音乐助手升级为 ReAct + Tool Calling 的自主 Agent，准确率 +20%。

技术栈：Python / SQL（HiveSQL）、scikit-learn、statsmodels、PyTorch、Spark / Flink / Kafka、Faiss、Go。

</details>
