---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1190"
target_object: "T1036.008"
stix_relationship_id: "relationship--27531ac2-9f44-4613-89e0-0fbfa30661b3"
---
# Relationship 6185: S1190 — uses → T1036.008

**Source object:** [[01 ATT&CK/S1190 - Kapeka|S1190: Kapeka]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1036.008 - Masquerade File Type|T1036.008: Masquerade File Type]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Kapeka](https://attack.mitre.org/software/S1190) masquerades as a Microsoft Word Add-In file, with the extension `.wll`, but is a malicious DLL file.(Citation: Microsoft KnuckleTouch 2024)(Citation: WithSecure Kapeka 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--27531ac2-9f44-4613-89e0-0fbfa30661b3`.
