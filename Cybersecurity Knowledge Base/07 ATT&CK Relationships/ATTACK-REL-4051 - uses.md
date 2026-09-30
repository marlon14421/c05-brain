---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0531"
target_object: "T1686.002"
stix_relationship_id: "relationship--c1b233f3-87f7-43e8-8185-0c6aa0e1b959"
---
# Relationship 4051: S0531 — uses → T1686.002

**Source object:** [[01 ATT&CK/S0531 - Grandoreiro|S0531: Grandoreiro]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1686.002 - Network Device Firewall|T1686.002: Network Device Firewall]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Grandoreiro](https://attack.mitre.org/software/S0531) can block the Deibold Warsaw GAS Tecnologia security tool at the firewall level. (Citation: ESET Grandoreiro April 2020)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c1b233f3-87f7-43e8-8185-0c6aa0e1b959`.
