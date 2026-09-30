---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0093"
target_object: "T1041"
stix_relationship_id: "relationship--380743e5-616c-4524-96e6-d545e5b653ea"
---
# Relationship 3276: G0093 — uses → T1041

**Source object:** [[01 ATT&CK/G0093 - GALLIUM|G0093: GALLIUM]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1041 - Exfiltration Over C2 Channel|T1041: Exfiltration Over C2 Channel]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[GALLIUM](https://attack.mitre.org/groups/G0093) used Web shells and [HTRAN](https://attack.mitre.org/software/S0040) for C2 and to exfiltrate data.(Citation: Cybereason Soft Cell June 2019)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--380743e5-616c-4524-96e6-d545e5b653ea`.
