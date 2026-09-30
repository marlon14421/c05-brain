---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0148"
target_object: "T1070.009"
stix_relationship_id: "relationship--f7873bae-95b2-4463-808f-8f9d5c9deb8e"
---
# Relationship 3965: S0148 — uses → T1070.009

**Source object:** [[01 ATT&CK/S0148 - RTM|S0148: RTM]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1070.009 - Clear Persistence|T1070.009: Clear Persistence]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[RTM](https://attack.mitre.org/software/S0148) has the ability to remove Registry entries that it created for persistence.(Citation: ESET RTM Feb 2017)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--f7873bae-95b2-4463-808f-8f9d5c9deb8e`.
