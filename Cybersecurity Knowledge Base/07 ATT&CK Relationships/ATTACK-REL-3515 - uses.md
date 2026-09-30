---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0365"
target_object: "T1003.001"
stix_relationship_id: "relationship--e998971c-c944-4255-8831-89d49d0e5285"
---
# Relationship 3515: S0365 — uses → T1003.001

**Source object:** [[01 ATT&CK/S0365 - Olympic Destroyer|S0365: Olympic Destroyer]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1003.001 - LSASS Memory|T1003.001: LSASS Memory]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Olympic Destroyer](https://attack.mitre.org/software/S0365) contains a module that tries to obtain credentials from LSASS, similar to [Mimikatz](https://attack.mitre.org/software/S0002). These credentials are used with [PsExec](https://attack.mitre.org/software/S0029) and [Windows Management Instrumentation](https://attack.mitre.org/techniques/T1047) to help the malware propagate itself across a network.(Citation: Talos Olympic Destroyer 2018)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e998971c-c944-4255-8831-89d49d0e5285`.
