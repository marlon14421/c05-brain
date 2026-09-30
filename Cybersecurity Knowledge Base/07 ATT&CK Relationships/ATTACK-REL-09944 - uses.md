---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1055"
target_object: "T1566"
stix_relationship_id: "relationship--18f5dc98-f6fd-489a-ab3e-93f3c613e82e"
---
# Relationship 9944: G1055 — uses → T1566

**Source object:** [[01 ATT&CK/G1055 - VOID MANTICORE|G1055: VOID MANTICORE]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1566 - Phishing|T1566: Phishing]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[VOID MANTICORE](https://attack.mitre.org/groups/G1055) has emailed victims threatening messages.(Citation: DOJ FBI Handala Hack March 2026) [VOID MANTICORE](https://attack.mitre.org/groups/G1055) has used phishing as an initial access vector.(Citation: Domain Tools Handala Hack Karma Homeland Justice MOIS April 2026)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--18f5dc98-f6fd-489a-ab3e-93f3c613e82e`.
