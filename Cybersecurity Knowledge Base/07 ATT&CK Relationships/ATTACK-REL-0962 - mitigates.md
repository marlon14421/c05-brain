---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1053"
target_object: "T1485.001"
stix_relationship_id: "relationship--a142c98a-6ccc-4f78-9882-e66dd4827cf6"
---
# Relationship 0962: M1053 — mitigates → T1485.001

**Source object:** [[01 ATT&CK/M1053 - Data Backup|M1053: Data Backup]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1485.001 - Lifecycle-Triggered Deletion|T1485.001: Lifecycle-Triggered Deletion]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Consider implementing IT disaster recovery plans that contain procedures for taking regular data backups that can be used to restore organizational data.(Citation: Ready.gov IT DRP) Ensure backups are stored off system and protected from common methods adversaries may use to gain access and destroy the backups to prevent recovery.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a142c98a-6ccc-4f78-9882-e66dd4827cf6`.
