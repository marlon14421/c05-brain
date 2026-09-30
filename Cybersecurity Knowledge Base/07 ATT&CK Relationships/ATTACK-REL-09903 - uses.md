---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1059"
target_object: "T1070.006"
stix_relationship_id: "relationship--ecbe0204-b205-47d5-ba6a-ef5c29737eda"
---
# Relationship 9903: S1059 — uses → T1070.006

**Source object:** [[01 ATT&CK/S1059 - metaMain|S1059: metaMain]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1070.006 - Timestomp|T1070.006: Timestomp]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[metaMain](https://attack.mitre.org/software/S1059) can change the `CreationTime`, `LastAccessTime`, and `LastWriteTime` file time attributes when executed with `SYSTEM` privileges.(Citation: SentinelLabs Metador Technical Appendix Sept 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--ecbe0204-b205-47d5-ba6a-ef5c29737eda`.
