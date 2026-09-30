---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0633"
target_object: "T1016"
stix_relationship_id: "relationship--8babd998-d5ca-43b4-9a68-a20d5b84cf61"
---
# Relationship 4155: S0633 — uses → T1016

**Source object:** [[01 ATT&CK/S0633 - Sliver|S0633: Sliver]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1016 - System Network Configuration Discovery|T1016: System Network Configuration Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Sliver](https://attack.mitre.org/software/S0633) has the ability to gather network configuration information.(Citation: GitHub Sliver Ifconfig)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--8babd998-d5ca-43b4-9a68-a20d5b84cf61`.
