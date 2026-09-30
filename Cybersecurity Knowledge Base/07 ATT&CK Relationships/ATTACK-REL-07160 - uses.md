---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0259"
target_object: "T1543.003"
stix_relationship_id: "relationship--c0584f8c-e358-4058-aafc-130bfb54dc88"
---
# Relationship 7160: S0259 — uses → T1543.003

**Source object:** [[01 ATT&CK/S0259 - InnaputRAT|S0259: InnaputRAT]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1543.003 - Windows Service|T1543.003: Windows Service]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

Some [InnaputRAT](https://attack.mitre.org/software/S0259) variants create a new Windows service to establish persistence.(Citation: ASERT InnaputRAT April 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c0584f8c-e358-4058-aafc-130bfb54dc88`.
