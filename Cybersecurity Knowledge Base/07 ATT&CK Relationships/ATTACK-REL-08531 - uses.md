---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1111"
target_object: "T1027"
stix_relationship_id: "relationship--624b57dc-3cae-45c7-8473-c5116df57697"
---
# Relationship 8531: S1111 — uses → T1027

**Source object:** [[01 ATT&CK/S1111 - DarkGate|S1111: DarkGate]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027 - Obfuscated Files or Information|T1027: Obfuscated Files or Information]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[DarkGate](https://attack.mitre.org/software/S1111) uses a hard-coded string as a seed, along with the victim machine hardware identifier and input text, to generate a unique string used as an internal mutex value to evade static detection based on mutexes.(Citation: Trellix Darkgate 2023)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--624b57dc-3cae-45c7-8473-c5116df57697`.
