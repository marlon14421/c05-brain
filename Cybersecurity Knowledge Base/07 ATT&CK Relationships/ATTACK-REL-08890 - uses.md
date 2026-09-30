---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0601"
target_object: "T1014"
stix_relationship_id: "relationship--8f5fdbbc-73b1-48a6-9916-67c0baa0f66e"
---
# Relationship 8890: S0601 — uses → T1014

**Source object:** [[01 ATT&CK/S0601 - Hildegard|S0601: Hildegard]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1014 - Rootkit|T1014: Rootkit]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Hildegard](https://attack.mitre.org/software/S0601) has modified /etc/ld.so.preload to overwrite readdir() and readdir64().(Citation: Unit 42 Hildegard Malware)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--8f5fdbbc-73b1-48a6-9916-67c0baa0f66e`.
