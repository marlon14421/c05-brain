---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0082"
target_object: "T1690"
stix_relationship_id: "relationship--9ea5c70d-6f04-4530-925a-5fa0c3521b79"
---
# Relationship 3576: G0082 — uses → T1690

**Source object:** [[01 ATT&CK/G0082 - APT38|G0082: APT38]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1690 - Prevent Command History Logging|T1690: Prevent Command History Logging]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[APT38](https://attack.mitre.org/groups/G0082) has prepended a space to all of their terminal commands to operate without leaving traces in the HISTCONTROL environment.(Citation: CISA AA20-239A BeagleBoyz August 2020)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--9ea5c70d-6f04-4530-925a-5fa0c3521b79`.
