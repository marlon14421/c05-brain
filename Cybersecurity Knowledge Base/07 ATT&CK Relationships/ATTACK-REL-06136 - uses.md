---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0138"
target_object: "T1049"
stix_relationship_id: "relationship--2bb829ce-e597-4033-af7c-ef44aaebadb4"
---
# Relationship 6136: G0138 — uses → T1049

**Source object:** [[01 ATT&CK/G0138 - Andariel|G0138: Andariel]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1049 - System Network Connections Discovery|T1049: System Network Connections Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Andariel](https://attack.mitre.org/groups/G0138) has used the netstat -naop tcp command to display TCP connections on a victim's machine.(Citation: Kaspersky Andariel Ransomware June 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--2bb829ce-e597-4033-af7c-ef44aaebadb4`.
