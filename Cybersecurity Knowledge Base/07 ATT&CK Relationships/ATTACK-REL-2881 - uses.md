---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0016"
target_object: "T1665"
stix_relationship_id: "relationship--b6a99c7b-0c5c-4d07-ad28-273648ae081e"
---
# Relationship 2881: G0016 — uses → T1665

**Source object:** [[01 ATT&CK/G0016 - APT29|G0016: APT29]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1665 - Hide Infrastructure|T1665: Hide Infrastructure]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[APT29](https://attack.mitre.org/groups/G0016) uses compromised residential endpoints, typically within the same ISP IP address range, as proxies to hide the true source of C2 traffic.(Citation: NCSC et al APT29 2024)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--b6a99c7b-0c5c-4d07-ad28-273648ae081e`.
