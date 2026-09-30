---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0053"
target_object: "T1070.004"
stix_relationship_id: "relationship--1ace08c6-0f1a-487d-92b2-6c61c2299270"
---
# Relationship 7634: G0053 — uses → T1070.004

**Source object:** [[01 ATT&CK/G0053 - FIN5|G0053: FIN5]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1070.004 - File Deletion|T1070.004: File Deletion]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[FIN5](https://attack.mitre.org/groups/G0053) uses [SDelete](https://attack.mitre.org/software/S0195) to clean up the environment and attempt to prevent detection.(Citation: Mandiant FIN5 GrrCON Oct 2016)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--1ace08c6-0f1a-487d-92b2-6c61c2299270`.
