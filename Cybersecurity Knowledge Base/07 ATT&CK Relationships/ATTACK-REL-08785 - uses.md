---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1052"
target_object: "T1016"
stix_relationship_id: "relationship--b13bb5d3-b725-43f9-89d6-6baaa9481d11"
---
# Relationship 8785: S1052 — uses → T1016

**Source object:** [[01 ATT&CK/S1052 - DEADEYE|S1052: DEADEYE]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1016 - System Network Configuration Discovery|T1016: System Network Configuration Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[DEADEYE](https://attack.mitre.org/software/S1052) can discover the DNS domain name of a targeted system.(Citation: Mandiant APT41)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--b13bb5d3-b725-43f9-89d6-6baaa9481d11`.
