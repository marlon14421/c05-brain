---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1246"
target_object: "T1657"
stix_relationship_id: "relationship--e0f5fe34-8a13-4f86-9393-c3240466dc87"
---
# Relationship 7424: S1246 — uses → T1657

**Source object:** [[01 ATT&CK/S1246 - BeaverTail|S1246: BeaverTail]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1657 - Financial Theft|T1657: Financial Theft]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[BeaverTail](https://attack.mitre.org/software/S1246) has searched the victim device for browser extensions commonly associated with cryptocurrency wallets.(Citation: Esentire ContagiousInterview BeaverTail InvisibleFerret November 2024)(Citation: Recorded Future Contagious Inteview BeaverTail InvisibleFerret OtterCookie February 2025)(Citation: ESET Contagious Interview BeaverTail InvisibleFerret February 2025)(Citation: PaloAlto ContagiousInterview BeaverTail InvisibleFerret November 2023)(Citation: PaloAlto Unit42 ContagiousInterview BeaverTail InvisibileFerret October 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e0f5fe34-8a13-4f86-9393-c3240466dc87`.
