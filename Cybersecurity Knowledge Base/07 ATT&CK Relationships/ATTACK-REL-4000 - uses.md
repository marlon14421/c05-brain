---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0458"
target_object: "T1005"
stix_relationship_id: "relationship--3feb6e83-0491-4e3d-a581-3f68ab839e92"
---
# Relationship 4000: S0458 — uses → T1005

**Source object:** [[01 ATT&CK/S0458 - Ramsay|S0458: Ramsay]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1005 - Data from Local System|T1005: Data from Local System]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Ramsay](https://attack.mitre.org/software/S0458) can collect Microsoft Word documents from the target's file system, as well as .txt , .doc , and .xls files from the Internet Explorer cache.(Citation: Eset Ramsay May 2020)(Citation: Antiy CERT Ramsay April 2020)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--3feb6e83-0491-4e3d-a581-3f68ab839e92`.
