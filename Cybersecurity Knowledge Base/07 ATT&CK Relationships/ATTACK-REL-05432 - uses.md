---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1055"
target_object: "T1204.002"
stix_relationship_id: "relationship--b9247c37-ed60-477d-aade-45ceb5ff91a9"
---
# Relationship 5432: G1055 — uses → T1204.002

**Source object:** [[01 ATT&CK/G1055 - VOID MANTICORE|G1055: VOID MANTICORE]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1204.002 - Malicious File|T1204.002: Malicious File]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[VOID MANTICORE](https://attack.mitre.org/groups/G1055) has delivered malicious payloads that initiate through user execution to include interaction with a masqueraded file.(Citation: DOJ FBI Handala Hack March 2026)(Citation: FBI IC3 Flash VOID MANTICORE Handala Hack March 2026) [VOID MANTICORE](https://attack.mitre.org/groups/G1055) has used trojanized application lures to induce targets into executing malware enabling persistent surveillance.(Citation: Domain Tools Handala Hack Karma Homeland Justice MOIS April 2026)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--b9247c37-ed60-477d-aade-45ceb5ff91a9`.
