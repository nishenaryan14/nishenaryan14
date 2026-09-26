# Aryan Nishen

### Applied AI Engineer | Agentic Systems | LLM Engineering

I work on **AI systems that connect models to real engineering workflows**. My main areas are agentic workflows, retrieval, evaluation, automation, and the software around them.

I like working on the parts that are easy to overlook: getting the right context, deciding when a tool should be used, checking the output, and making sure the workflow has a sensible way to recover when something fails.

```text
Context → Reasoning → Tools → Validation → Evaluation → Reliable Execution
```

## What I work on

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,ts,fastapi,nodejs,react,nextjs,mongodb,redis,docker,githubactions&perline=5" alt="Core technology stack" />
</p>

<table align="center">
  <tr>
    <td align="center" width="33%">
      <strong>🤖 Agentic AI</strong><br><br>
      LangGraph · LangChain · CrewAI
    </td>
    <td align="center" width="33%">
      <strong>🧠 LLM Systems</strong><br><br>
      RAG · Structured Outputs · Evaluation
    </td>
    <td align="center" width="33%">
      <strong>🛡️ AI Reliability</strong><br><br>
      Validation · Quality Gates · HITL
    </td>
  </tr>
  <tr>
    <td align="center">
      <strong>⚙️ Automation</strong><br><br>
      AI Test Generation · Workflow Automation
    </td>
    <td align="center">
      <strong>🔗 Enterprise Integrations</strong><br><br>
      GitHub · Jira · ADO · TestRail · SharePoint
    </td>
    <td align="center">
      <strong>💻 Software Systems</strong><br><br>
      Python · TypeScript · FastAPI · React · Node.js
    </td>
  </tr>
</table>

<details>
<summary><strong>Technology stack</strong></summary>
<br>

| Category | Technologies |
| --- | --- |
| **AI / LLM** | LangGraph · LangChain · CrewAI · RAG · LLM Evaluation |
| **Languages** | Python · TypeScript · JavaScript |
| **Backend / APIs** | FastAPI · Node.js · NestJS · REST APIs |
| **Frontend** | React · Next.js |
| **Data / Infrastructure** | MongoDB · Redis · SQLite · Docker · GitHub Actions |
| **Enterprise Tooling** | GitHub · Jira · Azure DevOps · TestRail · SharePoint |

</details>

## Featured Project

### [JobFlow AI](https://github.com/nishenaryan14/JobFlow-AI)

**A full-stack AI job search and resume platform built with LangGraph.**

The project combines several AI workflows instead of putting a single LLM call behind a web interface.

**What I built**

- LangGraph workflows for job discovery and decision making
- Resume analysis and targeted job search
- Job quality checks, matching, and ranking
- AI-based ATS compatibility analysis
- Resume rewriting with evaluation and a reflection step
- LLM-as-a-judge checks for generated output
- Fabrication checks and controlled retries
- FastAPI, Next.js, MongoDB, and Redis
- Docker Compose and GitHub Actions

The project is built around structured outputs, conditional workflows, validation, and failure handling.

→ [Explore JobFlow AI](https://github.com/nishenaryan14/JobFlow-AI)

---

## Professional AI Engineering

Most of my professional work involves putting AI into existing engineering processes rather than building standalone demos.

### 🤖 User Story → Test Coverage

I worked on a workflow that takes a Jira story, finds related TestRail coverage, checks for overlap, and generates missing test cases for review.

**Workflow**

`Jira Context → Retrieval → Existing Coverage → Duplication Check → Test Generation → HITL Review → TestRail`

**What the system does**
- Retrieves relevant existing test cases using semantic search
- Uses story context to judge whether coverage already exists
- Detects duplicate or overlapping coverage before generating new cases
- Produces structured test cases and routes them through human review
- Connects Jira, TestRail, MongoDB, and supporting APIs

**Scale:** 600+ existing test cases indexed for retrieval. A typical story produces around 6 to 12 generated test cases, depending on its size and complexity.

---

### 🌐 Localization QA and Governance

I also work on AI-assisted localization workflows that combine automated validation with reviewer and governance signals.

**Workflow**

`Changed Content → Semantic Validation → Governance Signals → Resolution → Persistent Report`

**What the system does**
- Checks translated and localized content automatically
- Combines semantic validation with reviewer and governance state
- Applies explicit resolution rules instead of leaving the final decision to an LLM
- Produces structured reports that can be consumed by later workflow steps
- Uses GitHub change detection as part of the pipeline

The important part for me is making the result **traceable and usable by the rest of the engineering pipeline**.

---

### ⚙️ Multi-Agent Workflow Migration

I have also worked on moving multi-agent engineering workflows between AI execution environments, including a migration to **GitHub Copilot custom agents**.

The work involves:
- Running agents sequentially or in parallel
- Passing structured context between agents
- Connecting agents to internal and enterprise tools
- Handling failures and validating intermediate outputs
- Hardening the workflow so it can be maintained after migration

This gave me a practical view of what changes when an agentic workflow moves from a prototype or internal platform into a different execution environment.

---

<sub><strong>Professional focus:</strong> Agentic AI · RAG and Retrieval · LLM Evaluation · AI Automation · Enterprise Integrations · Human-in-the-Loop Systems</sub>

> Some of this work is proprietary, so the public profile focuses on the engineering patterns rather than implementation details.

## How I Approach AI Systems

My background in software engineering, automation, and quality engineering has a big influence on how I build AI systems.

I don't treat a good-looking model response as the end of the workflow. I care about what happens before and after it.

**1. Get the context right**  
Retrieval and structured context have a direct impact on the quality of the result.

**2. Check the output**  
Generated content, tool calls, and decisions should have validation where the workflow depends on them.

**3. Plan for failure**  
Retries, fallbacks, checkpoints, quality gates, and human review are part of the design when the workflow matters.

That is the approach I try to bring to every AI system I build.

## Currently Looking For

I am interested in **Applied AI Engineer** roles focused on agentic systems, LLM engineering, retrieval, evaluation, AI reliability, and AI-powered engineering tools.

I am especially interested in teams where AI has to work with real software systems and where engineering quality matters as much as the model itself.

## Connect

[LinkedIn](https://www.linkedin.com/in/aryan-nishen/) · [Email](mailto:aryannishen27@gmail.com) · [GitHub](https://github.com/nishenaryan14)

<sub>Building useful AI systems, one workflow at a time.</sub>
