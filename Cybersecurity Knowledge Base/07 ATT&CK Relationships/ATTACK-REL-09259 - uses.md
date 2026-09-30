---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0677"
target_object: "T1098.005"
stix_relationship_id: "relationship--5124a13e-f7a3-43ad-88e4-c73c380cb6f7"
---
# Relationship 9259: S0677 — uses → T1098.005

**Source object:** [[01 ATT&CK/S0677 - AADInternals|S0677: AADInternals]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1098.005 - Device Registration|T1098.005: Device Registration]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[AADInternals](https://attack.mitre.org/software/S0677) can register a device to Azure AD.(Citation: AADInternals Documentation)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--5124a13e-f7a3-43ad-88e4-c73c380cb6f7`.
