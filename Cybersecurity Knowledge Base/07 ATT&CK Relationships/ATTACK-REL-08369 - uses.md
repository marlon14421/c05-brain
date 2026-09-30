---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9042"
target_object: "T1036.004"
stix_relationship_id: "relationship--380bd384-e2c5-418b-9b69-740b03d9a3c7"
---
# Relationship 8369: S9042 — uses → T1036.004

**Source object:** [[01 ATT&CK/S9042 - CanisterWorm|S9042: CanisterWorm]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1036.004 - Masquerade Task or Service|T1036.004: Masquerade Task or Service]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[CanisterWorm](https://attack.mitre.org/software/S9042) has masqueraded itself as systemd or as a PostgreSQL utility named pgmon.(Citation: Palo Alto TeamPCP MAR 2026)(Citation: Aikido TeamPCP Trivy MAR 2026)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--380bd384-e2c5-418b-9b69-740b03d9a3c7`.
