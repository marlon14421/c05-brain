---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1052"
target_object: "T1550.002"
stix_relationship_id: "relationship--2dcd6644-f1d4-4001-81a5-95701fd29360"
---
# Relationship 0770: M1052 — mitigates → T1550.002

**Source object:** [[01 ATT&CK/M1052 - User Account Control|M1052: User Account Control]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1550.002 - Pass the Hash|T1550.002: Pass the Hash]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Enable pass the hash mitigations to apply UAC restrictions to local accounts on network logon. The associated Registry key is located HKLM\SOFTWARE\Microsoft\Windows\CurrentVersion\Policies\System\LocalAccountTokenFilterPolicy . Through GPO: Computer Configuration > [Policies] > Administrative Templates > SCM: Pass the Hash Mitigations: Apply UAC restrictions to local accounts on network logons.(Citation: GitHub IAD Secure Host Baseline UAC Filtering)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--2dcd6644-f1d4-4001-81a5-95701fd29360`.
