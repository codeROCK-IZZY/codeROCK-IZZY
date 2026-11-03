<div align="center">

<img src="assets/terminal.svg" alt="Rocklyn — AI &amp; Cloud Software Engineer" width="100%"/>

<br/>

<a href="#-projects"><img src="https://img.shields.io/badge/projects-8_shipped-2ea44f?style=for-the-badge&logo=github&logoColor=white" alt="8 projects shipped"/></a>
<a href="#-how-i-build"><img src="https://img.shields.io/badge/CI-green_on_every_repo-2ea44f?style=for-the-badge&logo=githubactions&logoColor=white" alt="CI green on every repo"/></a>
<a href="#-stack"><img src="https://img.shields.io/badge/focus-AI_%C2%B7_Cloud_%C2%B7_Full--stack-8957e5?style=for-the-badge" alt="Focus: AI, cloud, full-stack"/></a>

</div>

---

```python
class Rocklyn(SoftwareEngineer):
    """I build AI products and the cloud platforms they run on: end to end, tested, documented."""

    role      = "AI & Cloud Software Engineer"
    languages = ["Python", "TypeScript", "SQL", "HCL"]

    def builds(self):
        return {
            "ai":        ["grounded RAG with citations", "LLM agents with human approval",
                          "speech + vision + OCR pipelines", "classical ML with explainability"],
            "backend":   ["FastAPI services", "PostgreSQL (pgvector, job queues)", "Kafka streaming"],
            "frontend":  ["React + TypeScript dashboards"],
            "cloud":     ["AWS landing zones", "ECS / RDS / EFS", "Terraform with tests"],
        }

    def principles(self):
        return [
            "Measure it: AI features ship with an evaluation, not a demo.",
            "Say \"I don't know\": answers cite their source or decline.",
            "Secure by default: least privilege, no long-lived keys, audit trails.",
            "Write it down: design docs, runbooks and known limitations in every repo.",
        ]
```

## 🚀 Projects

<table>
<tr>
<td width="50%" valign="top">

### 🗣️ [Multimodal AI Assistant](https://github.com/codeROCK-IZZY/multimodal-ai-assistant)
Talk or type, attach photos, PDFs and voice notes. Answers cite the **page, line or timestamp**, decline when the files don't say, and run tools under permissions that **prompt injection can't bypass**.

`faster-whisper` `Piper TTS` `RapidOCR` `cross-encoder` `FastAPI` `React`

</td>
<td width="50%" valign="top">

### ☁️ [Enterprise AWS Cloud Platform](https://github.com/codeROCK-IZZY/enterprise-aws-cloud-platform)
A Terraform **landing zone**: Organizations with guardrail SCPs, tamper-resistant org-wide logging, GuardDuty and Security Hub, and a Transit Gateway network with prod/non-prod isolation. **Tested without an AWS account**.

`Terraform` `AWS Organizations` `Transit Gateway` `IPAM` `Checkov`

</td>
</tr>
<tr>
<td valign="top">

### 🤖 [Autonomous Business Operations](https://github.com/codeROCK-IZZY/autonomous-business-platform)
AI agents that handle refunds, supplier invoices and purchase requests, with **human approval** for risky actions, idempotent tools, retries and a **hash-chained audit trail**.

`LangGraph` `Claude API` `PostgreSQL` `FastAPI` `React`

</td>
<td valign="top">

### 💳 [Fraud Detection Engine](https://github.com/codeROCK-IZZY/fraud-detection-engine)
Real-time fraud scoring on a **Kafka** transaction stream, with explainable model decisions and an analyst case workflow.

`Kafka` `XGBoost` `SHAP` `FastAPI` `React`

</td>
</tr>
<tr>
<td valign="top">

### 📄 [Intelligent Document AI](https://github.com/codeROCK-IZZY/intelligent-document-ai)
Turns PDFs, Word files and scans into searchable, structured data, with **grounded Q&A** that refuses to answer without a citation.

`OCR` `pgvector` `embeddings` `Claude citations` `FastAPI`

</td>
<td valign="top">

### 🏭 [AI Predictive Maintenance](https://github.com/codeROCK-IZZY/ai-predictive-maintenance)
Predicts industrial equipment failures days ahead from sensor data, explains each prediction, and tracks the fleet on a dashboard.

`scikit-learn` `XGBoost` `SHAP` `FastAPI` `React`

</td>
</tr>
<tr>
<td valign="top">

### 🔎 [AI Research & Knowledge Engine](https://github.com/codeROCK-IZZY/ai-research-engine)
Team knowledge bases built from files and the web, with hybrid search, re-ranking and cited answers.

`pgvector` `ONNX re-ranker` `hybrid search` `FastAPI`

</td>
<td valign="top">

### 🧠 [AI Developer Intelligence](https://github.com/codeROCK-IZZY/ai-developer-intelligence)
Understands any codebase: parses five languages, maps dependencies, flags risks and answers questions about the code.

`tree-sitter` `PageRank` `MinHash` `pgvector` `FastAPI`

</td>
</tr>
</table>

<details>
<summary><b>🛠️ In progress</b></summary>
<br/>

| Project | What it will do |
|---|---|
| [aws-mlops-platform](https://github.com/codeROCK-IZZY/aws-mlops-platform) | Notebook-to-production ML on AWS: training pipelines, model registry and monitored deployments |
| [distributed-ai-inference](https://github.com/codeROCK-IZZY/distributed-ai-inference) | Serving model predictions at scale on Kubernetes, with autoscaling and load tests |

</details>

## 🧰 Stack

<p>
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python"/>
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript"/>
<img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI"/>
<img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" alt="React"/>
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL"/>
<img src="https://img.shields.io/badge/Apache_Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white" alt="Apache Kafka"/>
<img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white" alt="scikit-learn"/>
<img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langchain&logoColor=white" alt="LangGraph"/>
<img src="https://img.shields.io/badge/Claude_API-D97757?style=flat-square&logo=anthropic&logoColor=white" alt="Claude API"/>
<img src="https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white" alt="AWS"/>
<img src="https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white" alt="Terraform"/>
<img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker"/>
<img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" alt="GitHub Actions"/>
<img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white" alt="Tailwind CSS"/>
</p>

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

<div align="center">

<sub>Built in public, one production-grade project at a time.</sub>

</div>
