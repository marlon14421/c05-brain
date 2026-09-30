---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0589"
target_object: "T1071.001"
stix_relationship_id: "relationship--fbc77ca5-46b1-4c5b-8e48-d053d1eb238d"
---
# Relationship 4416: S0589 — uses → T1071.001

**Source object:** [[01 ATT&CK/S0589 - Sibot|S0589: Sibot]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1071.001 - Web Protocols|T1071.001: Web Protocols]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Sibot](https://attack.mitre.org/software/S0589) communicated with its C2 server via HTTP GET requests.(Citation: MSTIC NOBELIUM Mar 2021)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--fbc77ca5-46b1-4c5b-8e48-d053d1eb238d`.
