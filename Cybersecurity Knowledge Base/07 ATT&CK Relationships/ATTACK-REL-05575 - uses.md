---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1245"
target_object: "T1048.003"
stix_relationship_id: "relationship--ec1c1a92-8c19-4b09-9722-9db244ec30ca"
---
# Relationship 5575: S1245 — uses → T1048.003

**Source object:** [[01 ATT&CK/S1245 - InvisibleFerret|S1245: InvisibleFerret]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1048.003 - Exfiltration Over Unencrypted Non-C2 Protocol|T1048.003: Exfiltration Over Unencrypted Non-C2 Protocol]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[InvisibleFerret](https://attack.mitre.org/software/S1245) has used FTP to exfiltrate files and directories using the command `ssh_upload` which contains with six subcommands of `.sdira`, `sdir`, `sfile`, `sfinda`, `sfindr` and `sfind` that had varying functions.(Citation: ESET Contagious Interview BeaverTail InvisibleFerret February 2025)(Citation: Zscaler ContagiousInterview BeaverTail InvisibleFerret November 2024) [InvisibleFerret](https://attack.mitre.org/software/S1245) has exfiltrated stolen files and data to the C2 servers over ports 1224, 2245 and 8637.(Citation: Esentire ContagiousInterview BeaverTail InvisibleFerret November 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--ec1c1a92-8c19-4b09-9722-9db244ec30ca`.
