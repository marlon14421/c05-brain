---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1149"
target_object: "T1027.009"
stix_relationship_id: "relationship--3a1ee04f-672a-4fc6-80fe-40feb5472625"
---
# Relationship 9006: S1149 — uses → T1027.009

**Source object:** [[01 ATT&CK/S1149 - CHIMNEYSWEEP|S1149: CHIMNEYSWEEP]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027.009 - Embedded Payloads|T1027.009: Embedded Payloads]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[CHIMNEYSWEEP](https://attack.mitre.org/software/S1149) can extract RC4 encrypted embedded payloads for privilege escalation.(Citation: Mandiant ROADSWEEP August 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--3a1ee04f-672a-4fc6-80fe-40feb5472625`.
