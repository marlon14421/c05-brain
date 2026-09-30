---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1018"
target_object: "T1497.001"
stix_relationship_id: "relationship--80933d22-6aa2-466d-95c2-af486b81c624"
---
# Relationship 3680: S1018 — uses → T1497.001

**Source object:** [[01 ATT&CK/S1018 - Saint Bot|S1018: Saint Bot]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1497.001 - System Checks|T1497.001: System Checks]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Saint Bot](https://attack.mitre.org/software/S1018) has run several virtual machine and sandbox checks, including checking if `Sbiedll.dll` is present in a list of loaded modules, comparing the machine name to `HAL9TH` and the user name to `JohnDoe`, and checking the BIOS version for known virtual machine identifiers.(Citation: Palo Alto Unit 42 OutSteel SaintBot February 2022 )

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--80933d22-6aa2-466d-95c2-af486b81c624`.
