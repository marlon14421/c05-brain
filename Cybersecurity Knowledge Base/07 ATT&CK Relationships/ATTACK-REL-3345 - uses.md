---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0570"
target_object: "T1490"
stix_relationship_id: "relationship--833e14f8-0f37-488a-a67c-3ff2fe524ac3"
---
# Relationship 3345: S0570 — uses → T1490

**Source object:** [[01 ATT&CK/S0570 - BitPaymer|S0570: BitPaymer]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1490 - Inhibit System Recovery|T1490: Inhibit System Recovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[BitPaymer](https://attack.mitre.org/software/S0570) attempts to remove the backup shadow files from the host using vssadmin.exe Delete Shadows /All /Quiet .(Citation: Crowdstrike Indrik November 2018)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--833e14f8-0f37-488a-a67c-3ff2fe524ac3`.
