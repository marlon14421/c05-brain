---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0076"
target_object: "T1048.003"
stix_relationship_id: "relationship--4612c0bd-f6f7-4c71-92dd-9f26ff1c3eef"
---
# Relationship 9894: G0076 — uses → T1048.003

**Source object:** [[01 ATT&CK/G0076 - Thrip|G0076: Thrip]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1048.003 - Exfiltration Over Unencrypted Non-C2 Protocol|T1048.003: Exfiltration Over Unencrypted Non-C2 Protocol]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Thrip](https://attack.mitre.org/groups/G0076) has used WinSCP to exfiltrate data from a targeted organization over FTP.(Citation: Symantec Thrip June 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--4612c0bd-f6f7-4c71-92dd-9f26ff1c3eef`.
