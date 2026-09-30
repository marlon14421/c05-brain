---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9041"
target_object: "T1567.001"
stix_relationship_id: "relationship--9374087b-bb02-47e1-ac3d-76e4886e73d8"
---
# Relationship 8150: S9041 — uses → T1567.001

**Source object:** [[01 ATT&CK/S9041 - TeamPCP Cloud Stealer|S9041: TeamPCP Cloud Stealer]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1567.001 - Exfiltration to Code Repository|T1567.001: Exfiltration to Code Repository]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[TeamPCP Cloud Stealer](https://attack.mitre.org/software/S9041) can create a repository in the victim's GitHub account using the victim's own GITHUB_TOKEN to upload stolen credentials.(Citation: Wiz Trivy Compromise MAR 2026)(Citation: Aqua Security Trivy Compromise MAR 2026)(Citation: Aqua Security Blog Trivy Compromise APR 2026)(Citation: Sysdig TeamPCP MAR 2026)(Citation: Wiz TeamPCP KICS MAR 2026)(Citation: Palo Alto TeamPCP MAR 2026)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--9374087b-bb02-47e1-ac3d-76e4886e73d8`.
