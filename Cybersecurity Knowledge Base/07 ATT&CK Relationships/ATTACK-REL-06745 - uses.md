---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0226"
target_object: "T1055"
stix_relationship_id: "relationship--95ed1db5-c388-4b1b-9824-9703b248f798"
---
# Relationship 6745: S0226 — uses → T1055

**Source object:** [[01 ATT&CK/S0226 - Smoke Loader|S0226: Smoke Loader]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1055 - Process Injection|T1055: Process Injection]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Smoke Loader](https://attack.mitre.org/software/S0226) injects into the Internet Explorer process.(Citation: Talos Smoke Loader July 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--95ed1db5-c388-4b1b-9824-9703b248f798`.
