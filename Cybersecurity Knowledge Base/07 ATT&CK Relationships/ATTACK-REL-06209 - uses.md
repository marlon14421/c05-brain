---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0049"
target_object: "T1059.001"
stix_relationship_id: "relationship--4fde23ab-b8db-4275-ac37-37e608cb00b0"
---
# Relationship 6209: G0049 — uses → T1059.001

**Source object:** [[01 ATT&CK/G0049 - OilRig|G0049: OilRig]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.001 - PowerShell|T1059.001: PowerShell]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[OilRig](https://attack.mitre.org/groups/G0049) has used PowerShell scripts for execution, including use of a macro to run a PowerShell command to decode file contents.(Citation: FireEye APT34 Dec 2017)(Citation: OilRig New Delivery Oct 2017)(Citation: Crowdstrike Helix Kitten Nov 2018)(Citation: Trend Micro Earth Simnavaz October 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--4fde23ab-b8db-4275-ac37-37e608cb00b0`.
