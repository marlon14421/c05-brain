---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0631"
target_object: "T1185"
stix_relationship_id: "relationship--cf130e28-dbd6-4312-ba0a-a3cbcf05c064"
---
# Relationship 9376: S0631 — uses → T1185

**Source object:** [[01 ATT&CK/S0631 - Chaes|S0631: Chaes]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1185 - Browser Session Hijacking|T1185: Browser Session Hijacking]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Chaes](https://attack.mitre.org/software/S0631) has used the Puppeteer module to hook and monitor the Chrome web browser to collect user information from infected hosts.(Citation: Cybereason Chaes Nov 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--cf130e28-dbd6-4312-ba0a-a3cbcf05c064`.
