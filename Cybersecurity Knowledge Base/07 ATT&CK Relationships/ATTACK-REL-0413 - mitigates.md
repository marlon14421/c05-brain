---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1044"
target_object: "T1547.008"
stix_relationship_id: "relationship--71bcc1dc-2392-448a-8133-f126fed08023"
---
# Relationship 0413: M1044 — mitigates → T1547.008

**Source object:** [[01 ATT&CK/M1044 - Restrict Library Loading|M1044: Restrict Library Loading]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1547.008 - LSASS Driver|T1547.008: LSASS Driver]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Ensure safe DLL search mode is enabled HKEY_LOCAL_MACHINE\\System\\CurrentControlSet\\Control\\Session Manager\\SafeDllSearchMode to mitigate risk that lsass.exe loads a malicious code library. (Citation: Microsoft DLL Security)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--71bcc1dc-2392-448a-8133-f126fed08023`.
