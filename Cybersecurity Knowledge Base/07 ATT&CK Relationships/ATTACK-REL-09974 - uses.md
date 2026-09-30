---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0331"
target_object: "T1204.002"
stix_relationship_id: "relationship--1cd41777-3d65-4e39-8de7-3951d1568c16"
---
# Relationship 9974: S0331 — uses → T1204.002

**Source object:** [[01 ATT&CK/S0331 - Agent Tesla|S0331: Agent Tesla]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1204.002 - Malicious File|T1204.002: Malicious File]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Agent Tesla](https://attack.mitre.org/software/S0331) has been executed through malicious e-mail attachments (Citation: Bitdefender Agent Tesla April 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--1cd41777-3d65-4e39-8de7-3951d1568c16`.
