---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0653"
target_object: "T1105"
stix_relationship_id: "relationship--ae7cd450-60bc-426b-92df-14d9d1be279b"
---
# Relationship 5214: S0653 — uses → T1105

**Source object:** [[01 ATT&CK/S0653 - xCaon|S0653: xCaon]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1105 - Ingress Tool Transfer|T1105: Ingress Tool Transfer]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[xCaon](https://attack.mitre.org/software/S0653) has a command to download files to the victim's machine.(Citation: Checkpoint IndigoZebra July 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--ae7cd450-60bc-426b-92df-14d9d1be279b`.
