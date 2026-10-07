---
tags:
  - cybersecurity
  - defensive-security
  - attack-review
attack_id: "T1685"
attack_type: "Technique"
source: MITRE ATT&CK
---
# T1685: Disable or Modify Tools — Defensive Application

## Source record

- [[01 ATT&CK/T1685 - Disable or Modify Tools|T1685 source record]]
- ATT&CK class: Technique
- Platforms: Containers, ESXi, IaaS, Linux, macOS, Network Devices, Windows
- Tactics: defense-impairment

## Source context

Adversaries may disable, degrade, or tamper with security tools or applications (e.g., endpoint detection and response (EDR) tools, intrusion detection systems (IDS), antivirus, logging agents, sensors, etc.) to impair or reduce visibility of defensive capabilities. This may include stopping specific services, killing processes, modifying or deleting tool configuration files and Registry keys, or preventing tools from updating. This may also include impairing defenses more broadly by disrupting preventative, detection, and response mechanisms across host, network, and cloud environments.(Citation: SCADAfence_ransomware) In addition to directly targeting tools, adversaries may block or manipulate indicators and telemetry used for detection. This includes maliciously disabling or redirecting sensors such as Event Tracing for Windows (ETW), modifying event log configurations (e.g., redirecting Security logs), or interfering with logging pipelines and forwarding mechanisms (e.g., SIEM ingestion).(Citation: Microsoft Lamin Sept 2017)(Citation: ETW Palantir) More advanced techniques include leveraging legitimate drivers or debugging mechanisms to render tools non-functional, bypassing anti-tampering protections, and targeting specific defenses such as Sysmon or cloud monitoring agents. Adversaries may also disrupt broader defensive operations, including update mechanisms, logging infrastructure (e.g., syslog), or event aggregation, further degrading an organization’s ability to detect and respond to malicious activity.(Citation: Cocomazzi FIN7 Reboot)

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
