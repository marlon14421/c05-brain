---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0129"
target_object: "T1547.001"
stix_relationship_id: "relationship--c0561e30-556b-486b-a7fa-1be6feece584"
---
# Relationship 5927: G0129 — uses → T1547.001

**Source object:** [[01 ATT&CK/G0129 - Mustang Panda|G0129: Mustang Panda]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1547.001 - Registry Run Keys - Startup Folder|T1547.001: Registry Run Keys / Startup Folder]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Mustang Panda](https://attack.mitre.org/groups/G0129) has created the registry key HKEY_LOCAL_MACHINE\SOFTWARE\Wow6432Node\Microsoft\Windows\CurrentVersion\Run\AdobelmdyU to maintain persistence.(Citation: Proofpoint TA416 November 2020) [Mustang Panda](https://attack.mitre.org/groups/G0129) has also established persistence via the registry key `HKCU\Software\Microsoft\Windows\CurrentVersion\Run`.(Citation: EclecticIQ Mustang Panda PlugX)(Citation: Sophos Mustang Panda PLUGX)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c0561e30-556b-486b-a7fa-1be6feece584`.
