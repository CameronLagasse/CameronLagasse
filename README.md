![header](https://capsule-render.vercel.app/api?type=waving&color=gradient&height=180&section=header&text=Cameron%20Lagasse&fontSize=48)

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&pause=1000&center=true&vCenter=true&width=700&lines=I+keep+big+GPU+clusters+running;Kubernetes+%7C+Slurm+%7C+Terraform;Agents+that+take+the+pain+out+of+on-call" alt="I keep big GPU clusters running" />
</p>

I keep big GPU clusters running so researchers can train models instead of fighting infrastructure.

I'm an HPC infrastructure engineer at Microsoft AI. My days are a mix of Kubernetes, Slurm, Terraform, and working out why a job that ran fine yesterday is stuck today.

## What I'm good at

<p align="center">
  <img src="https://skillicons.dev/icons?i=kubernetes,terraform,py,go,docker,azure,linux,grafana,prometheus,bash,git" alt="Kubernetes, Terraform, Python, Go, Docker, Azure, Linux, Grafana, Prometheus, Bash, Git" />
</p>
<p align="center">
  <img src="https://img.shields.io/badge/Slurm-1F6FEB?style=for-the-badge" alt="Slurm" />
  <img src="https://img.shields.io/badge/Datadog-632CA6?style=for-the-badge&logo=datadog&logoColor=white" alt="Datadog" />
  <img src="https://img.shields.io/badge/Argo%20CD-EF7B4D?style=for-the-badge&logo=argo&logoColor=white" alt="Argo CD" />
</p>

- **GPU cluster operations:** scheduling, quotas, node health, networking and storage for large training jobs
- **Kubernetes and Slurm:** running both, and debugging the places where they disagree
- **Infrastructure as code:** Terraform and GitOps with Argo CD, so changes are reviewed and repeatable
- **Observability:** Datadog, Grafana and Kusto, used to find a root cause rather than decorate a dashboard
- **Tooling:** Python and Go, mostly small tools that remove a manual step someone was doing at 2 a.m.
- **AI agents for operations:** agents that investigate failures and propose fixes, with humans deciding what ships

## Work I'm proud of

Most of what I build lives in private repos, so here it is in words.

| 🤖 Support agent | 🧠 Multi-agent engineering | 🔍 Failure investigation |
|---|---|---|
| Answers cluster users in Slack, digs through logs and metrics when a job fails, and proposes improvements to its own knowledge that a person accepts or refuses. | Coordinators plan the work, workers implement it in isolated worktrees, and reviewers from a different model family check every change before it merges. | Ties a failed training job to a cause, whether that is the node, the network, storage or the scheduler, and backs each claim with a query result. |

## How it fits together

```mermaid
flowchart LR
  U[Researcher] --> S[Scheduler: Slurm / Kubernetes]
  S --> G[GPU nodes]
  G --> O[Logs and metrics]
  O --> A[Ops agent]
  A --> H[Human decides]
```

## What I'm working on now

- Making operations agents trustworthy enough to carry real on-call work
- Bringing new GPU capacity into service without surprising the people already training on it

## Get in touch

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/cameronlagasse)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:camlag9@gmail.com)

I'm always happy to talk about GPU infrastructure, scheduling, or agents that do operations work.
