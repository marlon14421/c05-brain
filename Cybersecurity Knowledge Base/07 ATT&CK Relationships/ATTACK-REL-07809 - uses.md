---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0038"
target_object: "T1573.001"
stix_relationship_id: "relationship--73da57b5-e64f-44ee-85f7-d294c21fb534"
---
# Relationship 7809: G0038 — uses → T1573.001

**Source object:** [[01 ATT&CK/G0038 - Stealth Falcon|G0038: Stealth Falcon]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1573.001 - Symmetric Cryptography|T1573.001: Symmetric Cryptography]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Stealth Falcon](https://attack.mitre.org/groups/G0038) malware encrypts C2 traffic using RC4 with a hard-coded key.(Citation: Citizen Lab Stealth Falcon May 2016)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--73da57b5-e64f-44ee-85f7-d294c21fb534`.
