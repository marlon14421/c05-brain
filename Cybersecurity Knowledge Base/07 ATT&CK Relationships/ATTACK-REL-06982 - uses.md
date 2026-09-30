---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1035"
target_object: "T1033"
stix_relationship_id: "relationship--284843c3-18d0-4ddb-aab5-4588a6ec400e"
---
# Relationship 6982: G1035 — uses → T1033

**Source object:** [[01 ATT&CK/G1035 - Winter Vivern|G1035: Winter Vivern]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1033 - System Owner-User Discovery|T1033: System Owner/User Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Winter Vivern](https://attack.mitre.org/groups/G1035) PowerShell scripts execute `whoami` to identify the executing user.(Citation: SentinelOne WinterVivern 2023)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--284843c3-18d0-4ddb-aab5-4588a6ec400e`.
