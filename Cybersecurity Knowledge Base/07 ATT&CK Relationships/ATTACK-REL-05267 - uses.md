---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0046"
target_object: "T1036.003"
stix_relationship_id: "relationship--a4a49b56-e220-4a81-a0da-43b63c012cfe"
---
# Relationship 5267: S0046 — uses → T1036.003

**Source object:** [[01 ATT&CK/S0046 - CozyCar|S0046: CozyCar]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1036.003 - Rename Legitimate Utilities|T1036.003: Rename Legitimate Utilities]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

The [CozyCar](https://attack.mitre.org/software/S0046) dropper has masqueraded a copy of the infected system's rundll32.exe executable that was moved to the malware's install directory and renamed according to a predefined configuration file.(Citation: F-Secure CozyDuke)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a4a49b56-e220-4a81-a0da-43b63c012cfe`.
