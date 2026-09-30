---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0437"
target_object: "T1564.003"
stix_relationship_id: "relationship--7ded147e-f252-490a-b0d7-d8b3492c84eb"
---
# Relationship 7988: S0437 — uses → T1564.003

**Source object:** [[01 ATT&CK/S0437 - Kivars|S0437: Kivars]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1564.003 - Hidden Window|T1564.003: Hidden Window]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Kivars](https://attack.mitre.org/software/S0437) has the ability to conceal its activity through hiding active windows.(Citation: TrendMicro BlackTech June 2017)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--7ded147e-f252-490a-b0d7-d8b3492c84eb`.
