---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0032"
target_object: "T1070.003"
stix_relationship_id: "relationship--d39e7197-a9b3-4915-8cf0-98bbbd885cd5"
---
# Relationship 8696: G0032 — uses → T1070.003

**Source object:** [[01 ATT&CK/G0032 - Lazarus Group|G0032: Lazarus Group]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1070.003 - Clear Command History|T1070.003: Clear Command History]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Lazarus Group](https://attack.mitre.org/groups/G0032) has routinely deleted log files on a compromised router, including automatic log deletion through the use of the logrotate utility.(Citation: Kaspersky ThreatNeedle Feb 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d39e7197-a9b3-4915-8cf0-98bbbd885cd5`.
