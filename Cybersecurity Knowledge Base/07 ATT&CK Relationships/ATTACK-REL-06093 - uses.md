---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1056"
target_object: "T1555.006"
stix_relationship_id: "relationship--16b8ae40-963b-4a36-a19a-aab861c10a3b"
---
# Relationship 6093: G1056 — uses → T1555.006

**Source object:** [[01 ATT&CK/G1056 - TeamPCP|G1056: TeamPCP]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1555.006 - Cloud Secrets Management Stores|T1555.006: Cloud Secrets Management Stores]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[TeamPCP](https://attack.mitre.org/groups/G1056) has used malware to exfiltrate cloud secrets from targeted environments including AWS, GCP, and Azure.(Citation: Sysdig TeamPCP MAR 2026)(Citation: Aikido TeamPCP Telnyx MAR 2026)(Citation: Palo Alto TeamPCP MAR 2026)(Citation: FBI TeamPCP JUL 2026)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--16b8ae40-963b-4a36-a19a-aab861c10a3b`.
