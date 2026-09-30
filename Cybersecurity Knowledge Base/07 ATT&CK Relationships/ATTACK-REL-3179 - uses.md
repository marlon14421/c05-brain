---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0234"
target_object: "T1027.003"
stix_relationship_id: "relationship--5791055c-1a0c-460e-91cc-7d85278ce533"
---
# Relationship 3179: S0234 — uses → T1027.003

**Source object:** [[01 ATT&CK/S0234 - Bandook|S0234: Bandook]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027.003 - Steganography|T1027.003: Steganography]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Bandook](https://attack.mitre.org/software/S0234) has used .PNG images within a zip file to build the executable. (Citation: CheckPoint Bandook Nov 2020)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--5791055c-1a0c-460e-91cc-7d85278ce533`.
