---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0231"
target_object: "T1027.003"
stix_relationship_id: "relationship--c09c2f08-3bda-4af7-9578-01fa1c7fba2c"
---
# Relationship 9825: S0231 — uses → T1027.003

**Source object:** [[01 ATT&CK/S0231 - Invoke-PSImage|S0231: Invoke-PSImage]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027.003 - Steganography|T1027.003: Steganography]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Invoke-PSImage](https://attack.mitre.org/software/S0231) can be used to embed a PowerShell script within the pixels of a PNG file.(Citation: GitHub Invoke-PSImage)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c09c2f08-3bda-4af7-9578-01fa1c7fba2c`.
