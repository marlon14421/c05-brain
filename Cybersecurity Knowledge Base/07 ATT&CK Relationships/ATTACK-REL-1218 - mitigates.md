---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1038"
target_object: "T1574.009"
stix_relationship_id: "relationship--b7a27a94-f036-4a0b-a96c-aa7bb1c7311f"
---
# Relationship 1218: M1038 — mitigates → T1574.009

**Source object:** [[01 ATT&CK/M1038 - Execution Prevention|M1038: Execution Prevention]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1574.009 - Path Interception by Unquoted Path|T1574.009: Path Interception by Unquoted Path]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Adversaries will likely need to place new binaries in locations to be executed through this weakness. Identify and block potentially malicious software executed path interception by using application control tools, like Windows Defender Application Control, AppLocker, or Software Restriction Policies where appropriate.(Citation: SANS Application Whitelisting)(Citation: Microsoft Windows Defender Application Control)(Citation: Windows Commands JPCERT)(Citation: NSA MS AppLocker)(Citation: Microsoft Application Lockdown)(Citation: Microsoft Using Software Restriction )

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--b7a27a94-f036-4a0b-a96c-aa7bb1c7311f`.
