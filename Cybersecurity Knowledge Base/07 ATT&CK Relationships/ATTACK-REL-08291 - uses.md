---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9041"
target_object: "T1071.001"
stix_relationship_id: "relationship--f3586c05-e0be-4e55-b408-48b9a87c58f1"
---
# Relationship 8291: S9041 — uses → T1071.001

**Source object:** [[01 ATT&CK/S9041 - TeamPCP Cloud Stealer|S9041: TeamPCP Cloud Stealer]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1071.001 - Web Protocols|T1071.001: Web Protocols]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[TeamPCP Cloud Stealer](https://attack.mitre.org/software/S9041) has used `curl` to upload stolen data to attacker controlled domains.(Citation: Sysdig TeamPCP MAR 2026)(Citation: Wiz TeamPCP KICS MAR 2026)(Citation: Palo Alto TeamPCP MAR 2026)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--f3586c05-e0be-4e55-b408-48b9a87c58f1`.
