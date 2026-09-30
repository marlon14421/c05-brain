---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9015"
target_object: "T1027"
stix_relationship_id: "relationship--130768d0-0f98-4a1b-b4bb-34c5e372cda1"
---
# Relationship 6081: S9015 — uses → T1027

**Source object:** [[01 ATT&CK/S9015 - BRICKSTORM|S9015: BRICKSTORM]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027 - Obfuscated Files or Information|T1027: Obfuscated Files or Information]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[BRICKSTORM](https://attack.mitre.org/software/S9015) has utilized Go libraries to include Garble to obfuscate code.(Citation: Picus Security BRICKSTORM UNC5221 October 2025)(Citation: Google BRICKSTORM September 2025)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--130768d0-0f98-4a1b-b4bb-34c5e372cda1`.
