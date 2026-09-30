---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0058"
target_object: "T1033"
stix_relationship_id: "relationship--0df8e968-716a-4de9-9669-862af62d6eb6"
---
# Relationship 8142: S0058 — uses → T1033

**Source object:** [[01 ATT&CK/S0058 - SslMM|S0058: SslMM]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1033 - System Owner-User Discovery|T1033: System Owner/User Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[SslMM](https://attack.mitre.org/software/S0058) sends the logged-on username to its hard-coded C2.(Citation: Baumgartner Naikon 2015)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--0df8e968-716a-4de9-9669-862af62d6eb6`.
