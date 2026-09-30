---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0022"
target_object: "T1588.002"
stix_relationship_id: "relationship--b6f6b1e0-8e37-4f0a-b506-66537d3f0ff0"
---
# Relationship 8098: C0022 — uses → T1588.002

**Source object:** [[01 ATT&CK/C0022 - Operation Dream Job|C0022: Operation Dream Job]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1588.002 - Tool|T1588.002: Tool]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

For [Operation Dream Job](https://attack.mitre.org/campaigns/C0022), [Lazarus Group](https://attack.mitre.org/groups/G0032) obtained tools such as Wake-On-Lan, [Responder](https://attack.mitre.org/software/S0174), ChromePass, and dbxcli.(Citation: ClearSky Lazarus Aug 2020)(Citation: ESET Lazarus Jun 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--b6f6b1e0-8e37-4f0a-b506-66537d3f0ff0`.
