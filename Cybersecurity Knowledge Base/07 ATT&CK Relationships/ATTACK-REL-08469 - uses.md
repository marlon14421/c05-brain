---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0600"
target_object: "T1611"
stix_relationship_id: "relationship--46dd6393-93c7-4e61-8a47-ceecd5b77589"
---
# Relationship 8469: S0600 — uses → T1611

**Source object:** [[01 ATT&CK/S0600 - Doki|S0600: Doki]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1611 - Escape to Host|T1611: Escape to Host]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Doki](https://attack.mitre.org/software/S0600)’s container was configured to bind the host root directory.(Citation: Intezer Doki July 20)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--46dd6393-93c7-4e61-8a47-ceecd5b77589`.
