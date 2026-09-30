---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0045"
target_object: "T1029"
stix_relationship_id: "relationship--5eb253cb-2e81-4f51-bd0e-d1734283491c"
---
# Relationship 5864: S0045 — uses → T1029

**Source object:** [[01 ATT&CK/S0045 - ADVSTORESHELL|S0045: ADVSTORESHELL]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1029 - Scheduled Transfer|T1029: Scheduled Transfer]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[ADVSTORESHELL](https://attack.mitre.org/software/S0045) collects, compresses, encrypts, and exfiltrates data to the C2 server every 10 minutes.(Citation: ESET Sednit Part 2)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--5eb253cb-2e81-4f51-bd0e-d1734283491c`.
