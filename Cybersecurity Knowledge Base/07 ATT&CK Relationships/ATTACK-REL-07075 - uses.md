---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0049"
target_object: "T1057"
stix_relationship_id: "relationship--3363ae54-1fe3-4c9f-b074-79dc0d7fbba5"
---
# Relationship 7075: S0049 — uses → T1057

**Source object:** [[01 ATT&CK/S0049 - GeminiDuke|S0049: GeminiDuke]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1057 - Process Discovery|T1057: Process Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[GeminiDuke](https://attack.mitre.org/software/S0049) collects information on running processes and environment variables from the victim.(Citation: F-Secure The Dukes)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--3363ae54-1fe3-4c9f-b074-79dc0d7fbba5`.
