---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0016"
target_object: "T1078.004"
stix_relationship_id: "relationship--44ba0ff1-3858-4b2e-933d-e5dc00b4ca27"
---
# Relationship 3789: G0016 — uses → T1078.004

**Source object:** [[01 ATT&CK/G0016 - APT29|G0016: APT29]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1078.004 - Cloud Accounts|T1078.004: Cloud Accounts]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[APT29](https://attack.mitre.org/groups/G0016) has gained access to a global administrator account in Azure AD and has used `Service Principal` credentials in Exchange.(Citation: Mandiant APT29 Microsoft 365 2022)(Citation: Mandiant APT29 Eye Spy Email Nov 22)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--44ba0ff1-3858-4b2e-933d-e5dc00b4ca27`.
