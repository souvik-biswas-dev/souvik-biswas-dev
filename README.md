# Hi, I'm Souvik Biswas 👋

Backend and DevOps engineer (new grad 2026). I build Go and Node.js services, ship them with Docker, Kubernetes and AWS, and contribute to Kubernetes-ecosystem open source.

📫 souvikbiswas.dev@gmail.com · 🌐 [Portfolio](https://souvikbiswas-portfolio.pages.dev) · 💼 [LinkedIn](https://linkedin.com/in/souvik-biswas-dev)

## Open source (merged PRs)

| Project | Change | PR |
|---|---|---|
| Flux (CNCF) | `flux get` / `flux reconcile` accept kubectl-style `TYPE/NAME` args, e.g. `hr/podinfo` | [flux2#6134](https://github.com/fluxcd/flux2/pull/6134) |
| Open Cluster Management (CNCF) | Diagnosed a ~1% e2e flake in the klusterlet operator (double agent rollout plus a 163s leader-election wait against a 150s test timeout); merged a test-only fix | [ocm#1756](https://github.com/open-cluster-management-io/ocm/pull/1756) |
| Kubernetes minikube | Fixed arm64 lint failures in the KVM driver and added an arm64 runner to the CI lint matrix | [minikube#23860](https://github.com/kubernetes/minikube/pull/23860) |
| Gitea docs | Fixed a wrong repository path in the Backup & Restore guide, checked against the source and Docker templates | [docs#601](https://gitea.com/gitea/docs/pulls/601) |

[All merged PRs →](https://github.com/search?q=author%3Asouvik-biswas-dev+is%3Apr+is%3Amerged&type=pullrequests)

## Projects

- **[DriftWatch](https://github.com/souvik-biswas-dev/DriftWatch)**: Go service that compares running Docker containers with the docker-compose.yml in GitHub and flags 5 kinds of drift within 60 seconds. Agent pushes state over HTTPS, so servers never accept inbound connections.
- **[ReviewFlow](https://github.com/souvik-biswas-dev/ReviewFlow)**: real-time code review in Go with a race-free WebSocket room manager and a gqlgen GraphQL layer, no message broker.
- **School Portal 360** ([live](https://schoolportal360.com)): multi-tenant school ERP in production for 1,000+ students (Next.js, MongoDB, Redis, Docker, Kubernetes).

## Stack

**Languages:** Go, TypeScript, JavaScript, C++
**Backend:** Gin, Node.js, Express, GraphQL, WebSockets, BullMQ
**Data:** PostgreSQL, MongoDB, Redis
**Infra:** AWS, Docker, Kubernetes, Nginx, Caddy, GitHub Actions
