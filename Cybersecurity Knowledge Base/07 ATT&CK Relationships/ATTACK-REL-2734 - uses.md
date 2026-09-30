---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1246"
target_object: "T1082"
stix_relationship_id: "relationship--4c5755ef-d3fc-457d-9103-8bb9e37ae462"
---
# Relationship 2734: S1246 — uses → T1082

**Source object:** [[01 ATT&CK/S1246 - BeaverTail|S1246: BeaverTail]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1082 - System Information Discovery|T1082: System Information Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[BeaverTail](https://attack.mitre.org/software/S1246) has been known to collect basic system information.(Citation: Esentire ContagiousInterview BeaverTail InvisibleFerret November 2024)(Citation: PaloAlto ContagiousInterview BeaverTail InvisibleFerret November 2023) [BeaverTail](https://attack.mitre.org/software/S1246) has also collected data to include hostname and current timestamp prior to uploading data to the API endpoint `/uploads` on the C2 server.(Citation: ESET Contagious Interview BeaverTail InvisibleFerret February 2025)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--4c5755ef-d3fc-457d-9103-8bb9e37ae462`.
