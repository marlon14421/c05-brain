---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1055"
target_object: "T1199"
stix_relationship_id: "relationship--e59b9a1d-51cb-4ad8-b363-23ac4a7535ec"
---
# Relationship 8378: G1055 — uses → T1199

**Source object:** [[01 ATT&CK/G1055 - VOID MANTICORE|G1055: VOID MANTICORE]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1199 - Trusted Relationship|T1199: Trusted Relationship]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[VOID MANTICORE](https://attack.mitre.org/groups/G1055) has targeted IT and service providers in an effort to obtain credentials, relying largely on compromised VPN accounts for initial access.(Citation: Check Point VOID MANTICORE Handala Hack March 2026)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e59b9a1d-51cb-4ad8-b363-23ac4a7535ec`.
