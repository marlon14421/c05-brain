---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0502"
target_object: "T1105"
stix_relationship_id: "relationship--f3b7dbe2-1dd5-4d57-a5ef-1764775d5c99"
---
# Relationship 7421: S0502 — uses → T1105

**Source object:** [[01 ATT&CK/S0502 - Drovorub|S0502: Drovorub]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1105 - Ingress Tool Transfer|T1105: Ingress Tool Transfer]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Drovorub](https://attack.mitre.org/software/S0502) can download files to a compromised host.(Citation: NSA/FBI Drovorub August 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--f3b7dbe2-1dd5-4d57-a5ef-1764775d5c99`.
