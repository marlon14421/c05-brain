---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0654"
target_object: "T1197"
stix_relationship_id: "relationship--94e040f2-c1e7-4159-839f-c4a2497232f3"
---
# Relationship 8091: S0654 — uses → T1197

**Source object:** [[01 ATT&CK/S0654 - ProLock|S0654: ProLock]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1197 - BITS Jobs|T1197: BITS Jobs]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[ProLock](https://attack.mitre.org/software/S0654) can use BITS jobs to download its malicious payload.(Citation: Group IB Ransomware September 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--94e040f2-c1e7-4159-839f-c4a2497232f3`.
