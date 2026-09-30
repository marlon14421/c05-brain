---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1039"
target_object: "T1027"
stix_relationship_id: "relationship--a0040bac-4445-4999-bf0f-53b340f02218"
---
# Relationship 8529: S1039 — uses → T1027

**Source object:** [[01 ATT&CK/S1039 - Bumblebee|S1039: Bumblebee]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027 - Obfuscated Files or Information|T1027: Obfuscated Files or Information]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Bumblebee](https://attack.mitre.org/software/S1039) has been delivered as password-protected zipped ISO files and used control-flow-flattening to obfuscate the flow of functions.(Citation: Proofpoint Bumblebee April 2022)(Citation: Cybereason Bumblebee August 2022)(Citation: Medium Ali Salem Bumblebee April 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a0040bac-4445-4999-bf0f-53b340f02218`.
