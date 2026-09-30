---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0196"
target_object: "T1036.005"
stix_relationship_id: "relationship--5a1876a1-144f-4416-b9bf-6df819613962"
---
# Relationship 3108: S0196 — uses → T1036.005

**Source object:** [[01 ATT&CK/S0196 - PUNCHBUGGY|S0196: PUNCHBUGGY]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1036.005 - Match Legitimate Resource Name or Location|T1036.005: Match Legitimate Resource Name or Location]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[PUNCHBUGGY](https://attack.mitre.org/software/S0196) mimics filenames from %SYSTEM%\System32 to hide DLLs in %WINDIR% and/or %TEMP%.(Citation: FireEye Know Your Enemy FIN8 Aug 2016)(Citation: Morphisec ShellTea June 2019)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--5a1876a1-144f-4416-b9bf-6df819613962`.
