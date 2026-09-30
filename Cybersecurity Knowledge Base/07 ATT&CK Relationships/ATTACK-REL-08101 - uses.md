---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0065"
target_object: "T1055.001"
stix_relationship_id: "relationship--7995952f-370f-4514-a0c1-ce160b4c90c1"
---
# Relationship 8101: G0065 — uses → T1055.001

**Source object:** [[01 ATT&CK/G0065 - Leviathan|G0065: Leviathan]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1055.001 - Dynamic-link Library Injection|T1055.001: Dynamic-link Library Injection]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Leviathan](https://attack.mitre.org/groups/G0065) has utilized techniques like reflective DLL loading to write a DLL into memory and load a shell that provides backdoor access to the victim.(Citation: Accenture MUDCARP March 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--7995952f-370f-4514-a0c1-ce160b4c90c1`.
