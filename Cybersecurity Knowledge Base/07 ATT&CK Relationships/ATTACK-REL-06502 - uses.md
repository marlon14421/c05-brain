---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1245"
target_object: "T1056.001"
stix_relationship_id: "relationship--6672498e-4e40-4f1a-b469-fa7fc05ee68a"
---
# Relationship 6502: S1245 — uses → T1056.001

**Source object:** [[01 ATT&CK/S1245 - InvisibleFerret|S1245: InvisibleFerret]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1056.001 - Keylogging|T1056.001: Keylogging]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[InvisibleFerret](https://attack.mitre.org/software/S1245) has conducted keylogging using the Python project “pyWinHook” and "Pyhook".(Citation: Esentire ContagiousInterview BeaverTail InvisibleFerret November 2024)(Citation: ESET Contagious Interview BeaverTail InvisibleFerret February 2025)(Citation: PaloAlto ContagiousInterview BeaverTail InvisibleFerret November 2023) [InvisibleFerret](https://attack.mitre.org/software/S1245) has also captured keylogging thread checks for changes in an active window and key presses.(Citation: Zscaler ContagiousInterview BeaverTail InvisibleFerret November 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--6672498e-4e40-4f1a-b469-fa7fc05ee68a`.
