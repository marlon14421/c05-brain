---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0284"
target_object: "T1105"
stix_relationship_id: "relationship--0485006f-c4f6-4657-85a0-6beec8d9368a"
---
# Relationship 8082: S0284 — uses → T1105

**Source object:** [[01 ATT&CK/S0284 - More_eggs|S0284: More_eggs]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1105 - Ingress Tool Transfer|T1105: Ingress Tool Transfer]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[More_eggs](https://attack.mitre.org/software/S0284) can download and launch additional payloads.(Citation: Talos Cobalt Group July 2018)(Citation: Security Intelligence More Eggs Aug 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--0485006f-c4f6-4657-85a0-6beec8d9368a`.
