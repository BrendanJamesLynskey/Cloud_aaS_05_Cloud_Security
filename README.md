# 🛡 Cloud Security in Depth

Deck **05 of 6** in the [Cloud `*aaS` series](https://github.com/BrendanJamesLynskey/Cloud_aaS_Hub). The cross-cutting security disciplines for *aaS — identity (IAM, STS, federation), secrets &amp; encryption (KMS, HSM, BYOK, confidential compute), network security (PrivateLink, mTLS, zero trust), supply chain (SBOM, SLSA, Sigstore), compliance (SOC 2, ISO 27001, HIPAA, GDPR, PCI, FedRAMP, EU AI Act, DORA), detection &amp; response, and a tour of the past decade's defining incidents.

## ▶ [Open the Presentation](https://brendanjameslynskey.github.io/Cloud_aaS_05_Cloud_Security/)

## 🧭 [Series hub](https://github.com/BrendanJamesLynskey/Cloud_aaS_Hub)

---

## Contents

| # | Topic | Description |
|---|-------|-------------|
| 01 | Title | Identity → Secrets → Network → Encrypt → Audit |
| 02 | Topics | Identity / secrets / network / supply chain / compliance |
| 03 | Shared responsibility — in detail | Always-yours, always-theirs, S3 worked example, where most breaches happen |
| 04 | IAM core | Principal / STS / policy evaluator / resource — diagram + evaluation rules |
| 05 | STS &amp; federation | Humans (SSO), in-cloud workloads (IRSA, Pod Identity, Workload Identity, Managed Identity), CI via OIDC |
| 06 | Least privilege | Iterative tightening, conditions that punch above their weight, just-in-time access |
| 07 | Secrets — KMS / HSM / Vault | Tool comparison, envelope encryption, BYOK / HYOK / external key stores |
| 08 | Encryption | At rest (SSE-KMS, CMEK), in transit (TLS 1.3, mTLS), in use (Nitro Enclaves, SEV-SNP, TDX, confidential GPUs) |
| 09 | Network security | Service mesh, PrivateLink, WAF / DDoS, egress lockdown, DNS leaks |
| 10 | Zero trust | NIST 800-207 tenets, BeyondCorp lineage, IAP pattern, replacing the VPN |
| 11 | Supply chain | SBOM (SPDX, CycloneDX), SLSA levels, Sigstore (Cosign / Fulcio / Rekor), dependency-confusion |
| 12 | Container &amp; image security | Image-side, runtime-side, micro-VM isolation (Firecracker, gVisor, Kata), admission policy |
| 13 | Compliance frameworks | SOC 2 / ISO 27001 / HIPAA / GDPR / PCI / FedRAMP / EU AI Act / DORA — table |
| 14 | Detection &amp; SIEM | GuardDuty / Defender / SCC, Splunk / Sentinel / Datadog, detection-as-code, SOAR |
| 15 | Real incidents | Capital One, SolarWinds, Codecov, Okta HAR, MOVEit, Snowflake, XZ Utils, Storm-0558 |
| 16 | Anti-patterns | Public DB ports, optional MFA, static keys, off-CloudTrail, wildcard IAM, end-of-sprint security |
| 17 | Summary | Three takeaways &amp; next-deck pointer |

---

## Slide Controls

| Action | Key |
|--------|-----|
| Next / Previous | `→` `←` or swipe |
| Overview | `Esc` |
| Fullscreen | `F` |
| Speaker notes | `S` |
| Export to PDF | append `?print-pdf` to URL, then print |

## Technology

[Reveal.js 4.6](https://revealjs.com) · [highlight.js](https://highlightjs.org) · Playfair Display + DM Sans + JetBrains Mono · inline SVG diagrams. Single self-contained `index.html`.

## See also

- [Docker Security](https://github.com/BrendanJamesLynskey/Docker_Security) — the container-image security companion
- [Introduction to OAuth](https://github.com/BrendanJamesLynskey/Introduction_to_OAuth) — the auth foundation
- [OAuth for MCP](https://github.com/BrendanJamesLynskey/OAuth_for_MCP) — the providers tour
- [Introduction to Web Authentication](https://github.com/BrendanJamesLynskey/Introduction_to_Web_Authentication) — sessions, JWTs, MFA
- [Introduction to CI/CD](https://github.com/BrendanJamesLynskey/Introduction_to_CI_CD) — pipelines and secure delivery
- Previous in series: [Cloud_aaS_04_SaaS_Architecture](https://github.com/BrendanJamesLynskey/Cloud_aaS_04_SaaS_Architecture)
- Next in series: [Cloud_aaS_06_LLM_aaS](https://github.com/BrendanJamesLynskey/Cloud_aaS_06_LLM_aaS) — managed LLM services and their new security shapes

## License

Educational use. Code examples provided as-is.
