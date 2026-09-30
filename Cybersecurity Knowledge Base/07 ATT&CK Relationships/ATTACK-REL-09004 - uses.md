---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0352"
target_object: "T1082"
stix_relationship_id: "relationship--588865e4-caec-4150-9c03-df5e28eb9c79"
---
# Relationship 9004: S0352 — uses → T1082

**Source object:** [[01 ATT&CK/S0352 - OSX_OCEANLOTUS.D|S0352: OSX_OCEANLOTUS.D]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1082 - System Information Discovery|T1082: System Information Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[OSX_OCEANLOTUS.D](https://attack.mitre.org/software/S0352) collects processor information, memory information, computer name, hardware UUID, serial number, and operating system version. [OSX_OCEANLOTUS.D](https://attack.mitre.org/software/S0352) has used the ioreg command to gather some of this information.(Citation: TrendMicro MacOS April 2018)(Citation: Trend Micro MacOS Backdoor November 2020)(Citation: 20 macOS Common Tools and Techniques)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--588865e4-caec-4150-9c03-df5e28eb9c79`.
