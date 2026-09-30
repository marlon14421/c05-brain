---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0631"
target_object: "T1059.003"
stix_relationship_id: "relationship--c2021918-3624-4473-8246-fb044caf44e6"
---
# Relationship 3745: S0631 — uses → T1059.003

**Source object:** [[01 ATT&CK/S0631 - Chaes|S0631: Chaes]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.003 - Windows Command Shell|T1059.003: Windows Command Shell]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Chaes](https://attack.mitre.org/software/S0631) has used [cmd](https://attack.mitre.org/software/S0106) to execute tasks on the system.(Citation: Cybereason Chaes Nov 2020)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c2021918-3624-4473-8246-fb044caf44e6`.
