---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0122"
target_object: "T1114.003"
stix_relationship_id: "relationship--67f029d5-c44b-446b-9efe-0e0e0d85192a"
---
# Relationship 6723: G0122 — uses → T1114.003

**Source object:** [[01 ATT&CK/G0122 - Silent Librarian|G0122: Silent Librarian]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1114.003 - Email Forwarding Rule|T1114.003: Email Forwarding Rule]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Silent Librarian](https://attack.mitre.org/groups/G0122) has set up auto forwarding rules on compromised e-mail accounts.(Citation: DOJ Iran Indictments March 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--67f029d5-c44b-446b-9efe-0e0e0d85192a`.
