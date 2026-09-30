---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0007"
target_object: "T1189"
stix_relationship_id: "relationship--51fcdcd6-9c5a-425a-ab87-92d4faeb2ea4"
---
# Relationship 4601: G0007 — uses → T1189

**Source object:** [[01 ATT&CK/G0007 - APT28|G0007: APT28]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1189 - Drive-by Compromise|T1189: Drive-by Compromise]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[APT28](https://attack.mitre.org/groups/G0007) has compromised targets via strategic web compromise utilizing custom exploit kits.(Citation: Secureworks IRON TWILIGHT Active Measures March 2017) [APT28](https://attack.mitre.org/groups/G0007) used reflected cross-site scripting (XSS) against government websites to redirect users to phishing webpages.(Citation: Leonard TAG 2023)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--51fcdcd6-9c5a-425a-ab87-92d4faeb2ea4`.
