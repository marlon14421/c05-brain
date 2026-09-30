---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0187"
target_object: "T1132.001"
stix_relationship_id: "relationship--4abcf209-1dab-435b-a347-b8ff318ac5d8"
---
# Relationship 7099: S0187 — uses → T1132.001

**Source object:** [[01 ATT&CK/S0187 - Daserf|S0187: Daserf]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1132.001 - Standard Encoding|T1132.001: Standard Encoding]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Daserf](https://attack.mitre.org/software/S0187) uses custom base64 encoding to obfuscate HTTP traffic.(Citation: Secureworks BRONZE BUTLER Oct 2017)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--4abcf209-1dab-435b-a347-b8ff318ac5d8`.
