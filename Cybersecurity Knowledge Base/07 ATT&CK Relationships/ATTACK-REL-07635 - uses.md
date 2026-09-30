---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1213"
target_object: "T1204.002"
stix_relationship_id: "relationship--c021ed6c-a241-4c20-ad6c-3d267baeac40"
---
# Relationship 7635: S1213 — uses → T1204.002

**Source object:** [[01 ATT&CK/S1213 - Lumma Stealer|S1213: Lumma Stealer]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1204.002 - Malicious File|T1204.002: Malicious File]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Lumma Stealer](https://attack.mitre.org/software/S1213) has gained initial execution through victims opening malicious executable files embedded in zip archives, and MSI files within RAR files.(Citation: Cybereason LumaStealer Undated)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c021ed6c-a241-4c20-ad6c-3d267baeac40`.
