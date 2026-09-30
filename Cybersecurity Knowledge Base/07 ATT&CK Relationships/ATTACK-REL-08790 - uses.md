---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1239"
target_object: "T1132.002"
stix_relationship_id: "relationship--483a975b-6d40-439f-9fcf-f65cf6225828"
---
# Relationship 8790: S1239 — uses → T1132.002

**Source object:** [[01 ATT&CK/S1239 - TONESHELL|S1239: TONESHELL]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1132.002 - Non-Standard Encoding|T1132.002: Non-Standard Encoding]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[TONESHELL](https://attack.mitre.org/software/S1239) has encoded a payload with a random 32-byte key using XOR.(Citation: 2022 November_TrendMicro_Earth Preta_Toneshell_Pubload) [TONESHELL](https://attack.mitre.org/software/S1239) has also encoded payloads with a 256-byte key using XOR.(Citation: 2025_IBM_PUBLOAD_TONESHELL_HIUPAN_CLAIMLOADER_MUSTANG PANDA)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--483a975b-6d40-439f-9fcf-f65cf6225828`.
