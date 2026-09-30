---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0447"
target_object: "T1055.012"
stix_relationship_id: "relationship--33a464ab-cc0d-436d-9bcd-9d6e08994370"
---
# Relationship 7221: S0447 — uses → T1055.012

**Source object:** [[01 ATT&CK/S0447 - Lokibot|S0447: Lokibot]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1055.012 - Process Hollowing|T1055.012: Process Hollowing]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Lokibot](https://attack.mitre.org/software/S0447) has used process hollowing to inject itself into legitimate Windows process.(Citation: Infoblox Lokibot January 2019)(Citation: Talos Lokibot Jan 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--33a464ab-cc0d-436d-9bcd-9d6e08994370`.
