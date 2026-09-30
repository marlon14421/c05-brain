---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1048"
target_object: "T1057"
stix_relationship_id: "relationship--f1b29d7e-eba7-460a-bcec-33caf6a4fe15"
---
# Relationship 8549: S1048 — uses → T1057

**Source object:** [[01 ATT&CK/S1048 - macOS.OSAMiner|S1048: macOS.OSAMiner]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1057 - Process Discovery|T1057: Process Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[macOS.OSAMiner](https://attack.mitre.org/software/S1048) has used `ps ax | grep | grep -v grep | ...` and `ps ax | grep -E...` to conduct process discovery.(Citation: SentinelLabs reversing run-only applescripts 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--f1b29d7e-eba7-460a-bcec-33caf6a4fe15`.
