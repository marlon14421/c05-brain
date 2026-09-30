---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1047"
target_object: "T1556.007"
stix_relationship_id: "relationship--a5cca5a1-35c5-4e96-a343-3e2c81a0a202"
---
# Relationship 0243: M1047 — mitigates → T1556.007

**Source object:** [[01 ATT&CK/M1047 - Audit|M1047: Audit]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1556.007 - Hybrid Identity|T1556.007: Hybrid Identity]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Periodically review the hybrid identity solution in use for any discrepancies. For example, review all PTA agents in the Entra ID Management Portal to identify any unwanted or unapproved ones.(Citation: Mandiant Azure AD Backdoors) If ADFS is in use, review DLLs and executable files in the AD FS and Global Assembly Cache directories to ensure that they are signed by Microsoft. Note that in some cases binaries may be catalog-signed, which may cause the file to appear unsigned when viewing file properties.(Citation: MagicWeb)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a5cca5a1-35c5-4e96-a343-3e2c81a0a202`.
