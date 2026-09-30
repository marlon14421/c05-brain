---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0394"
target_object: "T1014"
stix_relationship_id: "relationship--8a8e30e6-c226-4739-87de-bd98c104d211"
---
# Relationship 4233: S0394 — uses → T1014

**Source object:** [[01 ATT&CK/S0394 - HiddenWasp|S0394: HiddenWasp]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1014 - Rootkit|T1014: Rootkit]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[HiddenWasp](https://attack.mitre.org/software/S0394) uses a rootkit to hook and implement functions on the system.(Citation: Intezer HiddenWasp Map 2019)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--8a8e30e6-c226-4739-87de-bd98c104d211`.
