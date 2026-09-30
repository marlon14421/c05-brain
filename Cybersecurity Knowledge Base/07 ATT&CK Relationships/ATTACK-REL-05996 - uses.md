---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0658"
target_object: "T1497.003"
stix_relationship_id: "relationship--e1ee2aae-72b0-4258-abab-2705d6b9268a"
---
# Relationship 5996: S0658 — uses → T1497.003

**Source object:** [[01 ATT&CK/S0658 - XCSSET|S0658: XCSSET]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1497.003 - Time Based Checks|T1497.003: Time Based Checks]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

Using the machine's local time, [XCSSET](https://attack.mitre.org/software/S0658) waits 43200 seconds (12 hours) from the initial creation timestamp of a specific file, .report . After the elapsed time, [XCSSET](https://attack.mitre.org/software/S0658) executes additional modules.(Citation: trendmicro xcsset xcode project 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e1ee2aae-72b0-4258-abab-2705d6b9268a`.
