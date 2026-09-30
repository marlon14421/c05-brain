---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1167"
target_object: "T1082"
stix_relationship_id: "relationship--85c11944-e1a0-49e0-a0ef-03e9df1b2adb"
---
# Relationship 7983: S1167 — uses → T1082

**Source object:** [[01 ATT&CK/S1167 - AcidPour|S1167: AcidPour]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1082 - System Information Discovery|T1082: System Information Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[AcidPour](https://attack.mitre.org/software/S1167) can identify various system locations and mapped devices on Linux systems as a precursor to wiping activity.(Citation: SentinelOne AcidPour 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--85c11944-e1a0-49e0-a0ef-03e9df1b2adb`.
