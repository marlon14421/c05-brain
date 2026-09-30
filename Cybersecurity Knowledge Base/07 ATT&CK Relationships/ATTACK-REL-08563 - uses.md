---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1090"
target_object: "T1057"
stix_relationship_id: "relationship--c434aa66-8fd2-47f0-8ec4-88a866d99e88"
---
# Relationship 8563: S1090 — uses → T1057

**Source object:** [[01 ATT&CK/S1090 - NightClub|S1090: NightClub]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1057 - Process Discovery|T1057: Process Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[NightClub](https://attack.mitre.org/software/S1090) has the ability to use `GetWindowThreadProcessId` to identify the process behind a specified window.(Citation: MoustachedBouncer ESET August 2023)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c434aa66-8fd2-47f0-8ec4-88a866d99e88`.
