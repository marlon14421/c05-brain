---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1202"
target_object: "T1135"
stix_relationship_id: "relationship--98b296c0-467b-4029-a813-0cd94c0a9520"
---
# Relationship 7381: S1202 — uses → T1135

**Source object:** [[01 ATT&CK/S1202 - LockBit 3.0|S1202: LockBit 3.0]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1135 - Network Share Discovery|T1135: Network Share Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[LockBit 3.0](https://attack.mitre.org/software/S1202) can identify network shares on compromised systems.(Citation: Joint Cybersecurity Advisory LockBit 3.0 MAR 2023)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--98b296c0-467b-4029-a813-0cd94c0a9520`.
