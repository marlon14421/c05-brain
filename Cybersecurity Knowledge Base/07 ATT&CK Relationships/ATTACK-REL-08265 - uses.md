---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0049"
target_object: "T1087.001"
stix_relationship_id: "relationship--2e69a835-6443-455e-8ff0-775bb8c823f1"
---
# Relationship 8265: S0049 — uses → T1087.001

**Source object:** [[01 ATT&CK/S0049 - GeminiDuke|S0049: GeminiDuke]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1087.001 - Local Account|T1087.001: Local Account]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[GeminiDuke](https://attack.mitre.org/software/S0049) collects information on local user accounts from the victim.(Citation: F-Secure The Dukes)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--2e69a835-6443-455e-8ff0-775bb8c823f1`.
