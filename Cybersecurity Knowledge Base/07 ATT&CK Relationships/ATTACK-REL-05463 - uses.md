---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9041"
target_object: "T1020"
stix_relationship_id: "relationship--ace245e2-6972-4247-9b08-4c6a375cfce7"
---
# Relationship 5463: S9041 — uses → T1020

**Source object:** [[01 ATT&CK/S9041 - TeamPCP Cloud Stealer|S9041: TeamPCP Cloud Stealer]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1020 - Automated Exfiltration|T1020: Automated Exfiltration]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[TeamPCP Cloud Stealer](https://attack.mitre.org/software/S9041) can compress and encrypt data and exfiltrate it via POST to scan.aquasecurtiy[.]org. If that method fails it attempts to use a stolen GITHUB_TOKEN to create a repo and exfiltrate the data there.(Citation: Wiz Trivy Compromise MAR 2026)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--ace245e2-6972-4247-9b08-4c6a375cfce7`.
