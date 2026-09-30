---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0599"
target_object: "T1610"
stix_relationship_id: "relationship--102ece09-4129-4662-b05c-243709cd7d1d"
---
# Relationship 7939: S0599 — uses → T1610

**Source object:** [[01 ATT&CK/S0599 - Kinsing|S0599: Kinsing]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1610 - Deploy Container|T1610: Deploy Container]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Kinsing](https://attack.mitre.org/software/S0599) was run through a deployed Ubuntu container.(Citation: Aqua Kinsing April 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--102ece09-4129-4662-b05c-243709cd7d1d`.
