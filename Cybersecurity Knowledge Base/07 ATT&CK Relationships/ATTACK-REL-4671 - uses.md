---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0356"
target_object: "T1016"
stix_relationship_id: "relationship--2251e15a-5b62-408d-b6a0-01aa8e2677b3"
---
# Relationship 4671: S0356 — uses → T1016

**Source object:** [[01 ATT&CK/S0356 - KONNI|S0356: KONNI]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1016 - System Network Configuration Discovery|T1016: System Network Configuration Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[KONNI](https://attack.mitre.org/software/S0356) can collect the IP address from the victim’s machine.(Citation: Talos Konni May 2017)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--2251e15a-5b62-408d-b6a0-01aa8e2677b3`.
