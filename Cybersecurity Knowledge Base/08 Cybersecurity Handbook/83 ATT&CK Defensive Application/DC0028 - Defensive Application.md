---
tags:
  - cybersecurity
  - defensive-security
  - attack-review
attack_id: "DC0028"
attack_type: "Data Component"
source: MITRE ATT&CK
---
# DC0028: Image Metadata — Defensive Application

## Source record

- [[01 ATT&CK/DC0028 - Image Metadata|DC0028 source record]]
- ATT&CK class: Data Component
- Platforms: Not specified
- Tactics: Not specified

## Source context

contextual information associated with a virtual machine image, such as its name, resource group, status (active or inactive), type (custom or prebuilt), size, creation date, and permissions. This metadata is critical for understanding the state and configuration of virtual machine images in cloud environments. Examples: - Azure Compute Service Image Metadata Example: - Name: MyCustomImage - Resource Group: MyResourceGroup - State: Available - Type: Managed Image - AWS EC2 AMI Metadata Example: - Image ID: ami-1234567890abcdef0 - Name: ProdImage - State: Available - Platform: Windows - Google Cloud Compute Engine Image Metadata Example: - Image Name: webserver-image - Project: my-project-id - Family: webserver - Source Disk: my-disk-id - VMware vSphere Template Metadata Example: - Name: LinuxTemplate - Disk Size: 40GB - Network Adapter: VM Network

## Defensive focus

Evaluate whether this telemetry component supplies timely and trustworthy evidence for a stated defensive question while respecting privacy and retention limits.

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Review checklist

- Which platform and event sources generate the data, and are they enabled throughout the target population?
- Are timestamps, identities, and fields reliable enough for the intended analytic?
- What collection gaps, sampling, or parser changes could weaken conclusions?
- Which sensitive fields need minimization or access restrictions?
- How are retention, integrity, and responder access governed?

## Safe validation

Validate collection with benign, expected events on owned systems and synthetic accounts. Document missing sources and do not infer absence of behavior from absent telemetry. Define written scope, test window, accounts, data boundaries, and stop conditions in advance. Preserve only the evidence required to verify the control and protect it from unauthorized access.

## Evidence and response

Record the source and version, environment, time range, expected behavior, observations, alternative explanations, and telemetry gaps. A catalog mapping is a lead for analysis, not an incident finding. Escalate and contain only under approved response procedures; verify remediation with a measurable retest.

## Further reading

- [MITRE ATT&CK](https://attack.mitre.org/)
- [[../../04 Defensive Playbooks/Defensive Playbooks|Defensive Playbooks]]
- [[../../06 Sources/Source Register|Source Register and dataset caveats]]
