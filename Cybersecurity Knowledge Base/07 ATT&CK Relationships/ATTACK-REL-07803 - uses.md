---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1200"
target_object: "T1071.001"
stix_relationship_id: "relationship--e9dbb844-f82d-4adf-b94a-ba181935a318"
---
# Relationship 7803: S1200 — uses → T1071.001

**Source object:** [[01 ATT&CK/S1200 - StealBit|S1200: StealBit]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1071.001 - Web Protocols|T1071.001: Web Protocols]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[StealBit](https://attack.mitre.org/software/S1200) can use HTTP to exfiltrate files to actor-controlled infrastructure.(Citation: FBI Lockbit 2.0 FEB 2022)(Citation: Cybereason StealBit Exfiltration Tool)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e9dbb844-f82d-4adf-b94a-ba181935a318`.
