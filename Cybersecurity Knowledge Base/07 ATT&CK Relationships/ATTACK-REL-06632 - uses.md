---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0060"
target_object: "T1080"
stix_relationship_id: "relationship--bf160f02-ab07-4f2d-8625-5818833bb77f"
---
# Relationship 6632: G0060 — uses → T1080

**Source object:** [[01 ATT&CK/G0060 - BRONZE BUTLER|G0060: BRONZE BUTLER]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1080 - Taint Shared Content|T1080: Taint Shared Content]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[BRONZE BUTLER](https://attack.mitre.org/groups/G0060) has placed malware on file shares and given it the same name as legitimate documents on the share.(Citation: Secureworks BRONZE BUTLER Oct 2017)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--bf160f02-ab07-4f2d-8625-5818833bb77f`.
