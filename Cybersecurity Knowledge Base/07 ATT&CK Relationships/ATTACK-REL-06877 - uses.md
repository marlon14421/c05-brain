---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0022"
target_object: "T1027.013"
stix_relationship_id: "relationship--c3d73dc3-06f6-422a-9be2-c4eb3ce36fbc"
---
# Relationship 6877: C0022 — uses → T1027.013

**Source object:** [[01 ATT&CK/C0022 - Operation Dream Job|C0022: Operation Dream Job]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027.013 - Encrypted-Encoded File|T1027.013: Encrypted/Encoded File]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

During [Operation Dream Job](https://attack.mitre.org/campaigns/C0022), [Lazarus Group](https://attack.mitre.org/groups/G0032) encrypted malware such as [DRATzarus](https://attack.mitre.org/software/S0694) with XOR and DLL files with base64.(Citation: ClearSky Lazarus Aug 2020)(Citation: ESET Lazarus Jun 2020)(Citation: McAfee Lazarus Jul 2020)(Citation: McAfee Lazarus Nov 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c3d73dc3-06f6-422a-9be2-c4eb3ce36fbc`.
