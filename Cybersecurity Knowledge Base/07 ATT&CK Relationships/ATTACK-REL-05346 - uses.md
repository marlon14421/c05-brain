---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0053"
target_object: "T1078"
stix_relationship_id: "relationship--32864e94-8581-4f77-bf7d-53aaf3710f60"
---
# Relationship 5346: S0053 — uses → T1078

**Source object:** [[01 ATT&CK/S0053 - SeaDuke|S0053: SeaDuke]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1078 - Valid Accounts|T1078: Valid Accounts]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

Some [SeaDuke](https://attack.mitre.org/software/S0053) samples have a module to extract email from Microsoft Exchange servers using compromised credentials.(Citation: Symantec Seaduke 2015)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--32864e94-8581-4f77-bf7d-53aaf3710f60`.
