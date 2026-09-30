---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0443"
target_object: "T1074.001"
stix_relationship_id: "relationship--aa12e2a6-02e7-4001-af7b-6a60021ddbfd"
---
# Relationship 6551: S0443 — uses → T1074.001

**Source object:** [[01 ATT&CK/S0443 - MESSAGETAP|S0443: MESSAGETAP]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1074.001 - Local Data Staging|T1074.001: Local Data Staging]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[MESSAGETAP](https://attack.mitre.org/software/S0443) stored targeted SMS messages that matched its target list in CSV files on the compromised system.(Citation: FireEye MESSAGETAP October 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--aa12e2a6-02e7-4001-af7b-6a60021ddbfd`.
