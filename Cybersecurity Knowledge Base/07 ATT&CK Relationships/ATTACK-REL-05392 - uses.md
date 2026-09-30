---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0120"
target_object: "T1003.002"
stix_relationship_id: "relationship--f1d5a985-406e-4b03-9f55-2706a2adba92"
---
# Relationship 5392: S0120 — uses → T1003.002

**Source object:** [[01 ATT&CK/S0120 - Fgdump|S0120: Fgdump]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1003.002 - Security Account Manager|T1003.002: Security Account Manager]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Fgdump](https://attack.mitre.org/software/S0120) can dump Windows password hashes.(Citation: Mandiant APT1)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--f1d5a985-406e-4b03-9f55-2706a2adba92`.
