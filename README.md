<div align="center">

<img src="assets/terminal.svg" alt="Rocklyn — AI, ML &amp; Cloud Engineer · Full-Stack Developer" width="100%"/>

<img src="assets/roles.svg" alt="Open to: AI Engineer, ML Engineer, LLM / GenAI Engineer, MLOps Engineer, Cloud &amp; Platform Engineer, Full-Stack Developer" width="100%"/>

<br/>

<a href="#-projects"><img src="https://img.shields.io/badge/projects-23_shipped-2ea44f?style=for-the-badge&logo=github&logoColor=white" alt="23 projects shipped"/></a>
<a href="#-how-i-build"><img src="https://img.shields.io/badge/CI-green_on_every_repo-2ea44f?style=for-the-badge&logo=githubactions&logoColor=white" alt="CI green on every repo"/></a>
<a href="#-education"><img src="https://img.shields.io/badge/M.S._CS-AI_concentration-1f6feb?style=for-the-badge&logo=academia&logoColor=white" alt="M.S. Computer Science, AI concentration"/></a>
<a href="#-roles-im-open-to"><img src="https://img.shields.io/badge/status-open_to_opportunities-8957e5?style=for-the-badge" alt="Open to opportunities"/></a>
<a href="https://www.linkedin.com/in/israel-rocklyn-789884140/"><img src="https://img.shields.io/badge/LinkedIn-connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="Connect on LinkedIn"/></a>

<br/><br/>

<img src="assets/stats.svg" alt="Highlights: 23 projects shipped, 92% grounded answer accuracy, 0 prompt-injection data changes, 32 infrastructure tests" width="100%"/>

<p align="center">
<a href="#-featured-project">Featured</a> ·
<a href="#-how-i-build-systems">Architecture</a> ·
<a href="#-projects">Projects</a> ·
<a href="#-roles-im-open-to">Roles</a> ·
<a href="#-stack">Stack</a> ·
<a href="#-education">Education</a> ·
<a href="#-digital-marketing--wordpress-toolkit">Marketing &amp; WordPress</a> ·
<a href="#-lets-build-something">Contact</a>
</p>

</div>

---

