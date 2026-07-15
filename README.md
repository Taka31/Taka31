# Cyril Menard

**Tech Lead & Software Architect** — Java & Spring Boot microservices, delivery engineering, AI-assisted operations.
Madrid, Spain · 15+ years in software engineering · I work in French, English and Spanish every day.

I design distributed systems and stay technically hands-on — from the architectural patterns down to the pipelines that ship them. I currently lead the transversal core team of an industrial microservices platform deployed across five regions, where I also took ownership of the delivery chain and rebuilt it end to end.

## What I actually do

**Architecture.** Microservices and event-driven design, API gateways, resilience patterns, and the progressive decomposition of a legacy monolith using a strangler fig approach. Java 21, Spring Boot 3, WebFlux, Hibernate/JPA. Kafka in production for notifications and document generation.

**Delivery engineering.** Where most of my energy goes. I took over a fragile delivery chain and rebuilt it end to end: CI/CD pipelines, tagging and versioning strategy, GitOps release flow with ArgoCD, and the platform's first automated test suite. Quality and security gates live inside the pipeline — SonarQube, Fortify (SAST), SCA dependency scanning. Currently pushing a continuous-release model to replace multi-month release cycles.

**AI-assisted delivery.** I built a release-manager MCP server (TypeScript, ~15 typed tools) that drives a full release cycle from chat: release branches across repos, image promotion, git tags, and one ArgoCD pull request per region.

It is deliberately a thin orchestration layer — it dispatches the existing audited pipelines rather than reimplementing CI, so the trace of every mutation stays where it belongs. Designed with an AI-safety posture: strict read/write separation, no direct git or GitOps writes, a defensive deny-list enforcing the immutable image lifecycle, and mandatory double confirmation for production. It is not an autonomous agent, by design — it tools the release manager, it does not replace them.

**Cloud-native (Azure, application level).** Kubernetes, Key Vault and secrets management, Azure DevOps, Docker, JFrog Artifactory, monitoring with Datadog. Security as a first-class concern: Spring Security, OAuth2/JWT, RBAC via Keycloak and Entra ID, OWASP.

## Currently learning

CKA (Certified Kubernetes Administrator), and infrastructure-as-code.

## Elsewhere

[LinkedIn](https://www.linkedin.com/in/cyril-menard-949246b5/)
