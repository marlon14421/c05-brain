---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0117"
target_object: "T1087.002"
stix_relationship_id: "relationship--8b425ec5-7be4-4225-a7c5-8f219fed7b6c"
---
# Relationship 7419: G0117 — uses → T1087.002

**Source object:** [[01 ATT&CK/G0117 - Fox Kitten|G0117: Fox Kitten]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1087.002 - Domain Account|T1087.002: Domain Account]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Fox Kitten](https://attack.mitre.org/groups/G0117) has used the Softerra LDAP browser to browse documentation on service accounts.(Citation: CISA AA20-259A Iran-Based Actor September 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--8b425ec5-7be4-4225-a7c5-8f219fed7b6c`.
