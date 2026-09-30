---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9007"
target_object: "T1106"
stix_relationship_id: "relationship--c57537e2-2b0e-4024-99fd-41b8aa1e7b07"
---
# Relationship 6440: S9007 — uses → T1106

**Source object:** [[01 ATT&CK/S9007 - HTTPTroy|S9007: HTTPTroy]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1106 - Native API|T1106: Native API]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[HTTPTroy](https://attack.mitre.org/software/S9007) has leveraged Windows Native API calls, including `GetProcAddress` to execute functions in memory.(Citation: Gen Digital Kimsuky HTTPTroy October 2025)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c57537e2-2b0e-4024-99fd-41b8aa1e7b07`.
