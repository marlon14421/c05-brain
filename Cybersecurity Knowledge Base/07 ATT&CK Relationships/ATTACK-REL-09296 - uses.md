---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1039"
target_object: "T1082"
stix_relationship_id: "relationship--02a1f8ce-390e-46e4-b945-9cd61c593f9f"
---
# Relationship 9296: S1039 — uses → T1082

**Source object:** [[01 ATT&CK/S1039 - Bumblebee|S1039: Bumblebee]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1082 - System Information Discovery|T1082: System Information Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Bumblebee](https://attack.mitre.org/software/S1039) can enumerate the OS version and domain on a targeted system.(Citation: Google EXOTIC LILY March 2022)(Citation: Proofpoint Bumblebee April 2022)(Citation: Symantec Bumblebee June 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--02a1f8ce-390e-46e4-b945-9cd61c593f9f`.
