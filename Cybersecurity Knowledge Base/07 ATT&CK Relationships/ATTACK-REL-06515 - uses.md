---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9015"
target_object: "T1140"
stix_relationship_id: "relationship--7b292c68-de29-4db0-8f07-67028da4a595"
---
# Relationship 6515: S9015 — uses → T1140

**Source object:** [[01 ATT&CK/S9015 - BRICKSTORM|S9015: BRICKSTORM]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1140 - Deobfuscate-Decode Files or Information|T1140: Deobfuscate/Decode Files or Information]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[BRICKSTORM](https://attack.mitre.org/software/S9015) has decoded its encrypted C2 traffic prior to execution.(Citation: CrowdStrike BRICKSTORM WARP PANDA UNC5221 December 2025)(Citation: CISA BRICKSTORM UNC5221 AR25-338A February 2026)(Citation: Picus Security BRICKSTORM UNC5221 October 2025)(Citation: Resecurity UNC5221 BRICKSTORM F5 Big-IP October 2025)(Citation: Google BRICKSTORM September 2025) [BRICKSTORM](https://attack.mitre.org/software/S9015) also has the ability to decode its obfuscated payload before execution.(Citation: Picus Security BRICKSTORM UNC5221 October 2025)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--7b292c68-de29-4db0-8f07-67028da4a595`.
