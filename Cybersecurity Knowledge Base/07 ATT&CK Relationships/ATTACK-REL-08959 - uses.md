---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0065"
target_object: "T1083"
stix_relationship_id: "relationship--26968975-5f01-4b4b-9cdc-ef3b76710304"
---
# Relationship 8959: S0065 — uses → T1083

**Source object:** [[01 ATT&CK/S0065 - 4H RAT|S0065: 4H RAT]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1083 - File and Directory Discovery|T1083: File and Directory Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[4H RAT](https://attack.mitre.org/software/S0065) has the capability to obtain file and directory listings.(Citation: CrowdStrike Putter Panda)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--26968975-5f01-4b4b-9cdc-ef3b76710304`.
