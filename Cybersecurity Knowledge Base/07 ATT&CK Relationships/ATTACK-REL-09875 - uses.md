---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1055"
target_object: "T1583.006"
stix_relationship_id: "relationship--7835c871-eb21-4790-ae9f-4d8af0436886"
---
# Relationship 9875: G1055 — uses → T1583.006

**Source object:** [[01 ATT&CK/G1055 - VOID MANTICORE|G1055: VOID MANTICORE]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1583.006 - Web Services|T1583.006: Web Services]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[VOID MANTICORE](https://attack.mitre.org/groups/G1055) has obtained access to commercial VPN services to launch malicious activity.(Citation: Check Point VOID MANTICORE Handala Hack March 2026)(Citation: SPECOPS Outpost24 Handala Hack Stryker March 2026) [VOID MANTICORE](https://attack.mitre.org/groups/G1055) has also leveraged Starlink internet services.(Citation: Check Point VOID MANTICORE Handala Hack March 2026) [VOID MANTICORE](https://attack.mitre.org/groups/G1055) has used operator-controlled Telegram bots and channels as C2 infrastructure.(Citation: Domain Tools Handala Hack Karma Homeland Justice MOIS April 2026)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--7835c871-eb21-4790-ae9f-4d8af0436886`.
