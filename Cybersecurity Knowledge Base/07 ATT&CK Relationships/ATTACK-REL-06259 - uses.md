---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0044"
target_object: "T1082"
stix_relationship_id: "relationship--ad60db1c-ea28-4f3d-8ba3-d30a76a4751b"
---
# Relationship 6259: C0044 — uses → T1082

**Source object:** [[01 ATT&CK/C0044 - Juicy Mix|C0044: Juicy Mix]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1082 - System Information Discovery|T1082: System Information Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

During [Juicy Mix](https://attack.mitre.org/campaigns/C0044), [OilRig](https://attack.mitre.org/groups/G0049) used a script to send the name of the compromised host via HTTP `POST` to register it with C2.(Citation: ESET OilRig Campaigns Sep 2023)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--ad60db1c-ea28-4f3d-8ba3-d30a76a4751b`.
