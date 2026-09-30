---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0607"
target_object: "T1489"
stix_relationship_id: "relationship--8efafb84-44c7-405d-96b6-55d12f397d01"
---
# Relationship 2848: S0607 — uses → T1489

**Source object:** [[01 ATT&CK/S0607 - KillDisk|S0607: KillDisk]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1489 - Service Stop|T1489: Service Stop]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[KillDisk](https://attack.mitre.org/software/S0607) terminates various processes to get the user to reboot the victim machine.(Citation: Trend Micro KillDisk 2)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--8efafb84-44c7-405d-96b6-55d12f397d01`.
