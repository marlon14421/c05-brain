---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1017"
target_object: "T1041"
stix_relationship_id: "relationship--0f483f1d-cd24-4446-8725-8af01fcd089c"
---
# Relationship 3517: S1017 — uses → T1041

**Source object:** [[01 ATT&CK/S1017 - OutSteel|S1017: OutSteel]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1041 - Exfiltration Over C2 Channel|T1041: Exfiltration Over C2 Channel]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[OutSteel](https://attack.mitre.org/software/S1017) can upload files from a compromised host over its C2 channel.(Citation: Palo Alto Unit 42 OutSteel SaintBot February 2022 )

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--0f483f1d-cd24-4446-8725-8af01fcd089c`.
