---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0037"
target_object: "T1218.011"
stix_relationship_id: "relationship--eaa42ea7-0a48-4ec9-82cd-1bab99db9e38"
---
# Relationship 9145: C0037 — uses → T1218.011

**Source object:** [[01 ATT&CK/C0037 - Water Curupira Pikabot Distribution|C0037: Water Curupira Pikabot Distribution]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1218.011 - Rundll32|T1218.011: Rundll32]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Water Curupira Pikabot Distribution](https://attack.mitre.org/campaigns/C0037) utilizes rundll32.exe to execute the final [Pikabot](https://attack.mitre.org/software/S1145) payload, using the named exports `Crash` or `Limit` depending on the variant.(Citation: TrendMicro Pikabot 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--eaa42ea7-0a48-4ec9-82cd-1bab99db9e38`.