> [!TIP]
> **Recruiter summary (20 seconds)**
> - **Who:** AI, ML & Cloud Engineer and Full-Stack Developer, who also builds WordPress sites and runs digital marketing.
> - **Education:** M.S. Computer Science (concentration in Artificial Intelligence) · B.Sc. Information Systems.
> - **Proof:** 23 production-grade projects with tests, CI and **measured results**, from RAG and LLM agents to ML models and an AWS landing zone.
> - **Strengths:** shipping end to end (data → model → API → UI → infrastructure), honest evaluation, and security by default.
> - **Status:** available for hire, based in the United States. Start with the [featured project](#-featured-project).

### ⚡ Currently

- ✅ **Just shipped** [`distributed-ai-inference`](https://github.com/codeROCK-IZZY/distributed-ai-inference): a Go inference gateway with admission control, tenant isolation and failover on Kubernetes
- ✅ **Also new** [`aws-mlops-platform`](https://github.com/codeROCK-IZZY/aws-mlops-platform): promotion gates, drift-triggered retraining and SageMaker canary deploys
- 💬 **Ask me about** RAG that cites its sources, guarding LLM agents with human approval, telling real model drift from noise, and testing infrastructure without an AWS account

---

```python
class Rocklyn(AIEngineer, MLEngineer, CloudEngineer, FullStackDeveloper):
    """I build AI products and the cloud platforms they run on: end to end, tested, documented."""

    roles     = ["AI Engineer", "ML Engineer", "LLM / GenAI Engineer", "MLOps Engineer",
                 "Cloud & Platform Engineer", "Full-Stack Developer"]
    languages = ["Python", "TypeScript", "SQL", "HCL", "PHP"]
    education = {"M.S. Computer Science": "concentration in Artificial Intelligence",
                 "B.Sc. Information Systems": "technology in service of the business"}

    def builds(self):
        return {
            "ai":        ["grounded RAG with citations", "LLM agents with human approval",
                          "speech + vision + OCR pipelines", "classical ML with explainability"],
            "backend":   ["FastAPI services", "PostgreSQL (pgvector, job queues)", "Kafka streaming"],
            "frontend":  ["React + TypeScript dashboards"],
            "cloud":     ["AWS landing zones", "ECS / RDS / EFS", "Terraform with tests"],
            "web":       ["WordPress (Elementor, Divi, ACF)", "WooCommerce and Shopify stores"],
            "growth":    ["SEO", "GA4 + Tag Manager analytics", "Google and Meta Ads", "email and CRM"],
        }

    def principles(self):
        return [
            "Measure it: AI features ship with an evaluation, not a demo.",
            "Say \"I don't know\": answers cite their source or decline.",
            "Secure by default: least privilege, no long-lived keys, audit trails.",
            "Write it down: design docs, runbooks and known limitations in every repo.",
        ]
```

## ⭐ Featured project

<table>
<tr>
<td width="55%" valign="top">
<a href="https://github.com/codeROCK-IZZY/multimodal-ai-assistant"><img src="https://raw.githubusercontent.com/codeROCK-IZZY/multimodal-ai-assistant/main/docs/images/chat.png" alt="Multimodal AI Assistant: answers with citations" width="100%"/></a>
</td>
<td width="45%" valign="top">

### [Multimodal AI Assistant](https://github.com/codeROCK-IZZY/multimodal-ai-assistant)

Ask about a **receipt photo, a scanned PDF or a voice memo** by typing or speaking. Every answer quotes
its source with the **page, line or timestamp**. When the files don't contain the answer, it says so.

- 🎙️ Whisper speech-to-text and Piper voice replies, **all on CPU**
- 🔎 Two-stage retrieval: embeddings, then a **cross-encoder** that decides answerability
- 🛡️ Tools behind a permission gate that **prompt injection can't bypass**
- 🧪 Evaluation suite enforced in CI: OCR, speech, Q&A, tools, injection

[**See the code →**](https://github.com/codeROCK-IZZY/multimodal-ai-assistant)

</td>
</tr>
</table>

<p align="center">
<a href="https://github.com/codeROCK-IZZY/multimodal-ai-assistant"><img src="https://raw.githubusercontent.com/codeROCK-IZZY/multimodal-ai-assistant/main/docs/images/voice.png" alt="Voice memo answered with a timestamp citation" width="32%"/></a>
<a href="https://github.com/codeROCK-IZZY/autonomous-business-platform"><img src="https://raw.githubusercontent.com/codeROCK-IZZY/autonomous-business-platform/main/docs/images/run.png" alt="AI agent run paused for human approval" width="32%"/></a>
<a href="https://github.com/codeROCK-IZZY/ai-predictive-maintenance"><img src="https://raw.githubusercontent.com/codeROCK-IZZY/ai-predictive-maintenance/main/docs/screenshots/dashboard.png" alt="Predictive maintenance fleet dashboard" width="32%"/></a>
</p>

## 🏗️ How I build systems

<img src="assets/architecture.svg" alt="Data in → processing → retrieval and models → guardrails → API → product, with CI and AWS infrastructure-as-code underneath" width="100%"/>

## 🚀 Projects

<table>
<tr>
<td width="50%" valign="top">

### 🔁 [AWS MLOps Platform](https://github.com/codeROCK-IZZY/aws-mlops-platform)
Keeps a production model healthy **after** it ships: data contracts, MLflow registry, **promotion gates** against the champion, drift and performance monitoring that **retrains by itself**, and SageMaker **canary deploys with auto-rollback**.

📊 Every drift detected **in its first month** · **0/12** false alarms · PR-AUC **0.64 vs 0.58** unmanaged

`MLflow` `SageMaker` `XGBoost` `Terraform` `FastAPI` `React`

</td>
<td width="50%" valign="top">

### 🗣️ [Multimodal AI Assistant](https://github.com/codeROCK-IZZY/multimodal-ai-assistant)
Talk or type, attach photos, PDFs and voice notes. Answers cite the **page, line or timestamp**, decline when the files don't say, and run tools under permissions that **prompt injection can't bypass**.

📊 **92%** grounded-answer accuracy · **4%** speech WER · **0** prompt-injection data changes

`faster-whisper` `Piper TTS` `RapidOCR` `cross-encoder` `FastAPI` `React`

</td>
</tr>
<tr>
<td valign="top">

### ☁️ [Enterprise AWS Cloud Platform](https://github.com/codeROCK-IZZY/enterprise-aws-cloud-platform)
A Terraform **landing zone**: Organizations with guardrail SCPs, tamper-resistant org-wide logging, GuardDuty and Security Hub, and a Transit Gateway network with prod/non-prod isolation. **Tested without an AWS account**.

📊 **32** Terraform tests on a mocked provider · **0** Checkov failures · AWS quotas checked before plan

`Terraform` `AWS Organizations` `Transit Gateway` `IPAM` `Checkov`

</td>
<td valign="top">

### 🤖 [Autonomous Business Operations](https://github.com/codeROCK-IZZY/autonomous-business-platform)
AI agents that handle refunds, supplier invoices and purchase requests, with **human approval** for risky actions, idempotent tools, retries and a **hash-chained audit trail**.

📊 **96.9%** correct outcomes on 129 labelled cases · **100%** approval precision and recall

`LangGraph` `Claude API` `PostgreSQL` `FastAPI` `React`

</td>
</tr>
<tr>
<td valign="top">

### 💳 [Fraud Detection Engine](https://github.com/codeROCK-IZZY/fraud-detection-engine)
Real-time fraud scoring on a **Kafka** transaction stream, with explainable model decisions and an analyst case workflow.

📊 Catches **93%** of fraud dollars at ~31 alerts/day · **96%** precision in the critical band

`Kafka` `XGBoost` `SHAP` `FastAPI` `React`

</td>
<td valign="top">

### 📄 [Intelligent Document AI](https://github.com/codeROCK-IZZY/intelligent-document-ai)
Turns PDFs, Word files and scans into searchable, structured data, with **grounded Q&A** that refuses to answer without a citation.

📊 Retrieval recall@5 **1.0** · field extraction **100%** · OCR error rate **1.6%**

`OCR` `pgvector` `embeddings` `Claude citations` `FastAPI`

</td>
</tr>
<tr>
<td valign="top">

### 🏭 [AI Predictive Maintenance](https://github.com/codeROCK-IZZY/ai-predictive-maintenance)
Predicts industrial equipment failures days ahead from sensor data, explains each prediction, and tracks the fleet on a dashboard.

📊 Flagged **34 of 35** held-out failures, **6.6 days** ahead on average · precision **0.83**

`scikit-learn` `XGBoost` `SHAP` `FastAPI` `React`

</td>
<td valign="top">

### 🔎 [AI Research & Knowledge Engine](https://github.com/codeROCK-IZZY/ai-research-engine)
Team knowledge bases built from files and the web, with hybrid search, re-ranking and cited answers.

📊 Citation precision **99.3%** · **100%** correct "not found" · MRR **1.0** with re-ranking

`pgvector` `ONNX re-ranker` `hybrid search` `FastAPI`

</td>
</tr>
<tr>
<td valign="top">

### 🧠 [AI Developer Intelligence](https://github.com/codeROCK-IZZY/ai-developer-intelligence)
Understands any codebase: parses five languages, maps dependencies, flags risks and answers questions about the code.

📊 **100%** precision and recall on 21 planted findings · semantic search recall@5 **95%**

`tree-sitter` `PageRank` `MinHash` `pgvector` `FastAPI`

</td>
<td valign="top">

### ⚡ [Distributed AI Inference](https://github.com/codeROCK-IZZY/distributed-ai-inference)
Model serving that **stays predictable under overload**: a Go gateway with per-tenant quotas, **admission control** (Little's law), deadlines, fan-out and failover, in front of batching ONNX workers on **Kubernetes**.

📊 Overload: **38.6 vs 0.05** req/s served · noisy neighbour: **98.7% vs 23.8%** · replica killed: **0** errors

`Go` `Kubernetes` `KEDA` `ONNX Runtime` `Prometheus`

</td>
</tr>
<tr>
<td valign="top">

### ⚡ [AWS Serverless Event Platform](https://github.com/codeROCK-IZZY/aws-serverless-event-platform)
Event-driven order processing with **exactly-once effects under at-least-once delivery**: an idempotent API, a transactional outbox, and a Step Functions saga that compensates. A fault-injection evaluation removes each mechanism to **measure what it prevents**.

📊 **0** invariant violations under **566** injected faults · **68** double charges prevented · **$130** per million orders

`Lambda` `Step Functions` `DynamoDB` `EventBridge` `SQS` `Terraform`

</td>
<td valign="top">

### 🛡️ [AWS Security Guardrails](https://github.com/codeROCK-IZZY/aws-security-guardrails)
Detect AWS misconfigurations **as they happen** (CloudTrail → EventBridge), fix the safe ones behind exemptions, a re-check, a **circuit breaker** and an exact **rollback**, and find **IAM privilege-escalation paths**, not just wildcards.

📊 **100%** precision/recall on 446 labelled findings (string matching: **19.5%**) · **0** unintended changes in 237 fixes

`Python` `Lambda` `EventBridge` `Security Hub` `IAM` `Terraform`

</td>
</tr>
<tr>
<td valign="top">

### 💰 [AWS FinOps Optimizer](https://github.com/codeROCK-IZZY/aws-finops-optimizer)
Cost recommendations you can act on, from **CUR 2.0**: waste with evidence, rightsizing on **peaks not averages**, the **provably optimal Savings Plan**, backtested forecasts and anomalies that respect the weekly cycle.

📊 **31.8%** of a $115k/month run rate identified · **0** unsafe downsizes (average-CPU rule: **77**) · **0** false anomaly alarms (vs **33**)

`Python` `DuckDB` `Athena` `CloudWatch` `AWS Budgets` `Terraform`

</td>
<td valign="top">

### 🏞️ [AWS Data Lakehouse](https://github.com/codeROCK-IZZY/aws-data-lakehouse)
Bronze/silver/gold that gets the numbers right when the feed does not: **data contracts** with quarantine, **idempotent MERGE**, late data, schema evolution, and snapshots with **time travel** and lineage.

📊 **$0.00** revenue error on $19.1M (naive append: **$2.24M**) · **942/942** bad rows quarantined · **0** snapshots on replay

`Python` `DuckDB` `Parquet` `S3` `Glue` `Athena` `Terraform`

</td>
</tr>
<tr>
<td valign="top">

### 🌍 [AWS Resilience Lab](https://github.com/codeROCK-IZZY/aws-resilience-lab)
Multi-region **disaster recovery measured**: the four AWS DR strategies compared on RTO, RPO and cost, and a **guarded failover controller** (quorum, error-rate alarm, hysteresis, fencing) against a naive one.

📊 **3.4 min** RTO p95 active-active (backup and restore: **105 min**) · **0** split-brain writes (naive: **19,082**) · **0/20** false failovers

`Python` `NumPy` `Route 53` `DynamoDB` `S3 CRR` `AWS FIS` `Terraform`

</td>
<td valign="top">

### 🛡️ [LLM Guardrails Gateway](https://github.com/codeROCK-IZZY/llm-guardrails-gateway)
A security gateway in front of any LLM: **prompt-injection detection** (including hidden in documents and obfuscated), **PII redaction and restoration**, output checks for leaks and phishing links, rate limits and budgets.

📊 **0%** attack success (no gateway: **100%**, keywords: **91%**) · **90%** of hand-written attacks caught · **3.1 ms** p95

`Python` `scikit-learn` `FastAPI` `Docker` `Claude API`

</td>
</tr>
<tr>
<td valign="top">

### 📏 [LLM Evaluation Platform](https://github.com/codeROCK-IZZY/llm-evaluation-platform)
Evaluation that holds up: judges **calibrated against human labels** (kappa), **debiased pairwise judging**, paired tests with Holm correction, and a **slice-aware release gate** with measured false alarms and power.

📊 kappa **0.91** vs humans (uncalibrated **0.51**) · **96%** of slice regressions blocked at **2.5%** false alarms · overall-mean gate: **1.5%**

`Python` `NumPy` `SciPy` `Statistics`

</td>
<td valign="top">

### 🎯 [Recommender System](https://github.com/codeROCK-IZZY/recommender-system)
Recommendations measured honestly: **EASE, implicit ALS, BPR and item-kNN** against popularity on a **temporal split**, tuned on validation, a **cold-start hybrid**, and a serving API.

📊 **+29%** NDCG over popularity (CI +0.034 to +0.043) · cold-start NDCG **2.8x** · a random split flatters by **65%**

`Python` `NumPy` `SciPy` `FastAPI`

</td>
</tr>
<tr>
<td valign="top">

### 📈 [Demand Forecasting](https://github.com/codeROCK-IZZY/demand-forecasting)
Hierarchical, probabilistic forecasting: a **global quantile GBM**, **conformal intervals**, bottom-up / WLS / **MinT reconciliation**, a rolling backtest, and **costed stock decisions**.

📊 **36%** less error than seasonal naive · coverage **72% → 81.8%** for an 80% interval · stock cost **−51%**

`Python` `scikit-learn` `NumPy`

</td>
<td valign="top">

### 🧬 [Entity Resolution](https://github.com/codeROCK-IZZY/entity-resolution)
Which records are the same person: **multi-key blocking**, a **learned matcher** with nickname- and typo-aware features, and **average-linkage clustering** that won't chain look-alikes together.

📊 F1 **0.986** on unseen people (rules **0.930**) · **4.9x** fewer errors · twins merged **1.3%** (connected components: **33%**)

`Python` `scikit-learn` `NumPy`

</td>
</tr>
<tr>
<td valign="top">

### 🧪 [Experimentation Platform](https://github.com/codeROCK-IZZY/experimentation-platform)
A/B tests that keep their promises: **CUPED**, an **always-valid sequential test** for teams that peek, **SRM checks**, the **delta method** and **FDR control**, all measured on simulated experiments.

📊 peeking: **26.6%** false positives → **0.7%** · CUPED **−22%** variance · slicing false finds **36% → 4.6%**

`Python` `NumPy` `SciPy`

</td>
<td valign="top">

### 🗄️ [Feature Store](https://github.com/codeROCK-IZZY/feature-store)
Training sets that see what serving sees: **point-in-time joins** as known at each moment, an **online store that matches offline exactly**, and **skew detection**, with the leakage it prevents measured.

📊 **0** of 44,000 rows differ from serving · label-date leak: AUC **1.00 offline → 0.71** in production · pence bug caught on **4/4** amount features

`Python` `NumPy` `scikit-learn`

</td>
</tr>
<tr>
<td valign="top">

### 🔍 [Visual Anomaly Detection](https://github.com/codeROCK-IZZY/visual-anomaly-detection)
Unsupervised defect detection on CPU: a **PatchCore-style patch memory** with a **greedy coreset**, trained on good parts only, against pixel statistics and PCA, with **image and pixel AUROC** per defect.

📊 AUROC **0.974** (pixel stats **0.847**, PCA **0.764**) · **77%** of defects caught at ~4% false alarms · **43 ms** per image

`Python` `NumPy` `SciPy` `scikit-learn`

</td>
<td valign="top">

</td>
</tr>
</table>


## 🎯 Roles I'm open to

<p align="center">
<img src="https://img.shields.io/badge/AI_Engineer-8957e5?style=for-the-badge&logo=openaigym&logoColor=white" alt="AI Engineer"/>
<img src="https://img.shields.io/badge/Machine_Learning_Engineer-6e40c9?style=for-the-badge&logo=scikitlearn&logoColor=white" alt="Machine Learning Engineer"/>
<img src="https://img.shields.io/badge/LLM_%2F_GenAI_Engineer-a371f7?style=for-the-badge&logo=anthropic&logoColor=white" alt="LLM / GenAI Engineer"/>
<img src="https://img.shields.io/badge/MLOps_Engineer-1f6feb?style=for-the-badge&logo=mlflow&logoColor=white" alt="MLOps Engineer"/>
<img src="https://img.shields.io/badge/AI_Solutions_Engineer-388bfd?style=for-the-badge&logo=googlecloud&logoColor=white" alt="AI Solutions Engineer"/>
<img src="https://img.shields.io/badge/Cloud_%26_Platform_Engineer-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white" alt="Cloud &amp; Platform Engineer"/>
<img src="https://img.shields.io/badge/Full--Stack_Developer-2ea043?style=for-the-badge&logo=react&logoColor=white" alt="Full-Stack Developer"/>
<img src="https://img.shields.io/badge/WordPress_Developer-21759B?style=for-the-badge&logo=wordpress&logoColor=white" alt="WordPress Developer"/>
</p>

| If you need… | Look at |
|---|---|
| **AI / LLM engineering:** RAG, agents, evaluation, guardrails | [Multimodal Assistant](https://github.com/codeROCK-IZZY/multimodal-ai-assistant) · [Business Agents](https://github.com/codeROCK-IZZY/autonomous-business-platform) · [Document AI](https://github.com/codeROCK-IZZY/intelligent-document-ai) · [Guardrails Gateway](https://github.com/codeROCK-IZZY/llm-guardrails-gateway) · [Evaluation Platform](https://github.com/codeROCK-IZZY/llm-evaluation-platform) · [Visual Anomaly Detection](https://github.com/codeROCK-IZZY/visual-anomaly-detection) |
| **Machine learning:** models that explain themselves | [Predictive Maintenance](https://github.com/codeROCK-IZZY/ai-predictive-maintenance) · [Fraud Detection](https://github.com/codeROCK-IZZY/fraud-detection-engine) · [Recommender System](https://github.com/codeROCK-IZZY/recommender-system) · [Demand Forecasting](https://github.com/codeROCK-IZZY/demand-forecasting) · [Entity Resolution](https://github.com/codeROCK-IZZY/entity-resolution) · [Experimentation Platform](https://github.com/codeROCK-IZZY/experimentation-platform) |
| **MLOps:** registry, gated promotion, drift monitoring, retraining | [AWS MLOps Platform](https://github.com/codeROCK-IZZY/aws-mlops-platform) · [Feature Store](https://github.com/codeROCK-IZZY/feature-store) |
| **Model serving and distributed systems:** load shedding, quotas, failover, Kubernetes | [Distributed AI Inference](https://github.com/codeROCK-IZZY/distributed-ai-inference) |
| **Search and developer tools** | [Research Engine](https://github.com/codeROCK-IZZY/ai-research-engine) · [Developer Intelligence](https://github.com/codeROCK-IZZY/ai-developer-intelligence) |
| **Cloud and platform engineering** | [Enterprise AWS Cloud Platform](https://github.com/codeROCK-IZZY/enterprise-aws-cloud-platform) · [Serverless Event Platform](https://github.com/codeROCK-IZZY/aws-serverless-event-platform) · [Security Guardrails](https://github.com/codeROCK-IZZY/aws-security-guardrails) · [FinOps Optimizer](https://github.com/codeROCK-IZZY/aws-finops-optimizer) · [Data Lakehouse](https://github.com/codeROCK-IZZY/aws-data-lakehouse) · [Resilience Lab](https://github.com/codeROCK-IZZY/aws-resilience-lab) |

## 🎓 Education

<table>
<tr>
<td width="50%" valign="top">

### M.S. Computer Science
**Concentration: Artificial Intelligence**

Graduate-level focus on artificial intelligence and machine learning: the foundation behind the AI
systems in the projects above.

</td>
<td width="50%" valign="top">

### B.Sc. Information Systems
**Business technology and data**

How technology serves a business: the reason my projects start from a real business problem and end
with documentation for the people who run them.

</td>
</tr>
</table>

## 🧰 Stack

| | |
|---|---|
| **AI & ML** | <img src="https://img.shields.io/badge/Claude_API-D97757?style=flat-square&logo=anthropic&logoColor=white" alt="Claude API"/> <img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langchain&logoColor=white" alt="LangGraph"/> <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white" alt="scikit-learn"/> <img src="https://img.shields.io/badge/XGBoost-337AB7?style=flat-square" alt="XGBoost"/> <img src="https://img.shields.io/badge/MLflow-0194E2?style=flat-square&logo=mlflow&logoColor=white" alt="MLflow"/> <img src="https://img.shields.io/badge/SageMaker-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white" alt="SageMaker"/> <img src="https://img.shields.io/badge/ONNX_Runtime-005CED?style=flat-square&logo=onnx&logoColor=white" alt="ONNX Runtime"/> <img src="https://img.shields.io/badge/Whisper-412991?style=flat-square" alt="Whisper"/> <img src="https://img.shields.io/badge/pgvector-336791?style=flat-square&logo=postgresql&logoColor=white" alt="pgvector"/> |
| **Backend** | <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python"/> <img src="https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white" alt="Go"/> <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI"/> <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL"/> <img src="https://img.shields.io/badge/Apache_Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white" alt="Apache Kafka"/> <img src="https://img.shields.io/badge/SQLAlchemy-D71F00?style=flat-square&logo=sqlalchemy&logoColor=white" alt="SQLAlchemy"/> |
| **Frontend** | <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript"/> <img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" alt="React"/> <img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white" alt="Tailwind CSS"/> <img src="https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white" alt="Vite"/> |
| **Cloud & DevOps** | <img src="https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white" alt="AWS"/> <img src="https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white" alt="Terraform"/> <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker"/> <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white" alt="Kubernetes"/> <img src="https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white" alt="Prometheus"/> <img src="https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white" alt="Grafana"/> <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" alt="GitHub Actions"/> <img src="https://img.shields.io/badge/Checkov-6C2DC7?style=flat-square" alt="Checkov"/> |
| **Web & growth** | <img src="https://img.shields.io/badge/WordPress-21759B?style=flat-square&logo=wordpress&logoColor=white" alt="WordPress"/> <img src="https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white" alt="PHP"/> <img src="https://img.shields.io/badge/SEO-47A248?style=flat-square&logo=googlesearchconsole&logoColor=white" alt="SEO"/> <img src="https://img.shields.io/badge/Google_Analytics_4-E37400?style=flat-square&logo=googleanalytics&logoColor=white" alt="Google Analytics 4"/> <img src="https://img.shields.io/badge/Google_Ads-4285F4?style=flat-square&logo=googleads&logoColor=white" alt="Google Ads"/> <a href="#-digital-marketing--wordpress-toolkit">full toolkit ↓</a> |

## 🧪 How I build

```yaml
every_repo:
  ci:             [lint, type-check, tests, secret scan]          # green on main, every repo
  ai_features:    measured on labelled evaluation sets            # accuracy, citations, abstention, safety
  security:       least-privilege IAM, no long-lived credentials, input validation, audit trails
  infrastructure: Terraform for AWS, validated in CI, never applied without review
  docs:           [README, design doc, operations runbook, known limitations, model / AI card]
  data:           synthetic only, generated by code, no real customer data
```

## 📣 Digital Marketing & WordPress Toolkit

Besides engineering AI systems, I build and grow websites: WordPress builds, SEO, analytics, campaigns
and e-commerce. I can ship a product **and** help it reach the right people.

<table>
<tr><td><b>🧱 WordPress & page builders</b></td><td><img src="https://img.shields.io/badge/WordPress-21759B?style=flat-square&logo=wordpress&logoColor=white" alt="WordPress"/> <img src="https://img.shields.io/badge/Elementor-92003B?style=flat-square&logo=elementor&logoColor=white" alt="Elementor"/> <img src="https://img.shields.io/badge/Gutenberg-1E1E1E?style=flat-square&logo=wordpress&logoColor=white" alt="Gutenberg"/> <img src="https://img.shields.io/badge/Divi-8A2BE2?style=flat-square" alt="Divi"/> <img src="https://img.shields.io/badge/WPBakery-0073AA?style=flat-square" alt="WPBakery"/> <img src="https://img.shields.io/badge/ACF-00A0D2?style=flat-square" alt="ACF"/></td></tr>
<tr><td><b>🧑‍💻 Web development</b></td><td><img src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white" alt="HTML5"/> <img src="https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css&logoColor=white" alt="CSS3"/> <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" alt="JavaScript"/> <img src="https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white" alt="PHP"/></td></tr>
<tr><td><b>🔍 SEO & site optimization</b></td><td><img src="https://img.shields.io/badge/Ahrefs-FF8800?style=flat-square&logo=ahrefs&logoColor=white" alt="Ahrefs"/> <img src="https://img.shields.io/badge/SEMrush-FF642D?style=flat-square&logo=semrush&logoColor=white" alt="SEMrush"/> <img src="https://img.shields.io/badge/Yoast_SEO-A4286A?style=flat-square&logo=yoast&logoColor=white" alt="Yoast SEO"/> <img src="https://img.shields.io/badge/Rank_Math-4E2DD6?style=flat-square" alt="Rank Math"/> <img src="https://img.shields.io/badge/Screaming_Frog-6DBE45?style=flat-square" alt="Screaming Frog"/> <img src="https://img.shields.io/badge/PageSpeed_Insights-4285F4?style=flat-square&logo=google&logoColor=white" alt="PageSpeed Insights"/> <img src="https://img.shields.io/badge/GTmetrix-1A7BC4?style=flat-square" alt="GTmetrix"/> <img src="https://img.shields.io/badge/Core_Web_Vitals-0F9D58?style=flat-square&logo=lighthouse&logoColor=white" alt="Core Web Vitals"/></td></tr>
<tr><td><b>📈 Analytics & tracking</b></td><td><img src="https://img.shields.io/badge/Google_Analytics_4-E37400?style=flat-square&logo=googleanalytics&logoColor=white" alt="Google Analytics 4"/> <img src="https://img.shields.io/badge/Search_Console-458CF5?style=flat-square&logo=googlesearchconsole&logoColor=white" alt="Search Console"/> <img src="https://img.shields.io/badge/Tag_Manager-246FDB?style=flat-square&logo=googletagmanager&logoColor=white" alt="Tag Manager"/> <img src="https://img.shields.io/badge/Looker_Studio-4285F4?style=flat-square&logo=looker&logoColor=white" alt="Looker Studio"/> <img src="https://img.shields.io/badge/Hotjar-FF3C00?style=flat-square&logo=hotjar&logoColor=white" alt="Hotjar"/> <img src="https://img.shields.io/badge/Microsoft_Clarity-0078D4?style=flat-square" alt="Microsoft Clarity"/> <img src="https://img.shields.io/badge/A%2FB_testing_%26_CRO-2EA043?style=flat-square" alt="A/B testing & CRO"/></td></tr>
<tr><td><b>📣 Marketing platforms</b></td><td><img src="https://img.shields.io/badge/Google_Ads-4285F4?style=flat-square&logo=googleads&logoColor=white" alt="Google Ads"/> <img src="https://img.shields.io/badge/HubSpot-FF7A59?style=flat-square&logo=hubspot&logoColor=white" alt="HubSpot"/> <img src="https://img.shields.io/badge/Mailchimp-FFE01B?style=flat-square&logo=mailchimp&logoColor=black" alt="Mailchimp"/> <img src="https://img.shields.io/badge/Constant_Contact-1856ED?style=flat-square" alt="Constant Contact"/> <img src="https://img.shields.io/badge/GoHighLevel-188BF6?style=flat-square" alt="GoHighLevel"/> <img src="https://img.shields.io/badge/Salesforce-00A1E0?style=flat-square" alt="Salesforce"/> <img src="https://img.shields.io/badge/Hootsuite-143059?style=flat-square&logo=hootsuite&logoColor=white" alt="Hootsuite"/> <img src="https://img.shields.io/badge/Buffer-231F20?style=flat-square&logo=buffer&logoColor=white" alt="Buffer"/> <img src="https://img.shields.io/badge/Meta_Business_Suite-0467DF?style=flat-square&logo=meta&logoColor=white" alt="Meta Business Suite"/></td></tr>
<tr><td><b>🛒 E-commerce & payments</b></td><td><img src="https://img.shields.io/badge/Shopify-7AB55C?style=flat-square&logo=shopify&logoColor=white" alt="Shopify"/> <img src="https://img.shields.io/badge/WooCommerce-96588A?style=flat-square&logo=woocommerce&logoColor=white" alt="WooCommerce"/> <img src="https://img.shields.io/badge/Stripe-635BFF?style=flat-square&logo=stripe&logoColor=white" alt="Stripe"/> <img src="https://img.shields.io/badge/PayPal-003087?style=flat-square&logo=paypal&logoColor=white" alt="PayPal"/> <img src="https://img.shields.io/badge/Square-3E4348?style=flat-square&logo=square&logoColor=white" alt="Square"/></td></tr>
<tr><td><b>🎨 Design & creative</b></td><td><img src="https://img.shields.io/badge/Canva-00C4CC?style=flat-square" alt="Canva"/> <img src="https://img.shields.io/badge/Photoshop-31A8FF?style=flat-square&logo=adobephotoshop&logoColor=white" alt="Photoshop"/> <img src="https://img.shields.io/badge/Figma-F24E1E?style=flat-square&logo=figma&logoColor=white" alt="Figma"/> <img src="https://img.shields.io/badge/Illustrator-FF9A00?style=flat-square&logo=adobeillustrator&logoColor=white" alt="Illustrator"/></td></tr>
<tr><td><b>🌐 Hosting, performance & accessibility</b></td><td><img src="https://img.shields.io/badge/cPanel-FF6C2C?style=flat-square&logo=cpanel&logoColor=white" alt="cPanel"/> <img src="https://img.shields.io/badge/DNS_%26_SSL-30363D?style=flat-square&logo=letsencrypt&logoColor=white" alt="DNS & SSL"/> <img src="https://img.shields.io/badge/CDN-F38020?style=flat-square&logo=cloudflare&logoColor=white" alt="CDN"/> <img src="https://img.shields.io/badge/Caching_%26_image_optimization-2EA043?style=flat-square" alt="Caching & image optimization"/> <img src="https://img.shields.io/badge/WCAG_2.1_%2F_2.2-005A9C?style=flat-square" alt="WCAG 2.1 / 2.2"/></td></tr>
<tr><td><b>🗂️ Workflow & AI</b></td><td><img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" alt="Git"/> <img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white" alt="GitHub"/> <img src="https://img.shields.io/badge/ClickUp-7B68EE?style=flat-square&logo=clickup&logoColor=white" alt="ClickUp"/> <img src="https://img.shields.io/badge/Trello-0052CC?style=flat-square&logo=trello&logoColor=white" alt="Trello"/> <img src="https://img.shields.io/badge/Asana-F06A6A?style=flat-square&logo=asana&logoColor=white" alt="Asana"/> <img src="https://img.shields.io/badge/ChatGPT-10A37F?style=flat-square" alt="ChatGPT"/> <img src="https://img.shields.io/badge/AI--assisted_content_%26_SEO-8957E5?style=flat-square" alt="AI-assisted content & SEO"/></td></tr>
</table>

```js
const marketing = {
  wordpress:   "business sites with Elementor, Gutenberg, Divi or WPBakery; ACF and PHP for custom features",
  seo:         "technical audits, keyword research and Core Web Vitals fixes that move rankings",
  analytics:   "GA4, Tag Manager and Looker Studio dashboards; heatmaps and A/B tests for conversion",
  campaigns:   "Google Ads, Meta, email (Mailchimp, HubSpot, Constant Contact) and CRM automation",
  ecommerce:   "WooCommerce and Shopify stores with Stripe, PayPal and Square payments",
  quality:     "fast, secure, accessible (WCAG 2.1 / 2.2) sites on managed hosting with CDN and SSL",
};
```

<!-- Contribution snake (regenerated daily by .github/workflows/snake.yml). Re-enable once the graph fills in:
## 🐍 Contribution activity

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/codeROCK-IZZY/codeROCK-IZZY/output/github-snake-dark.svg"/>
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/codeROCK-IZZY/codeROCK-IZZY/output/github-snake.svg"/>
  <img alt="Contribution graph eaten by a snake" src="https://raw.githubusercontent.com/codeROCK-IZZY/codeROCK-IZZY/output/github-snake.svg" width="100%"/>
</picture>

-->

---

<div align="center">

### 🤝 Let's build something

**Hiring for AI, ML, cloud or full-stack work?** Start with the [featured project](#-featured-project);
every README opens with the problem, the design and the measured results.

<a href="https://israelrocklyn.info"><img src="https://img.shields.io/badge/Portfolio-israelrocklyn.info-ffb454?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Portfolio: israelrocklyn.info"/></a>
<a href="https://www.linkedin.com/in/israel-rocklyn-789884140/"><img src="https://img.shields.io/badge/LinkedIn-Israel_Rocklyn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn: Israel Rocklyn"/></a>
<img src="https://img.shields.io/badge/Available_for_hire-yes-2ea043?style=for-the-badge&logo=handshake&logoColor=white" alt="Available for hire"/>
<img src="https://img.shields.io/badge/Location-United_States-1f6feb?style=for-the-badge&logo=googlemaps&logoColor=white" alt="Location: United States"/>

<sub>Built in public, one production-grade project at a time.</sub>

</div>
