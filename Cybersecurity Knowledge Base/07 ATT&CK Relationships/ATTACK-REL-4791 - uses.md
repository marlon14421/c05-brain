---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0012"
target_object: "T1005"
stix_relationship_id: "relationship--ea944454-a4e9-44fb-9cf1-3f018a455740"
---
# Relationship 4791: C0012 — uses → T1005

**Source object:** [[01 ATT&CK/C0012 - Operation CuckooBees|C0012: Operation CuckooBees]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1005 - Data from Local System|T1005: Data from Local System]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

During [Operation CuckooBees](https://attack.mitre.org/campaigns/C0012), the threat actors collected data, files, and other information from compromised networks.(Citation: Cybereason OperationCuckooBees May 2022)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--ea944454-a4e9-44fb-9cf1-3f018a455740`.
