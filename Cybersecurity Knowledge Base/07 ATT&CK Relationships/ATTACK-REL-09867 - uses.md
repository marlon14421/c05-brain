---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0576"
target_object: "T1106"
stix_relationship_id: "relationship--bf6a8896-2e07-4ed8-9f51-3847c3b0745f"
---
# Relationship 9867: S0576 — uses → T1106

**Source object:** [[01 ATT&CK/S0576 - MegaCortex|S0576: MegaCortex]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1106 - Native API|T1106: Native API]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

After escalating privileges, [MegaCortex](https://attack.mitre.org/software/S0576) calls TerminateProcess() , CreateRemoteThread , and other Win32 APIs.(Citation: IBM MegaCortex)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--bf6a8896-2e07-4ed8-9f51-3847c3b0745f`.
