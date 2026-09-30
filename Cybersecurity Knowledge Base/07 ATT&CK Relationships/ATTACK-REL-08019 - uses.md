---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0626"
target_object: "T1105"
stix_relationship_id: "relationship--96b018b8-701c-4658-b58b-716ba632fd72"
---
# Relationship 8019: S0626 — uses → T1105

**Source object:** [[01 ATT&CK/S0626 - P8RAT|S0626: P8RAT]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1105 - Ingress Tool Transfer|T1105: Ingress Tool Transfer]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[P8RAT](https://attack.mitre.org/software/S0626) can download additional payloads to a target system.(Citation: Securelist APT10 March 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--96b018b8-701c-4658-b58b-716ba632fd72`.
