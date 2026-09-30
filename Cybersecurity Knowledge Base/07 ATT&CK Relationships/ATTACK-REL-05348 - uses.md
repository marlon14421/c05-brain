---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1096"
target_object: "T1083"
stix_relationship_id: "relationship--e2f772c3-0822-4c4c-8a8d-51094349ccc5"
---
# Relationship 5348: S1096 — uses → T1083

**Source object:** [[01 ATT&CK/S1096 - Cheerscrypt|S1096: Cheerscrypt]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1083 - File and Directory Discovery|T1083: File and Directory Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Cheerscrypt](https://attack.mitre.org/software/S1096) can search for log and VMware-related files with .log, .vmdk, .vmem, .vswp, and .vmsn extensions.(Citation: Trend Micro Cheerscrypt May 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e2f772c3-0822-4c4c-8a8d-51094349ccc5`.
