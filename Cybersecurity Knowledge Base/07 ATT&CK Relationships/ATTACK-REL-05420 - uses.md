---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0172"
target_object: "T1543.003"
stix_relationship_id: "relationship--ecca0af0-1549-4068-b01d-bab711c491c5"
---
# Relationship 5420: S0172 — uses → T1543.003

**Source object:** [[01 ATT&CK/S0172 - Reaver|S0172: Reaver]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1543.003 - Windows Service|T1543.003: Windows Service]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Reaver](https://attack.mitre.org/software/S0172) installs itself as a new service.(Citation: Palo Alto Reaver Nov 2017)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--ecca0af0-1549-4068-b01d-bab711c491c5`.
