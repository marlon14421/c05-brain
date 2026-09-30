---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9037"
target_object: "T1559.001"
stix_relationship_id: "relationship--b6ab77f2-e201-4184-b093-d6f54ada594b"
---
# Relationship 7091: S9037 — uses → T1559.001

**Source object:** [[01 ATT&CK/S9037 - RustyWater|S9037: RustyWater]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1559.001 - Component Object Model|T1559.001: Component Object Model]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[RustyWater](https://attack.mitre.org/software/S9037) has used a WScript.Shell COM object to execute the CertificationKit.ini file.(Citation: CloudSEK_RustyWater_Jan2026)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--b6ab77f2-e201-4184-b093-d6f54ada594b`.
