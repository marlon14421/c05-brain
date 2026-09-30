---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1245"
target_object: "T1057"
stix_relationship_id: "relationship--624ea031-fa6f-42f6-a3e8-c6ee0063be20"
---
# Relationship 6330: S1245 — uses → T1057

**Source object:** [[01 ATT&CK/S1245 - InvisibleFerret|S1245: InvisibleFerret]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1057 - Process Discovery|T1057: Process Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[InvisibleFerret](https://attack.mitre.org/software/S1245) has the capability to query installed programs and running processes.(Citation: Zscaler ContagiousInterview BeaverTail InvisibleFerret November 2024) [InvisibleFerret](https://attack.mitre.org/software/S1245) has also identified running processes using the Python project “psutil”.(Citation: PaloAlto ContagiousInterview BeaverTail InvisibleFerret November 2023)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--624ea031-fa6f-42f6-a3e8-c6ee0063be20`.
