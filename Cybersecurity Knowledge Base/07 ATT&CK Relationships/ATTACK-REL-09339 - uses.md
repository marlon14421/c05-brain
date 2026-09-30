---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1046"
target_object: "S0190"
stix_relationship_id: "relationship--3b6996b8-7890-466b-9435-45ecff42f82f"
---
# Relationship 9339: G1046 — uses → S0190

**Source object:** [[01 ATT&CK/G1046 - Storm-1811|G1046: Storm-1811]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S0190 - BITSAdmin|S0190: BITSAdmin]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Storm-1811](https://attack.mitre.org/groups/G1046) has used [BITSAdmin](https://attack.mitre.org/software/S0190) to download payloads.(Citation: Microsoft Storm-1811 2024)(Citation: RedCanary June Insights 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--3b6996b8-7890-466b-9435-45ecff42f82f`.
