---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0677"
target_object: "T1649"
stix_relationship_id: "relationship--234867ce-57bb-41c6-beb5-af9cc00e1a39"
---
# Relationship 7589: S0677 — uses → T1649

**Source object:** [[01 ATT&CK/S0677 - AADInternals|S0677: AADInternals]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1649 - Steal or Forge Authentication Certificates|T1649: Steal or Forge Authentication Certificates]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[AADInternals](https://attack.mitre.org/software/S0677) can create and export various authentication certificates, including those associated with Azure AD joined/registered devices.(Citation: AADInternals Documentation)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--234867ce-57bb-41c6-beb5-af9cc00e1a39`.
