---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0046"
target_object: "T1497"
stix_relationship_id: "relationship--8f88490e-346b-4462-b077-0211707c21a3"
---
# Relationship 6807: S0046 — uses → T1497

**Source object:** [[01 ATT&CK/S0046 - CozyCar|S0046: CozyCar]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1497 - Virtualization-Sandbox Evasion|T1497: Virtualization/Sandbox Evasion]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

Some versions of [CozyCar](https://attack.mitre.org/software/S0046) will check to ensure it is not being executed inside a virtual machine or a known malware analysis sandbox environment. If it detects that it is, it will exit.(Citation: F-Secure CozyDuke)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--8f88490e-346b-4462-b077-0211707c21a3`.
