# Defensive Security Engineering Portfolio

I build small, reproducible security tools that favor **authorization, read-only defaults, synthetic fixtures, and deterministic tests**. This profile documents hands-on work across Windows security diagnostics, secure software development, detection engineering, and incident response.

## Featured projects

| Project | What it demonstrates | Status |
|---|---|---|
| [Windows Driver Policy Auditor](https://github.com/Ildosoft/windows-driver-policy-auditor) | Read-only Windows Code Integrity diagnostics, offline XML analysis, structured findings, and HTML reporting | [![CI](https://github.com/Ildosoft/windows-driver-policy-auditor/actions/workflows/ci.yml/badge.svg)](https://github.com/Ildosoft/windows-driver-policy-auditor/actions/workflows/ci.yml) |
| [SecurePatch Lab](https://github.com/Ildosoft/securepatch-lab) | Regression-tested fixes for common application-security defects plus deterministic SBOM generation | [![CI](https://github.com/Ildosoft/securepatch-lab/actions/workflows/ci.yml/badge.svg)](https://github.com/Ildosoft/securepatch-lab/actions/workflows/ci.yml) |
| [Detection Engineering Lab](https://github.com/Ildosoft/detection-engineering-lab) | Sigma and YARA artifacts, ATT&CK mapping, synthetic positive/negative telemetry, and rule regression tests | [![CI](https://github.com/Ildosoft/detection-engineering-lab/actions/workflows/ci.yml/badge.svg)](https://github.com/Ildosoft/detection-engineering-lab/actions/workflows/ci.yml) |
| [Incident Response Evidence Collector](https://github.com/Ildosoft/incident-response-evidence-collector) | Read-only triage collection, redaction, normalized timelines, SHA-256 manifests, and offline verification | [![CI](https://github.com/Ildosoft/incident-response-evidence-collector/actions/workflows/ci.yml/badge.svg)](https://github.com/Ildosoft/incident-response-evidence-collector/actions/workflows/ci.yml) |

## Engineering principles

- Work only on systems and data that are owned or explicitly authorized.
- Prefer offline, read-only, and deterministic workflows.
- Use synthetic fixtures instead of malware samples or third-party private data.
- Keep safety boundaries, expected behavior, and limitations visible in each repository.
- Require automated tests and reviewable output before publishing a release.

## Skills demonstrated

- Python packaging, unit tests, GitHub Actions, release notes, and changelogs
- Windows Code Integrity and driver-policy diagnostics
- Secure coding, patch validation, and software supply-chain metadata
- Sigma/YARA rule authoring and detection regression testing
- Incident-response evidence handling, redaction, timelines, and integrity manifests

Every featured repository includes architecture documentation, sample reports generated from local synthetic fixtures, automated CI, and tagged releases.
