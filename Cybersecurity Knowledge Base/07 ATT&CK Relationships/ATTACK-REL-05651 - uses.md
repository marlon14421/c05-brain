---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1148"
target_object: "T1539"
stix_relationship_id: "relationship--d8c19b7a-71a0-4941-9244-f9784e5e99fc"
---
# Relationship 5651: S1148 — uses → T1539

**Source object:** [[01 ATT&CK/S1148 - Raccoon Stealer|S1148: Raccoon Stealer]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1539 - Steal Web Session Cookie|T1539: Steal Web Session Cookie]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Raccoon Stealer](https://attack.mitre.org/software/S1148) attempts to steal cookies and related information in browser history.(Citation: Sekoia Raccoon2 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d8c19b7a-71a0-4941-9244-f9784e5e99fc`.
