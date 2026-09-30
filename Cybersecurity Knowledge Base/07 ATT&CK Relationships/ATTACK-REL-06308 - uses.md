---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0491"
target_object: "T1204.002"
stix_relationship_id: "relationship--6a552e69-29f1-4acc-8bd2-1f32d7550443"
---
# Relationship 6308: S0491 — uses → T1204.002

**Source object:** [[01 ATT&CK/S0491 - StrongPity|S0491: StrongPity]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1204.002 - Malicious File|T1204.002: Malicious File]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[StrongPity](https://attack.mitre.org/software/S0491) has been executed via compromised installation files for legitimate software including compression applications, security software, browsers, file recovery applications, and other tools and utilities.(Citation: Talos Promethium June 2020)(Citation: Bitdefender StrongPity June 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--6a552e69-29f1-4acc-8bd2-1f32d7550443`.
