---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0673"
target_object: "T1059.001"
stix_relationship_id: "relationship--43ec2047-44fb-49a5-b24a-9edcb5378e5c"
---
# Relationship 9121: S0673 — uses → T1059.001

**Source object:** [[01 ATT&CK/S0673 - DarkWatchman|S0673: DarkWatchman]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.001 - PowerShell|T1059.001: PowerShell]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[DarkWatchman](https://attack.mitre.org/software/S0673) can execute PowerShell commands and has used PowerShell to execute a keylogger.(Citation: Prevailion DarkWatchman 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--43ec2047-44fb-49a5-b24a-9edcb5378e5c`.
