---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0543"
target_object: "T1059.003"
stix_relationship_id: "relationship--52978273-355d-4043-b65e-a3e1d0b84b9e"
---
# Relationship 3006: S0543 — uses → T1059.003

**Source object:** [[01 ATT&CK/S0543 - Spark|S0543: Spark]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.003 - Windows Command Shell|T1059.003: Windows Command Shell]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Spark](https://attack.mitre.org/software/S0543) can use cmd.exe to run commands.(Citation: Unit42 Molerat Mar 2020)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--52978273-355d-4043-b65e-a3e1d0b84b9e`.
