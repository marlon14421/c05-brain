---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0031"
target_object: "T1059.003"
stix_relationship_id: "relationship--3f14994e-149d-4cca-85b8-eec0964120d3"
---
# Relationship 6576: S0031 — uses → T1059.003

**Source object:** [[01 ATT&CK/S0031 - BACKSPACE|S0031: BACKSPACE]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.003 - Windows Command Shell|T1059.003: Windows Command Shell]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

Adversaries can direct [BACKSPACE](https://attack.mitre.org/software/S0031) to execute from the command line on infected hosts, or have [BACKSPACE](https://attack.mitre.org/software/S0031) create a reverse shell.(Citation: FireEye APT30)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--3f14994e-149d-4cca-85b8-eec0964120d3`.
