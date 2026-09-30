---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0572"
target_object: "T1082"
stix_relationship_id: "relationship--b844919a-e7d8-4317-9f0d-56338bae818c"
---
# Relationship 4702: S0572 — uses → T1082

**Source object:** [[01 ATT&CK/S0572 - Caterpillar WebShell|S0572: Caterpillar WebShell]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1082 - System Information Discovery|T1082: System Information Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Caterpillar WebShell](https://attack.mitre.org/software/S0572) has a module to gather information from the compromised asset, including the computer version, computer name, IIS version, and more.(Citation: ClearSky Lebanese Cedar Jan 2021)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--b844919a-e7d8-4317-9f0d-56338bae818c`.
