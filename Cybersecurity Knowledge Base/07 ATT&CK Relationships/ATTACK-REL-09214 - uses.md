---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0144"
target_object: "T1057"
stix_relationship_id: "relationship--e6f69552-fe0e-4b40-ad20-4410048277e6"
---
# Relationship 9214: S0144 — uses → T1057

**Source object:** [[01 ATT&CK/S0144 - ChChes|S0144: ChChes]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1057 - Process Discovery|T1057: Process Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[ChChes](https://attack.mitre.org/software/S0144) collects its process identifier (PID) on the victim.(Citation: Palo Alto menuPass Feb 2017)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e6f69552-fe0e-4b40-ad20-4410048277e6`.
