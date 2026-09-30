---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0564"
target_object: "T1059.003"
stix_relationship_id: "relationship--209fe032-42b5-4268-85bf-4db099e06d92"
---
# Relationship 4355: S0564 — uses → T1059.003

**Source object:** [[01 ATT&CK/S0564 - BlackMould|S0564: BlackMould]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.003 - Windows Command Shell|T1059.003: Windows Command Shell]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[BlackMould](https://attack.mitre.org/software/S0564) can run cmd.exe with parameters.(Citation: Microsoft GALLIUM December 2019)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--209fe032-42b5-4268-85bf-4db099e06d92`.
