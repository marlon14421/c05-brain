---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1122"
target_object: "T1115"
stix_relationship_id: "relationship--d9ce0226-58f6-4907-a20f-6c821b537f7f"
---
# Relationship 7696: S1122 — uses → T1115

**Source object:** [[01 ATT&CK/S1122 - Mispadu|S1122: Mispadu]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1115 - Clipboard Data|T1115: Clipboard Data]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Mispadu](https://attack.mitre.org/software/S1122) has the ability to capture and replace Bitcoin wallet data in the clipboard on a compromised host.(Citation: ESET Security Mispadu Facebook Ads 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d9ce0226-58f6-4907-a20f-6c821b537f7f`.
