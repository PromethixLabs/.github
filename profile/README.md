# Promethix Labs

Promethix Labs is a small engineering group for software, infrastructure, automation, and platform projects.

We work on practical tools and systems across application development, platform engineering, hosting, operations, and developer experience. Some of that work is published as open source, including .NET libraries, Kubernetes tooling, Helm charts, and release/provenance utilities.

Public open-source projects from Promethix Labs are intended to remain open and usable by the community.

## Projects

| Project | Focus | Notes |
| --- | --- | --- |
| [AdoScope](https://github.com/PromethixLabs/Promethix.Framework.Ado) | ADO.NET / Dapper data access | Project name for the `Promethix.Framework.Ado` C# library. Provides scoped connection and transaction lifecycle management for applications that need explicit persistence boundaries. |
| [Promethix.Operator.CloudflareRouter](https://github.com/PromethixLabs/Promethix.Operator.CloudflareRouter) | Kubernetes / Cloudflare Tunnel | Declarative route lifecycle management for publishing services through Cloudflare Tunnels. |
| [Promethix Helm Charts](https://github.com/PromethixLabs/charts) | Helm / Kubernetes packaging | Public Helm chart repository for Promethix Labs components. |

> **AdoScope in production**  
> The `Promethix.Framework.Ado` library is used in large enterprise .NET systems and built around production-proven data-access patterns where transaction correctness, maintainability, and operational clarity matter.

## Engineering principles

- Explicit, reviewable architecture
- Production-grade defaults
- Security and operational safety first
- Supply-chain transparency where it adds value
- Small, composable tools over large frameworks

## Supply-chain and release transparency

Where practical, Promethix projects publish checksums, SBOMs, and provenance material for release artefacts.

## Links

- Maintainer: [gentoorax](https://github.com/gentoorax)
- CV: [chrislaw.dev/cv](https://chrislaw.dev/cv)
- Trust and provenance: [trust.promethix.dev](https://trust.promethix.dev)
