# Hi, I'm Cameron 👋

I keep big GPU clusters running so researchers can train models instead of fighting infrastructure.

I'm an HPC infrastructure engineer at Microsoft AI. My days are a mix of Kubernetes, Slurm, Terraform, and working out why a job that ran fine yesterday is stuck today.

## What I'm good at

- **GPU cluster operations:** scheduling, quotas, node health, networking and storage for large training jobs
- **Kubernetes and Slurm:** running both, and debugging the places where they disagree
- **Infrastructure as code:** Terraform and GitOps with Argo CD, so changes are reviewed and repeatable
- **Observability:** Datadog, Grafana and Kusto, used to find a root cause rather than decorate a dashboard
- **Tooling:** Python and Go, mostly small tools that remove a manual step someone was doing at 2 a.m.
- **AI agents for operations:** agents that investigate failures and propose fixes, with humans deciding what ships

## Work I'm proud of

Most of what I build lives in private repos, so here it is in words.

- **A support agent for cluster users.** It answers questions in Slack, digs through logs and metrics when a job fails, and proposes improvements to its own knowledge that a person accepts or refuses.
- **A multi-agent engineering setup.** Coordinators plan the work, workers implement it in isolated worktrees, and reviewers from a different model family check every change before it merges.
- **Failure investigation that shows its evidence.** Tooling that ties a failed training job to a cause, whether that is the node, the network, storage or the scheduler, and backs each claim with a query result.
- **[example-files](https://github.com/CameronLagasse/example-files).** Helm charts and configs from my homelab (Grafana, Home Assistant, nginx, an Airflow DAG) that you can copy and adapt.

## What I'm working on now

- Making operations agents trustworthy enough to carry real on-call work
- Bringing new GPU capacity into service without surprising the people already training on it

## Get in touch

Email me at [camlag9@gmail.com](mailto:camlag9@gmail.com) or find me on [LinkedIn](https://www.linkedin.com/in/cameronlagasse). I'm always happy to talk about GPU infrastructure, scheduling, or agents that do operations work.
