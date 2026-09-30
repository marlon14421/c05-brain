---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0282"
target_object: "T1071.001"
stix_relationship_id: "relationship--11f12767-22ca-4f4a-a911-8211dc8ac478"
---
# Relationship 8997: S0282 — uses → T1071.001

**Source object:** [[01 ATT&CK/S0282 - MacSpy|S0282: MacSpy]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1071.001 - Web Protocols|T1071.001: Web Protocols]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[MacSpy](https://attack.mitre.org/software/S0282) uses HTTP for command and control.(Citation: objsee mac malware 2017)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--11f12767-22ca-4f4a-a911-8211dc8ac478`.
