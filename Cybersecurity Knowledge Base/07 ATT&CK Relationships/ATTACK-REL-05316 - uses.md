---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0606"
target_object: "T1036.005"
stix_relationship_id: "relationship--509a016a-6243-40b1-b1b5-74f6c79ce413"
---
# Relationship 5316: S0606 — uses → T1036.005

**Source object:** [[01 ATT&CK/S0606 - Bad Rabbit|S0606: Bad Rabbit]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1036.005 - Match Legitimate Resource Name or Location|T1036.005: Match Legitimate Resource Name or Location]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Bad Rabbit](https://attack.mitre.org/software/S0606) has masqueraded as a Flash Player installer through the executable file install_flash_player.exe .(Citation: ESET Bad Rabbit)(Citation: Secure List Bad Rabbit)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--509a016a-6243-40b1-b1b5-74f6c79ce413`.
