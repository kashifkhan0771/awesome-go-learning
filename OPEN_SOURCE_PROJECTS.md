# Go Open Source Projects to Contribute To

> Well-known open source projects written in Go that welcome outside contributions.

Contributing to a real project is one of the best ways to get better at Go. You read production code, get reviews from experienced maintainers and learn how large codebases are organized. Every project below is open source, active and has a contributing guide. Most also label issues that are good for newcomers.

Back to the [main list](README.md).

## How to Start

1. Pick a project you already use, or one in an area you want to learn.
2. Read its contributing guide and code of conduct before writing code.
3. Build the project and run its tests locally.
4. Start with a labeled beginner issue, a docs fix or a missing test.
5. Comment on the issue before starting, so maintainers can confirm nobody else is on it.
6. Keep the first pull request small and follow the review feedback.

Each entry shows its license. Links go to the contributing guide and the project's own beginner label, since projects name that label differently.

## Contents

- [How to Start](#how-to-start)
- [🧰 Language & Tooling](#-language--tooling)
- [☸️ Containers & Kubernetes](#-containers--kubernetes)
- [🌐 Networking & Infrastructure](#-networking--infrastructure)
- [📈 Observability](#-observability)
- [🔐 Security](#-security)
- [💻 Developer Tools](#-developer-tools)
- [💾 Storage & Sync](#-storage--sync)
- [📦 Libraries & Frameworks](#-libraries--frameworks)

## 🧰 Language & Tooling

*The language itself and the tools around it.*

- [Delve](https://github.com/go-delve/delve) - `MIT` Debugger for Go programs. [Contributing guide](https://github.com/go-delve/delve/blob/master/CONTRIBUTING.md)
- [Go](https://github.com/golang/go) - `BSD-3-Clause` The Go compiler, runtime, standard library and tools. Changes are reviewed on Gerrit, not GitHub pull requests. The contributing guide explains the process. [Contributing guide](https://github.com/golang/go/blob/master/CONTRIBUTING.md)
- [golangci-lint](https://github.com/golangci/golangci-lint) - `GPL-3.0` Runner that combines many Go linters into one tool. [Contributing guide](https://github.com/golangci/golangci-lint/blob/main/.github/CONTRIBUTING.md) · [Good first issues](https://github.com/golangci/golangci-lint/issues?q=is%3Aissue%20is%3Aopen%20label%3A%22good%20first%20issue%22)
- [GoReleaser](https://github.com/goreleaser/goreleaser) - `MIT` Automates building and publishing releases of Go projects. [Contributing guide](https://github.com/goreleaser/goreleaser/blob/main/CONTRIBUTING.md) · [Good first issues](https://github.com/goreleaser/goreleaser/issues?q=is%3Aissue%20is%3Aopen%20label%3A%22good-first-issue%22)

## ☸️ Containers & Kubernetes

*Container runtimes, orchestration and the cloud-native stack.*

- [Argo CD](https://github.com/argoproj/argo-cd) - `Apache-2.0` GitOps continuous delivery tool for Kubernetes. [Contributing guide](https://github.com/argoproj/argo-cd/blob/master/CONTRIBUTING.md) · [Good first issues](https://github.com/argoproj/argo-cd/issues?q=is%3Aissue%20is%3Aopen%20label%3A%22good%20first%20issue%22)
- [containerd](https://github.com/containerd/containerd) - `Apache-2.0` Container runtime used by Docker and Kubernetes. [Contributing guide](https://github.com/containerd/containerd/blob/main/CONTRIBUTING.md) · [Good first issues](https://github.com/containerd/containerd/issues?q=is%3Aissue%20is%3Aopen%20label%3A%22exp/beginner%22)
- [Dapr](https://github.com/dapr/dapr) - `Apache-2.0` Runtime with building blocks for distributed applications. [Contributing guide](https://github.com/dapr/dapr/blob/master/CONTRIBUTING.md) · [Good first issues](https://github.com/dapr/dapr/issues?q=is%3Aissue%20is%3Aopen%20label%3A%22good%20first%20issue%22)
- [Docker CLI](https://github.com/docker/cli) - `Apache-2.0` The docker command-line client. [Contributing guide](https://github.com/docker/cli/blob/master/CONTRIBUTING.md) · [Good first issues](https://github.com/docker/cli/issues?q=is%3Aissue%20is%3Aopen%20label%3A%22exp/beginner%22)
- [etcd](https://github.com/etcd-io/etcd) - `Apache-2.0` Distributed key-value store that holds Kubernetes cluster state. [Contributing guide](https://github.com/etcd-io/etcd/blob/main/CONTRIBUTING.md) · [Good first issues](https://github.com/etcd-io/etcd/issues?q=is%3Aissue%20is%3Aopen%20label%3A%22good%20first%20issue%22)
- [Helm](https://github.com/helm/helm) - `Apache-2.0` Package manager for Kubernetes. [Contributing guide](https://github.com/helm/helm/blob/main/CONTRIBUTING.md) · [Good first issues](https://github.com/helm/helm/issues?q=is%3Aissue%20is%3Aopen%20label%3A%22good%20first%20issue%22)
- [Istio](https://github.com/istio/istio) - `Apache-2.0` Service mesh for connecting and securing services. [Contributing guide](https://github.com/istio/istio/blob/master/CONTRIBUTING.md) · [Good first issues](https://github.com/istio/istio/issues?q=is%3Aissue%20is%3Aopen%20label%3A%22good%20first%20issue%22)
- [k3s](https://github.com/k3s-io/k3s) - `Apache-2.0` Lightweight Kubernetes distribution. [Contributing guide](https://github.com/k3s-io/k3s/blob/main/CONTRIBUTING.md) · [Good first issues](https://github.com/k3s-io/k3s/issues?q=is%3Aissue%20is%3Aopen%20label%3A%22kind/good-first-issue%22)
- [kind](https://github.com/kubernetes-sigs/kind) - `Apache-2.0` Runs local Kubernetes clusters inside Docker containers. [Contributing guide](https://github.com/kubernetes-sigs/kind/blob/main/CONTRIBUTING.md) · [Good first issues](https://github.com/kubernetes-sigs/kind/issues?q=is%3Aissue%20is%3Aopen%20label%3A%22good%20first%20issue%22)
- [Kubernetes](https://github.com/kubernetes/kubernetes) - `Apache-2.0` Container orchestration system. [Contributing guide](https://github.com/kubernetes/kubernetes/blob/master/CONTRIBUTING.md) · [Good first issues](https://github.com/kubernetes/kubernetes/issues?q=is%3Aissue%20is%3Aopen%20label%3A%22good%20first%20issue%22)
- [Moby](https://github.com/moby/moby) - `Apache-2.0` The open source project behind the Docker Engine. [Contributing guide](https://github.com/moby/moby/blob/master/CONTRIBUTING.md) · [Good first issues](https://github.com/moby/moby/issues?q=is%3Aissue%20is%3Aopen%20label%3A%22exp/beginner%22)

## 🌐 Networking & Infrastructure

*Servers, proxies, messaging and infrastructure as code.*

- [Caddy](https://github.com/caddyserver/caddy) - `Apache-2.0` Web server with automatic HTTPS. [Contributing guide](https://github.com/caddyserver/caddy/blob/master/.github/CONTRIBUTING.md) · [Good first issues](https://github.com/caddyserver/caddy/issues?q=is%3Aissue%20is%3Aopen%20label%3A%22good%20first%20issue%20%3Ababy_chick%3A%22)
- [gRPC-Go](https://github.com/grpc/grpc-go) - `Apache-2.0` The Go implementation of gRPC. [Contributing guide](https://github.com/grpc/grpc-go/blob/master/CONTRIBUTING.md)
- [NATS Server](https://github.com/nats-io/nats-server) - `Apache-2.0` Server for the NATS messaging system. [Contributing guide](https://github.com/nats-io/nats-server/blob/main/CONTRIBUTING.md) · [Good first issues](https://github.com/nats-io/nats-server/issues?q=is%3Aissue%20is%3Aopen%20label%3A%22good%20first%20issue%22)
- [OpenTofu](https://github.com/opentofu/opentofu) - `MPL-2.0` Open source infrastructure as code tool, a fork of Terraform. [Contributing guide](https://github.com/opentofu/opentofu/blob/main/CONTRIBUTING.md) · [Good first issues](https://github.com/opentofu/opentofu/issues?q=is%3Aissue%20is%3Aopen%20label%3A%22good%20first%20issue%22)
- [Tailscale](https://github.com/tailscale/tailscale) - `BSD-3-Clause` WireGuard-based private networking client and tools. [Contributing guide](https://github.com/tailscale/tailscale/blob/main/.github/CONTRIBUTING.md) · [Good first issues](https://github.com/tailscale/tailscale/issues?q=is%3Aissue%20is%3Aopen%20label%3A%22good%20first%20issue%22)
- [Temporal](https://github.com/temporalio/temporal) - `MIT` Server for running durable workflows. [Contributing guide](https://github.com/temporalio/temporal/blob/main/CONTRIBUTING.md) · [Good first issues](https://github.com/temporalio/temporal/issues?q=is%3Aissue%20is%3Aopen%20label%3A%22good%20first%20issue%22)
- [Traefik](https://github.com/traefik/traefik) - `MIT` Reverse proxy and load balancer for cloud-native apps. [Contributing guide](https://github.com/traefik/traefik/blob/master/CONTRIBUTING.md) · [Good first issues](https://github.com/traefik/traefik/issues?q=is%3Aissue%20is%3Aopen%20label%3A%22contributor/good-first-issue%22)
- [Vitess](https://github.com/vitessio/vitess) - `Apache-2.0` Clustering system for scaling MySQL horizontally. [Contributing guide](https://github.com/vitessio/vitess/blob/main/CONTRIBUTING.md) · [Good first issues](https://github.com/vitessio/vitess/issues?q=is%3Aissue%20is%3Aopen%20label%3A%22good%20first%20issue%22)

## 📈 Observability

*Metrics, tracing and telemetry.*

- [Jaeger](https://github.com/jaegertracing/jaeger) - `Apache-2.0` Distributed tracing platform. [Contributing guide](https://github.com/jaegertracing/jaeger/blob/main/CONTRIBUTING.md) · [Good first issues](https://github.com/jaegertracing/jaeger/issues?q=is%3Aissue%20is%3Aopen%20label%3A%22good%20first%20issue%22)
- [OpenTelemetry Go](https://github.com/open-telemetry/opentelemetry-go) - `Apache-2.0` OpenTelemetry API and SDK for Go. [Contributing guide](https://github.com/open-telemetry/opentelemetry-go/blob/main/CONTRIBUTING.md) · [Good first issues](https://github.com/open-telemetry/opentelemetry-go/issues?q=is%3Aissue%20is%3Aopen%20label%3A%22good%20first%20issue%22)
- [Prometheus](https://github.com/prometheus/prometheus) - `Apache-2.0` Monitoring system and time series database. [Contributing guide](https://github.com/prometheus/prometheus/blob/main/CONTRIBUTING.md) · [Good first issues](https://github.com/prometheus/prometheus/issues?q=is%3Aissue%20is%3Aopen%20label%3A%22good%20first%20issue%22)
- [Telegraf](https://github.com/influxdata/telegraf) - `MIT` Agent for collecting and sending metrics and logs. [Contributing guide](https://github.com/influxdata/telegraf/blob/master/CONTRIBUTING.md) · [Good first issues](https://github.com/influxdata/telegraf/issues?q=is%3Aissue%20is%3Aopen%20label%3A%22good%20first%20issue%22)

## 🔐 Security

*Secret scanning, vulnerability scanning and supply chain security.*

- [Cosign](https://github.com/sigstore/cosign) - `Apache-2.0` Signs and verifies container images and other artifacts. [Contributing guide](https://github.com/sigstore/cosign/blob/main/CONTRIBUTING.md) · [Good first issues](https://github.com/sigstore/cosign/issues?q=is%3Aissue%20is%3Aopen%20label%3A%22good%20first%20issue%22)
- [Gitleaks](https://github.com/gitleaks/gitleaks) - `MIT` Scans git repositories and files for hardcoded secrets. [Contributing guide](https://github.com/gitleaks/gitleaks/blob/master/CONTRIBUTING.md) · [Good first issues](https://github.com/gitleaks/gitleaks/issues?q=is%3Aissue%20is%3Aopen%20label%3A%22good%20first%20issue%22)
- [Grype](https://github.com/anchore/grype) - `Apache-2.0` Vulnerability scanner for container images and filesystems. [Contributing guide](https://github.com/anchore/grype/blob/main/CONTRIBUTING.md) · [Good first issues](https://github.com/anchore/grype/issues?q=is%3Aissue%20is%3Aopen%20label%3A%22good-first-issue%22)
- [Nuclei](https://github.com/projectdiscovery/nuclei) - `MIT` Template-based vulnerability scanner with a YAML DSL. [Contributing guide](https://github.com/projectdiscovery/nuclei/blob/dev/CONTRIBUTING.md) · [Good first issues](https://github.com/projectdiscovery/nuclei/issues?q=is%3Aissue%20is%3Aopen%20label%3A%22good%20first%20issue%22)
- [Syft](https://github.com/anchore/syft) - `Apache-2.0` Generates software bills of materials from images and filesystems. [Contributing guide](https://github.com/anchore/syft/blob/main/CONTRIBUTING.md) · [Good first issues](https://github.com/anchore/syft/issues?q=is%3Aissue%20is%3Aopen%20label%3A%22good-first-issue%22)
- [Trivy](https://github.com/aquasecurity/trivy) - `Apache-2.0` Scanner for vulnerabilities, misconfigurations and secrets. [Contributing guide](https://github.com/aquasecurity/trivy/blob/main/CONTRIBUTING.md) · [Good first issues](https://github.com/aquasecurity/trivy/issues?q=is%3Aissue%20is%3Aopen%20label%3A%22good%20first%20issue%22)
- [TruffleHog](https://github.com/trufflesecurity/trufflehog) - `AGPL-3.0` Finds leaked credentials and checks whether they are still valid. [Contributing guide](https://github.com/trufflesecurity/trufflehog/blob/main/CONTRIBUTING.md) · [Good first issues](https://github.com/trufflesecurity/trufflehog/issues?q=is%3Aissue%20is%3Aopen%20label%3A%22good%20first%20issue%22)

## 💻 Developer Tools

*Apps and CLIs that developers use every day.*

- [fzf](https://github.com/junegunn/fzf) - `MIT` Command-line fuzzy finder.
- [Gitea](https://github.com/go-gitea/gitea) - `MIT` Self-hosted Git service with code review and CI. [Contributing guide](https://github.com/go-gitea/gitea/blob/main/CONTRIBUTING.md) · [Good first issues](https://github.com/go-gitea/gitea/issues?q=is%3Aissue%20is%3Aopen%20label%3A%22good%20first%20issue%22)
- [GitHub CLI](https://github.com/cli/cli) - `MIT` GitHub's official command-line tool. [Contributing guide](https://github.com/cli/cli/blob/trunk/.github/CONTRIBUTING.md) · [Good first issues](https://github.com/cli/cli/issues?q=is%3Aissue%20is%3Aopen%20label%3A%22good%20first%20issue%22)
- [Glow](https://github.com/charmbracelet/glow) - `MIT` Renders Markdown in the terminal. [Contributing guide](https://github.com/charmbracelet/.github/blob/main/CONTRIBUTING.md) · [Good first issues](https://github.com/charmbracelet/glow/issues?q=is%3Aissue%20is%3Aopen%20label%3A%22good%20first%20issue%22)
- [Hugo](https://github.com/gohugoio/hugo) - `Apache-2.0` Static site generator. [Contributing guide](https://github.com/gohugoio/hugo/blob/master/CONTRIBUTING.md)
- [lazygit](https://github.com/jesseduffield/lazygit) - `MIT` Terminal UI for git commands. [Contributing guide](https://github.com/jesseduffield/lazygit/blob/master/CONTRIBUTING.md) · [Good first issues](https://github.com/jesseduffield/lazygit/issues?q=is%3Aissue%20is%3Aopen%20label%3A%22good%20first%20issue%22)
- [Ollama](https://github.com/ollama/ollama) - `MIT` Runs large language models locally. [Contributing guide](https://github.com/ollama/ollama/blob/main/CONTRIBUTING.md) · [Good first issues](https://github.com/ollama/ollama/issues?q=is%3Aissue%20is%3Aopen%20label%3A%22good%20first%20issue%22)

## 💾 Storage & Sync

*Backup, sync and file transfer.*

- [rclone](https://github.com/rclone/rclone) - `MIT` Syncs files to and from many cloud storage providers. [Contributing guide](https://github.com/rclone/rclone/blob/master/CONTRIBUTING.md) · [Good first issues](https://github.com/rclone/rclone/issues?q=is%3Aissue%20is%3Aopen%20label%3A%22good%20first%20issue%22)
- [restic](https://github.com/restic/restic) - `BSD-2-Clause` Encrypted, deduplicating backup program. [Contributing guide](https://github.com/restic/restic/blob/master/CONTRIBUTING.md) · [Good first issues](https://github.com/restic/restic/issues?q=is%3Aissue%20is%3Aopen%20label%3A%22help%3A%20good%20first%20issue%22)
- [Syncthing](https://github.com/syncthing/syncthing) - `MPL-2.0` Continuous peer-to-peer file synchronization. [Contributing guide](https://github.com/syncthing/syncthing/blob/main/CONTRIBUTING.md) · [Good first issues](https://github.com/syncthing/syncthing/issues?q=is%3Aissue%20is%3Aopen%20label%3A%22good%20first%20issue%22)

## 📦 Libraries & Frameworks

*Libraries many Go programs depend on.*

- [Bubble Tea](https://github.com/charmbracelet/bubbletea) - `MIT` Framework for building terminal user interfaces. [Contributing guide](https://github.com/charmbracelet/.github/blob/main/CONTRIBUTING.md) · [Good first issues](https://github.com/charmbracelet/bubbletea/issues?q=is%3Aissue%20is%3Aopen%20label%3A%22good%20first%20issue%22)
- [Chi](https://github.com/go-chi/chi) - `MIT` Lightweight HTTP router built on net/http. [Contributing guide](https://github.com/go-chi/chi/blob/master/CONTRIBUTING.md)
- [Cobra](https://github.com/spf13/cobra) - `Apache-2.0` Library for building command-line applications. [Contributing guide](https://github.com/spf13/cobra/blob/main/CONTRIBUTING.md) · [Good first issues](https://github.com/spf13/cobra/issues?q=is%3Aissue%20is%3Aopen%20label%3A%22good-first-issue%22)
- [Echo](https://github.com/labstack/echo) - `MIT` Minimalist web framework. [Good first issues](https://github.com/labstack/echo/issues?q=is%3Aissue%20is%3Aopen%20label%3A%22good%20first%20issue%22)
- [Fiber](https://github.com/gofiber/fiber) - `MIT` Express-inspired web framework. [Contributing guide](https://github.com/gofiber/fiber/blob/main/.github/CONTRIBUTING.md)
- [Gin](https://github.com/gin-gonic/gin) - `MIT` HTTP web framework. [Contributing guide](https://github.com/gin-gonic/gin/blob/master/CONTRIBUTING.md)
- [Viper](https://github.com/spf13/viper) - `MIT` Configuration library for Go applications. [Good first issues](https://github.com/spf13/viper/issues?q=is%3Aissue%20is%3Aopen%20label%3A%22good%20first%20issue%22)

## Suggest a Project

Know a Go project that welcomes contributors? Open a pull request following the [contribution guidelines](CONTRIBUTING.md). Projects must be open source (OSI-approved license), active, written mostly in Go and have a contributing guide.
