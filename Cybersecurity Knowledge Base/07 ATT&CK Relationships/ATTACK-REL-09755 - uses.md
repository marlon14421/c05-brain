---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0038"
target_object: "T1001.002"
stix_relationship_id: "relationship--c0905059-1f3c-414c-8027-b8ec2e4b3c89"
---
# Relationship 9755: S0038 — uses → T1001.002

**Source object:** [[01 ATT&CK/S0038 - Duqu|S0038: Duqu]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1001.002 - Steganography|T1001.002: Steganography]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

When the [Duqu](https://attack.mitre.org/software/S0038) command and control is operating over HTTP or HTTPS, Duqu uploads data to its controller by appending it to a blank JPG file.(Citation: Symantec W32.Duqu)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c0905059-1f3c-414c-8027-b8ec2e4b3c89`.
