---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1154"
target_object: "T1129"
stix_relationship_id: "relationship--fd385a66-84ba-4bd5-8ab2-afd7c7699e57"
---
# Relationship 5994: S1154 — uses → T1129

**Source object:** [[01 ATT&CK/S1154 - VersaMem|S1154: VersaMem]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1129 - Shared Modules|T1129: Shared Modules]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[VersaMem](https://attack.mitre.org/software/S1154) relied on the Java Instrumentation API and Javassist to dynamically modify Java code existing in memory.(Citation: Lumen Versa 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--fd385a66-84ba-4bd5-8ab2-afd7c7699e57`.
