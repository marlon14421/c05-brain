---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0451"
target_object: "T1543.003"
stix_relationship_id: "relationship--80bead39-b050-48d9-b185-aa31d1681a61"
---
# Relationship 8993: S0451 — uses → T1543.003

**Source object:** [[01 ATT&CK/S0451 - LoudMiner|S0451: LoudMiner]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1543.003 - Windows Service|T1543.003: Windows Service]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[LoudMiner](https://attack.mitre.org/software/S0451) can automatically launch a Linux virtual machine as a service at startup if the AutoStart option is enabled in the VBoxVmService configuration file.(Citation: ESET LoudMiner June 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--80bead39-b050-48d9-b185-aa31d1681a61`.
