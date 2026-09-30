---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0404"
target_object: "T1003.003"
stix_relationship_id: "relationship--4faa4943-e54e-420d-a391-350ef629e766"
---
# Relationship 7971: S0404 — uses → T1003.003

**Source object:** [[01 ATT&CK/S0404 - esentutl|S0404: esentutl]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1003.003 - NTDS|T1003.003: NTDS]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[esentutl](https://attack.mitre.org/software/S0404) can copy `ntds.dit` using the Volume Shadow Copy service.(Citation: LOLBAS Esentutl)(Citation: Cary Esentutl)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--4faa4943-e54e-420d-a391-350ef629e766`.
