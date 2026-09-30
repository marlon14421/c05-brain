---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0653"
target_object: "T1547"
stix_relationship_id: "relationship--1858731f-2e82-4704-acba-b8de57dcfc4f"
---
# Relationship 7021: S0653 — uses → T1547

**Source object:** [[01 ATT&CK/S0653 - xCaon|S0653: xCaon]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1547 - Boot or Logon Autostart Execution|T1547: Boot or Logon Autostart Execution]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[xCaon](https://attack.mitre.org/software/S0653) has added persistence via the Registry key HKEY_CURRENT_USER\Software\Microsoft\Windows NT\CurrentVersion\Windows\load which causes the malware to run each time any user logs in.(Citation: Checkpoint IndigoZebra July 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--1858731f-2e82-4704-acba-b8de57dcfc4f`.
