---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0066"
target_object: "T1105"
stix_relationship_id: "relationship--f0ef3f47-5651-4638-a007-cb585d3174b0"
---
# Relationship 5751: G0066 — uses → T1105

**Source object:** [[01 ATT&CK/G0066 - Elderwood|G0066: Elderwood]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1105 - Ingress Tool Transfer|T1105: Ingress Tool Transfer]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

The Ritsol backdoor trojan used by [Elderwood](https://attack.mitre.org/groups/G0066) can download files onto a compromised host from a remote location.(Citation: Symantec Ristol May 2012)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--f0ef3f47-5651-4638-a007-cb585d3174b0`.
