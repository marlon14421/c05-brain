---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0669"
target_object: "T1036.005"
stix_relationship_id: "relationship--b3dac4f5-b074-41fa-8737-280c3369c73e"
---
# Relationship 4110: S0669 — uses → T1036.005

**Source object:** [[01 ATT&CK/S0669 - KOCTOPUS|S0669: KOCTOPUS]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1036.005 - Match Legitimate Resource Name or Location|T1036.005: Match Legitimate Resource Name or Location]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[KOCTOPUS](https://attack.mitre.org/software/S0669) has been disguised as legitimate software programs associated with the travel and airline industries.(Citation: Arghire LazyScripter)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--b3dac4f5-b074-41fa-8737-280c3369c73e`.
