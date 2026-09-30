---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0350"
target_object: "T1033"
stix_relationship_id: "relationship--bd62c9fa-b1d4-4fb9-a892-99703e1f794d"
---
# Relationship 2770: S0350 — uses → T1033

**Source object:** [[01 ATT&CK/S0350 - zwShell|S0350: zwShell]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1033 - System Owner-User Discovery|T1033: System Owner/User Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[zwShell](https://attack.mitre.org/software/S0350) can obtain the name of the logged-in user on the victim.(Citation: McAfee Night Dragon)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--bd62c9fa-b1d4-4fb9-a892-99703e1f794d`.
