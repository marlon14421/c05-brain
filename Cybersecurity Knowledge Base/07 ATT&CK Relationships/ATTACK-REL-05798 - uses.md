---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0370"
target_object: "T1486"
stix_relationship_id: "relationship--ac263a26-1773-4ac1-b81b-b29f9ace484a"
---
# Relationship 5798: S0370 — uses → T1486

**Source object:** [[01 ATT&CK/S0370 - SamSam|S0370: SamSam]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1486 - Data Encrypted for Impact|T1486: Data Encrypted for Impact]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[SamSam](https://attack.mitre.org/software/S0370) encrypts victim files using RSA-2048 encryption and demands a ransom be paid in Bitcoin to decrypt those files.(Citation: Sophos SamSam Apr 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--ac263a26-1773-4ac1-b81b-b29f9ace484a`.
