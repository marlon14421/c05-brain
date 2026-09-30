---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0439"
target_object: "T1090.002"
stix_relationship_id: "relationship--95e5fd0e-b9c1-4efa-b462-a922456401e6"
---
# Relationship 8241: S0439 — uses → T1090.002

**Source object:** [[01 ATT&CK/S0439 - Okrum|S0439: Okrum]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1090.002 - External Proxy|T1090.002: External Proxy]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Okrum](https://attack.mitre.org/software/S0439) can identify proxy servers configured and used by the victim, and use it to make HTTP requests to C2 its server.(Citation: ESET Okrum July 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--95e5fd0e-b9c1-4efa-b462-a922456401e6`.
