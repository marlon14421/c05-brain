---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0458"
target_object: "T1106"
stix_relationship_id: "relationship--239eb918-b9e0-499c-9934-96382fa782a0"
---
# Relationship 7793: S0458 — uses → T1106

**Source object:** [[01 ATT&CK/S0458 - Ramsay|S0458: Ramsay]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1106 - Native API|T1106: Native API]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Ramsay](https://attack.mitre.org/software/S0458) can use Windows API functions such as WriteFile , CloseHandle , and GetCurrentHwProfile during its collection and file storage operations. [Ramsay](https://attack.mitre.org/software/S0458) can execute its embedded components via CreateProcessA and ShellExecute .(Citation: Eset Ramsay May 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--239eb918-b9e0-499c-9934-96382fa782a0`.
