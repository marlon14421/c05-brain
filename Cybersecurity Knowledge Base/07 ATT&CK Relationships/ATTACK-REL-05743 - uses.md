---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0439"
target_object: "T1056.001"
stix_relationship_id: "relationship--d96d964f-fec6-475e-acc5-d25ff0d46af9"
---
# Relationship 5743: S0439 — uses → T1056.001

**Source object:** [[01 ATT&CK/S0439 - Okrum|S0439: Okrum]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1056.001 - Keylogging|T1056.001: Keylogging]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Okrum](https://attack.mitre.org/software/S0439) was seen using a keylogger tool to capture keystrokes. (Citation: ESET Okrum July 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d96d964f-fec6-475e-acc5-d25ff0d46af9`.
