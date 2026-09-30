---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0004"
target_object: "T1007"
stix_relationship_id: "relationship--7b529102-f95c-4ca1-a5c4-5a3497ab3674"
---
# Relationship 8660: G0004 — uses → T1007

**Source object:** [[01 ATT&CK/G0004 - Ke3chang|G0004: Ke3chang]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1007 - System Service Discovery|T1007: System Service Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Ke3chang](https://attack.mitre.org/groups/G0004) performs service discovery using net start commands.(Citation: Mandiant Operation Ke3chang November 2014)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--7b529102-f95c-4ca1-a5c4-5a3497ab3674`.
