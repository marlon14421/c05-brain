---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1105"
target_object: "T1059.004"
stix_relationship_id: "relationship--494a36cf-644a-4efe-90c9-eb3b10d549e6"
---
# Relationship 5178: S1105 — uses → T1059.004

**Source object:** [[01 ATT&CK/S1105 - COATHANGER|S1105: COATHANGER]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.004 - Unix Shell|T1059.004: Unix Shell]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[COATHANGER](https://attack.mitre.org/software/S1105) provides a BusyBox reverse shell for command and control.(Citation: NCSC-NL COATHANGER Feb 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--494a36cf-644a-4efe-90c9-eb3b10d549e6`.
