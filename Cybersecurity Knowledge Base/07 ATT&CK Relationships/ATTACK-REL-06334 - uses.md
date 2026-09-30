---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9032"
target_object: "T1056.002"
stix_relationship_id: "relationship--7ead2d52-702b-4894-a27d-755e6bd68d32"
---
# Relationship 6334: S9032 — uses → T1056.002

**Source object:** [[01 ATT&CK/S9032 - MuddyViper|S9032: MuddyViper]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1056.002 - GUI Input Capture|T1056.002: GUI Input Capture]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[MuddyViper](https://attack.mitre.org/software/S9032) has displayed a fake Windows Security dialog to gather credentials.(Citation: ESET_MuddyWater_Dec2025)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--7ead2d52-702b-4894-a27d-755e6bd68d32`.
