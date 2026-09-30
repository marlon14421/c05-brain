---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1105"
target_object: "T1027.002"
stix_relationship_id: "relationship--94883652-f338-47e5-95d9-b38060137fde"
---
# Relationship 2969: S1105 — uses → T1027.002

**Source object:** [[01 ATT&CK/S1105 - COATHANGER|S1105: COATHANGER]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027.002 - Software Packing|T1027.002: Software Packing]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

The first stage of [COATHANGER](https://attack.mitre.org/software/S1105) is delivered as a packed file.(Citation: NCSC-NL COATHANGER Feb 2024)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--94883652-f338-47e5-95d9-b38060137fde`.
