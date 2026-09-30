---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0036"
target_object: "T1005"
stix_relationship_id: "relationship--18324fed-7770-4768-b652-59860ac4782f"
---
# Relationship 4370: S0036 — uses → T1005

**Source object:** [[01 ATT&CK/S0036 - FLASHFLOOD|S0036: FLASHFLOOD]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1005 - Data from Local System|T1005: Data from Local System]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[FLASHFLOOD](https://attack.mitre.org/software/S0036) searches for interesting files (either a default or customized set of file extensions) on the local system. [FLASHFLOOD](https://attack.mitre.org/software/S0036) will scan the My Recent Documents, Desktop, Temporary Internet Files, and TEMP directories. [FLASHFLOOD](https://attack.mitre.org/software/S0036) also collects information stored in the Windows Address Book.(Citation: FireEye APT30)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--18324fed-7770-4768-b652-59860ac4782f`.
