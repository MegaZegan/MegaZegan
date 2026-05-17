# MegaZegan

Cybersecurity-focused developer building practical defensive tooling for SOC workflows, cloud security reviews, and secure development pipelines.

## Focus Areas

- Blue-team automation and detection engineering
- Log analysis, alert triage, and security reporting
- Cloud IAM policy review and least-privilege design
- Secret scanning and DevSecOps guardrails
- Python command-line tools with tests and CI

## Featured Security Projects

### [TraceLens](https://github.com/MegaZegan/TraceLens)

Defensive log triage CLI for suspicious authentication, firewall, DNS, and outbound traffic patterns.

- Finds login-success-after-failures, denied connection sweeps, suspicious DNS labels, and large outbound transfers.
- Works against local CSV/JSONL telemetry, so it is safe to demo in interviews without touching real targets.
- Built as a clean Python package with pytest coverage and GitHub Actions.

### [SentinelForge](https://github.com/MegaZegan/SentinelForge)

Defensive SOC analytics toolkit for log normalization, detection rules, risk scoring, and HTML reports.

- Detects brute force attempts, impossible travel, privilege escalation, web probing, IOC matches, and possible exfiltration.
- Includes synthetic demo logs, configurable thresholds, and an analyst-friendly report generator.
- Built with Python, pytest, and GitHub Actions.

### [CloudPolicyLens](https://github.com/MegaZegan/CloudPolicyLens)

IAM-style cloud policy linter for risky permissions and weak security guardrails.

- Flags wildcard administrator access, public principals, risky `iam:PassRole`, sensitive actions, and broad `NotAction` policies.
- Produces explainable findings with remediation guidance.
- Designed for cloud security reviews and CI checks.

### [SecretHawk](https://github.com/MegaZegan/SecretHawk)

Local defensive secret scanner with masked findings, entropy checks, allowlist comments, and SARIF output.

- Detects common token patterns and high-entropy secrets before they reach production.
- Masks sensitive values by default to avoid leaking secrets in logs.
- Supports JSON and SARIF output for automation.

## Creative & Coding Projects

### [PipBoy-3000-Interface](https://github.com/MegaZegan/PipBoy-3000-Interface)

Retro Fallout-inspired Pip-Boy interface with inventory, map, radio, status panels, themes, and responsive UI polish.

- Live demo: [megazegan.github.io/PipBoy-3000-Interface](https://megazegan.github.io/PipBoy-3000-Interface/)
- Shows frontend creativity, theming, animation, and GitHub Pages deployment.

### [AlgoKit-Lite](https://github.com/MegaZegan/AlgoKit-Lite)

Small Python algorithms and data-structure toolkit with CLI demos and tests.

- Includes sorting, searching, graph shortest path, LRU cache, and text utilities.
- Shows general coding fundamentals next to the cybersecurity tools.

## Technical Stack

Python, CLI tooling, pytest, GitHub Actions, JSON/CSV log processing, IAM policy analysis, SARIF, HTML, CSS, JavaScript, responsive UI, defensive security automation.

## Current Direction

I am building a cybersecurity portfolio around practical blue-team engineering: tools that are safe to demo, easy to explain, and useful in real review workflows.
