---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0006"
target_object: "T1036.005"
stix_relationship_id: "relationship--c7823efd-005f-49ad-94cf-ebc44a87abed"
---
# Relationship 8840: G0006 — uses → T1036.005

**Source object:** [[01 ATT&CK/G0006 - APT1|G0006: APT1]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1036.005 - Match Legitimate Resource Name or Location|T1036.005: Match Legitimate Resource Name or Location]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

The file name AcroRD32.exe, a legitimate process name for Adobe's Acrobat Reader, was used by [APT1](https://attack.mitre.org/groups/G0006) as a name for malware.(Citation: Mandiant APT1)(Citation: Mandiant APT1 Appendix)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c7823efd-005f-49ad-94cf-ebc44a87abed`.
