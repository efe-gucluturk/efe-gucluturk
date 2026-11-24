<div align="center">

# Efe Güçlütürk

**Cybersecurity Engineer** · Offensive Security, AppSec & Detection Engineering

![Offensive Security](https://img.shields.io/badge/Offensive_Security-0d1117?style=flat-square&labelColor=0d1117&color=f85149)
![AppSec](https://img.shields.io/badge/AppSec-0d1117?style=flat-square&labelColor=0d1117&color=58a6ff)
![DevSecOps](https://img.shields.io/badge/DevSecOps-0d1117?style=flat-square&labelColor=0d1117&color=3fb950)
![Detection Engineering](https://img.shields.io/badge/Detection_Engineering-0d1117?style=flat-square&labelColor=0d1117&color=d29922)

</div>

---

I build security tooling that is itself hardened: scanners, detection engines and recon platforms where the
attack surface of the tool is treated as seriously as the attack surface it analyses.

## The Vigil Security Suite

Three Python tools covering detection, code/repo hygiene and external recon.

| Project | What it does | Domain |
|---|---|---|
| [**VigilSIEM**](https://github.com/efe-gucluturk/vigilsiem) | Secure-by-design mini-SIEM. Ingests logs via authenticated API and a tailing agent, normalizes SSH/nginx/JSON events, detects with declarative YAML rules, time-window correlation and rolling-baseline anomaly scoring, and tags alerts with MITRE ATT&CK. | Blue Team / SOC |
| [**GitVigil**](https://github.com/efe-gucluturk/gitvigil) | Scans full Git history for leaked secrets and IaC misconfigurations, including deleted commits and dangling blobs. Secrets are redacted by default; supports ignore files and `--fail-on` gating. | DevSecOps / AppSec |
| [**ReconVigil**](https://github.com/efe-gucluturk/reconvigil) | Attack surface management and web recon: CT/wordlist subdomain discovery, SPF/DMARC and TLS/header audit, subdomain takeover fingerprints, exposed-file checks, and drift tracking between scans. Strict scope enforcement and SSRF guarding. | Offensive Recon |

## Core Engineering Principles

- **Secure-by-Design** — fail-closed configuration, least-privilege containers (non-root, dropped capabilities), no `eval`/`pickle`/`shell=True`, `yaml.safe_load` only.
- **Zero-Trust Input Validation** — strict schemas (`extra="forbid"`, bounded lengths), streaming body caps, SSRF defences with IP pinning, escaped report output.
- **SAST / CI Automation** — ruff, bandit and tests enforced in GitHub Actions on every change.
- **Adversarial Testing** — attack simulators and deterministic offline tests that exercise the failure modes the tools are built to catch.

## Technical Arsenal

![Python](https://img.shields.io/badge/Python-0d1117?style=flat-square&logo=python&logoColor=3776AB)
![FastAPI](https://img.shields.io/badge/FastAPI-0d1117?style=flat-square&logo=fastapi&logoColor=009688)
![Linux](https://img.shields.io/badge/Linux-0d1117?style=flat-square&logo=linux&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-0d1117?style=flat-square&logo=docker&logoColor=2496ED)
![OWASP Top 10](https://img.shields.io/badge/OWASP_Top_10-0d1117?style=flat-square&logo=owasp&logoColor=white)
![MITRE ATT&CK](https://img.shields.io/badge/MITRE_ATT%26CK-0d1117?style=flat-square&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-0d1117?style=flat-square&logo=githubactions&logoColor=2088FF)

## GitHub Stats

<div align="center">

[![GitHub Stats](https://github-readme-stats.vercel.app/api?username=efe-gucluturk&show_icons=true&theme=tokyonight&hide_border=true)](https://github.com/efe-gucluturk)
[![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=efe-gucluturk&layout=compact&theme=tokyonight&hide_border=true)](https://github.com/efe-gucluturk?tab=repositories)

</div>

If the cards do not render, see [repositories](https://github.com/efe-gucluturk?tab=repositories) and [contribution activity](https://github.com/efe-gucluturk).
