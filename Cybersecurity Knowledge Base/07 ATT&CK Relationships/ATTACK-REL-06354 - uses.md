---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1247"
target_object: "T1489"
stix_relationship_id: "relationship--0c7d07b5-c838-4858-a404-5f9ba0733ca4"
---
# Relationship 6354: S1247 — uses → T1489

**Source object:** [[01 ATT&CK/S1247 - Embargo|S1247: Embargo]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1489 - Service Stop|T1489: Service Stop]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Embargo](https://attack.mitre.org/software/S1247) has terminated active processes and services based on a hardcoded list using the `CloseServiceHandle()` function.(Citation: Cyble Embargo Ransomware May 2024) [Embargo](https://attack.mitre.org/software/S1247) has also leveraged MS4Killer to terminate processes contained in an embedded list of security software process names that were XOR-encrypted.(Citation: ESET Embargo Ransomware October 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--0c7d07b5-c838-4858-a404-5f9ba0733ca4`.
