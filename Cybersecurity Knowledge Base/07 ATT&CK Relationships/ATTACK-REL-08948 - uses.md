---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1022"
target_object: "T1620"
stix_relationship_id: "relationship--9d67040f-625a-49bd-aacb-48024fc7c4b2"
---
# Relationship 8948: S1022 — uses → T1620

**Source object:** [[01 ATT&CK/S1022 - IceApple|S1022: IceApple]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1620 - Reflective Code Loading|T1620: Reflective Code Loading]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[IceApple](https://attack.mitre.org/software/S1022) can use reflective code loading to load .NET assemblies into `MSExchangeOWAAppPool` on targeted Exchange servers.(Citation: CrowdStrike IceApple May 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--9d67040f-625a-49bd-aacb-48024fc7c4b2`.
