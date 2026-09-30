---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1234"
target_object: "T1036.001"
stix_relationship_id: "relationship--8ebafdbf-ebc8-4e14-9f4b-b1a0f6e79f3f"
---
# Relationship 5255: S1234 — uses → T1036.001

**Source object:** [[01 ATT&CK/S1234 - SplatCloak|S1234: SplatCloak]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1036.001 - Invalid Code Signature|T1036.001: Invalid Code Signature]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[SplatCloak](https://attack.mitre.org/software/S1234) has used a revoked certificate to exploit Windows driver execution policy where certificates issued before a specific date could still load.(Citation: Zscaler PAKLOG CorkLog SplatCloak Splatdropper April 2025)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--8ebafdbf-ebc8-4e14-9f4b-b1a0f6e79f3f`.
