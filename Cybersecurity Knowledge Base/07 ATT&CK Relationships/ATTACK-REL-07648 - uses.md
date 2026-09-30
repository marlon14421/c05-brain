---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0492"
target_object: "T1105"
stix_relationship_id: "relationship--7f249ef4-8a3c-4ab5-998f-256ac8ecf588"
---
# Relationship 7648: S0492 — uses → T1105

**Source object:** [[01 ATT&CK/S0492 - CookieMiner|S0492: CookieMiner]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1105 - Ingress Tool Transfer|T1105: Ingress Tool Transfer]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[CookieMiner](https://attack.mitre.org/software/S0492) can download additional scripts from a web server.(Citation: Unit42 CookieMiner Jan 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--7f249ef4-8a3c-4ab5-998f-256ac8ecf588`.
