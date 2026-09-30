---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0277"
target_object: "T1083"
stix_relationship_id: "relationship--ddbbd283-6874-4348-82c7-98df6d59ac41"
---
# Relationship 8340: S0277 — uses → T1083

**Source object:** [[01 ATT&CK/S0277 - FruitFly|S0277: FruitFly]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1083 - File and Directory Discovery|T1083: File and Directory Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[FruitFly](https://attack.mitre.org/software/S0277) looks for specific files and file types.(Citation: objsee mac malware 2017)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--ddbbd283-6874-4348-82c7-98df6d59ac41`.
