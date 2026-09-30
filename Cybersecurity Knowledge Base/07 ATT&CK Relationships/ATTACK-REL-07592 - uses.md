---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1065"
target_object: "T1057"
stix_relationship_id: "relationship--368510dc-1050-45df-81f2-1fca6118c2b0"
---
# Relationship 7592: S1065 — uses → T1057

**Source object:** [[01 ATT&CK/S1065 - Woody RAT|S1065: Woody RAT]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1057 - Process Discovery|T1057: Process Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Woody RAT](https://attack.mitre.org/software/S1065) can call `NtQuerySystemProcessInformation` with `SystemProcessInformation` to enumerate all running processes, including associated information such as PID, parent PID, image name, and owner.(Citation: MalwareBytes WoodyRAT Aug 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--368510dc-1050-45df-81f2-1fca6118c2b0`.
