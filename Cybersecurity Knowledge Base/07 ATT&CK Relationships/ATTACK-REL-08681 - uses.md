---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9007"
target_object: "T1041"
stix_relationship_id: "relationship--7acdc32c-1838-47f3-a0c3-2a902de15410"
---
# Relationship 8681: S9007 — uses → T1041

**Source object:** [[01 ATT&CK/S9007 - HTTPTroy|S9007: HTTPTroy]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1041 - Exfiltration Over C2 Channel|T1041: Exfiltration Over C2 Channel]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[HTTPTroy](https://attack.mitre.org/software/S9007) has exfiltrated encrypted data over the C2 channel using the `up ` command.(Citation: Gen Digital Kimsuky HTTPTroy October 2025)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--7acdc32c-1838-47f3-a0c3-2a902de15410`.
