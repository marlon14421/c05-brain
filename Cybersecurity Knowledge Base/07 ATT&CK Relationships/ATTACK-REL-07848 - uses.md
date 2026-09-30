---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9019"
target_object: "T1105"
stix_relationship_id: "relationship--aa736843-16e9-4872-827a-41d24782cdb7"
---
# Relationship 7848: S9019 — uses → T1105

**Source object:** [[01 ATT&CK/S9019 - PureCrypter|S9019: PureCrypter]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1105 - Ingress Tool Transfer|T1105: Ingress Tool Transfer]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[PureCrypter](https://attack.mitre.org/software/S9019) can download additional payloads for execution on the compromised host.(Citation: Zscaler PureCrypter JUN 2022)(Citation: Check Point Blind Eagle MAR 2025)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--aa736843-16e9-4872-827a-41d24782cdb7`.
