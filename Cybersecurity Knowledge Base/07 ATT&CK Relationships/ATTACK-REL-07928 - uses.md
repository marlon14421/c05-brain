---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1057"
target_object: "T1657"
stix_relationship_id: "relationship--adae2782-ce69-4587-bfb0-2417ee44e0fa"
---
# Relationship 7928: G1057 — uses → T1657

**Source object:** [[01 ATT&CK/G1057 - ShinyHunters|G1057: ShinyHunters]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1657 - Financial Theft|T1657: Financial Theft]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[ShinyHunters](https://attack.mitre.org/groups/G1057) has called or sent text messages or emails to employees of victim organizations to demand payment in Bitcoin within 72 hours. Email addresses used in extortion activities include shinycorp@tuta[.]com, shinygroup@tuta[.]com, shinycorp@tutanota[.]com, and shinygroup@onionmail[.]com.(Citation: Google Salesforce JUN 2025)(Citation: Mandiant_SHDataTheft_Jan2026)(Citation: FBI_SHLMS_May2026)(Citation: Intel471_SH_Aug2021)(Citation: Unit42KelleyVaya_BlingLibra_Aug2024)(Citation: SOCRadar_ShinyHunters_Mar2024)(Citation: ElecticIQ Buyukkaya_ShinyHunters_Sept2025)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--adae2782-ce69-4587-bfb0-2417ee44e0fa`.
