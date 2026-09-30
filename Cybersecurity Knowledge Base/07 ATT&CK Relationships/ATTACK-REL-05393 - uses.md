---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0139"
target_object: "T1685.006"
stix_relationship_id: "relationship--e9e1ba6c-10ed-4b1f-8c82-4102ccbbe394"
---
# Relationship 5393: G0139 — uses → T1685.006

**Source object:** [[01 ATT&CK/G0139 - TeamTNT|G0139: TeamTNT]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1685.006 - Clear Linux or Mac System Logs|T1685.006: Clear Linux or Mac System Logs]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[TeamTNT](https://attack.mitre.org/groups/G0139) has removed system logs from /var/log/syslog .(Citation: Aqua TeamTNT August 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e9e1ba6c-10ed-4b1f-8c82-4102ccbbe394`.
