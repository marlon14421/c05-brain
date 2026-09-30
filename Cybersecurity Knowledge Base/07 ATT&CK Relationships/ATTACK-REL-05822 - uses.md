---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0449"
target_object: "T1070"
stix_relationship_id: "relationship--cabbe975-9936-4a9a-8fae-a747b3dc7a9d"
---
# Relationship 5822: S0449 — uses → T1070

**Source object:** [[01 ATT&CK/S0449 - Maze|S0449: Maze]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1070 - Indicator Removal|T1070: Indicator Removal]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Maze](https://attack.mitre.org/software/S0449) has used the “Wow64RevertWow64FsRedirection” function following attempts to delete the shadow volumes, in order to leave the system in the same state as it was prior to redirection.(Citation: McAfee Maze March 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--cabbe975-9936-4a9a-8fae-a747b3dc7a9d`.
