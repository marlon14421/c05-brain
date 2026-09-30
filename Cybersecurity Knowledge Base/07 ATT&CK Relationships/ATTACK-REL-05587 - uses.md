---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0247"
target_object: "T1082"
stix_relationship_id: "relationship--8a00aa55-b7b2-4df5-902b-d01bfdf89089"
---
# Relationship 5587: S0247 — uses → T1082

**Source object:** [[01 ATT&CK/S0247 - NavRAT|S0247: NavRAT]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1082 - System Information Discovery|T1082: System Information Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[NavRAT](https://attack.mitre.org/software/S0247) uses systeminfo on a victim’s machine.(Citation: Talos NavRAT May 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--8a00aa55-b7b2-4df5-902b-d01bfdf89089`.
