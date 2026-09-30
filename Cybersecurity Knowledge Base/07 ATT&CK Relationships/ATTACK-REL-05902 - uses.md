---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1161"
target_object: "T1690"
stix_relationship_id: "relationship--e13b34ab-ba4a-4fc0-9bea-3cd4ed165a57"
---
# Relationship 5902: S1161 — uses → T1690

**Source object:** [[01 ATT&CK/S1161 - BPFDoor|S1161: BPFDoor]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1690 - Prevent Command History Logging|T1690: Prevent Command History Logging]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[BPFDoor](https://attack.mitre.org/software/S1161) sets the `MYSQL_HISTFILE` and `HISTFILE` to `/dev/null` preventing the shell and MySQL from logging history in `/proc/ /environ`.(Citation: Sandfly BPFDoor 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e13b34ab-ba4a-4fc0-9bea-3cd4ed165a57`.
