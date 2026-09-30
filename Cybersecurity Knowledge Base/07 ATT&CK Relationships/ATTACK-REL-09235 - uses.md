---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1245"
target_object: "T1016"
stix_relationship_id: "relationship--8c77a1d6-183d-4d51-a116-71ce85850698"
---
# Relationship 9235: S1245 — uses → T1016

**Source object:** [[01 ATT&CK/S1245 - InvisibleFerret|S1245: InvisibleFerret]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1016 - System Network Configuration Discovery|T1016: System Network Configuration Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[InvisibleFerret](https://attack.mitre.org/software/S1245) has collected the local IP address, and external IP.(Citation: ESET Contagious Interview BeaverTail InvisibleFerret February 2025)(Citation: PaloAlto ContagiousInterview BeaverTail InvisibleFerret November 2023)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--8c77a1d6-183d-4d51-a116-71ce85850698`.
