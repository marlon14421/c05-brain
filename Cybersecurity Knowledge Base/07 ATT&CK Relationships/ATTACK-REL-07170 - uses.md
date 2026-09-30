---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0114"
target_object: "T1110.004"
stix_relationship_id: "relationship--bfc3568d-1304-43ce-be97-5fc4209d8a79"
---
# Relationship 7170: G0114 — uses → T1110.004

**Source object:** [[01 ATT&CK/G0114 - Chimera|G0114: Chimera]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1110.004 - Credential Stuffing|T1110.004: Credential Stuffing]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Chimera](https://attack.mitre.org/groups/G0114) has used credential stuffing against victim's remote services to obtain valid accounts.(Citation: NCC Group Chimera January 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--bfc3568d-1304-43ce-be97-5fc4209d8a79`.
