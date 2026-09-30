---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0641"
target_object: "T1554"
stix_relationship_id: "relationship--5c365b61-0c14-41aa-b82a-052eb977062b"
---
# Relationship 3933: S0641 — uses → T1554

**Source object:** [[01 ATT&CK/S0641 - Kobalos|S0641: Kobalos]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1554 - Compromise Host Software Binary|T1554: Compromise Host Software Binary]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Kobalos](https://attack.mitre.org/software/S0641) replaced the SSH client with a trojanized SSH client to steal credentials on compromised systems.(Citation: ESET Kobalos Jan 2021)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--5c365b61-0c14-41aa-b82a-052eb977062b`.
