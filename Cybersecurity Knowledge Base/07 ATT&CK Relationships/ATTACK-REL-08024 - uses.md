---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0666"
target_object: "T1559.001"
stix_relationship_id: "relationship--fa939612-0aa1-40b6-aab6-7a1b1872c93b"
---
# Relationship 8024: S0666 — uses → T1559.001

**Source object:** [[01 ATT&CK/S0666 - Gelsemium|S0666: Gelsemium]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1559.001 - Component Object Model|T1559.001: Component Object Model]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Gelsemium](https://attack.mitre.org/software/S0666) can use the `IARPUinstallerStringLauncher` COM interface are part of its UAC bypass process.(Citation: ESET Gelsemium June 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--fa939612-0aa1-40b6-aab6-7a1b1872c93b`.
