---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0094"
target_object: "T1071.003"
stix_relationship_id: "relationship--a573685b-3135-44ae-9f9a-844dfc5bdaa2"
---
# Relationship 8990: G0094 — uses → T1071.003

**Source object:** [[01 ATT&CK/G0094 - Kimsuky|G0094: Kimsuky]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1071.003 - Mail Protocols|T1071.003: Mail Protocols]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Kimsuky](https://attack.mitre.org/groups/G0094) has used e-mail to send exfiltrated data to C2 servers.(Citation: CISA AA20-301A Kimsuky)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a573685b-3135-44ae-9f9a-844dfc5bdaa2`.
