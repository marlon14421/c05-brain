---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0486"
target_object: "T1105"
stix_relationship_id: "relationship--db2b0471-38e9-4c50-bf96-1c498f38223c"
---
# Relationship 9453: S0486 — uses → T1105

**Source object:** [[01 ATT&CK/S0486 - Bonadan|S0486: Bonadan]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1105 - Ingress Tool Transfer|T1105: Ingress Tool Transfer]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Bonadan](https://attack.mitre.org/software/S0486) can download additional modules from the C2 server.(Citation: ESET ForSSHe December 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--db2b0471-38e9-4c50-bf96-1c498f38223c`.
