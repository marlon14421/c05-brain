---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0026"
target_object: "S1075"
stix_relationship_id: "relationship--dc71c59d-1c71-480a-97de-972248489aa4"
---
# Relationship 9166: C0026 — uses → S1075

**Source object:** [[01 ATT&CK/C0026 - C0026|C0026: C0026]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S1075 - KOPILUWAK|S1075: KOPILUWAK]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[KOPILUWAK](https://attack.mitre.org/software/S1075) was used as a first-stage profiling utility for previous victims of [ANDROMEDA](https://attack.mitre.org/software/S1074) during [C0026](https://attack.mitre.org/campaigns/C0026).(Citation: Mandiant Suspected Turla Campaign February 2023)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--dc71c59d-1c71-480a-97de-972248489aa4`.
