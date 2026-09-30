---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1041"
target_object: "T1685.006"
stix_relationship_id: "relationship--d1c161ef-1dca-488d-b50d-8a5c98980e35"
---
# Relationship 8041: G1041 — uses → T1685.006

**Source object:** [[01 ATT&CK/G1041 - Sea Turtle|G1041: Sea Turtle]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1685.006 - Clear Linux or Mac System Logs|T1685.006: Clear Linux or Mac System Logs]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Sea Turtle](https://attack.mitre.org/groups/G1041) has overwritten Linux system logs and unsets the Bash history file (effectively removing logging) during intrusions.(Citation: Hunt Sea Turtle 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d1c161ef-1dca-488d-b50d-8a5c98980e35`.
