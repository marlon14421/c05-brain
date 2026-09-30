---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0599"
target_object: "T1110"
stix_relationship_id: "relationship--6c56201e-f348-43ea-8b51-8230d2bf0970"
---
# Relationship 7544: S0599 — uses → T1110

**Source object:** [[01 ATT&CK/S0599 - Kinsing|S0599: Kinsing]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1110 - Brute Force|T1110: Brute Force]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Kinsing](https://attack.mitre.org/software/S0599) has attempted to brute force hosts over SSH.(Citation: Aqua Kinsing April 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--6c56201e-f348-43ea-8b51-8230d2bf0970`.
