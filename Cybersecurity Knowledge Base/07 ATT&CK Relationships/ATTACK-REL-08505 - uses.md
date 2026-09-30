---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1015"
target_object: "T1559.001"
stix_relationship_id: "relationship--5b2b610f-7563-49d0-8ee3-066cc82fd35c"
---
# Relationship 8505: S1015 — uses → T1559.001

**Source object:** [[01 ATT&CK/S1015 - Milan|S1015: Milan]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1559.001 - Component Object Model|T1559.001: Component Object Model]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Milan](https://attack.mitre.org/software/S1015) can use a COM component to generate scheduled tasks.(Citation: ClearSky Siamesekitten August 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--5b2b610f-7563-49d0-8ee3-066cc82fd35c`.
