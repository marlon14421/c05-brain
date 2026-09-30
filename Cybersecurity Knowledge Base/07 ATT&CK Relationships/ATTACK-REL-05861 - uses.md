---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0022"
target_object: "S0678"
stix_relationship_id: "relationship--5687f6c6-f749-456e-a7fe-179017d50e9b"
---
# Relationship 5861: C0022 — uses → S0678

**Source object:** [[01 ATT&CK/C0022 - Operation Dream Job|C0022: Operation Dream Job]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S0678 - Torisma|S0678: Torisma]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

During [Operation Dream Job](https://attack.mitre.org/campaigns/C0022), [Lazarus Group](https://attack.mitre.org/groups/G0032) used [Torisma](https://attack.mitre.org/software/S0678) to actively monitor for new drives and remote desktop connections on an infected system.(Citation: McAfee Lazarus Jul 2020)(Citation: McAfee Lazarus Nov 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--5687f6c6-f749-456e-a7fe-179017d50e9b`.
