---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1106"
target_object: "T1090.003"
stix_relationship_id: "relationship--bd95ad97-90ed-4d48-bd50-a4ac234d63ad"
---
# Relationship 8056: S1106 — uses → T1090.003

**Source object:** [[01 ATT&CK/S1106 - NGLite|S1106: NGLite]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1090.003 - Multi-hop Proxy|T1090.003: Multi-hop Proxy]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[NGLite](https://attack.mitre.org/software/S1106) has abused NKN infrastructure for its C2 communication.(Citation: NGLite Trojan)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--bd95ad97-90ed-4d48-bd50-a4ac234d63ad`.
