---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9024"
target_object: "T1553.002"
stix_relationship_id: "relationship--f1964de7-05d2-46e9-a04e-c2d739976306"
---
# Relationship 7135: S9024 — uses → T1553.002

**Source object:** [[01 ATT&CK/S9024 - SPAWNCHIMERA|S9024: SPAWNCHIMERA]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1553.002 - Code Signing|T1553.002: Code Signing]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[SPAWNCHIMERA](https://attack.mitre.org/software/S9024) has generated RSA keys against modified files to sign the manifest file, so they appear legitimate.(Citation: CISA SPAWNCHIMERA RESURGE February 2026)(Citation: Google UNC5221 Ivanti January 2025)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--f1964de7-05d2-46e9-a04e-c2d739976306`.
