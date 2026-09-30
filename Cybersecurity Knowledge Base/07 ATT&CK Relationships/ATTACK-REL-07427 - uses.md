---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1207"
target_object: "T1497"
stix_relationship_id: "relationship--6ac4c8cc-c782-4749-9d22-7c5e70ff5ce0"
---
# Relationship 7427: S1207 — uses → T1497

**Source object:** [[01 ATT&CK/S1207 - XLoader|S1207: XLoader]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1497 - Virtualization-Sandbox Evasion|T1497: Virtualization/Sandbox Evasion]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[XLoader](https://attack.mitre.org/software/S1207) can utilize decoy command and control domains within the malware configuration to circumvent sandbox analysis.(Citation: ANY.RUN XLoader 2023)(Citation: CheckPoint XLoader 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--6ac4c8cc-c782-4749-9d22-7c5e70ff5ce0`.
