# Awesome Tools

A curated list of tools and projects that I find interesting. Inclusion in this list does not necessarily indicate usage, endorsement, or recommendation.

## AI / Machine Learning

- [KServe](https://github.com/kserve/kserve) - A standardized, highly scalable machine learning model serving platform for Kubernetes that supports serverless, multi-framework deployments.
- [Kubeflow](https://www.kubeflow.org/) - A cloud-native platform designed to make deployments of machine learning workflows on Kubernetes simple, portable, and scalable.
- [Ollama](https://github.com/ollama/ollama) - Get up and running with large language models locally.
- [oMLX](https://github.com/jundot/omlx) - An open-source, high-performance LLM inference server optimized for Apple Silicon using the MLX framework. It features OpenAI- and Anthropic-compatible APIs and includes paged SSD caching to speed up Time to First Token (TTFT) for large context windows.
- [Open WebUI](https://github.com/open-webui/open-webui) - User-friendly AI Interface (Supports Ollama, OpenAI API, ...).
- [OpenClaw](https://github.com/openclaw/openclaw) - Your own personal AI assistant. Any OS. Any Platform.
- [Opencode](https://github.com/anomalyco/opencode) - The open source coding agent.
- [OpenLIT](https://github.com/openlit/openlit) - Open-source platform for AI engineering offering OpenTelemetry-native LLM observability, evaluations, and prompt management.
- [Pi](https://github.com/earendil-works/pi) - An open-source AI agent toolkit providing a unified LLM API, interactive TUI, agent loop, and coding agent CLI.
- [Zoo Code](https://github.com/Zoo-Code-Org/Zoo-Code) - An open-source AI-powered coding assistant and VS Code extension supporting autonomous development, custom workflow modes, and Model Context Protocol (MCP) integrations.

## Android

- [GrapheneOS](https://grapheneos.org/) - A security and privacy focused mobile OS with Android app compatibility.


## Cloud Desktop & OS

- [Atlas](https://github.com/Atlas-OS/Atlas) - An open-source modification for Windows 10 and 11 designed to optimize system performance, minimize latency, and improve privacy.
- [Kasm Workspaces](https://github.com/kasmtech/workspaces-issues) - A container streaming platform for delivering browser, desktop, and application workloads to the web browser.
- [Puter](https://github.com/HeyPuter/puter) - An advanced, open-source internet OS designed to run in the browser, featuring a feature-rich desktop environment and file management system.
- [Webtop](https://github.com/linuxserver/docker-webtop) - Linux in a web browser supporting popular desktop environments (Ubuntu, Alpine, Arch, and Fedora).


## Communication & Collaboration

- [Linkwarden](https://github.com/linkwarden/linkwarden) - Self-hosted collaborative bookmark manager to collect, read, annotate, and fully preserve what matters, all in one place.
- [Mattermost](https://github.com/mattermost/mattermost) - An open-source messaging platform for secure team collaboration and devops workflows.
- [Rocket.Chat](https://github.com/RocketChat/Rocket.Chat) - A highly customizable open source communications platform for team messaging, customer service, and community engagement.

## Databases

- [CloudNativePG](https://github.com/cloudnative-pg/cloudnative-pg) - A comprehensive platform designed to seamlessly manage PostgreSQL databases within Kubernetes environments, covering the entire operational lifecycle.
- [Greenmask](https://github.com/GreenmaskIO/greenmask) - Open-source utility for database anonymization, synthetic data generation, and logical dumps.
- [MariaDB Operator](https://github.com/mariadb-operator/mariadb-operator) - Run and operate MariaDB in a cloud native way.
- [OpenEverest](https://github.com/openeverest/openeverest) - An open-source platform for automated database provisioning and management on Kubernetes.
- [Supabase](https://github.com/supabase/supabase) - An open source Firebase alternative giving you a dedicated Postgres database to build your web, mobile, and AI applications.
- [SurrealDB](https://github.com/surrealdb/surrealdb) - A scalable, distributed, collaborative, document-graph database for the realtime web.
- [Vitess](https://github.com/vitessio/vitess) - A database clustering system for horizontal scaling of MySQL, allowing you to grow your database indefinitely.

## Development

### Application Platforms

- [Radius](https://github.com/radius-project/radius) - A cloud-native, portable application platform that makes app development easier for teams building cloud-native apps.

### Containers

- [Apple Container](https://github.com/apple/container) - A tool for creating and running Linux containers using lightweight virtual machines on a Mac, optimized for Apple silicon.
- [Buildah](https://github.com/containers/buildah) - A tool that facilitates building OCI images.
- [Harbor](https://github.com/goharbor/harbor) - An open source trusted cloud native registry project that stores, signs, and scans content.
- [Kaniko](https://github.com/chainguard-forks/kaniko) - A tool to build container images in Kubernetes without Docker daemon. This repository is a fork of [GoogleContainerTools/kaniko](https://github.com/GoogleContainerTools/kaniko) maintained by Chainguard. Another community fork is available at [osscontainertools/kaniko](https://github.com/osscontainertools/kaniko).
- [Nerdctl](https://github.com/containerd/nerdctl) - Docker-compatible CLI for containerd, with support for Compose, Rootless, eStargz, OCIcrypt, IPFS, and more.
- [ORAS](https://github.com/oras-project/oras) - OCI registry client - managing content like artifacts, images, packages.
- [Podman](https://github.com/containers/podman) - A tool for managing OCI containers and pods.
- [Rancher Desktop](https://github.com/rancher-sandbox/rancher-desktop) - Container Management and Kubernetes on the Desktop.


### Developer Portals

- [Backstage](https://github.com/backstage/backstage) - An open framework for building developer portals.

### Dotfile Management

- [chezmoi](https://github.com/twpayne/chezmoi) - Manage your dotfiles across multiple distinct machines, securely.

### Feature Flagging

- [Flagd](https://github.com/open-feature/flagd) - A feature flag daemon with a Unix philosophy that provides an HTTP or gRPC API for flag evaluation.
- [OpenFeature](https://github.com/open-feature/spec) - An open standard for feature flag management, providing a consistent API for developers. [Website](https://openfeature.dev)
- [Unleash](https://github.com/Unleash/unleash) - An open-source feature management platform that gives you a great overview of all feature toggles across all your applications and services.



### Frameworks

- [Flutter](https://github.com/flutter/flutter) - Flutter makes it easy and fast to build beautiful apps for mobile and beyond.

### GitHub Actions

- [Attest](https://github.com/actions/attest) - A GitHub Action for securely generating artifact attestations. It supports signing artifacts directly within workflows, enabling verified provenance.
- [Release Please Action](https://github.com/googleapis/release-please-action) - A GitHub Action that runs Release Please automatically within workflows. It provides a seamless way to create release proposals and manage automated versioning natively inside GitHub.
- [SBOM Action](https://github.com/anchore/sbom-action) - A GitHub Action that leverages Syft to generate a Software Bill of Materials (SBOM) for container images and directories. It integrates seamlessly into CI/CD pipelines to ensure continuous visibility of software dependencies.
- [SLSA GitHub Generator](https://github.com/slsa-framework/slsa-github-generator) - A utility for generating SLSA3+ provenance for native GitHub Actions. It provides highly reliable and tamper-proof build provenance out of the box.

### Package Management

- [Homebrew](https://github.com/Homebrew/brew) - The missing package manager for macOS (or Linux).
- [uv](https://github.com/astral-sh/uv) - An extremely fast Python package and project manager, written in Rust. It serves as a drop-in replacement for pip, pip-tools, and virtualenv.

### Release Management

- [Release Please](https://github.com/googleapis/release-please) - Automates Semantic Versioning and conventional commits for your repositories. It creates release Pull Requests, manages version bumps, and generates changelogs based on standard commit messages.

### Shell

- [iTerm2](https://github.com/gnachman/iTerm2) - iTerm2 is a terminal emulator for Mac OS X that does amazing things.
- [Nerd Fonts](https://github.com/ryanoasis/nerd-fonts) - Iconic font aggregator, collection, & patcher.
- [Oh My Zsh](https://github.com/ohmyzsh/ohmyzsh) - A delightful community-driven framework for managing your zsh configuration.
- [Starship](https://github.com/starship/starship) - The minimal, blazing-fast, and infinitely customizable prompt for any shell!

### Source Code Management

- [Gitea](https://github.com/go-gitea/gitea) - A painless self-hosted all-in-one software development service, including Git hosting, code review, team collaboration, package registry and CI/CD.

### Utilities

- [IT Tools](https://github.com/CorentinTh/it-tools) - Collection of handy online tools for developers, with great UX.

## Home

### Automation

- [Home Assistant](https://github.com/home-assistant/core) - Open source home automation that puts local control and privacy first.
- [Z-Wave JS UI](https://github.com/zwave-js/zwave-js-ui) - Full featured Z-Wave Control Panel UI and MQTT gateway.

### Inventory

- [Homebox](https://github.com/sysadminsmedia/homebox) - The inventory and organization system built for the Home User.

### Media

- [Immich](https://github.com/immich-app/immich) - High performance self-hosted photo and video management solution.
- [Jellyfin](https://github.com/jellyfin/jellyfin) - The Free Software Media System.

## Knowledge Management

- [HedgeDoc](https://github.com/hedgedoc/hedgedoc) - An open-source, web-based, real-time collaborative markdown editor. It allows teams to write and share documents, notes, and presentations with instant live preview.
- [Joplin](https://github.com/laurent22/joplin) - The privacy-focused note taking app with sync capabilities for Windows, macOS, Linux, Android and iOS.
- [Logseq](https://github.com/logseq/logseq) - A privacy-first, open-source platform for knowledge management and collaboration.
- [Open Notebook](https://github.com/lfnovo/open-notebook) - An open source implementation of Notebook LM with more flexibility and features.

## Kubernetes

### Autoscaling

- [KEDA](https://github.com/kedacore/keda) - A specialized Kubernetes autoscaler that drives the scaling of any container based on metrics from diverse external event sources, including queues, streams, and databases.

### Control Planes

- [Crossplane](https://github.com/crossplane/crossplane) - The Cloud Native Control Plane.
- [Kro](https://github.com/kubernetes-sigs/kro) - Kube Resource Orchestrator.

### Dashboards

- [Headlamp](https://github.com/kubernetes-sigs/headlamp) - A Kubernetes web UI that is fully-featured, user-friendly and extensible.

### Development Tools

- [Kompose](https://github.com/kubernetes/kompose) - A tool to convert Docker Compose files to Kubernetes orchestrators, making the migration process easier.

### GitOps & Continuous Delivery

- [Argo CD](https://github.com/argoproj/argo-cd) - Declarative Continuous Delivery for Kubernetes.
- [Flux](https://github.com/fluxcd/flux2) - Open and extensible continuous delivery solution for Kubernetes. Powered by GitOps Toolkit.
- [KubeVela](https://github.com/kubevela/kubevela) - A modern application delivery platform that makes deploying and operating applications across hybrid, multi-cloud environments easier, faster and more reliable.

### Networking

- [Cilium](https://github.com/cilium/cilium) - eBPF-based Networking, Security, and Observability solution for Kubernetes.

### Serverless

- [Knative Serving](https://github.com/knative/serving) - Kubernetes-based, scale-to-zero, request-driven compute platform that manages the lifecycle of your workloads.

### Service Mesh

- [Istio](https://github.com/istio/istio) - Connect, secure, control, and observe services.

## Messaging & Streaming

- [AutoMQ](https://github.com/AutoMQ/automq) - A diskless Kafka® on S3 offering 10x cost savings and scaling in seconds.
- [Strimzi](https://github.com/strimzi/strimzi-kafka-operator) - Apache Kafka® running on Kubernetes.

## Monitoring

- [Alloy](https://github.com/grafana/alloy) - OpenTelemetry Collector distribution with programmable pipelines.
- [Beyla](https://github.com/grafana/beyla) - eBPF-based autoinstrumentation of web applications and network metrics.
- [Blackbox Exporter](https://github.com/prometheus/blackbox_exporter) - Blackbox prober exporter for Prometheus.
- [Grafana](https://github.com/grafana/grafana) - The open and composable observability and data visualization platform.
- [Loki](https://github.com/grafana/loki) - Like Prometheus, but for logs.
- [Mimir](https://github.com/grafana/mimir) - Provides horizontally scalable, highly available, multi-tenant, long-term storage for Prometheus.
- [OpenTelemetry](https://github.com/open-telemetry/opentelemetry-specification) - Specifications for OpenTelemetry, an observability framework for cloud-native software.
- [Pyroscope](https://github.com/grafana/pyroscope) - Continuous Profiling Platform. Debug performance issues down to a single line of code.
- [Sloth](https://github.com/slok/sloth) - Easy and simple Prometheus SLO (service level objectives) generator.
- [Tempo](https://github.com/grafana/tempo) - A high volume, minimal dependency distributed tracing backend.
- [Uptime Kuma](https://github.com/louislam/uptime-kuma) - A fancy self-hosted monitoring tool that supports various notification types and monitoring protocols.

## Networking

- [Firezone](https://github.com/firezone/firezone) - Enterprise-ready zero-trust access platform built on WireGuard.
- [NetBird](https://github.com/netbirdio/netbird) - Connect your devices into a secure WireGuard-based overlay network with SSO, MFA and granular access controls. Like a self-hosted Tailscale.
- [Netmaker](https://github.com/gravitl/netmaker) - Automates fast, secure, and distributed virtual networks using WireGuard.
- [OPNsense](https://github.com/opnsense/core) - An open source, easy-to-use and easy-to-build firewall and routing platform. Forked from pfSense.
- [Pangolin](https://github.com/fosrl/pangolin) - Identity-aware VPN and reverse proxy for remote access.
- [Wiredoor](https://github.com/wiredoor/wiredoor) - Self-hosted ingress-as-a-service platform that allows you to expose applications and services running in private or local networks to the internet.

## Personal Tools

### Finance

- [Sure](https://github.com/we-promise/sure) - The personal finance app for everyone.

### Location & Travel

- [AirTrail](https://github.com/johanohly/AirTrail) - An open-source, self-hosted personal flight tracking system to visualize flights on interactive maps, import flight logs, and view travel statistics.
- [Dawarich](https://github.com/Freika/dawarich) - An open-source, self-hosted location tracking web application and Google Timeline alternative for visualizing location history and trips.


## Search Engines

- [SearXNG](https://github.com/searxng/searxng) - A free internet metasearch engine which aggregates results from various search services and databases without tracking or profiling users.

## Security

- [Coraza](https://github.com/corazawaf/coraza) - OWASP Coraza WAF is a golang modsecurity compatible web application firewall library.
- [CrowdSec](https://github.com/crowdsecurity/crowdsec) - The open-source and participative security solution offering crowdsourced protection against malicious IPs.
- [Falco](https://github.com/falcosecurity/falco) - Cloud Native Runtime Security tool that detects anomalous behavior at the application, container, host, and network levels.
- [Kubescape](https://github.com/kubescape/kubescape) - Open-source Kubernetes security platform for risk analysis, security compliance, CI/CD scanning, and image vulnerability scanning.
- [Kubeshark](https://github.com/kubeshark/kubeshark) - API traffic analyzer for Kubernetes offering real-time, protocol-level visibility into K8s internal network traffic.
- [Prowler](https://github.com/prowler-cloud/prowler) - Open-source cloud security platform that automates security and compliance across any cloud environment.
- [Tetragon](https://github.com/cilium/tetragon/) - eBPF-based security observability and runtime enforcement tool, capable of detecting and restricting malicious activity in real-time.
- [Tracee](https://github.com/aquasecurity/tracee) - Linux Runtime Security and Forensics tool using eBPF to trace and analyze events in the system.
- [Wazuh](https://github.com/wazuh/wazuh) - The Open Source Security Platform providing unified XDR and SIEM protection for endpoints and cloud workloads.

### Encryption

- [Cryptomator](https://github.com/cryptomator/cryptomator) - Secure client-side encryption for your cloud storage, ensuring privacy and control over your data.

### Identity & Access Management

- [Authelia](https://github.com/authelia/authelia) - The Single Sign-On Multi-Factor portal for web apps.
- [Dex](https://github.com/dexidp/dex) - OpenID Connect (OIDC) identity and OAuth 2.0 provider with pluggable connectors.
- [LLDAP](https://github.com/lldap/lldap) - Light LDAP implementation for authentication.
- [OAuth2 Proxy](https://github.com/oauth2-proxy/oauth2-proxy) - A reverse proxy that provides authentication with Google, Azure, OpenID Connect and many more identity providers.

### Password Managers

- [Vaultwarden](https://github.com/dani-garcia/vaultwarden) - An unofficial Bitwarden compatible server written in Rust, perfect for self-hosting password management.

### Pentesting

- [Shannon](https://github.com/KeygraphHQ/shannon) - Fully autonomous AI hacker to find actual exploits in your web apps.

### Personal Security

- [Personal Security Checklist](https://github.com/lissy93/personal-security-checklist) - A compiled checklist of 300+ tips for protecting digital security and privacy.

### Secrets Management

- [Infisical](https://github.com/Infisical/infisical) - Open source secret management platform with Privileged Access Management (PAM) and certificate management (PKI) to help teams sync secrets across their development lifecycle and infrastructure.
- [OpenBao](https://github.com/openbao/openbao) - Open source secret management software for managing secrets and protecting sensitive data, created as a fork of HashiCorp Vault.

### SLSA

- [Cosign](https://github.com/sigstore/cosign) - A widely-used tool for container signing, verification, and storage in an OCI registry. Cosign supports keyless signing using OpenID Connect, making it simple to secure software artifacts.
- [Fulcio](https://github.com/sigstore/fulcio) - A free code signing Certificate Authority (CA) built to make short-lived certificates accessible to everyone. It issues temporary certificates based on an OpenID Connect identity, eliminating the need to manage long-term signing keys.
- [Rekor](https://github.com/sigstore/rekor) - A secure software supply chain transparency log. It uses an immutable, tamper-resistant ledger to record metadata generated throughout the software supply chain.
- [Syft](https://github.com/anchore/syft) - A CLI tool and library for creating a comprehensive Software Bill of Materials (SBOM) from container images and filesystems. It provides deep visibility into packages and dependencies, aiding in vulnerability management.

## Static Site Generators

- [Hugo](https://github.com/gohugoio/hugo) - The world’s fastest framework for building websites, offering amazing speed and flexibility.

## Storage

### Backups

- [Kopia](https://github.com/kopia/kopia) - Cross-platform backup tool for Windows, macOS & Linux with fast, incremental backups, client-side end-to-end encryption, compression and data deduplication.

### File Sharing & Management

- [Filebrowser](https://github.com/filebrowser/filebrowser) - A web-based file manager that allows you to manage your files within a specified directory on your server from any browser.
- [LocalSend](https://github.com/localsend/localsend) - An open-source cross-platform alternative to AirDrop.
- [Nextcloud](https://github.com/nextcloud/server) - A safe home for all your data, providing a collaborative platform for file hosting, sharing, and productivity.
- [OpenCloud](https://github.com/opencloud-eu/opencloud) - An open source platform for file management, sharing, and collaboration that focuses on simplicity and data sovereignty.
- [Rclone](https://github.com/rclone/rclone) - "rsync for cloud storage", a command-line program to manage files on various cloud storage providers.
- [Seafile](https://github.com/haiwen/seafile) - A high-performance file syncing and sharing solution that extends beyond basic storage with flexible file organization and views.
- [Syncthing](https://github.com/syncthing/syncthing) - Open source continuous file synchronization program.

### Infrastructure

- [Ceph](https://github.com/ceph/ceph) - A distributed object, block, and file storage platform designed for scalability, reliability, and performance.
- [Rook](https://github.com/rook/rook) - An open source cloud-native storage orchestrator for Kubernetes, providing platform, framework, and support for a diverse set of storage solutions to natively integrate with cloud-native environments.
- [RustFS](https://github.com/rustfs/rustfs) - An open-source, S3-compatible high-performance object storage system supporting migration and coexistence with other S3-compatible platforms.
- [SeaweedFS](https://github.com/seaweedfs/seaweedfs) - A fast distributed storage system for blobs, objects, files, and data lake, designed to store billions of files efficiently.

## Virtualization

- [KubeVirt](https://github.com/kubevirt/kubevirt) - Kubernetes Virtualization API and runtime in order to define and manage virtual machines, using KVM under the hood.
- [Proxmox](https://www.proxmox.com/en/) - Develops powerful and efficient open-source server solutions like the Proxmox VE platform, Proxmox Backup Server, and Proxmox Mail Gateway.
- [XCP-ng](https://github.com/xcp-ng/xcp) - An open-source virtualization platform and hypervisor based on XenServer.

## Web Analytics

- [Plausible](https://github.com/plausible/analytics) - Simple, open source, lightweight and privacy-friendly web analytics alternative to Google Analytics.
- [PostHog](https://github.com/PostHog/posthog) - An all-in-one developer platform for building successful products, offering product analytics, web analytics, session replay, and more.
- [Umami](https://github.com/umami-software/umami) - A modern, privacy-focused analytics platform. An open-source alternative to Google Analytics, Mixpanel and Amplitude.
