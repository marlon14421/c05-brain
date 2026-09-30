---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1047"
target_object: "T1558.004"
stix_relationship_id: "relationship--3de2faf5-8019-4aad-a317-fb66554cd2c0"
---
# Relationship 1223: M1047 — mitigates → T1558.004

**Source object:** [[01 ATT&CK/M1047 - Audit|M1047: Audit]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1558.004 - AS-REP Roasting|T1558.004: AS-REP Roasting]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Kerberos preauthentication is enabled by default. Older protocols might not support preauthentication therefore it is possible to have this setting disabled. Make sure that all accounts have preauthentication whenever possible and audit changes to setting. Windows tools such as PowerShell may be used to easily find which accounts have preauthentication disabled. (Citation: Microsoft Preauthentication Jul 2012)(Citation: Stealthbits Cracking AS-REP Roasting Jun 2019)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--3de2faf5-8019-4aad-a317-fb66554cd2c0`.
