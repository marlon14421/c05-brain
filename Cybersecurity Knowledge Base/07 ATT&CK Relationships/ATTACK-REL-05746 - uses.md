---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0044"
target_object: "T1132.001"
stix_relationship_id: "relationship--654d5d71-a4ab-4768-8089-fddc3b1c63ad"
---
# Relationship 5746: C0044 — uses → T1132.001

**Source object:** [[01 ATT&CK/C0044 - Juicy Mix|C0044: Juicy Mix]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1132.001 - Standard Encoding|T1132.001: Standard Encoding]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

During [Juicy Mix](https://attack.mitre.org/campaigns/C0044), [OilRig](https://attack.mitre.org/groups/G0049) used a VBS script to send the Base64-encoded name of the compromised computer to C2.(Citation: ESET OilRig Campaigns Sep 2023)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--654d5d71-a4ab-4768-8089-fddc3b1c63ad`.
