---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1025"
target_object: "T1106"
stix_relationship_id: "relationship--26818c78-7042-4493-a94b-eec0d7b9972a"
---
# Relationship 8238: S1025 — uses → T1106

**Source object:** [[01 ATT&CK/S1025 - Amadey|S1025: Amadey]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1106 - Native API|T1106: Native API]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Amadey](https://attack.mitre.org/software/S1025) has used a variety of Windows API calls, including `GetComputerNameA`, `GetUserNameA`, and `CreateProcessA`.(Citation: BlackBerry Amadey 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--26818c78-7042-4493-a94b-eec0d7b9972a`.
