---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0028"
target_object: "T1072"
stix_relationship_id: "relationship--b38cfcfd-b8e3-4a9c-ade9-8a8bfeb04694"
---
# Relationship 6891: G0028 — uses → T1072

**Source object:** [[01 ATT&CK/G0028 - Threat Group-1314|G0028: Threat Group-1314]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1072 - Software Deployment Tools|T1072: Software Deployment Tools]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Threat Group-1314](https://attack.mitre.org/groups/G0028) actors used a victim's endpoint management platform, Altiris, for lateral movement.(Citation: Dell TG-1314)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--b38cfcfd-b8e3-4a9c-ade9-8a8bfeb04694`.
