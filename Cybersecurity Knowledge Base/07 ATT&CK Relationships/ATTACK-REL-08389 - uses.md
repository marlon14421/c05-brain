---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0083"
target_object: "T1071.001"
stix_relationship_id: "relationship--87cc66d0-7cab-4584-b86e-f2d56d492271"
---
# Relationship 8389: G0083 — uses → T1071.001

**Source object:** [[01 ATT&CK/G0083 - SilverTerrier|G0083: SilverTerrier]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1071.001 - Web Protocols|T1071.001: Web Protocols]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[SilverTerrier](https://attack.mitre.org/groups/G0083) uses HTTP for C2 communications.(Citation: Unit42 SilverTerrier 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--87cc66d0-7cab-4584-b86e-f2d56d492271`.
