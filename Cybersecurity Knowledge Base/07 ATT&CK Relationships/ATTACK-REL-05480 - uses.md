---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0244"
target_object: "T1518.001"
stix_relationship_id: "relationship--26289101-47e6-47a5-bc9f-19bf918721d6"
---
# Relationship 5480: S0244 — uses → T1518.001

**Source object:** [[01 ATT&CK/S0244 - Comnie|S0244: Comnie]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1518.001 - Security Software Discovery|T1518.001: Security Software Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Comnie](https://attack.mitre.org/software/S0244) attempts to detect several anti-virus products.(Citation: Palo Alto Comnie)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--26289101-47e6-47a5-bc9f-19bf918721d6`.
