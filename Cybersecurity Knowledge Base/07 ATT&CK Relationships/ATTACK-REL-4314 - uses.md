---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1140"
target_object: "T1560"
stix_relationship_id: "relationship--60fd7b53-b65a-49d3-ba1c-40beb74e8088"
---
# Relationship 4314: S1140 — uses → T1560

**Source object:** [[01 ATT&CK/S1140 - Spica|S1140: Spica]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1560 - Archive Collected Data|T1560: Archive Collected Data]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Spica](https://attack.mitre.org/software/S1140) can archive collected documents for exfiltration.(Citation: Google TAG COLDRIVER January 2024)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--60fd7b53-b65a-49d3-ba1c-40beb74e8088`.
