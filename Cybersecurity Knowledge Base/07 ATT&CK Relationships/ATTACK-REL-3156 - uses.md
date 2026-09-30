---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9010"
target_object: "T1565.002"
stix_relationship_id: "relationship--9260c5d3-a816-4ab9-9582-0b2fe95a9261"
---
# Relationship 3156: S9010 — uses → T1565.002

**Source object:** [[01 ATT&CK/S9010 - GlassWorm|S9010: GlassWorm]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1565.002 - Transmitted Data Manipulation|T1565.002: Transmitted Data Manipulation]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[GlassWorm](https://attack.mitre.org/software/S9010) can intercept and modify transaction details associated with hardware wallet applications before signing.(Citation: Koi Glassworm New Tricks December 2025)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--9260c5d3-a816-4ab9-9582-0b2fe95a9261`.
