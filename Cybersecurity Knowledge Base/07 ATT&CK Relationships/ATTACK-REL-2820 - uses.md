---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1240"
target_object: "T1218.007"
stix_relationship_id: "relationship--ae711f8d-3b42-405f-8e31-fdb561f08a79"
---
# Relationship 2820: S1240 — uses → T1218.007

**Source object:** [[01 ATT&CK/S1240 - RedLine Stealer|S1240: RedLine Stealer]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1218.007 - Msiexec|T1218.007: Msiexec]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[RedLine Stealer](https://attack.mitre.org/software/S1240) has been installed via MSI Installer.(Citation: McAfee RedLine Stealer April 2024)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--ae711f8d-3b42-405f-8e31-fdb561f08a79`.
