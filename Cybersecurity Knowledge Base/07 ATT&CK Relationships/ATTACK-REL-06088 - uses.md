---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0381"
target_object: "T1218.007"
stix_relationship_id: "relationship--f0966da3-d23d-4949-99d6-ddc680f4a5f3"
---
# Relationship 6088: S0381 — uses → T1218.007

**Source object:** [[01 ATT&CK/S0381 - FlawedAmmyy|S0381: FlawedAmmyy]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1218.007 - Msiexec|T1218.007: Msiexec]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[FlawedAmmyy](https://attack.mitre.org/software/S0381) has been installed via `msiexec.exe`.(Citation: Korean FSI TA505 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--f0966da3-d23d-4949-99d6-ddc680f4a5f3`.
