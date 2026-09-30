---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1124"
target_object: "T1036.005"
stix_relationship_id: "relationship--71d14fd4-c393-4dd9-9ae3-3970295ac4a5"
---
# Relationship 4422: S1124 — uses → T1036.005

**Source object:** [[01 ATT&CK/S1124 - SocGholish|S1124: SocGholish]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1036.005 - Match Legitimate Resource Name or Location|T1036.005: Match Legitimate Resource Name or Location]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[SocGholish](https://attack.mitre.org/software/S1124) has been named `AutoUpdater.js` to mimic legitimate update files.(Citation: SocGholish-update)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--71d14fd4-c393-4dd9-9ae3-3970295ac4a5`.
