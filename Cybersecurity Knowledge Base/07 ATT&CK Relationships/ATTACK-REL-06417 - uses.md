---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0010"
target_object: "S1042"
stix_relationship_id: "relationship--078ceddf-b534-4e33-acf8-8181adb249f2"
---
# Relationship 6417: C0010 — uses → S1042

**Source object:** [[01 ATT&CK/C0010 - C0010|C0010: C0010]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S1042 - SUGARDUMP|S1042: SUGARDUMP]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

(Citation: Mandiant UNC3890 Aug 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--078ceddf-b534-4e33-acf8-8181adb249f2`.
