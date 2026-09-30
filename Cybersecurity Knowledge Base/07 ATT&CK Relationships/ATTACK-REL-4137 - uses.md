---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0117"
target_object: "T1190"
stix_relationship_id: "relationship--6d4f3696-caa9-4100-bef5-e42d0f18470e"
---
# Relationship 4137: G0117 — uses → T1190

**Source object:** [[01 ATT&CK/G0117 - Fox Kitten|G0117: Fox Kitten]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1190 - Exploit Public-Facing Application|T1190: Exploit Public-Facing Application]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Fox Kitten](https://attack.mitre.org/groups/G0117) has exploited known vulnerabilities in Fortinet, PulseSecure, and Palo Alto VPN appliances.(Citation: ClearkSky Fox Kitten February 2020)(Citation: Dragos PARISITE )(Citation: CrowdStrike PIONEER KITTEN August 2020)(Citation: CISA AA20-259A Iran-Based Actor September 2020)(Citation: ClearSky Pay2Kitten December 2020)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--6d4f3696-caa9-4100-bef5-e42d0f18470e`.
