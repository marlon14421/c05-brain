---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0476"
target_object: "T1555.004"
stix_relationship_id: "relationship--13c82683-dea9-418b-9112-a801c4cebc64"
---
# Relationship 7955: S0476 — uses → T1555.004

**Source object:** [[01 ATT&CK/S0476 - Valak|S0476: Valak]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1555.004 - Windows Credential Manager|T1555.004: Windows Credential Manager]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Valak](https://attack.mitre.org/software/S0476) can use a .NET compiled module named exchgrabber to enumerate credentials from the Credential Manager.(Citation: SentinelOne Valak June 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--13c82683-dea9-418b-9112-a801c4cebc64`.
