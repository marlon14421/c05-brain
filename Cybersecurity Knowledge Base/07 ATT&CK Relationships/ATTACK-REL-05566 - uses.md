---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0237"
target_object: "T1049"
stix_relationship_id: "relationship--27a36f9c-2292-4bf0-8c08-9ccfc1effffe"
---
# Relationship 5566: S0237 — uses → T1049

**Source object:** [[01 ATT&CK/S0237 - GravityRAT|S0237: GravityRAT]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1049 - System Network Connections Discovery|T1049: System Network Connections Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[GravityRAT](https://attack.mitre.org/software/S0237) uses the netstat command to find open ports on the victim’s machine.(Citation: Talos GravityRAT)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--27a36f9c-2292-4bf0-8c08-9ccfc1effffe`.
