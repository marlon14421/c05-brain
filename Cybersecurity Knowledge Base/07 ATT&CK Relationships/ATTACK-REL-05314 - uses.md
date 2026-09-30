---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0138"
target_object: "T1592.002"
stix_relationship_id: "relationship--9fc2e926-e5a9-4c56-8d7c-cdef9dd7f7ab"
---
# Relationship 5314: G0138 — uses → T1592.002

**Source object:** [[01 ATT&CK/G0138 - Andariel|G0138: Andariel]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1592.002 - Software|T1592.002: Software]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Andariel](https://attack.mitre.org/groups/G0138) has inserted a malicious script within compromised websites to collect potential victim information such as browser type, system language, Flash Player version, and other data.(Citation: TrendMicro New Andariel Tactics July 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--9fc2e926-e5a9-4c56-8d7c-cdef9dd7f7ab`.
