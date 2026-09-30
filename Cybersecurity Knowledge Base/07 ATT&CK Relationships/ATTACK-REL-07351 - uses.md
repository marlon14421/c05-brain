---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0108"
target_object: "T1059.001"
stix_relationship_id: "relationship--06de29d8-365b-4072-a4bb-9d436763ea1e"
---
# Relationship 7351: G0108 — uses → T1059.001

**Source object:** [[01 ATT&CK/G0108 - Blue Mockingbird|G0108: Blue Mockingbird]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.001 - PowerShell|T1059.001: PowerShell]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Blue Mockingbird](https://attack.mitre.org/groups/G0108) has used PowerShell reverse TCP shells to issue interactive commands over a network connection.(Citation: RedCanary Mockingbird May 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--06de29d8-365b-4072-a4bb-9d436763ea1e`.
