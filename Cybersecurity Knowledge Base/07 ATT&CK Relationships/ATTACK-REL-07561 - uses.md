---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1091"
target_object: "T1685.002"
stix_relationship_id: "relationship--16bf5f35-b65b-4450-8873-d3c8e80fbbf8"
---
# Relationship 7561: S1091 — uses → T1685.002

**Source object:** [[01 ATT&CK/S1091 - Pacu|S1091: Pacu]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1685.002 - Disable or Modify Cloud Log|T1685.002: Disable or Modify Cloud Log]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Pacu](https://attack.mitre.org/software/S1091) can disable or otherwise restrict various AWS logging services, such as AWS CloudTrail and VPC flow logs.(Citation: GitHub Pacu)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--16bf5f35-b65b-4450-8873-d3c8e80fbbf8`.
