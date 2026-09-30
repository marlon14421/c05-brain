---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1053"
target_object: "T1021.007"
stix_relationship_id: "relationship--604eeaa1-b458-43a6-9618-7c55b8bc7a62"
---
# Relationship 5110: G1053 — uses → T1021.007

**Source object:** [[01 ATT&CK/G1053 - Storm-0501|G1053: Storm-0501]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1021.007 - Cloud Services|T1021.007: Cloud Services]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Storm-0501](https://attack.mitre.org/groups/G1053) has used compromised Entra Connect Sync Server to move laterally within the victim environment.(Citation: Microsoft Storm-0501 Embargo Ransomware August 2025)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--604eeaa1-b458-43a6-9618-7c55b8bc7a62`.
