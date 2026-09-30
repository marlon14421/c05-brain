---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0401"
target_object: "T1105"
stix_relationship_id: "relationship--15bb2796-7c6d-4d03-8d86-8d83254bcf0b"
---
# Relationship 9143: S0401 — uses → T1105

**Source object:** [[01 ATT&CK/S0401 - Exaramel for Linux|S0401: Exaramel for Linux]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1105 - Ingress Tool Transfer|T1105: Ingress Tool Transfer]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Exaramel for Linux](https://attack.mitre.org/software/S0401) has a command to download a file from and to a remote C2 server.(Citation: ESET TeleBots Oct 2018)(Citation: ANSSI Sandworm January 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--15bb2796-7c6d-4d03-8d86-8d83254bcf0b`.
