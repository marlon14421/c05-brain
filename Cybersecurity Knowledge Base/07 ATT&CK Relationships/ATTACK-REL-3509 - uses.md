---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0245"
target_object: "T1082"
stix_relationship_id: "relationship--8840d33c-de12-45d5-a0e3-cdfddf789794"
---
# Relationship 3509: S0245 — uses → T1082

**Source object:** [[01 ATT&CK/S0245 - BADCALL|S0245: BADCALL]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1082 - System Information Discovery|T1082: System Information Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[BADCALL](https://attack.mitre.org/software/S0245) collects the computer name and host name on the compromised system.(Citation: US-CERT BADCALL)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--8840d33c-de12-45d5-a0e3-cdfddf789794`.
