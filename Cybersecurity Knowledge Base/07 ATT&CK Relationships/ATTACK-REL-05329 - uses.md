---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9041"
target_object: "T1613"
stix_relationship_id: "relationship--45fa0f91-6a04-45e2-94fd-d058c57bcc7c"
---
# Relationship 5329: S9041 — uses → T1613

**Source object:** [[01 ATT&CK/S9041 - TeamPCP Cloud Stealer|S9041: TeamPCP Cloud Stealer]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1613 - Container and Resource Discovery|T1613: Container and Resource Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[TeamPCP Cloud Stealer](https://attack.mitre.org/software/S9041) can identify Docker and Kubernetes environments for credentials.(Citation: Aqua Security Blog Trivy Compromise APR 2026)(Citation: Wiz TeamPCP KICS MAR 2026)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--45fa0f91-6a04-45e2-94fd-d058c57bcc7c`.
