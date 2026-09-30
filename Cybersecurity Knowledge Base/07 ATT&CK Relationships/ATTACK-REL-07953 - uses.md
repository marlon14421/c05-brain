---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0533"
target_object: "T1543.003"
stix_relationship_id: "relationship--5724994d-7213-4a70-8065-1a12280f8f4c"
---
# Relationship 7953: S0533 — uses → T1543.003

**Source object:** [[01 ATT&CK/S0533 - SLOTHFULMEDIA|S0533: SLOTHFULMEDIA]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1543.003 - Windows Service|T1543.003: Windows Service]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[SLOTHFULMEDIA](https://attack.mitre.org/software/S0533) has created a service on victim machines named "TaskFrame" to establish persistence.(Citation: CISA MAR SLOTHFULMEDIA October 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--5724994d-7213-4a70-8065-1a12280f8f4c`.
