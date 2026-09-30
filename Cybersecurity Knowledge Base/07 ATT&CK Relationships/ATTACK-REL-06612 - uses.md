---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1037"
target_object: "T1586.002"
stix_relationship_id: "relationship--d8eae2c0-acc2-4bc5-9eb2-ea7550ff6989"
---
# Relationship 6612: G1037 — uses → T1586.002

**Source object:** [[01 ATT&CK/G1037 - TA577|G1037: TA577]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1586.002 - Email Accounts|T1586.002: Email Accounts]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[TA577](https://attack.mitre.org/groups/G1037) has sent thread hijacked messages from compromised emails.(Citation: Latrodectus APR 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d8eae2c0-acc2-4bc5-9eb2-ea7550ff6989`.
