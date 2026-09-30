---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1240"
target_object: "T1614"
stix_relationship_id: "relationship--79275d9c-25cb-4792-8ac9-57009b44bd35"
---
# Relationship 3599: S1240 — uses → T1614

**Source object:** [[01 ATT&CK/S1240 - RedLine Stealer|S1240: RedLine Stealer]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1614 - System Location Discovery|T1614: System Location Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[RedLine Stealer](https://attack.mitre.org/software/S1240) has gathered detailed information about victims’ systems, such as IP addresses, and geolocation.(Citation: ESET RedLine Stealer November 2024)(Citation: Kroll RedLine Stealer August 2024)(Citation: Proofpoint RedLine Stealer March 2020) [RedLine Stealer](https://attack.mitre.org/software/S1240) has also checked the IP from where it was being executed and leveraged an opensource geolocation IP-lookup service. (Citation: McAfee RedLine Stealer April 2024)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--79275d9c-25cb-4792-8ac9-57009b44bd35`.
