---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1040"
target_object: "T1048.002"
stix_relationship_id: "relationship--d3a5df12-454a-44f7-a3d1-9154dcc815e9"
---
# Relationship 9077: S1040 — uses → T1048.002

**Source object:** [[01 ATT&CK/S1040 - Rclone|S1040: Rclone]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1048.002 - Exfiltration Over Asymmetric Encrypted Non-C2 Protocol|T1048.002: Exfiltration Over Asymmetric Encrypted Non-C2 Protocol]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Rclone](https://attack.mitre.org/software/S1040) can exfiltrate data over SFTP or HTTPS via WebDAV.(Citation: Rclone)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d3a5df12-454a-44f7-a3d1-9154dcc815e9`.
