---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1053"
target_object: "T1552.004"
stix_relationship_id: "relationship--dabf635b-40fd-45e1-b7b8-ed6de9d1bf22"
---
# Relationship 6431: G1053 — uses → T1552.004

**Source object:** [[01 ATT&CK/G1053 - Storm-0501|G1053: Storm-0501]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1552.004 - Private Keys|T1552.004: Private Keys]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Storm-0501](https://attack.mitre.org/groups/G1053) has leveraged the Azure Owner role to access and steal the Storage Account Access keys using the `Microsoft.Storage/storageAccounts/listkeys/action` operation.(Citation: Microsoft Storm-0501 Embargo Ransomware August 2025)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--dabf635b-40fd-45e1-b7b8-ed6de9d1bf22`.
