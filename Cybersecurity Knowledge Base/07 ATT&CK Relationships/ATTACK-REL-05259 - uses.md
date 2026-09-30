---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0608"
target_object: "T1105"
stix_relationship_id: "relationship--fa443fec-23f0-40dd-8a94-06cd19f4eb86"
---
# Relationship 5259: S0608 — uses → T1105

**Source object:** [[01 ATT&CK/S0608 - Conficker|S0608: Conficker]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1105 - Ingress Tool Transfer|T1105: Ingress Tool Transfer]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Conficker](https://attack.mitre.org/software/S0608) downloads an HTTP server to the infected machine.(Citation: SANS Conficker)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--fa443fec-23f0-40dd-8a94-06cd19f4eb86`.
