---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1056"
target_object: "T1190"
stix_relationship_id: "relationship--269fbafb-f9ad-4782-b9e6-ccf44e3723f8"
---
# Relationship 6979: G1056 — uses → T1190

**Source object:** [[01 ATT&CK/G1056 - TeamPCP|G1056: TeamPCP]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1190 - Exploit Public-Facing Application|T1190: Exploit Public-Facing Application]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[TeamPCP](https://attack.mitre.org/groups/G1056) has exploited misconfigurations in GitHub Actions and vulnerabilities such as CVE-2026-33634 in the Aqua Security Trivy scanner and CVE-2025-55182 (React2Shell) against vulnerable cloud endpoints.(Citation: Aqua Security Blog Trivy Compromise APR 2026)(Citation: Aikido TeamPCP Telnyx MAR 2026)(Citation: Palo Alto TeamPCP MAR 2026)(Citation: Wiz Mini Shai-Hulud MAY 2026)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--269fbafb-f9ad-4782-b9e6-ccf44e3723f8`.
