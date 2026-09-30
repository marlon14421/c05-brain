---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0083"
target_object: "T1071.003"
stix_relationship_id: "relationship--5e7e3226-1583-48de-9376-946fa88b6d15"
---
# Relationship 7041: G0083 — uses → T1071.003

**Source object:** [[01 ATT&CK/G0083 - SilverTerrier|G0083: SilverTerrier]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1071.003 - Mail Protocols|T1071.003: Mail Protocols]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[SilverTerrier](https://attack.mitre.org/groups/G0083) uses SMTP for C2 communications.(Citation: Unit42 SilverTerrier 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--5e7e3226-1583-48de-9376-946fa88b6d15`.
