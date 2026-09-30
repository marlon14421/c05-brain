---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0028"
target_object: "T1021.002"
stix_relationship_id: "relationship--0512a63b-58c8-4b0c-b2b4-e4da562cee5f"
---
# Relationship 9284: G0028 — uses → T1021.002

**Source object:** [[01 ATT&CK/G0028 - Threat Group-1314|G0028: Threat Group-1314]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1021.002 - SMB-Windows Admin Shares|T1021.002: SMB/Windows Admin Shares]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Threat Group-1314](https://attack.mitre.org/groups/G0028) actors mapped network drives using net use .(Citation: Dell TG-1314)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--0512a63b-58c8-4b0c-b2b4-e4da562cee5f`.
