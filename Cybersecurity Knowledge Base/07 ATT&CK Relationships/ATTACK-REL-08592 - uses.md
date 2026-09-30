---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0496"
target_object: "T1083"
stix_relationship_id: "relationship--74972bfd-6910-4602-8327-5cc6db07e48a"
---
# Relationship 8592: S0496 — uses → T1083

**Source object:** [[01 ATT&CK/S0496 - REvil|S0496: REvil]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1083 - File and Directory Discovery|T1083: File and Directory Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[REvil](https://attack.mitre.org/software/S0496) has the ability to identify specific files and directories that are not to be encrypted.(Citation: Kaspersky Sodin July 2019)(Citation: Cylance Sodinokibi July 2019)(Citation: Secureworks GandCrab and REvil September 2019)(Citation: McAfee Sodinokibi October 2019)(Citation: Intel 471 REvil March 2020)(Citation: Secureworks REvil September 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--74972bfd-6910-4602-8327-5cc6db07e48a`.
