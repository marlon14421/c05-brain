---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0449"
target_object: "T1218.007"
stix_relationship_id: "relationship--e3fa0df1-d388-4e74-b561-acc5094a8e1b"
---
# Relationship 3831: S0449 — uses → T1218.007

**Source object:** [[01 ATT&CK/S0449 - Maze|S0449: Maze]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1218.007 - Msiexec|T1218.007: Msiexec]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Maze](https://attack.mitre.org/software/S0449) has delivered components for its ransomware attacks using MSI files, some of which have been executed from the command-line using msiexec .(Citation: Sophos Maze VM September 2020)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e3fa0df1-d388-4e74-b561-acc5094a8e1b`.
