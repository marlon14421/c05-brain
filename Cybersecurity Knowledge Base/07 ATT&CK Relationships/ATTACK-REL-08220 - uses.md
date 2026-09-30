---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0044"
target_object: "T1555.003"
stix_relationship_id: "relationship--fe5fd754-0170-44ac-a51c-cf2efba3bfee"
---
# Relationship 8220: C0044 — uses → T1555.003

**Source object:** [[01 ATT&CK/C0044 - Juicy Mix|C0044: Juicy Mix]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1555.003 - Credentials from Web Browsers|T1555.003: Credentials from Web Browsers]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

During [Juicy Mix](https://attack.mitre.org/campaigns/C0044), [OilRig](https://attack.mitre.org/groups/G0049) used the CDumper (Chrome browser) and EDumper (Edge browser) to collect credentials.(Citation: ESET OilRig Campaigns Sep 2023)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--fe5fd754-0170-44ac-a51c-cf2efba3bfee`.
