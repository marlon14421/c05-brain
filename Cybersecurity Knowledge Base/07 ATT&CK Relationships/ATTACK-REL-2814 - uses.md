---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1246"
target_object: "T1001.001"
stix_relationship_id: "relationship--a8b92dca-8843-4d3c-9bff-88c922201b09"
---
# Relationship 2814: S1246 — uses → T1001.001

**Source object:** [[01 ATT&CK/S1246 - BeaverTail|S1246: BeaverTail]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1001.001 - Junk Data|T1001.001: Junk Data]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[BeaverTail](https://attack.mitre.org/software/S1246) has added junk data or a dummy character prepended to a string to hamper decoding attempts.(Citation: ESET Contagious Interview BeaverTail InvisibleFerret February 2025)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a8b92dca-8843-4d3c-9bff-88c922201b09`.
