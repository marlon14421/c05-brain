---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0129"
target_object: "T1059.003"
stix_relationship_id: "relationship--672c21b6-0a54-4b70-8ce0-591cc5a72622"
---
# Relationship 9586: G0129 — uses → T1059.003

**Source object:** [[01 ATT&CK/G0129 - Mustang Panda|G0129: Mustang Panda]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.003 - Windows Command Shell|T1059.003: Windows Command Shell]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Mustang Panda](https://attack.mitre.org/groups/G0129) has executed HTA files via cmd.exe, and used batch scripts for collection.(Citation: Anomali MUSTANG PANDA October 2019)(Citation: Avira Mustang Panda January 2020) [Mustang Panda](https://attack.mitre.org/groups/G0129) has also utilized cmd.exe to execute commands on an infected host such as `cmd.exe /c ping.exe 8.8.8.8 -n 70&&"%temp%\FontEDL.exe"`.(Citation: Cisco Talos MUSTANG PANDA PLUGX PUBLOAD MAY 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--672c21b6-0a54-4b70-8ce0-591cc5a72622`.
