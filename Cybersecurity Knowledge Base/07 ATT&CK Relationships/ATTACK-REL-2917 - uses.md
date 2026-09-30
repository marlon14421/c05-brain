---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0099"
target_object: "T1534"
stix_relationship_id: "relationship--96ebe8fc-85be-4652-b6dd-24f318b83129"
---
# Relationship 2917: G0099 — uses → T1534

**Source object:** [[01 ATT&CK/G0099 - APT-C-36|G0099: APT-C-36]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1534 - Internal Spearphishing|T1534: Internal Spearphishing]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[APT-C-36](https://attack.mitre.org/groups/G0099) has used a compromised account to send a phishing email to an address likely used and monitored by the IT team within the same targeted organization.(Citation: Zscaler BlindEagle DEC 2025)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--96ebe8fc-85be-4652-b6dd-24f318b83129`.
