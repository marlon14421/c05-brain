---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0401"
target_object: "T1070.004"
stix_relationship_id: "relationship--9cc847b7-61ae-46f7-ab06-16560775d44b"
---
# Relationship 4271: S0401 — uses → T1070.004

**Source object:** [[01 ATT&CK/S0401 - Exaramel for Linux|S0401: Exaramel for Linux]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1070.004 - File Deletion|T1070.004: File Deletion]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Exaramel for Linux](https://attack.mitre.org/software/S0401) can uninstall its persistence mechanism and delete its configuration file.(Citation: ANSSI Sandworm January 2021)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--9cc847b7-61ae-46f7-ab06-16560775d44b`.
