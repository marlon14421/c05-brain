---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0017"
target_object: "T1574"
stix_relationship_id: "relationship--84f6c3c2-8758-4179-98ca-74e9f726fe7d"
---
# Relationship 5793: C0017 — uses → T1574

**Source object:** [[01 ATT&CK/C0017 - C0017|C0017: C0017]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1574 - Hijack Execution Flow|T1574: Hijack Execution Flow]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

During [C0017](https://attack.mitre.org/campaigns/C0017), [APT41](https://attack.mitre.org/groups/G0096) established persistence by loading malicious libraries via modifications to the Import Address Table (IAT) within legitimate Microsoft binaries.(Citation: Mandiant APT41)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--84f6c3c2-8758-4179-98ca-74e9f726fe7d`.
