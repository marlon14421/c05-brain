---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0454"
target_object: "T1120"
stix_relationship_id: "relationship--dfdd269c-9d78-46da-8b31-3141a5398bfd"
---
# Relationship 3245: S0454 — uses → T1120

**Source object:** [[01 ATT&CK/S0454 - Cadelspy|S0454: Cadelspy]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1120 - Peripheral Device Discovery|T1120: Peripheral Device Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Cadelspy](https://attack.mitre.org/software/S0454) has the ability to steal information about printers and the documents sent to printers.(Citation: Symantec Chafer Dec 2015)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--dfdd269c-9d78-46da-8b31-3141a5398bfd`.
