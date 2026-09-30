---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0572"
target_object: "T1105"
stix_relationship_id: "relationship--d4dc5fe6-fbfb-4718-8a7f-cd1eca70db61"
---
# Relationship 8728: S0572 — uses → T1105

**Source object:** [[01 ATT&CK/S0572 - Caterpillar WebShell|S0572: Caterpillar WebShell]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1105 - Ingress Tool Transfer|T1105: Ingress Tool Transfer]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Caterpillar WebShell](https://attack.mitre.org/software/S0572) has a module to download and upload files to the system.(Citation: ClearSky Lebanese Cedar Jan 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d4dc5fe6-fbfb-4718-8a7f-cd1eca70db61`.
