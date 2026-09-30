---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0562"
target_object: "T1565.001"
stix_relationship_id: "relationship--41d6749b-9bd1-47f6-80c4-52652b965e78"
---
# Relationship 2828: S0562 — uses → T1565.001

**Source object:** [[01 ATT&CK/S0562 - SUNSPOT|S0562: SUNSPOT]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1565.001 - Stored Data Manipulation|T1565.001: Stored Data Manipulation]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[SUNSPOT](https://attack.mitre.org/software/S0562) created a copy of the SolarWinds Orion software source file with a .bk extension to backup the original content, wrote [SUNBURST](https://attack.mitre.org/software/S0559) using the same filename but with a .tmp extension, and then moved [SUNBURST](https://attack.mitre.org/software/S0559) using MoveFileEx to the original filename with a .cs extension so it could be compiled within Orion software.(Citation: CrowdStrike SUNSPOT Implant January 2021)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--41d6749b-9bd1-47f6-80c4-52652b965e78`.
