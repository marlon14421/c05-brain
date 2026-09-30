---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0078"
target_object: "T1070.006"
stix_relationship_id: "relationship--d8a7ec97-b262-489d-bc4b-e2c7007f75bc"
---
# Relationship 9046: S0078 — uses → T1070.006

**Source object:** [[01 ATT&CK/S0078 - Psylo|S0078: Psylo]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1070.006 - Timestomp|T1070.006: Timestomp]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Psylo](https://attack.mitre.org/software/S0078) has a command to conduct timestomping by setting a specified file’s timestamps to match those of a system file in the System32 directory.(Citation: Scarlet Mimic Jan 2016)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d8a7ec97-b262-489d-bc4b-e2c7007f75bc`.
