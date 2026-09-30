---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0079"
target_object: "T1059.001"
stix_relationship_id: "relationship--da3fc762-2ac5-4ab7-8c77-6df2f06b5680"
---
# Relationship 6506: G0079 — uses → T1059.001

**Source object:** [[01 ATT&CK/G0079 - DarkHydrus|G0079: DarkHydrus]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.001 - PowerShell|T1059.001: PowerShell]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[DarkHydrus](https://attack.mitre.org/groups/G0079) leveraged PowerShell to download and execute additional scripts for execution.(Citation: Unit 42 DarkHydrus July 2018)(Citation: Unit 42 Playbook Dec 2017)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--da3fc762-2ac5-4ab7-8c77-6df2f06b5680`.
