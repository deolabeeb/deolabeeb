# Abeeb Adesina Adeola

**Python Engineering | AI/ML Applications & Automation**

I build Python applications and automation workflows with a focus on reliability, clear interfaces, and reproducible tests. My portfolio shows what I have built, how it is tested, and what I am developing next.

[Portfolio website](https://deolabeeb.github.io/data-ml-portfolio/) · [SupportOps case study](https://deolabeeb.github.io/data-ml-portfolio/projects/supportops.html)

## Current engineering work

**SupportOps — a locally tested customer-support prototype.** Built with Python, FastAPI and LangGraph, it looks up synthetic orders, keeps each customer's conversations separate and saves conversation history in SQLite. Tests cover how the workflow handles failures and limits the work a request can perform.

The accepted prototype passed 134 regression tests on Windows with Python 3.12.14 on 1 October 2026, including 27 tests of execution limits. Separate-process checks verified that saved conversations survive a restart and remain isolated between customers. This work builds on a supplied starter, extended with Codex assistance.

The prototype uses predictable mock responses and synthetic data. It has not been deployed as a service or verified with a live language model. A later attempt to add an optional model provider remains unfinished because of a timeout problem; passing diagnostic tests did not resolve that problem. Timeouts limit how long callers wait, but cannot forcibly stop blocking work. The current working source includes unfinished changes and is not presented as the verified prototype release.

## Open-source contribution focus

I want to apply my Python engineering work to useful open-source contributions: clear bug reports, small fixes, regression tests and practical documentation. My goal is to build a record of reviewed contributions and progress into paid contributor work. I will link accepted contributions here as they become available.

## Portfolio direction

I’m developing distinct tracks for document retrieval (DocOps), reviewed lead workflows (LeadOps), synthetic invoice checks (FinanceOps), reproducible data pipelines (DataOps), leakage-aware ML serving (PredictOps) and agent reliability evaluation (AgentEval). These tracks are planned; their results will be added as they become verified.

## Engineering approach

Clear API and data contracts, explicit ownership boundaries, reproducible tests and observable failure paths. Coursework, forks and upstream-derived work retain their attribution; project claims stay tied to evidence.

[GitHub](https://github.com/deolabeeb) · [Existing portfolio repository](https://github.com/deolabeeb/data-ml-portfolio)

The account Profile README and the portfolio repository landing page are separate entry points. The published website and case study are static portfolio pages; the SupportOps application remains a local mock, not a live service.

[Email](mailto:deolabeeb@gmail.com) · [LinkedIn](https://linkedin.com/in/abeeb-adesina)
