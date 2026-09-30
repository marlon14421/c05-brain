---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1248"
target_object: "T1105"
stix_relationship_id: "relationship--a8195876-514d-49b7-9b9c-30c75eaff089"
---
# Relationship 8276: S1248 — uses → T1105

**Source object:** [[01 ATT&CK/S1248 - XORIndex Loader|S1248: XORIndex Loader]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1105 - Ingress Tool Transfer|T1105: Ingress Tool Transfer]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[XORIndex Loader](https://attack.mitre.org/software/S1248) has been used to download a malicious payload to include [BeaverTail](https://attack.mitre.org/software/S1246).(Citation: Socket BeaverTail XORIndex HexEval Contagious Interview July 2025)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a8195876-514d-49b7-9b9c-30c75eaff089`.
