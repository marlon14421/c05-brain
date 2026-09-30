---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0466"
target_object: "T1036"
stix_relationship_id: "relationship--81603db2-a657-4716-a7ca-e6562799e98e"
---
# Relationship 5093: S0466 — uses → T1036

**Source object:** [[01 ATT&CK/S0466 - WindTail|S0466: WindTail]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1036 - Masquerading|T1036: Masquerading]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[WindTail](https://attack.mitre.org/software/S0466) has used icons mimicking MS Office files to mask payloads.(Citation: objective-see windtail1 dec 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--81603db2-a657-4716-a7ca-e6562799e98e`.
