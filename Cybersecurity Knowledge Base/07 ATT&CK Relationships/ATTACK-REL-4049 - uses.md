---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0492"
target_object: "T1059.006"
stix_relationship_id: "relationship--e2a29101-0b7e-4dab-adec-602712c09893"
---
# Relationship 4049: S0492 — uses → T1059.006

**Source object:** [[01 ATT&CK/S0492 - CookieMiner|S0492: CookieMiner]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.006 - Python|T1059.006: Python]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[CookieMiner](https://attack.mitre.org/software/S0492) has used python scripts on the user’s system, as well as the Python variant of the [Empire](https://attack.mitre.org/software/S0363) agent, EmPyre.(Citation: Unit42 CookieMiner Jan 2019)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e2a29101-0b7e-4dab-adec-602712c09893`.
