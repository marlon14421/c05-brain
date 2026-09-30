---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1111"
target_object: "T1083"
stix_relationship_id: "relationship--9f44fb67-6ad0-44c3-bc84-8b12b50819a9"
---
# Relationship 5912: S1111 — uses → T1083

**Source object:** [[01 ATT&CK/S1111 - DarkGate|S1111: DarkGate]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1083 - File and Directory Discovery|T1083: File and Directory Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

Some versions of [DarkGate](https://attack.mitre.org/software/S1111) search for the hard-coded folder C:\Program Files\e Carte Bleue .(Citation: Ensilo Darkgate 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--9f44fb67-6ad0-44c3-bc84-8b12b50819a9`.
