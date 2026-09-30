---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1018"
target_object: "T1204.002"
stix_relationship_id: "relationship--b0766ea1-924a-4e1f-92db-17e5f4a3b72d"
---
# Relationship 2741: G1018 — uses → T1204.002

**Source object:** [[01 ATT&CK/G1018 - TA2541|G1018: TA2541]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1204.002 - Malicious File|T1204.002: Malicious File]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[TA2541](https://attack.mitre.org/groups/G1018) has used macro-enabled MS Word documents to lure victims into executing malicious payloads.(Citation: Proofpoint TA2541 February 2022)(Citation: Cisco Operation Layover September 2021)(Citation: Telefonica Snip3 December 2021)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--b0766ea1-924a-4e1f-92db-17e5f4a3b72d`.
