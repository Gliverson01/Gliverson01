## Hi, I'm Gliverson Almeida

**Site Reliability Engineer** at ChatGuru, a WhatsApp customer service SaaS. I run 22 production environments on
managed Kubernetes (100+ nodes, 3,000+ pods) with MongoDB, Kafka and AWS.

What I work on:

- **Incident response with evidence:** correlating Prometheus metrics, Loki logs, Kafka queues and the database
  until the root cause is proven, then writing it down as a postmortem and a runbook.
- **Observability:** Prometheus, Loki, Grafana and alerting that points to the source of each alert.
- **Cloud cost:** AWS and OVHcloud cost analysis, from usage metrics to right-sizing.
- **AI for operations, safely:** AI agents (Claude Code, MCP) that help with investigation, behind tested guardrails
  that block production writes and keep credentials and customer data out of reach.

### Projects

| Project | What it shows | Stack |
|---|---|---|
| [ai-ops-guardrails](https://github.com/Gliverson01/ai-ops-guardrails) | Claude Code hook that lets an AI agent investigate production without changing it: parses each command and blocks writes to Kubernetes, databases, S3, Terraform and protected branches | Python · Claude Code · pytest |
| [Monitoramento-de-Infraestrutura-Web](https://github.com/Gliverson01/Monitoramento-de-Infraestrutura-Web) | Synthetic monitoring of my website with a 99.5% SLO, burn-rate alerts tested with promtool and CI that boots the stack | Prometheus · Blackbox · Grafana · GitHub Actions |
| [kubernetes-pick](https://github.com/Gliverson01/kubernetes-pick) | Hands-on Kubernetes labs from the LINUXtips PICK program, in progress | Kubernetes · kind |
| [Pipeline-CI-CD-com-GitHub-Actions-e-FastAPI](https://github.com/Gliverson01/Pipeline-CI-CD-com-GitHub-Actions-e-FastAPI) | CI/CD with tests, linting and a Docker build | GitHub Actions · Docker · Python |
| [Automacao-de-Rotinas-com-Ansible-e-Docker](https://github.com/Gliverson01/Automacao-de-Rotinas-com-Ansible-e-Docker) | Linux provisioning and containerized deploys | Ansible · Docker · Shell |

### Stack

Kubernetes · Kustomize · Docker · Prometheus · Grafana · Loki · AWS · OVHcloud · MongoDB · Kafka · Terraform ·
GitHub Actions · Ansible · Python · Bash · Claude Code · MCP

### Contact

[LinkedIn](https://www.linkedin.com/in/gliverson-almeida/) · [Website](https://www.gliversonalmeida.com.br/) ·
gliversonfrp@gmail.com
