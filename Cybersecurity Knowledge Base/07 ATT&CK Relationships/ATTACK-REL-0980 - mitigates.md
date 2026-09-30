---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1029"
target_object: "T1565"
stix_relationship_id: "relationship--6bc7c37c-ce58-4613-9401-e2f3f45f30fa"
---
# Relationship 0980: M1029 — mitigates → T1565

**Source object:** [[01 ATT&CK/M1029 - Remote Data Storage|M1029: Remote Data Storage]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1565 - Data Manipulation|T1565: Data Manipulation]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Consider implementing IT disaster recovery plans that contain procedures for taking regular data backups that can be used to restore organizational data.(Citation: Ready.gov IT DRP) Ensure backups are stored off system and is protected from common methods adversaries may use to gain access and manipulate backups.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--6bc7c37c-ce58-4613-9401-e2f3f45f30fa`.
