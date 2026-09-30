---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1032"
target_object: "T1074"
stix_relationship_id: "relationship--514198d4-dac9-4982-8d80-429b7843b639"
---
# Relationship 5014: G1032 — uses → T1074

**Source object:** [[01 ATT&CK/G1032 - INC Ransom|G1032: INC Ransom]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1074 - Data Staged|T1074: Data Staged]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[INC Ransom](https://attack.mitre.org/groups/G1032) has staged data on compromised hosts prior to exfiltration.(Citation: Huntress INC Ransom Group August 2023)(Citation: SOCRadar INC Ransom January 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--514198d4-dac9-4982-8d80-429b7843b639`.
