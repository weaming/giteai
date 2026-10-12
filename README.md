# GiteAI

GiteAI is a fork of [Gitea](https://github.com/go-gitea/gitea) for continuous, AI-assisted software development.

It keeps Gitea's self-hosted Git forge workflow—repositories, issues, pull requests, code review, project boards, packages and CI/CD—while exploring an AI-native development loop.

## Direction

- Use issues and comments as durable task context.
- Use branches and pull requests as execution and review boundaries.
- Support separate developer, reviewer and manager agents.
- Provide task queues, leases, retries and quality gates.
- Connect any agent through APIs, webhooks, MCP or CLI adapters.
- Integrate with local tools such as [xbot](https://github.com/weaming/ai-box/tree/main/xbot).
- Keep human approval for production and high-risk changes.

The goal is to make software development continue safely while people are away, without tying the workflow to a specific model or agent runtime.

## Upstream

This repository follows upstream Gitea. Use the upstream documentation for installation, development and contribution details until a GiteAI-specific behavior is documented here.

- [Gitea documentation](https://docs.gitea.com/)
- [Development guide](docs/development.md)
- [Contributing guide](CONTRIBUTING.md)
- [Gitea API](https://docs.gitea.com/api/)

GiteAI-specific changes should remain small, well-tested and easy to rebase onto upstream.
