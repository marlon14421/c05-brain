---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0161"
target_object: "T1113"
stix_relationship_id: "relationship--c0223316-4b0b-461e-8947-01c0f5baeef2"
---
# Relationship 7990: S0161 — uses → T1113

**Source object:** [[01 ATT&CK/S0161 - XAgentOSX|S0161: XAgentOSX]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1113 - Screen Capture|T1113: Screen Capture]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[XAgentOSX](https://attack.mitre.org/software/S0161) contains the takeScreenShot (along with startTakeScreenShot and stopTakeScreenShot) functions to take screenshots using the CGGetActiveDisplayList, CGDisplayCreateImage, and NSImage:initWithCGImage methods.(Citation: XAgentOSX 2017)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c0223316-4b0b-461e-8947-01c0f5baeef2`.
