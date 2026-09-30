---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1013"
target_object: "T1059.003"
stix_relationship_id: "relationship--6025ae9c-80d1-4615-9556-174a9ccfef3c"
---
# Relationship 4552: G1013 — uses → T1059.003

**Source object:** [[01 ATT&CK/G1013 - Metador|G1013: Metador]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.003 - Windows Command Shell|T1059.003: Windows Command Shell]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Metador](https://attack.mitre.org/groups/G1013) has used the Windows command line to execute commands.(Citation: SentinelLabs Metador Sept 2022)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--6025ae9c-80d1-4615-9556-174a9ccfef3c`.
