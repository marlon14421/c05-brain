---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0349"
target_object: "T1555"
stix_relationship_id: "relationship--b0f355cc-e11f-4027-9db3-59ec64cd367f"
---
# Relationship 9458: S0349 — uses → T1555

**Source object:** [[01 ATT&CK/S0349 - LaZagne|S0349: LaZagne]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1555 - Credentials from Password Stores|T1555: Credentials from Password Stores]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[LaZagne](https://attack.mitre.org/software/S0349) can obtain credentials from databases, mail, and WiFi across multiple platforms.(Citation: GitHub LaZagne Dec 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--b0f355cc-e11f-4027-9db3-59ec64cd367f`.
