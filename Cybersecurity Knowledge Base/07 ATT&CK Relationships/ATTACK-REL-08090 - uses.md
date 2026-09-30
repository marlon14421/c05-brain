---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0256"
target_object: "T1027.013"
stix_relationship_id: "relationship--91a362c7-a111-4a1e-8978-1afcc110e5cf"
---
# Relationship 8090: S0256 — uses → T1027.013

**Source object:** [[01 ATT&CK/S0256 - Mosquito|S0256: Mosquito]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027.013 - Encrypted-Encoded File|T1027.013: Encrypted/Encoded File]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Mosquito](https://attack.mitre.org/software/S0256)’s installer is obfuscated with a custom crypter to obfuscate the installer.(Citation: ESET Turla Mosquito Jan 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--91a362c7-a111-4a1e-8978-1afcc110e5cf`.
