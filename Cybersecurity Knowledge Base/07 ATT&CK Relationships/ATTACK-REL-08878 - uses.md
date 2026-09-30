---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9007"
target_object: "T1132.002"
stix_relationship_id: "relationship--6e83007d-1812-4627-b77b-e5571a871166"
---
# Relationship 8878: S9007 — uses → T1132.002

**Source object:** [[01 ATT&CK/S9007 - HTTPTroy|S9007: HTTPTroy]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1132.002 - Non-Standard Encoding|T1132.002: Non-Standard Encoding]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[HTTPTroy](https://attack.mitre.org/software/S9007) has obfuscated HTTP POST request communications utilizing XOR with a designated key of 0x56, followed by Base64 encoding.(Citation: Gen Digital Kimsuky HTTPTroy October 2025)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--6e83007d-1812-4627-b77b-e5571a871166`.
