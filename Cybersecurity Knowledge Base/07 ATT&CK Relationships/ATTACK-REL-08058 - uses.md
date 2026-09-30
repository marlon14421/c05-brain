---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0047"
target_object: "T1059.003"
stix_relationship_id: "relationship--f73df541-6b55-42d1-aec3-53660fda1508"
---
# Relationship 8058: G0047 — uses → T1059.003

**Source object:** [[01 ATT&CK/G0047 - Gamaredon Group|G0047: Gamaredon Group]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.003 - Windows Command Shell|T1059.003: Windows Command Shell]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Gamaredon Group](https://attack.mitre.org/groups/G0047) has used various batch scripts to establish C2 and download additional files. [Gamaredon Group](https://attack.mitre.org/groups/G0047)'s backdoor malware has also been written to a batch file.(Citation: Palo Alto Gamaredon Feb 2017)(Citation: ESET Gamaredon June 2020)(Citation: CERT-EE Gamaredon January 2021)(Citation: Unit 42 Gamaredon February 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--f73df541-6b55-42d1-aec3-53660fda1508`.
