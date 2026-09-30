---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0009"
target_object: "T1105"
stix_relationship_id: "relationship--fb0206c4-ed10-4922-9935-cbb2c7462acd"
---
# Relationship 8221: S0009 — uses → T1105

**Source object:** [[01 ATT&CK/S0009 - Hikit|S0009: Hikit]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1105 - Ingress Tool Transfer|T1105: Ingress Tool Transfer]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Hikit](https://attack.mitre.org/software/S0009) has the ability to download files to a compromised host.(Citation: Novetta-Axiom)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--fb0206c4-ed10-4922-9935-cbb2c7462acd`.
