<p align="center"><img src="logo.png" alt="Opsburg" width="160"></p>

# Opsburg

**When the giants stumble, your city keeps flying.**

Your company's work, done by people and by AI agents, now runs on a handful of US clouds and AI models. One hiccup on
their side and everything stops: the team waits for someone else's status page, every agent stalls at once, and nobody
inside the company can fix it.

Opsburg is a city builder for the teams who keep a company running. Your flying city is your real stack, and every
building is wired to the provider it draws power from. The game is making sure no single giant can ground it.

🌐 **Website:** [opsburg.github.io](https://opsburg.github.io/)

## Power

| In the game | In the real world |
|---|---|
| Foreign power plant | A US cloud or AI provider |
| Blackout | A provider outage: people and agents stop |
| Own engine | Infrastructure you control: your servers, a European cloud, a self-hosted open model |
| Reserve line | Failover to a second source |
| Rehearsed blackout | Cutting a dependency on purpose to see what keeps flying |

## The city

| In the game | In the real world |
|---|---|
| Clocktower | Control plane |
| Boiler House | Compute node |
| Factory | Service |
| Vault | Database |
| Telegraph | Message queue |
| Observatory | Monitoring |
| Lightning Spire | Firewall |
| Airship | Deploy |
| Automaton | AI agent |
| Storm | Incident |
| Pressure | Load |
| Coal | Cost |

## Under the brass

- **No single source:** GitHub, GitLab and Azure DevOps for code; your Kubernetes through Argo CD for deploys
- **Automatons on more than one model:** AI agents that read logs and propose fixes, built to switch to another provider or to a model you host
- **Self-hostable:** the whole city runs on servers you own

## Repositories

| Repository | What it is |
|---|---|
| [opsburg](https://github.com/opsburg/opsburg) | The game server and console: backend, frontend, Docker images |
| [opsburg.github.io](https://github.com/opsburg/opsburg.github.io) | The website |
| [pipeline-models](https://github.com/opsburg/pipeline-models) | The CI pipelines copied into every repository a city creates |
| [github-action](https://github.com/opsburg/github-action) | GitHub Action: upload a frontend bundle or register a Docker image |
| [azure-devops-extension](https://github.com/opsburg/azure-devops-extension) | The same two steps as Azure Pipelines tasks |
| [templates](https://github.com/opsburg/templates) | The starter templates for services and frontends |
| [design-system](https://github.com/opsburg/design-system) | The React component library: `@opsburg/design-system` · [Storybook](https://opsburg.github.io/design-system/) |
| [telemetry-be](https://github.com/opsburg/telemetry-be) | Collects the anonymous usage ping of self-hosted installations |
| [backoffice-be](https://github.com/opsburg/backoffice-be) · [backoffice-fe](https://github.com/opsburg/backoffice-fe) | The internal backoffice: users, projects, packages and telemetry |
| [telemetry-infrastructure](https://github.com/opsburg/telemetry-infrastructure) · [backoffice-infrastructure](https://github.com/opsburg/backoffice-infrastructure) | OpenTofu for the telemetry and backoffice containers |
| [infrastructure](https://github.com/opsburg/infrastructure) | OpenTofu for the console, Redis and Metabase |

> Opsburg is in the workshop and not playable yet.
