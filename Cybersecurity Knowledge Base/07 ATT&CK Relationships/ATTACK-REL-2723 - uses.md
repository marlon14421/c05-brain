---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0041"
target_object: "T1556.002"
stix_relationship_id: "relationship--8cbb1567-70c5-4daf-b163-cbc6cc40a794"
---
# Relationship 2723: G0041 — uses → T1556.002

**Source object:** [[01 ATT&CK/G0041 - Strider|G0041: Strider]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1556.002 - Password Filter DLL|T1556.002: Password Filter DLL]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Strider](https://attack.mitre.org/groups/G0041) has registered its persistence module on domain controllers as a Windows LSA (Local System Authority) password filter to acquire credentials any time a domain, local user, or administrator logs in or changes a password.(Citation: Kaspersky ProjectSauron Full Report)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--8cbb1567-70c5-4daf-b163-cbc6cc40a794`.
