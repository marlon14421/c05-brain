---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0240"
target_object: "T1012"
stix_relationship_id: "relationship--2de4d7df-18fc-4202-93ee-2fcfe6f2e501"
---
# Relationship 8384: S0240 — uses → T1012

**Source object:** [[01 ATT&CK/S0240 - ROKRAT|S0240: ROKRAT]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1012 - Query Registry|T1012: Query Registry]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[ROKRAT](https://attack.mitre.org/software/S0240) can access the HKLM\System\CurrentControlSet\Services\mssmbios\Data\SMBiosData Registry key to obtain the System manufacturer value to identify the machine type.(Citation: Talos Group123)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--2de4d7df-18fc-4202-93ee-2fcfe6f2e501`.
