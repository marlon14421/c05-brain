---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0377"
target_object: "T1059.004"
stix_relationship_id: "relationship--0929a479-8ece-4c24-a97f-4da7e33d3c2f"
---
# Relationship 5769: S0377 — uses → T1059.004

**Source object:** [[01 ATT&CK/S0377 - Ebury|S0377: Ebury]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.004 - Unix Shell|T1059.004: Unix Shell]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Ebury](https://attack.mitre.org/software/S0377) can use the commands `Xcsh` or `Xcls` to open a shell with [Ebury](https://attack.mitre.org/software/S0377) level permissions and `Xxsh` to open a shell with root level.(Citation: ESET Ebury May 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--0929a479-8ece-4c24-a97f-4da7e33d3c2f`.
