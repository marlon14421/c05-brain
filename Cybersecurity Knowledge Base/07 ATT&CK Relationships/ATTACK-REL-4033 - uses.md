---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0266"
target_object: "T1552.002"
stix_relationship_id: "relationship--91cff72f-644b-42e3-9c86-8cc6475f725a"
---
# Relationship 4033: S0266 — uses → T1552.002

**Source object:** [[01 ATT&CK/S0266 - TrickBot|S0266: TrickBot]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1552.002 - Credentials in Registry|T1552.002: Credentials in Registry]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[TrickBot](https://attack.mitre.org/software/S0266) has retrieved PuTTY credentials by querying the Software\SimonTatham\Putty\Sessions registry key (Citation: TrendMicro Trickbot Feb 2019)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--91cff72f-644b-42e3-9c86-8cc6475f725a`.
