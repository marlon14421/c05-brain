---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0457"
target_object: "T1489"
stix_relationship_id: "relationship--e6a3f7bf-33c3-4d4c-bb27-46bd2842c750"
---
# Relationship 6363: S0457 — uses → T1489

**Source object:** [[01 ATT&CK/S0457 - Netwalker|S0457: Netwalker]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1489 - Service Stop|T1489: Service Stop]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Netwalker](https://attack.mitre.org/software/S0457) can terminate system processes and services, some of which relate to backup software.(Citation: TrendMicro Netwalker May 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e6a3f7bf-33c3-4d4c-bb27-46bd2842c750`.
