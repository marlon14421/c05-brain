---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0534"
target_object: "T1204.001"
stix_relationship_id: "relationship--17e7193e-6583-4bae-8a17-de75f006cd36"
---
# Relationship 4350: S0534 — uses → T1204.001

**Source object:** [[01 ATT&CK/S0534 - Bazar|S0534: Bazar]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1204.001 - Malicious Link|T1204.001: Malicious Link]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Bazar](https://attack.mitre.org/software/S0534) can gain execution after a user clicks on a malicious link to decoy landing pages hosted on Google Docs.(Citation: Cybereason Bazar July 2020)(Citation: Zscaler Bazar September 2020)(Citation: CrowdStrike Wizard Spider October 2020)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--17e7193e-6583-4bae-8a17-de75f006cd36`.
