---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0124"
target_object: "T1059"
stix_relationship_id: "relationship--bea0bf7c-62c8-4334-b523-5cc6ec8b36c8"
---
# Relationship 7084: G0124 — uses → T1059

**Source object:** [[01 ATT&CK/G0124 - Windigo|G0124: Windigo]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059 - Command and Scripting Interpreter|T1059: Command and Scripting Interpreter]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Windigo](https://attack.mitre.org/groups/G0124) has used a Perl script for information gathering.(Citation: ESET ForSSHe December 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--bea0bf7c-62c8-4334-b523-5cc6ec8b36c8`.
