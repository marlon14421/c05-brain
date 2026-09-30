---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0154"
target_object: "T1134.004"
stix_relationship_id: "relationship--538e4202-41cf-4d4e-9c1c-30df5bc30a22"
---
# Relationship 6365: S0154 — uses → T1134.004

**Source object:** [[01 ATT&CK/S0154 - Cobalt Strike|S0154: Cobalt Strike]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1134.004 - Parent PID Spoofing|T1134.004: Parent PID Spoofing]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Cobalt Strike](https://attack.mitre.org/software/S0154) can spawn processes with alternate PPIDs.(Citation: CobaltStrike Daddy May 2017)(Citation: Cobalt Strike Manual 4.3 November 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--538e4202-41cf-4d4e-9c1c-30df5bc30a22`.
