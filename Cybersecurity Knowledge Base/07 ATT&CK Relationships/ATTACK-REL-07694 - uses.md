---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0022"
target_object: "T1587.001"
stix_relationship_id: "relationship--d1bd6ce6-eb5f-41a1-b26f-4fe0d83e51ea"
---
# Relationship 7694: C0022 — uses → T1587.001

**Source object:** [[01 ATT&CK/C0022 - Operation Dream Job|C0022: Operation Dream Job]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1587.001 - Malware|T1587.001: Malware]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

For [Operation Dream Job](https://attack.mitre.org/campaigns/C0022), [Lazarus Group](https://attack.mitre.org/groups/G0032) developed custom tools such as Sumarta, DBLL Dropper, [Torisma](https://attack.mitre.org/software/S0678), and [DRATzarus](https://attack.mitre.org/software/S0694) for their operations.(Citation: ClearSky Lazarus Aug 2020)(Citation: ESET Lazarus Jun 2020)(Citation: McAfee Lazarus Jul 2020)(Citation: McAfee Lazarus Nov 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d1bd6ce6-eb5f-41a1-b26f-4fe0d83e51ea`.
