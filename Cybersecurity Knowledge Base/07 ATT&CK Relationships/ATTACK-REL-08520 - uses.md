---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1184"
target_object: "T1543"
stix_relationship_id: "relationship--4b992403-58a0-455c-a028-83743f0885b9"
---
# Relationship 8520: S1184 — uses → T1543

**Source object:** [[01 ATT&CK/S1184 - BOLDMOVE|S1184: BOLDMOVE]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1543 - Create or Modify System Process|T1543: Create or Modify System Process]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[BOLDMOVE](https://attack.mitre.org/software/S1184) can free all resources and terminate itself on victim machines.(Citation: Google Cloud BOLDMOVE 2023)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--4b992403-58a0-455c-a028-83743f0885b9`.
