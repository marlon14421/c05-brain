---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1245"
target_object: "T1560.001"
stix_relationship_id: "relationship--d5d9878c-4255-452e-810e-65816dfa2685"
---
# Relationship 6476: S1245 — uses → T1560.001

**Source object:** [[01 ATT&CK/S1245 - InvisibleFerret|S1245: InvisibleFerret]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1560.001 - Archive via Utility|T1560.001: Archive via Utility]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[InvisibleFerret](https://attack.mitre.org/software/S1245) has used 7zip, RAR and zip files to archive collected data for exfiltration.(Citation: ESET Contagious Interview BeaverTail InvisibleFerret February 2025)(Citation: Zscaler ContagiousInterview BeaverTail InvisibleFerret November 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d5d9878c-4255-452e-810e-65816dfa2685`.
