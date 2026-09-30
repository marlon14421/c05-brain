---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0024"
target_object: "T1082"
stix_relationship_id: "relationship--c1a4334d-8975-4ca2-8734-d6c26e36702a"
---
# Relationship 4292: S0024 — uses → T1082

**Source object:** [[01 ATT&CK/S0024 - Dyre|S0024: Dyre]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1082 - System Information Discovery|T1082: System Information Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Dyre](https://attack.mitre.org/software/S0024) has the ability to identify the computer name, OS version, and hardware configuration on a compromised host.(Citation: Malwarebytes Dyreza November 2015)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c1a4334d-8975-4ca2-8734-d6c26e36702a`.
