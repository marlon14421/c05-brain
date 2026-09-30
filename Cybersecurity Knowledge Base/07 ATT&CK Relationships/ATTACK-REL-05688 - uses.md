---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1200"
target_object: "T1083"
stix_relationship_id: "relationship--ffb9fa57-09be-4812-ae15-b7b16b024811"
---
# Relationship 5688: S1200 — uses → T1083

**Source object:** [[01 ATT&CK/S1200 - StealBit|S1200: StealBit]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1083 - File and Directory Discovery|T1083: File and Directory Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[StealBit](https://attack.mitre.org/software/S1200) can be configured to exfiltrate specific file types.(Citation: FBI Lockbit 2.0 FEB 2022)(Citation: Cybereason StealBit Exfiltration Tool)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--ffb9fa57-09be-4812-ae15-b7b16b024811`.
