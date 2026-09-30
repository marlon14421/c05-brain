---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0119"
target_object: "T1105"
stix_relationship_id: "relationship--d9360852-584e-4980-9f9b-f56193bd3fc0"
---
# Relationship 8641: G0119 — uses → T1105

**Source object:** [[01 ATT&CK/G0119 - Indrik Spider|G0119: Indrik Spider]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1105 - Ingress Tool Transfer|T1105: Ingress Tool Transfer]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Indrik Spider](https://attack.mitre.org/groups/G0119) has downloaded additional scripts, malware, and tools onto a compromised host.(Citation: Crowdstrike Indrik November 2018)(Citation: Symantec WastedLocker June 2020)(Citation: Mandiant_UNC2165)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d9360852-584e-4980-9f9b-f56193bd3fc0`.
