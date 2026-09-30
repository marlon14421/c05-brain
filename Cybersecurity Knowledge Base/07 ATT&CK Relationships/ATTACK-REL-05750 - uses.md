---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0651"
target_object: "T1567.002"
stix_relationship_id: "relationship--b38a0fe4-6482-4c13-9def-5c8a82f31226"
---
# Relationship 5750: S0651 — uses → T1567.002

**Source object:** [[01 ATT&CK/S0651 - BoxCaon|S0651: BoxCaon]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1567.002 - Exfiltration to Cloud Storage|T1567.002: Exfiltration to Cloud Storage]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[BoxCaon](https://attack.mitre.org/software/S0651) has the capability to download folders' contents on the system and upload the results back to its Dropbox drive.(Citation: Checkpoint IndigoZebra July 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--b38a0fe4-6482-4c13-9def-5c8a82f31226`.
