---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0477"
target_object: "T1005"
stix_relationship_id: "relationship--bd2312fb-51ff-4766-a24f-1f5911457bc6"
---
# Relationship 9467: S0477 — uses → T1005

**Source object:** [[01 ATT&CK/S0477 - Goopy|S0477: Goopy]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1005 - Data from Local System|T1005: Data from Local System]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Goopy](https://attack.mitre.org/software/S0477) has the ability to exfiltrate documents from infected systems.(Citation: Cybereason Cobalt Kitty 2017)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--bd2312fb-51ff-4766-a24f-1f5911457bc6`.
