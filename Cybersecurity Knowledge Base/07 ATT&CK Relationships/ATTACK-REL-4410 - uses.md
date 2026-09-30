---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0012"
target_object: "T1005"
stix_relationship_id: "relationship--c011e80b-7b86-405a-8d41-745bd37a0d10"
---
# Relationship 4410: S0012 — uses → T1005

**Source object:** [[01 ATT&CK/S0012 - PoisonIvy|S0012: PoisonIvy]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1005 - Data from Local System|T1005: Data from Local System]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[PoisonIvy](https://attack.mitre.org/software/S0012) creates a backdoor through which remote attackers can steal system information.(Citation: Symantec Darkmoon Aug 2005)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c011e80b-7b86-405a-8d41-745bd37a0d10`.
