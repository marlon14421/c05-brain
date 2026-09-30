---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0013"
target_object: "T1049"
stix_relationship_id: "relationship--8b020cdd-4731-4dd5-8407-7f3076ab1d2d"
---
# Relationship 4909: S0013 — uses → T1049

**Source object:** [[01 ATT&CK/S0013 - PlugX|S0013: PlugX]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1049 - System Network Connections Discovery|T1049: System Network Connections Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[PlugX](https://attack.mitre.org/software/S0013) has a module for enumerating TCP and UDP network connections and associated processes using the netstat command.(Citation: CIRCL PlugX March 2013)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--8b020cdd-4731-4dd5-8407-7f3076ab1d2d`.
