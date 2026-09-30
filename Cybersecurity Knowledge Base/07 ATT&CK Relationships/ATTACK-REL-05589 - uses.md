---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1102"
target_object: "T1567.002"
stix_relationship_id: "relationship--cb0ca294-246f-417f-bf19-9faebeb7e727"
---
# Relationship 5589: S1102 — uses → T1567.002

**Source object:** [[01 ATT&CK/S1102 - Pcexter|S1102: Pcexter]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1567.002 - Exfiltration to Cloud Storage|T1567.002: Exfiltration to Cloud Storage]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Pcexter](https://attack.mitre.org/software/S1102) can upload stolen files to OneDrive storage accounts via HTTP `POST`.(Citation: Kaspersky ToddyCat Check Logs October 2023)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--cb0ca294-246f-417f-bf19-9faebeb7e727`.
