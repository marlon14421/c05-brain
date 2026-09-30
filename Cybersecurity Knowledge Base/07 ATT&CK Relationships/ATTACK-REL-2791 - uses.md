---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0622"
target_object: "T1057"
stix_relationship_id: "relationship--49944838-b6f8-4e1c-94d4-5b70cb436700"
---
# Relationship 2791: S0622 — uses → T1057

**Source object:** [[01 ATT&CK/S0622 - AppleSeed|S0622: AppleSeed]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1057 - Process Discovery|T1057: Process Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[AppleSeed](https://attack.mitre.org/software/S0622) can enumerate the current process on a compromised host.(Citation: Malwarebytes Kimsuky June 2021)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--49944838-b6f8-4e1c-94d4-5b70cb436700`.
