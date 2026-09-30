---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0376"
target_object: "T1124"
stix_relationship_id: "relationship--d060e004-9eb7-425e-924c-0555fa80e083"
---
# Relationship 8227: S0376 — uses → T1124

**Source object:** [[01 ATT&CK/S0376 - HOPLIGHT|S0376: HOPLIGHT]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1124 - System Time Discovery|T1124: System Time Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[HOPLIGHT](https://attack.mitre.org/software/S0376) has been observed collecting system time from victim machines.(Citation: US-CERT HOPLIGHT Apr 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d060e004-9eb7-425e-924c-0555fa80e083`.
