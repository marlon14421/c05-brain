---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9043"
target_object: "T1555.005"
stix_relationship_id: "relationship--971e0f50-01f7-4403-b99e-94ed4cf65269"
---
# Relationship 5989: S9043 — uses → T1555.005

**Source object:** [[01 ATT&CK/S9043 - Mini Shai-Hulud|S9043: Mini Shai-Hulud]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1555.005 - Password Managers|T1555.005: Password Managers]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Mini Shai-Hulud](https://attack.mitre.org/software/S9043) has gathered credentials stored in password managers to include password vaults.(Citation: Wiz Mini Shai-Hulud MAY 2026)(Citation: Hunt.io TeamPCP Toolkit MAY 2026)(Citation: Phoenix TeamPCP 20 MAY 2026)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--971e0f50-01f7-4403-b99e-94ed4cf65269`.
