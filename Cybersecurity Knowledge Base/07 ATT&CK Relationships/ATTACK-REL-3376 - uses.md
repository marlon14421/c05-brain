---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0482"
target_object: "T1543.001"
stix_relationship_id: "relationship--72df7e88-84ce-449b-ae0f-a8ceb9316964"
---
# Relationship 3376: S0482 — uses → T1543.001

**Source object:** [[01 ATT&CK/S0482 - Bundlore|S0482: Bundlore]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1543.001 - Launch Agent|T1543.001: Launch Agent]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Bundlore](https://attack.mitre.org/software/S0482) can persist via a LaunchAgent.(Citation: MacKeeper Bundlore Apr 2019)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--72df7e88-84ce-449b-ae0f-a8ceb9316964`.
