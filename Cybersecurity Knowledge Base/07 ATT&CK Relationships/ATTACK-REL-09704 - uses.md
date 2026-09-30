---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0695"
target_object: "T1055"
stix_relationship_id: "relationship--2c6c5572-9b89-40cd-8faa-6317945cf939"
---
# Relationship 9704: S0695 — uses → T1055

**Source object:** [[01 ATT&CK/S0695 - Donut|S0695: Donut]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1055 - Process Injection|T1055: Process Injection]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Donut](https://attack.mitre.org/software/S0695) includes a subproject DonutTest to inject shellcode into a target process.(Citation: Donut Github)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--2c6c5572-9b89-40cd-8faa-6317945cf939`.
