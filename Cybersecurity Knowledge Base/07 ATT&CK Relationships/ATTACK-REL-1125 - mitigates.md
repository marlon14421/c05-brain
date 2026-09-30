---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1043"
target_object: "T1547.008"
stix_relationship_id: "relationship--6ca7aa45-86c5-4ba7-bd43-8d9446fb05d2"
---
# Relationship 1125: M1043 — mitigates → T1547.008

**Source object:** [[01 ATT&CK/M1043 - Credential Access Protection|M1043: Credential Access Protection]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1547.008 - LSASS Driver|T1547.008: LSASS Driver]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

On Windows 10 and Server 2016, enable Windows Defender Credential Guard (Citation: Microsoft Enable Cred Guard April 2017) to run lsass.exe in an isolated virtualized environment without any device drivers. (Citation: Microsoft Credential Guard April 2017)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--6ca7aa45-86c5-4ba7-bd43-8d9446fb05d2`.
