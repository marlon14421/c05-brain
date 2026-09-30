---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0022"
target_object: "T1583.006"
stix_relationship_id: "relationship--78a7e89b-4560-4105-adfb-47393c39625b"
---
# Relationship 5107: C0022 — uses → T1583.006

**Source object:** [[01 ATT&CK/C0022 - Operation Dream Job|C0022: Operation Dream Job]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1583.006 - Web Services|T1583.006: Web Services]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

During [Operation Dream Job](https://attack.mitre.org/campaigns/C0022), [Lazarus Group](https://attack.mitre.org/groups/G0032) used file hosting services like DropBox and OneDrive.(Citation: ClearSky Lazarus Aug 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--78a7e89b-4560-4105-adfb-47393c39625b`.
