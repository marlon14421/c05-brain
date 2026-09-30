---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0692"
target_object: "T1070"
stix_relationship_id: "relationship--2123bedd-f2b3-4856-9ee4-5d23aa9c8745"
---
# Relationship 9398: S0692 — uses → T1070

**Source object:** [[01 ATT&CK/S0692 - SILENTTRINITY|S0692: SILENTTRINITY]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1070 - Indicator Removal|T1070: Indicator Removal]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[SILENTTRINITY](https://attack.mitre.org/software/S0692) can remove artifacts from the compromised host, including created Registry keys.(Citation: GitHub SILENTTRINITY Modules July 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--2123bedd-f2b3-4856-9ee4-5d23aa9c8745`.
