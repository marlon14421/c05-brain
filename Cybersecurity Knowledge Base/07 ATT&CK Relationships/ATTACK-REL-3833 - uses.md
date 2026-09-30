---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0128"
target_object: "T1059.003"
stix_relationship_id: "relationship--a2a31eb7-0b22-416c-b12d-e52e5f37f8b8"
---
# Relationship 3833: S0128 — uses → T1059.003

**Source object:** [[01 ATT&CK/S0128 - BADNEWS|S0128: BADNEWS]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.003 - Windows Command Shell|T1059.003: Windows Command Shell]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[BADNEWS](https://attack.mitre.org/software/S0128) is capable of executing commands via cmd.exe.(Citation: Forcepoint Monsoon)(Citation: TrendMicro Patchwork Dec 2017)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a2a31eb7-0b22-416c-b12d-e52e5f37f8b8`.
