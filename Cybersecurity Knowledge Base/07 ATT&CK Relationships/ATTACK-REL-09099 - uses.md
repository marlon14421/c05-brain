---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1116"
target_object: "T1056.003"
stix_relationship_id: "relationship--ad895e1f-327d-4873-9d73-5bc4bf60e816"
---
# Relationship 9099: S1116 — uses → T1056.003

**Source object:** [[01 ATT&CK/S1116 - WARPWIRE|S1116: WARPWIRE]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1056.003 - Web Portal Capture|T1056.003: Web Portal Capture]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[WARPWIRE](https://attack.mitre.org/software/S1116) can capture credentials submitted during the web logon process in order to access layer seven applications such as RDP.(Citation: Mandiant Cutting Edge January 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--ad895e1f-327d-4873-9d73-5bc4bf60e816`.
