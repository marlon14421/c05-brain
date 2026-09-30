---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0171"
target_object: "T1518.001"
stix_relationship_id: "relationship--863c1d57-db93-49a9-a953-eb7c2d6b2e5b"
---
# Relationship 6229: S0171 — uses → T1518.001

**Source object:** [[01 ATT&CK/S0171 - Felismus|S0171: Felismus]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1518.001 - Security Software Discovery|T1518.001: Security Software Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Felismus](https://attack.mitre.org/software/S0171) checks for processes associated with anti-virus vendors.(Citation: Forcepoint Felismus Mar 2017)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--863c1d57-db93-49a9-a953-eb7c2d6b2e5b`.
