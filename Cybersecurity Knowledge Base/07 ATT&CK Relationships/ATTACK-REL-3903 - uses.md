---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0062"
target_object: "T1059.001"
stix_relationship_id: "relationship--c08f55ca-366b-4554-879b-1b19042f9be8"
---
# Relationship 3903: G0062 — uses → T1059.001

**Source object:** [[01 ATT&CK/G0062 - TA459|G0062: TA459]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.001 - PowerShell|T1059.001: PowerShell]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[TA459](https://attack.mitre.org/groups/G0062) has used PowerShell for execution of a payload.(Citation: Proofpoint TA459 April 2017)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c08f55ca-366b-4554-879b-1b19042f9be8`.
