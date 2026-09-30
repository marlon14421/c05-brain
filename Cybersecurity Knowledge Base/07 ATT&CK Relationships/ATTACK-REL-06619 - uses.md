---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1056"
target_object: "T1583.001"
stix_relationship_id: "relationship--16ba0b1d-4de2-4195-ac05-dde67fe15f8e"
---
# Relationship 6619: G1056 — uses → T1583.001

**Source object:** [[01 ATT&CK/G1056 - TeamPCP|G1056: TeamPCP]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1583.001 - Domains|T1583.001: Domains]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[TeamPCP](https://attack.mitre.org/groups/G1056) has registered domains resembling legitimate victim sites such as scan.aquasecurtiy[.]org, checkmarx[.]zone, and git-tanstack[.]com to mask C2 and exfiltration endpoints.(Citation: Wiz Trivy Compromise MAR 2026)(Citation: Aqua Security Trivy Compromise MAR 2026)(Citation: Aqua Security Blog Trivy Compromise APR 2026)(Citation: Sysdig TeamPCP MAR 2026)(Citation: Wiz TeamPCP KICS MAR 2026)(Citation: Wiz Mini Shai-Hulud MAY 2026)(Citation: Trend Micro TeamPCP MAY 2026)(Citation: Phoenix TeamPCP 20 MAY 2026) [TeamPCP](https://attack.mitre.org/groups/G1056) has also set up a dark web leak site to post stolen data.(Citation: Palo Alto TeamPCP MAR 2026)(Citation: FBI TeamPCP JUL 2026)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--16ba0b1d-4de2-4195-ac05-dde67fe15f8e`.
