---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0343"
target_object: "T1027.011"
stix_relationship_id: "relationship--5f3176fa-827b-4c3c-ba71-6e8ef6cdebb9"
---
# Relationship 3237: S0343 — uses → T1027.011

**Source object:** [[01 ATT&CK/S0343 - Exaramel for Windows|S0343: Exaramel for Windows]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027.011 - Fileless Storage|T1027.011: Fileless Storage]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Exaramel for Windows](https://attack.mitre.org/software/S0343) stores the backdoor's configuration in the Registry in XML format.(Citation: ESET TeleBots Oct 2018)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--5f3176fa-827b-4c3c-ba71-6e8ef6cdebb9`.
