---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1247"
target_object: "T1053.005"
stix_relationship_id: "relationship--9cd7aeeb-5341-4a84-bdca-788674223e11"
---
# Relationship 9980: S1247 — uses → T1053.005

**Source object:** [[01 ATT&CK/S1247 - Embargo|S1247: Embargo]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1053.005 - Scheduled Task|T1053.005: Scheduled Task]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Embargo](https://attack.mitre.org/software/S1247) has obtained persistence of the loader MDeployer by creating a scheduled task named “Perf_sys.”(Citation: ESET Embargo Ransomware October 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--9cd7aeeb-5341-4a84-bdca-788674223e11`.
