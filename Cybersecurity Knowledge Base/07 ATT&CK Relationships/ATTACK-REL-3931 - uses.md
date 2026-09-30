---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0106"
target_object: "T1021.004"
stix_relationship_id: "relationship--fa69ac7a-8031-4fac-91e2-65e90f378cd1"
---
# Relationship 3931: G0106 — uses → T1021.004

**Source object:** [[01 ATT&CK/G0106 - Rocke|G0106: Rocke]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1021.004 - SSH|T1021.004: SSH]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Rocke](https://attack.mitre.org/groups/G0106) has spread its coinminer via SSH.(Citation: Anomali Rocke March 2019)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--fa69ac7a-8031-4fac-91e2-65e90f378cd1`.
