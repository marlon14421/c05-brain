---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0034"
target_object: "T1057"
stix_relationship_id: "relationship--16043223-3846-4138-93d0-671339ba3646"
---
# Relationship 9048: S0034 — uses → T1057

**Source object:** [[01 ATT&CK/S0034 - NETEAGLE|S0034: NETEAGLE]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1057 - Process Discovery|T1057: Process Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[NETEAGLE](https://attack.mitre.org/software/S0034) can send process listings over the C2 channel.(Citation: FireEye APT30)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--16043223-3846-4138-93d0-671339ba3646`.
