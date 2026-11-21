# DevOps Configuration and Commands

A practical reference for common DevOps commands, configuration patterns, and troubleshooting workflows.

## Command areas

| Area | Examples |
| --- | --- |
| Linux | Users, permissions, processes, services, filesystems, networking |
| Git and GitHub | Repository setup, branches, remotes, tags, recovery |
| Jenkins | Service management, agents, credentials, pipeline diagnostics |
| Docker | Build, run, inspect, logs, networks, volumes, cleanup |
| Kubernetes | kubectl workflows, manifests, rollout, logs, debugging |
| Helm | Repositories, charts, values, upgrades, rollback |
| Terraform | Init, validate, plan, apply, state, import, workspaces |
| Ansible | Inventory, ad hoc commands, playbooks, vault, linting |
| Cloud CLIs | Authentication, compute, storage, networking, IAM |
| Observability | Prometheus, Grafana, logs, metrics, health checks |
| Security | TLS, SSH, secrets, scanning, access verification |

## Entry format

Every command or configuration example should document:

1. Purpose and prerequisites
2. Safe command or configuration example
3. Expected result
4. Common failure modes
5. Rollback or cleanup procedure when applicable

## Safety rules

- Test destructive commands in a non-production environment first.
- Explain placeholders and environment-specific values.
- Never commit passwords, tokens, private keys, kubeconfig credentials, state files, or production secrets.
- Prefer repeatable automation over undocumented manual changes.
