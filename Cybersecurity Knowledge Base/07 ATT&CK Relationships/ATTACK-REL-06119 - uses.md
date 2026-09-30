---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0107"
target_object: "T1048.003"
stix_relationship_id: "relationship--ed2c177c-18fc-4bfd-9169-48af1557a542"
---
# Relationship 6119: S0107 — uses → T1048.003

**Source object:** [[01 ATT&CK/S0107 - Cherry Picker|S0107: Cherry Picker]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1048.003 - Exfiltration Over Unencrypted Non-C2 Protocol|T1048.003: Exfiltration Over Unencrypted Non-C2 Protocol]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Cherry Picker](https://attack.mitre.org/software/S0107) exfiltrates files over FTP.(Citation: Trustwave Cherry Picker)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--ed2c177c-18fc-4bfd-9169-48af1557a542`.
