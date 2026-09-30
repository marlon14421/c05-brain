---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0618"
target_object: "T1490"
stix_relationship_id: "relationship--9a91c3cf-b39d-470f-85fc-14bbebe39e98"
---
# Relationship 3598: S0618 — uses → T1490

**Source object:** [[01 ATT&CK/S0618 - FIVEHANDS|S0618: FIVEHANDS]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1490 - Inhibit System Recovery|T1490: Inhibit System Recovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[FIVEHANDS](https://attack.mitre.org/software/S0618) has the ability to delete volume shadow copies on compromised hosts.(Citation: FireEye FiveHands April 2021)(Citation: CISA AR21-126A FIVEHANDS May 2021)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--9a91c3cf-b39d-470f-85fc-14bbebe39e98`.
