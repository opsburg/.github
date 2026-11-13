<p align="center"><img src="logo.png" alt="Opsburg" width="160"></p>

# Opsburg

**Keep your cloud up and running. Play it like a city.**

Opsburg builds and ships your apps and AI agents, from the repository to your Kubernetes. Then it turns running them
into a game: your stack is a flying steampunk city, every service is a building, every deploy an airship, every incident
a storm. Your team keeps the city flying, and your cloud stays up.

🌐 **Website:** [opsburg.github.io](https://opsburg.github.io/)

## The platform

- **Build:** apps and AI agents from templates, with repositories on GitHub, GitLab or Azure DevOps and CI included
- **Ship:** a tag builds and registers the version; one click deploys it through GitOps and Argo CD, with rollback
- **Run:** live state, logs and incidents; AI agents read the logs, propose the fix and ask before touching production
- **Your rules:** your single sign-on, roles and AI models; self-hosted, with an MCP server for AI clients

## The game

- **Uptime streaks:** every day the city stays in the air adds to the streak
- **Missions:** real chores turned into missions, from patching the vaults to retiring old airships
- **Storm drills:** rehearse an incident on purpose and see who repairs it first
- **A city that grows:** every service, environment and team adds a building

## The city

| In the game | In the real world |
|---|---|
| Clocktower | Control plane |
| Boiler House | Compute node |
| Factory | Service |
| Vault | Database |
| Telegraph | Message queue and logs |
| Observatory | Monitoring |
| Lightning Spire | Firewall |
| Airship | Deploy |
| Automaton | AI agent |
| Storm | Incident |
| Pressure | Load |
| Coal | Cost |

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
