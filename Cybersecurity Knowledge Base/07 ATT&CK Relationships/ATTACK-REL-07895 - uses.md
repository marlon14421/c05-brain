---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1133"
target_object: "T1480"
stix_relationship_id: "relationship--7313a6d7-fb8f-4254-8de2-fd42da02dd6a"
---
# Relationship 7895: S1133 — uses → T1480

**Source object:** [[01 ATT&CK/S1133 - Apostle|S1133: Apostle]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1480 - Execution Guardrails|T1480: Execution Guardrails]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Apostle](https://attack.mitre.org/software/S1133)'s ransomware variant requires that a base64-encoded argument is passed when executed, that is used as the Public Key for subsequent encryption operations. If [Apostle](https://attack.mitre.org/software/S1133) is executed without this argument, it automatically runs a self-delete function.(Citation: SentinelOne Agrius 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--7313a6d7-fb8f-4254-8de2-fd42da02dd6a`.
