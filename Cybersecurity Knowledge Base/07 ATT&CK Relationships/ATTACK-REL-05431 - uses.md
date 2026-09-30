---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0279"
target_object: "T1555.001"
stix_relationship_id: "relationship--6209bf2d-6ffd-4740-96cb-ef04379ae126"
---
# Relationship 5431: S0279 — uses → T1555.001

**Source object:** [[01 ATT&CK/S0279 - Proton|S0279: Proton]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1555.001 - Keychain|T1555.001: Keychain]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Proton](https://attack.mitre.org/software/S0279) gathers credentials in files for keychains.(Citation: objsee mac malware 2017)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--6209bf2d-6ffd-4740-96cb-ef04379ae126`.
