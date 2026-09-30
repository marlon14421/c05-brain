---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0483"
target_object: "T1105"
stix_relationship_id: "relationship--a8484e9d-ad08-4d2c-8328-24552dd22f35"
---
# Relationship 8011: S0483 — uses → T1105

**Source object:** [[01 ATT&CK/S0483 - IcedID|S0483: IcedID]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1105 - Ingress Tool Transfer|T1105: Ingress Tool Transfer]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[IcedID](https://attack.mitre.org/software/S0483) has the ability to download additional modules and a configuration file from C2.(Citation: IBM IcedID November 2017)(Citation: Juniper IcedID June 2020)(Citation: DFIR_Quantum_Ransomware)(Citation: Latrodectus APR 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a8484e9d-ad08-4d2c-8328-24552dd22f35`.
