---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0106"
target_object: "T1222.002"
stix_relationship_id: "relationship--a2f88508-4177-4294-b287-6a3494f6e738"
---
# Relationship 4680: G0106 — uses → T1222.002

**Source object:** [[01 ATT&CK/G0106 - Rocke|G0106: Rocke]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1222.002 - Linux and Mac Permissions|T1222.002: Linux and Mac Permissions]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Rocke](https://attack.mitre.org/groups/G0106) has changed file permissions of files so they could not be modified.(Citation: Anomali Rocke March 2019)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a2f88508-4177-4294-b287-6a3494f6e738`.
