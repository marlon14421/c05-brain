---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0022"
target_object: "T1546.008"
stix_relationship_id: "relationship--a92197a8-ec5c-4366-92af-f45078a3bfd7"
---
# Relationship 4083: G0022 — uses → T1546.008

**Source object:** [[01 ATT&CK/G0022 - APT3|G0022: APT3]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1546.008 - Accessibility Features|T1546.008: Accessibility Features]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[APT3](https://attack.mitre.org/groups/G0022) replaces the Sticky Keys binary C:\Windows\System32\sethc.exe for persistence.(Citation: aptsim)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a92197a8-ec5c-4366-92af-f45078a3bfd7`.
