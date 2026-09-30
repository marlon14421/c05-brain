---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0276"
target_object: "T1071.001"
stix_relationship_id: "relationship--39556624-1c45-4178-bfa4-7a20b254df7e"
---
# Relationship 3665: S0276 — uses → T1071.001

**Source object:** [[01 ATT&CK/S0276 - Keydnap|S0276: Keydnap]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1071.001 - Web Protocols|T1071.001: Web Protocols]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Keydnap](https://attack.mitre.org/software/S0276) uses HTTPS for command and control.(Citation: synack 2016 review)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--39556624-1c45-4178-bfa4-7a20b254df7e`.
