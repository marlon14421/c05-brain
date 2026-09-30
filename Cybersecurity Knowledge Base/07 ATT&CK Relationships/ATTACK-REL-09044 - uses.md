---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1238"
target_object: "T1036.005"
stix_relationship_id: "relationship--b0e113b1-91b2-4f93-bd3c-c1d564096d34"
---
# Relationship 9044: S1238 — uses → T1036.005

**Source object:** [[01 ATT&CK/S1238 - STATICPLUGIN|S1238: STATICPLUGIN]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1036.005 - Match Legitimate Resource Name or Location|T1036.005: Match Legitimate Resource Name or Location]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[STATICPLUGIN](https://attack.mitre.org/software/S1238) has leveraged naming conventions that match legitimate services to include AdobePlugins.exe.(Citation: Google Threat Intelligence Group MUSTANG PANDA PLUGX August 2025)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--b0e113b1-91b2-4f93-bd3c-c1d564096d34`.
