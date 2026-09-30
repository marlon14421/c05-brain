---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1055"
target_object: "T1583.001"
stix_relationship_id: "relationship--285c89fe-b2c7-41ed-8079-822a7fb0bec2"
---
# Relationship 7416: G1055 — uses → T1583.001

**Source object:** [[01 ATT&CK/G1055 - VOID MANTICORE|G1055: VOID MANTICORE]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1583.001 - Domains|T1583.001: Domains]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[VOID MANTICORE](https://attack.mitre.org/groups/G1055) has registered domains for messaging purposes.(Citation: SPECOPS Outpost24 Handala Hack Stryker March 2026) [VOID MANTICORE](https://attack.mitre.org/groups/G1055) has created typosquatted domains and sub-domains in attempts to avoid detection or draw suspicion.(Citation: DOJ FBI Handala Hack March 2026)(Citation: FBI IC3 Flash VOID MANTICORE Handala Hack March 2026) [VOID MANTICORE](https://attack.mitre.org/groups/G1055) has also purchased domains leveraging cryptocurrency platforms to include LiteCoin and Ramzinex.(Citation: DOJ FBI Handala Hack March 2026) [VOID MANTICORE](https://attack.mitre.org/groups/G1055) has registered and rotated domains to support public-facing dissemination infrastructure, replacing disrupted domains with new registrations.(Citation: Domain Tools Handala Hack Karma Homeland Justice MOIS April 2026)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--285c89fe-b2c7-41ed-8079-822a7fb0bec2`.
