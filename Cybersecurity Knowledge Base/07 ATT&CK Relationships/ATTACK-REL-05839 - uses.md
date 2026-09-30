---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1070"
target_object: "T1486"
stix_relationship_id: "relationship--6aedddc0-0c82-48f0-b9cc-071d440a367c"
---
# Relationship 5839: S1070 — uses → T1486

**Source object:** [[01 ATT&CK/S1070 - Black Basta|S1070: Black Basta]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1486 - Data Encrypted for Impact|T1486: Data Encrypted for Impact]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Black Basta](https://attack.mitre.org/software/S1070) can encrypt files with the ChaCha20 cypher and using a multithreaded process to increase speed.(Citation: Minerva Labs Black Basta May 2022)(Citation: BlackBerry Black Basta May 2022)(Citation: Cyble Black Basta May 2022)(Citation: NCC Group Black Basta June 2022)(Citation: Uptycs Black Basta ESXi June 2022)(Citation: Deep Instinct Black Basta August 2022)(Citation: Palo Alto Networks Black Basta August 2022)(Citation: Trend Micro Black Basta Spotlight September 2022)(Citation: Check Point Black Basta October 2022) [Black Basta](https://attack.mitre.org/software/S1070) has also encrypted files while the victim system is in safe mode, appending `.basta` upon completion.(Citation: Trend Micro Black Basta May 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--6aedddc0-0c82-48f0-b9cc-071d440a367c`.
