---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0040"
target_object: "T1036.005"
stix_relationship_id: "relationship--42d4ae64-75da-4dfd-b23f-d270252115ee"
---
# Relationship 4040: G0040 — uses → T1036.005

**Source object:** [[01 ATT&CK/G0040 - Patchwork|G0040: Patchwork]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1036.005 - Match Legitimate Resource Name or Location|T1036.005: Match Legitimate Resource Name or Location]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Patchwork](https://attack.mitre.org/groups/G0040) installed its payload in the startup programs folder as "Baidu Software Update." The group also adds its second stage payload to the startup programs as “Net Monitor."(Citation: Cymmetria Patchwork) They have also dropped [QuasarRAT](https://attack.mitre.org/software/S0262) binaries as files named microsoft_network.exe and crome.exe.(Citation: Volexity Patchwork June 2018)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--42d4ae64-75da-4dfd-b23f-d270252115ee`.
