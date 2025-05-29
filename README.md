# 🛡️ crowdstrike-ops

Operational playbooks, deployment guides, and automation tooling for CrowdStrike Falcon — covering agent installation, CLI queries, detection response workflows, and multi-platform management.

## 📌 Purpose

This repo serves as a practical reference for working with CrowdStrike Falcon in a hands-on, security operations context. It focuses on:

- Deploying Falcon agents across multiple OS platforms
- Using the Falcon CLI for investigation and response
- Writing detection-response SOPs
- Integrating CrowdStrike into your broader security stack

Whether you're an aspiring SOC analyst, security engineer, or platform operator, this repo will sharpen your CrowdStrike readiness.

## 🧱 Folder Structure

| Folder                | Description                                              |
|-----------------------|----------------------------------------------------------|
| `agent-deployment/`   | Install scripts, silent install flags, and platform notes|
| `falcon-cli/`         | Falcon sensor CLI usage and real-world examples         |
| `detection-response/` | Mock detection scenarios and triage workflows           |
| `integration-guides/` | Forwarding Falcon data into SIEMs, Splunk, etc.         |
| `hardening-baselines/`| Pre-agent OS hardening tips by OS                       |
| `audit-scripts/`      | Scripts to validate agent status and coverage           |
| `references/`         | Falcon API docs, threat links, and lab environment tips |

## ⚙️ Covered Topics

- ✅ Installing the Falcon sensor across Linux, Windows, macOS
- ✅ CLI commands to inspect, isolate, or check agent behavior
- ✅ Detection triage: What to check first
- ✅ Falcon API awareness and reporting
- ✅ Integration with SIEM or logging pipelines (CloudTrail, etc.)
- ✅ Writing response checklists and escalation SOPs
- ✅ Mass-agent audit across hybrid environments

## 🛠️ Tools & Languages

- Bash / PowerShell
- Falcon CLI
- JSON APIs
- Python (optional for future automation)

## 💼 Use Cases

- Internal SOC toolkits
- Interview take-home projects
- Lab-based CrowdStrike exposure
- Cross-team onboarding guide for Falcon

## 🚀 Roadmap

- [ ] Add mass agent status collection script
- [ ] Create a simulated alert + investigation walkthrough
- [ ] Document Falcon API token usage and Python integration
- [ ] Add SIEM forwarding example (Splunk, Sentinel)

## 🔐 Note

No sensitive information is stored or implied in this repository. This repo is educational and lab-focused only.

## 🤝 Contributions

Security-minded collaborators welcome! Submit real-world use cases, CLI snippets, or Falcon integration notes via PR.

