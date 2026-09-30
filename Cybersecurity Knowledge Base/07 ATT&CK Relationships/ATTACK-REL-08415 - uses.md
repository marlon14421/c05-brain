---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0658"
target_object: "T1560"
stix_relationship_id: "relationship--7bbd6131-24cd-437e-8057-02f84b357cbe"
---
# Relationship 8415: S0658 — uses → T1560

**Source object:** [[01 ATT&CK/S0658 - XCSSET|S0658: XCSSET]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1560 - Archive Collected Data|T1560: Archive Collected Data]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[XCSSET](https://attack.mitre.org/software/S0658) will compress entire ~/Desktop folders excluding all .git folders, but only if the total data size is under 200MB.(Citation: trendmicro xcsset xcode project 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--7bbd6131-24cd-437e-8057-02f84b357cbe`.
