---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1200"
target_object: "T1685"
stix_relationship_id: "relationship--d28f8ff7-5dfc-4113-a4bf-cdb0ea1e5812"
---
# Relationship 2799: S1200 — uses → T1685

**Source object:** [[01 ATT&CK/S1200 - StealBit|S1200: StealBit]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1685 - Disable or Modify Tools|T1685: Disable or Modify Tools]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[StealBit](https://attack.mitre.org/software/S1200) can configure processes to not display certain Windows error messages by through use of the `NtSetInformationProcess`.(Citation: Cybereason StealBit Exfiltration Tool)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d28f8ff7-5dfc-4113-a4bf-cdb0ea1e5812`.
