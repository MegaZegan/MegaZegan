# MegaZegan

Cybersecurity-focused developer building practical defensive tooling for SOC workflows, cloud security reviews, and secure development pipelines.

## Focus Areas

- Blue-team automation and detection engineering
- Log analysis, alert triage, and security reporting
- Cloud IAM policy review and least-privilege design
- Secret scanning and DevSecOps guardrails
- Python command-line tools with tests and CI

## Featured Security Projects

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

## Technical Stack

Python, CLI tooling, pytest, GitHub Actions, JSON/CSV log processing, IAM policy analysis, SARIF, defensive security automation.

## Current Direction

I am building a cybersecurity portfolio around practical blue-team engineering: tools that are safe to demo, easy to explain, and useful in real review workflows.
