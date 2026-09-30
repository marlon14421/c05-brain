---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9037"
target_object: "T1204.002"
stix_relationship_id: "relationship--e10a3f38-fe4b-4bf3-9d36-cdf18854ed2a"
---
# Relationship 8582: S9037 — uses → T1204.002

**Source object:** [[01 ATT&CK/S9037 - RustyWater|S9037: RustyWater]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1204.002 - Malicious File|T1204.002: Malicious File]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[RustyWater](https://attack.mitre.org/software/S9037) has used a Word document with a malicious Visual Basic for Applications (VBA) macro; when enabled, the CertificationKit.ini payload is constructed and executed.(Citation: CloudSEK_RustyWater_Jan2026)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e10a3f38-fe4b-4bf3-9d36-cdf18854ed2a`.
