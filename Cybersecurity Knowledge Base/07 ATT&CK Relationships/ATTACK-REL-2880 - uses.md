---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0268"
target_object: "T1036"
stix_relationship_id: "relationship--ffff35dc-3741-4fba-9680-f0fbe321c0b0"
---
# Relationship 2880: S0268 — uses → T1036

**Source object:** [[01 ATT&CK/S0268 - Bisonal|S0268: Bisonal]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1036 - Masquerading|T1036: Masquerading]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Bisonal](https://attack.mitre.org/software/S0268) dropped a decoy payload with a .jpg extension that contained a malicious Visual Basic script.(Citation: Talos Bisonal Mar 2020)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--ffff35dc-3741-4fba-9680-f0fbe321c0b0`.
