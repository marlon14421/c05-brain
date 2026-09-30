---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0016"
target_object: "T1203"
stix_relationship_id: "relationship--5ca1f5dc-9573-46bb-a9db-fb83cd15b272"
---
# Relationship 7056: G0016 — uses → T1203

**Source object:** [[01 ATT&CK/G0016 - APT29|G0016: APT29]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1203 - Exploitation for Client Execution|T1203: Exploitation for Client Execution]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[APT29](https://attack.mitre.org/groups/G0016) has used multiple software exploits for common client software, like Microsoft Word, Exchange, and Adobe Reader, to gain code execution.(Citation: F-Secure The Dukes)(Citation: Cybersecurity Advisory SVR TTP May 2021)(Citation: MSTIC NOBELIUM May 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--5ca1f5dc-9573-46bb-a9db-fb83cd15b272`.
