---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1047"
target_object: "T1053.002"
stix_relationship_id: "relationship--3e76b11e-8a9e-4300-b9d4-8cbd8e8bb37f"
---
# Relationship 0030: M1047 — mitigates → T1053.002

**Source object:** [[01 ATT&CK/M1047 - Audit|M1047: Audit]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1053.002 - At|T1053.002: At]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Toolkits like the PowerSploit framework contain PowerUp modules that can be used to explore systems for permission weaknesses in scheduled tasks that could be used to escalate privileges. (Citation: Powersploit) Windows operating system also creates a registry key specifically associated with the creation of a scheduled task on the destination host at: Microsoft\Windows NT\CurrentVersion\Schedule\TaskCache\Tree\At1. (Citation: Secureworks - AT.exe Scheduled Task) In Linux and macOS environments, scheduled tasks using [at](https://attack.mitre.org/software/S0110) can be audited locally, or through centrally collected logging, using syslog, or auditd events from the host. (Citation: Kifarunix - Task Scheduling in Linux)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--3e76b11e-8a9e-4300-b9d4-8cbd8e8bb37f`.
