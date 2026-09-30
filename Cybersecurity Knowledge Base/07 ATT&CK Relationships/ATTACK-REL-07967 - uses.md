---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0434"
target_object: "T1555.003"
stix_relationship_id: "relationship--14307b7b-0837-4c15-a959-0c8d24e05b6b"
---
# Relationship 7967: S0434 — uses → T1555.003

**Source object:** [[01 ATT&CK/S0434 - Imminent Monitor|S0434: Imminent Monitor]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1555.003 - Credentials from Web Browsers|T1555.003: Credentials from Web Browsers]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Imminent Monitor](https://attack.mitre.org/software/S0434) has a PasswordRecoveryPacket module for recovering browser passwords.(Citation: QiAnXin APT-C-36 Feb2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--14307b7b-0837-4c15-a959-0c8d24e05b6b`.
