---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0449"
target_object: "T1036.004"
stix_relationship_id: "relationship--20cedb41-1f7b-44df-8d49-5d6fc166c557"
---
# Relationship 3823: S0449 — uses → T1036.004

**Source object:** [[01 ATT&CK/S0449 - Maze|S0449: Maze]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1036.004 - Masquerade Task or Service|T1036.004: Masquerade Task or Service]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Maze](https://attack.mitre.org/software/S0449) operators have created scheduled tasks masquerading as "Windows Update Security", "Windows Update Security Patches", and "Google Chrome Security Update" designed to launch the ransomware.(Citation: Sophos Maze VM September 2020)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--20cedb41-1f7b-44df-8d49-5d6fc166c557`.
