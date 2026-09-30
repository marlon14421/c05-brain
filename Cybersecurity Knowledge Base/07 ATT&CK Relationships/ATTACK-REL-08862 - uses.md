---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0043"
target_object: "T1071.001"
stix_relationship_id: "relationship--7a10c6fe-be4a-4229-b038-5de99de13fd6"
---
# Relationship 8862: C0043 — uses → T1071.001

**Source object:** [[01 ATT&CK/C0043 - Indian Critical Infrastructure Intrusions|C0043: Indian Critical Infrastructure Intrusions]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1071.001 - Web Protocols|T1071.001: Web Protocols]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

During [Indian Critical Infrastructure Intrusions](https://attack.mitre.org/campaigns/C0043), [RedEcho](https://attack.mitre.org/groups/G1042) network activity included SSL traffic over TCP 443 and HTTP traffic over non-standard ports.(Citation: RecordedFuture RedEcho 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--7a10c6fe-be4a-4229-b038-5de99de13fd6`.
