---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1190"
target_object: "T1132.001"
stix_relationship_id: "relationship--97bb6552-08cc-4c75-938f-fde6041f114b"
---
# Relationship 7313: S1190 — uses → T1132.001

**Source object:** [[01 ATT&CK/S1190 - Kapeka|S1190: Kapeka]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1132.001 - Standard Encoding|T1132.001: Standard Encoding]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Kapeka](https://attack.mitre.org/software/S1190) utilizes JSON objects to send and receive information from command and control nodes.(Citation: WithSecure Kapeka 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--97bb6552-08cc-4c75-938f-fde6041f114b`.
