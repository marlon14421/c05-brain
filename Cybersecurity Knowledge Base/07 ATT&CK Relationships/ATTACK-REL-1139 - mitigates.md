---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1028"
target_object: "T1003.001"
stix_relationship_id: "relationship--516e746b-6208-41db-8ea8-4e3fa42f5053"
---
# Relationship 1139: M1028 — mitigates → T1003.001

**Source object:** [[01 ATT&CK/M1028 - Operating System Configuration|M1028: Operating System Configuration]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1003.001 - LSASS Memory|T1003.001: LSASS Memory]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Consider disabling or restricting NTLM.(Citation: Microsoft Disable NTLM Nov 2012) Consider disabling WDigest authentication.(Citation: Microsoft WDigest Mit)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--516e746b-6208-41db-8ea8-4e3fa42f5053`.
