---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0667"
target_object: "T1106"
stix_relationship_id: "relationship--a483131c-b3b5-4682-aafc-2761d75e2168"
---
# Relationship 8947: S0667 — uses → T1106

**Source object:** [[01 ATT&CK/S0667 - Chrommme|S0667: Chrommme]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1106 - Native API|T1106: Native API]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Chrommme](https://attack.mitre.org/software/S0667) can use Windows API including `WinExec` for execution.(Citation: ESET Gelsemium June 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a483131c-b3b5-4682-aafc-2761d75e2168`.
