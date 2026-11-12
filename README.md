# Awesome Cyber Resilience Act [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of resources, tools and guides for the EU Cyber Resilience Act (CRA, Regulation (EU) 2024/2847) — the regulation that makes cybersecurity mandatory for products with digital elements sold in the EU.

**Key dates:** entered into force 10 Dec 2024 · reporting obligations apply from **11 Sep 2026** · full application from **11 Dec 2027**.

## Contents

- [Official Sources](#official-sources)
- [Getting Started](#getting-started)
- [Guides](#guides)
- [Tools](#tools)
- [SBOM Standards & Tooling](#sbom-standards--tooling)
- [Community](#community)
- [Contributing](#contributing)

## Official Sources

- [Regulation (EU) 2024/2847 — EUR-Lex](https://eur-lex.europa.eu/eli/reg/2024/2847/oj) - The official regulation text.
- [European Commission — CRA overview](https://digital-strategy.ec.europa.eu/en/policies/cyber-resilience-act) - Policy page with background and updates.
- [ENISA](https://www.enisa.europa.eu/) - The EU cybersecurity agency receiving vulnerability and incident notifications under the CRA.

## Getting Started

- [Free CRA scope checker](https://nordchecks.com) - Answer 9 questions to learn whether the CRA applies to your product, your risk class and your deadlines. No signup.
- [CRA deadlines explained](https://nordchecks.com/guides/cra-deadlines-explained) - What applies on 11 September 2026 vs 11 December 2027.
- [Does the CRA apply to SaaS?](https://nordchecks.com/guides/does-the-cra-apply-to-saas) - Where the line runs for cloud services, apps, agents and on-prem software.

## Guides

- [CRA compliance checklist for small manufacturers](https://nordchecks.com/guides/cra-compliance-checklist) - Step-by-step obligations before both deadlines.
- [What is an SBOM (and how to create one without a DevOps team)](https://nordchecks.com/guides/what-is-an-sbom) - Plain-language SBOM guide incl. firmware.
- [CRA for IoT startups](https://nordchecks.com/guides/cra-for-iot-startups) - Practical plan for small connected-hardware teams.
- [CRA for machine builders](https://nordchecks.com/guides/cra-for-machine-builders) - How the CRA stacks on CE marking and the Machinery Regulation.

## Tools

- [Nordchecks](https://nordchecks.com/product) - CRA compliance tool for small teams: SBOM, daily vulnerability monitoring, 24h reporting setup and technical documentation.
- [sbomify](https://sbomify.com) - SBOM management and sharing platform with CRA workflows.
- [Dependency-Track](https://dependencytrack.org) - OWASP open-source component analysis platform.
- [OSV.dev](https://osv.dev) - Open vulnerability database with a free API for matching components against known CVEs.
- [fixdossier](https://github.com/itulo/fixdossier) - Open-source GitHub Action that builds a dated security-fix record and a SUPPORT.md support-period policy from GitHub history.

## SBOM Standards & Tooling

- [CycloneDX](https://cyclonedx.org) - OWASP SBOM standard, JSON-first, widely used for CRA purposes.
- [SPDX](https://spdx.dev) - Linux Foundation SBOM standard (ISO/IEC 5962).
- [Syft](https://github.com/anchore/syft) - Open-source SBOM generator for projects and container images.
- [Grype](https://github.com/anchore/grype) - Open-source vulnerability scanner for SBOMs and images.

## Community

- [r/EUCyberResilienceAct](https://www.reddit.com/r/EUCyberResilienceAct/) - Subreddit dedicated to the CRA.
- [r/CRACompliance](https://www.reddit.com/r/CRACompliance/) - Practical CRA compliance discussion.

## Contributing

Contributions welcome! Add resources via pull request — one link per line, format: `[Name](url) - Short description.` Keep it vendor-neutral: tools from any provider are welcome if they genuinely help with CRA compliance.

*Maintained by [Nordchecks](https://nordchecks.com).*
