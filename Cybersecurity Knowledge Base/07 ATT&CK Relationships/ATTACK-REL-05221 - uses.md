---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9041"
target_object: "T1059.004"
stix_relationship_id: "relationship--d586b2af-ad13-48f2-b7d6-126172d25f9a"
---
# Relationship 5221: S9041 — uses → T1059.004

**Source object:** [[01 ATT&CK/S9041 - TeamPCP Cloud Stealer|S9041: TeamPCP Cloud Stealer]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.004 - Unix Shell|T1059.004: Unix Shell]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[TeamPCP Cloud Stealer](https://attack.mitre.org/software/S9041) has abused the shell script files entrypoint.sh (in trivy-action) and setup.sh (in ast-github-action/2.3.28) for discovery and credential harvesting.(Citation: Sysdig TeamPCP MAR 2026) (Citation: Palo Alto TeamPCP MAR 2026)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d586b2af-ad13-48f2-b7d6-126172d25f9a`.
