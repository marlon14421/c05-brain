---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0501"
target_object: "T1106"
stix_relationship_id: "relationship--dfea8f12-5c47-4a11-a4ed-06d08192b9ab"
---
# Relationship 8108: S0501 — uses → T1106

**Source object:** [[01 ATT&CK/S0501 - PipeMon|S0501: PipeMon]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1106 - Native API|T1106: Native API]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[PipeMon](https://attack.mitre.org/software/S0501)'s first stage has been executed by a call to CreateProcess with the decryption password in an argument. [PipeMon](https://attack.mitre.org/software/S0501) has used a call to LoadLibrary to load its installer.(Citation: ESET PipeMon May 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--dfea8f12-5c47-4a11-a4ed-06d08192b9ab`.
