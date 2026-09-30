---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0670"
target_object: "T1112"
stix_relationship_id: "relationship--42a2aec6-4efb-44d0-8ae8-32a208c05da6"
---
# Relationship 7825: S0670 — uses → T1112

**Source object:** [[01 ATT&CK/S0670 - WarzoneRAT|S0670: WarzoneRAT]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1112 - Modify Registry|T1112: Modify Registry]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[WarzoneRAT](https://attack.mitre.org/software/S0670) can create `HKCU\Software\Classes\Folder\shell\open\command` as a new registry key during privilege escalation.(Citation: Uptycs Warzone UAC Bypass November 2020)(Citation: Check Point Warzone Feb 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--42a2aec6-4efb-44d0-8ae8-32a208c05da6`.
