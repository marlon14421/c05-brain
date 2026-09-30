---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1173"
target_object: "T1105"
stix_relationship_id: "relationship--1632dc5e-5ec9-4c93-9fc3-e4496879dfab"
---
# Relationship 5460: S1173 — uses → T1105

**Source object:** [[01 ATT&CK/S1173 - PowerExchange|S1173: PowerExchange]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1105 - Ingress Tool Transfer|T1105: Ingress Tool Transfer]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[PowerExchange](https://attack.mitre.org/software/S1173) can decode Base64-encoded files and call `WriteAllBytes` to write the files to compromised hosts.(Citation: Symantec Crambus OCT 2023)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--1632dc5e-5ec9-4c93-9fc3-e4496879dfab`.
