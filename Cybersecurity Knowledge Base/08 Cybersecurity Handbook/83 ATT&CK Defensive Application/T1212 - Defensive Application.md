---
tags:
  - cybersecurity
  - defensive-security
  - attack-review
attack_id: "T1212"
attack_type: "Technique"
source: MITRE ATT&CK
---
# T1212: Exploitation for Credential Access — Defensive Application

## Source record

- [[01 ATT&CK/T1212 - Exploitation for Credential Access|T1212 source record]]
- ATT&CK class: Technique
- Platforms: Linux, Windows, macOS, Identity Provider
- Tactics: credential-access

## Source context

Adversaries may exploit software vulnerabilities in an attempt to collect credentials. Exploitation of a software vulnerability occurs when an adversary takes advantage of a programming error in a program, service, or within the operating system software or kernel itself to execute adversary-controlled code. Credentialing and authentication mechanisms may be targeted for exploitation by adversaries as a means to gain access to useful credentials or circumvent the process to gain authenticated access to systems. One example of this is `MS14-068`, which targets Kerberos and can be used to forge Kerberos tickets using domain user permissions.(Citation: Technet MS14-068)(Citation: ADSecurity Detecting Forged Tickets) Another example of this is replay attacks, in which the adversary intercepts data packets sent between parties and then later replays these packets. If services don't properly validate authentication requests, these replayed packets may allow an adversary to impersonate one of the parties and gain unauthorized access or privileges.(Citation: Bugcrowd Replay Attack)(Citation: Comparitech Replay Attack)(Citation: Microsoft Midnight Blizzard Replay Attack) Such exploitation has been demonstrated in cloud environments as well. For example, adversaries have exploited vulnerabilities in public cloud infrastructure that allowed for unintended authentication token creation and renewal.(Citation: Storm-0558 techniques for unauthorized email access) Exploitation for credential access may also result in Privilege Escalation depending on the process targeted or credentials obtained.

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
