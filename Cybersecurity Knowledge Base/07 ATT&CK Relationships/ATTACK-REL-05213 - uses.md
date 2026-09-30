---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0515"
target_object: "T1560"
stix_relationship_id: "relationship--423b6f97-96c5-47f3-aa9f-f27bf5cd1ba0"
---
# Relationship 5213: S0515 — uses → T1560

**Source object:** [[01 ATT&CK/S0515 - WellMail|S0515: WellMail]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1560 - Archive Collected Data|T1560: Archive Collected Data]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[WellMail](https://attack.mitre.org/software/S0515) can archive files on the compromised host.(Citation: CISA WellMail July 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--423b6f97-96c5-47f3-aa9f-f27bf5cd1ba0`.
