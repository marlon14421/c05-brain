---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0337"
target_object: "T1105"
stix_relationship_id: "relationship--91eab726-0a0c-4898-8376-66987fd1037c"
---
# Relationship 5934: S0337 — uses → T1105

**Source object:** [[01 ATT&CK/S0337 - BadPatch|S0337: BadPatch]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1105 - Ingress Tool Transfer|T1105: Ingress Tool Transfer]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[BadPatch](https://attack.mitre.org/software/S0337) can download and execute or update malware.(Citation: Unit 42 BadPatch Oct 2017)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--91eab726-0a0c-4898-8376-66987fd1037c`.
