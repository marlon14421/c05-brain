---
tags:
  - cybersecurity
  - defensive-security
  - attack-review
attack_id: "T1677"
attack_type: "Technique"
source: MITRE ATT&CK
---
# T1677: Poisoned Pipeline Execution — Defensive Application

## Source record

- [[01 ATT&CK/T1677 - Poisoned Pipeline Execution|T1677 source record]]
- ATT&CK class: Technique
- Platforms: SaaS
- Tactics: execution

## Source context

Adversaries may manipulate continuous integration / continuous development (CI/CD) processes by injecting malicious code into the build process. There are several mechanisms for poisoning pipelines: * In a Direct Pipeline Execution scenario, the threat actor directly modifies the CI configuration file (e.g., `gitlab-ci.yml` in GitLab). They may include a command to exfiltrate credentials leveraged in the build process to a remote server, or to export them as a workflow artifact.(Citation: Unit 42 Palo Alto GitHub Actions Supply Chain Attack 2025)(Citation: OWASP CICD-SEC-4) * In an Indirect Pipeline Execution scenario, the threat actor injects malicious code into files referenced by the CI configuration file. These may include makefiles, scripts, unit tests, and linters.(Citation: OWASP CICD-SEC-4) * In a Public Pipeline Execution scenario, the threat actor does not have direct access to the repository but instead creates a malicious pull request from a fork that triggers a part of the CI/CD pipeline. For example, in GitHub Actions, the `pull_request_target` trigger allows workflows running from forked repositories to access secrets. If this trigger is combined with an explicit pull request checkout and a location for a threat actor to insert malicious code (e.g., an `npm build` command), a threat actor may be able to leak pipeline credentials.(Citation: Unit 42 Palo Alto GitHub Actions Supply Chain Attack 2025)(Citation: GitHub Security Lab GitHub Actions Security 2021) Similarly, threat actors may craft pull requests with malicious inputs (such as branch names) if the build pipeline treats those inputs as trusted.(Citation: Wiz Ultralytics AI Library Hijack 2024)(Citation: Synactiv Hijacking GitHub Runners)(Citation: GitHub Security Labs GitHub Actions Security Part 2 2021) Finally, if a pipeline leverages a self-hosted runner, a threat actor may be able to execute arbitrary code on a host inside the organization’s network.(Citation: John Stawinski PyTorch Supply Chain Attack 2024) By poisoning CI/CD pipelines, threat actors may be able to gain access to credentials, laterally move to additional hosts, or input malicious components to be shipped further down the pipeline (i.e., [Supply Chain Compromise](https://attack.mitre.org/techniques/T1195)).

## Defensive focus

Map the recorded behavior or objective to assets, trust boundaries, identities, and defensive controls in the local environment. ATT&CK classification alone does not establish activity or compromise.

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Review checklist

- Which assets, roles, platforms, and business services are actually exposed to this behavior?
- What prevention or hardening control applies, and which owner maintains it?
- Which telemetry source can support or refute the behavior, and what blind spots remain?
- What legitimate administrative or software behavior could look similar?
- What containment or recovery decision is authorized if evidence is confirmed?

## Safe validation

Use an isolated lab, benign simulation, or sanitized historical data. Test only owned or explicitly authorized systems; do not reproduce harmful behavior against production targets. Define written scope, test window, accounts, data boundaries, and stop conditions in advance. Preserve only the evidence required to verify the control and protect it from unauthorized access.

## Evidence and response

Record the source and version, environment, time range, expected behavior, observations, alternative explanations, and telemetry gaps. A catalog mapping is a lead for analysis, not an incident finding. Escalate and contain only under approved response procedures; verify remediation with a measurable retest.

## Further reading

- [MITRE ATT&CK](https://attack.mitre.org/)
- [[../../04 Defensive Playbooks/Defensive Playbooks|Defensive Playbooks]]
- [[../../06 Sources/Source Register|Source Register and dataset caveats]]
