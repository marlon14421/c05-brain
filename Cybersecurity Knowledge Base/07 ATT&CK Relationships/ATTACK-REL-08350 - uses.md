---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0348"
target_object: "T1057"
stix_relationship_id: "relationship--ed51de86-8e28-4436-a663-94b66f22a7df"
---
# Relationship 8350: S0348 — uses → T1057

**Source object:** [[01 ATT&CK/S0348 - Cardinal RAT|S0348: Cardinal RAT]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1057 - Process Discovery|T1057: Process Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Cardinal RAT](https://attack.mitre.org/software/S0348) contains watchdog functionality that ensures its process is always running, else spawns a new instance.(Citation: PaloAlto CardinalRat Apr 2017)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--ed51de86-8e28-4436-a663-94b66f22a7df`.
