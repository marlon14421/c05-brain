---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1053"
target_object: "T1490"
stix_relationship_id: "relationship--1a549ce9-124b-4a88-997f-c52b3a39a6bc"
---
# Relationship 5126: G1053 — uses → T1490

**Source object:** [[01 ATT&CK/G1053 - Storm-0501|G1053: Storm-0501]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1490 - Inhibit System Recovery|T1490: Inhibit System Recovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Storm-0501](https://attack.mitre.org/groups/G1053) has deleted snapshots, restore points, storage accounts, and backup services to prevent remediation and restoration.(Citation: Microsoft Storm-0501 Embargo Ransomware August 2025) [Storm-0501](https://attack.mitre.org/groups/G1053) has also impacted Azure resources through the targeting of `Microsoft.Compute/snapshots/delete`, `Microsoft.Compute/restorePointCollections/delete`, `Microsoft.Storage/storageAccounts/delete`, and `Microsoft.RecoveryServices/Vaults/backupFabrics/protectionContainers/delete`.(Citation: Microsoft Storm-0501 Embargo Ransomware August 2025)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--1a549ce9-124b-4a88-997f-c52b3a39a6bc`.
