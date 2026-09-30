---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0100"
target_object: "T1083"
stix_relationship_id: "relationship--40e6721c-f5fd-4c51-aec9-93b70e7e312c"
---
# Relationship 7304: G0100 — uses → T1083

**Source object:** [[01 ATT&CK/G0100 - Inception|G0100: Inception]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1083 - File and Directory Discovery|T1083: File and Directory Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Inception](https://attack.mitre.org/groups/G0100) used a file listing plugin to collect information about file and directories both on local and remote drives.(Citation: Symantec Inception Framework March 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--40e6721c-f5fd-4c51-aec9-93b70e7e312c`.
