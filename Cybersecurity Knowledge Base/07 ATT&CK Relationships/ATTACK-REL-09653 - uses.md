---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9023"
target_object: "T1686.003"
stix_relationship_id: "relationship--fbb495aa-063b-45c4-829a-a9499a66e525"
---
# Relationship 9653: S9023 — uses → T1686.003

**Source object:** [[01 ATT&CK/S9023 - HiddenFace|S9023: HiddenFace]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1686.003 - Windows Host Firewall|T1686.003: Windows Host Firewall]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[HiddenFace](https://attack.mitre.org/software/S9023) can reconfigure Windows firewalls to enable communication by adding a rule named “Cortana” to allow inbound connection to TCP/47000.(Citation: ESET HiddenFace 2024)(Citation: Trend Micro Earth Kasha NOV 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--fbb495aa-063b-45c4-829a-a9499a66e525`.
