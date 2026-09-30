---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0265"
target_object: "T1010"
stix_relationship_id: "relationship--afa84fd1-e910-4bc7-8270-1e9f9b02b53f"
---
# Relationship 7805: S0265 — uses → T1010

**Source object:** [[01 ATT&CK/S0265 - Kazuar|S0265: Kazuar]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1010 - Application Window Discovery|T1010: Application Window Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Kazuar](https://attack.mitre.org/software/S0265) gathers information about opened windows.(Citation: Unit 42 Kazuar May 2017)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--afa84fd1-e910-4bc7-8270-1e9f9b02b53f`.
