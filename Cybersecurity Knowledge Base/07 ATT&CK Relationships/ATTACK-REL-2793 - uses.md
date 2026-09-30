---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0112"
target_object: "T1071.001"
stix_relationship_id: "relationship--aca30dc6-34c2-45f3-87a4-9d9abda01036"
---
# Relationship 2793: G0112 — uses → T1071.001

**Source object:** [[01 ATT&CK/G0112 - Windshift|G0112: Windshift]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1071.001 - Web Protocols|T1071.001: Web Protocols]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Windshift](https://attack.mitre.org/groups/G0112) has used tools that communicate with C2 over HTTP.(Citation: BlackBerry Bahamut)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--aca30dc6-34c2-45f3-87a4-9d9abda01036`.
