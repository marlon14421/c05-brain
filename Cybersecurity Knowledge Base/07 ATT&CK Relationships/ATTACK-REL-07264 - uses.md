---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0129"
target_object: "T1132.001"
stix_relationship_id: "relationship--801f139f-1361-4d79-965e-078787f8ec36"
---
# Relationship 7264: S0129 — uses → T1132.001

**Source object:** [[01 ATT&CK/S0129 - AutoIt backdoor|S0129: AutoIt backdoor]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1132.001 - Standard Encoding|T1132.001: Standard Encoding]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[AutoIt backdoor](https://attack.mitre.org/software/S0129) has sent a C2 response that was base64-encoded.(Citation: Forcepoint Monsoon)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--801f139f-1361-4d79-965e-078787f8ec36`.
