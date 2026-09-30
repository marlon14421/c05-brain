---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1159"
target_object: "T1027.009"
stix_relationship_id: "relationship--e0d78b1f-4c62-4537-af82-da7575f1fe9e"
---
# Relationship 8532: S1159 — uses → T1027.009

**Source object:** [[01 ATT&CK/S1159 - DUSTTRAP|S1159: DUSTTRAP]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027.009 - Embedded Payloads|T1027.009: Embedded Payloads]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[DUSTTRAP](https://attack.mitre.org/software/S1159) contains additional embedded DLLs and configuration files that are loaded into memory during execution.(Citation: Google Cloud APT41 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e0d78b1f-4c62-4537-af82-da7575f1fe9e`.
