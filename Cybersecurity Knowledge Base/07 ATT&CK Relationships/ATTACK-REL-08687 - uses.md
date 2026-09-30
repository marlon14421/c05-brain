---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0370"
target_object: "T1027.016"
stix_relationship_id: "relationship--4c44fea9-545c-4d2f-a5e9-caee38ee65b4"
---
# Relationship 8687: S0370 — uses → T1027.016

**Source object:** [[01 ATT&CK/S0370 - SamSam|S0370: SamSam]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027.016 - Junk Code Insertion|T1027.016: Junk Code Insertion]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[SamSam](https://attack.mitre.org/software/S0370) has used garbage code to pad some of its malware components.(Citation: Sophos SamSam Apr 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--4c44fea9-545c-4d2f-a5e9-caee38ee65b4`.
