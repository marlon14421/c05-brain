---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0125"
target_object: "T1593.003"
stix_relationship_id: "relationship--7ce696b0-6d76-4f54-ae4f-4e7115255a5d"
---
# Relationship 6967: G0125 — uses → T1593.003

**Source object:** [[01 ATT&CK/G0125 - HAFNIUM|G0125: HAFNIUM]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1593.003 - Code Repositories|T1593.003: Code Repositories]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[HAFNIUM](https://attack.mitre.org/groups/G0125) has discovered leaked corporate credentials on public repositories including GitHub.(Citation: Microsoft Silk Typhoon MAR 2025)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--7ce696b0-6d76-4f54-ae4f-4e7115255a5d`.
