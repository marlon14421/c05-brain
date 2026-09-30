---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0115"
target_object: "T1566"
stix_relationship_id: "relationship--f7aab529-962c-4bb8-812b-d63e0f8df494"
---
# Relationship 7462: G0115 — uses → T1566

**Source object:** [[01 ATT&CK/G0115 - GOLD SOUTHFIELD|G0115: GOLD SOUTHFIELD]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1566 - Phishing|T1566: Phishing]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[GOLD SOUTHFIELD](https://attack.mitre.org/groups/G0115) has conducted malicious spam (malspam) campaigns to gain access to victim's machines.(Citation: Secureworks REvil September 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--f7aab529-962c-4bb8-812b-d63e0f8df494`.
