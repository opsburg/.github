<p align="center"><img src="logo.png" alt="Opsburg" width="160"></p>

# Opsburg

**Build your flying city. Run real infrastructure.**

Opsburg is a steampunk city builder for DevOps, SRE and platform engineers. Your city floats in the clouds, and every
piece of it is backed by a piece of your real stack: place a building and a service is created, launch an airship and a
version is built and deployed, weather a storm and an incident gets fixed.

🌐 **Website:** [opsburg.github.io](https://opsburg.github.io/)

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
| Storm | Incident |
| Pressure | Load |
| Coal | Cost |

## Under the brass

- **Your Git and your pipelines:** GitHub, GitLab and Azure DevOps
- **GitOps deploys:** Argo CD on your Kubernetes
- **Automatons:** AI agents that read logs, propose fixes and ask before they touch production

## Repositories

| Repository | What it is |
|---|---|
| [opsburg](https://github.com/opsburg/opsburg) | The game server and console: backend, frontend, Docker images |
| [opsburg.github.io](https://github.com/opsburg/opsburg.github.io) | The website |
| [pipeline-models](https://github.com/opsburg/pipeline-models) | The CI pipelines copied into every repository a city creates |
| [github-action](https://github.com/opsburg/github-action) | GitHub Action: upload a frontend bundle or register a Docker image |
| [azure-devops-extension](https://github.com/opsburg/azure-devops-extension) | The same two steps as Azure Pipelines tasks |
| [templates](https://github.com/opsburg/templates) | The starter templates for services and frontends |
| [design-system](https://github.com/opsburg/design-system) | The React component library: `@opsburg/design-system` |
| [telemetry-be](https://github.com/opsburg/telemetry-be) | Collects the anonymous usage ping of self-hosted installations |
| [backoffice-be](https://github.com/opsburg/backoffice-be) · [backoffice-fe](https://github.com/opsburg/backoffice-fe) | The internal backoffice: users, projects, packages and telemetry |
| [telemetry-infrastructure](https://github.com/opsburg/telemetry-infrastructure) · [backoffice-infrastructure](https://github.com/opsburg/backoffice-infrastructure) | OpenTofu for the telemetry and backoffice containers |

> Opsburg is in the workshop and not playable yet.
