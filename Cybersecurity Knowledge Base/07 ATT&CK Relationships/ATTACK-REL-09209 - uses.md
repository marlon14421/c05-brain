---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0276"
target_object: "T1548.001"
stix_relationship_id: "relationship--72b7d86e-5e78-4bc6-a16e-c4380d12d627"
---
# Relationship 9209: S0276 — uses → T1548.001

**Source object:** [[01 ATT&CK/S0276 - Keydnap|S0276: Keydnap]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1548.001 - Setuid and Setgid|T1548.001: Setuid and Setgid]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Keydnap](https://attack.mitre.org/software/S0276) adds the setuid flag to a binary so it can easily elevate in the future.(Citation: OSX Keydnap malware)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--72b7d86e-5e78-4bc6-a16e-c4380d12d627`.
