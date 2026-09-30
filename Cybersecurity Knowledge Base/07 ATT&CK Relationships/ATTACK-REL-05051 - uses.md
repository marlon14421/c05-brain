---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0386"
target_object: "T1105"
stix_relationship_id: "relationship--0d88d99d-88b0-4e49-b2c3-3607a32069ed"
---
# Relationship 5051: S0386 — uses → T1105

**Source object:** [[01 ATT&CK/S0386 - Ursnif|S0386: Ursnif]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1105 - Ingress Tool Transfer|T1105: Ingress Tool Transfer]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Ursnif](https://attack.mitre.org/software/S0386) has dropped payload and configuration files to disk. [Ursnif](https://attack.mitre.org/software/S0386) has also been used to download and execute additional payloads.(Citation: TrendMicro PE_URSNIF.A2)(Citation: TrendMicro BKDR_URSNIF.SM)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--0d88d99d-88b0-4e49-b2c3-3607a32069ed`.
