---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0019"
target_object: "T1574.001"
stix_relationship_id: "relationship--d4657411-8fa6-4bbc-9ed0-474eafd14375"
---
# Relationship 6780: G0019 — uses → T1574.001

**Source object:** [[01 ATT&CK/G0019 - Naikon|G0019: Naikon]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1574.001 - DLL|T1574.001: DLL]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Naikon](https://attack.mitre.org/groups/G0019) has used DLL side-loading to load malicious DLL's into legitimate executables.(Citation: CheckPoint Naikon May 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d4657411-8fa6-4bbc-9ed0-474eafd14375`.
