---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0129"
target_object: "T1572"
stix_relationship_id: "relationship--e67a8b60-ef9c-484b-91b4-0594a7b60eb2"
---
# Relationship 5141: G0129 — uses → T1572

**Source object:** [[01 ATT&CK/G0129 - Mustang Panda|G0129: Mustang Panda]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1572 - Protocol Tunneling|T1572: Protocol Tunneling]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Mustang Panda](https://attack.mitre.org/groups/G0129) has leveraged OpenSSH (sshd.exe) to execute commands, transfer files and spread across the environment communicating over SMB port 445.(Citation: Unit42 Chinese VSCode 06 September 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e67a8b60-ef9c-484b-91b4-0594a7b60eb2`.
