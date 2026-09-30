---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1059"
target_object: "T1560.003"
stix_relationship_id: "relationship--609a0483-ac4a-49d6-bc5d-3cb0ff6e8a97"
---
# Relationship 5007: S1059 — uses → T1560.003

**Source object:** [[01 ATT&CK/S1059 - metaMain|S1059: metaMain]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1560.003 - Archive via Custom Method|T1560.003: Archive via Custom Method]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[metaMain](https://attack.mitre.org/software/S1059) has used XOR-based encryption for collected files before exfiltration.(Citation: SentinelLabs Metador Sept 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--609a0483-ac4a-49d6-bc5d-3cb0ff6e8a97`.
