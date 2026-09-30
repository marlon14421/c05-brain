---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0537"
target_object: "T1573.001"
stix_relationship_id: "relationship--9ce0b5a6-b0e8-45b3-9c5c-bbb6b891a216"
---
# Relationship 3033: S0537 — uses → T1573.001

**Source object:** [[01 ATT&CK/S0537 - HyperStack|S0537: HyperStack]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1573.001 - Symmetric Cryptography|T1573.001: Symmetric Cryptography]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[HyperStack](https://attack.mitre.org/software/S0537) has used RSA encryption for C2 communications.(Citation: Accenture HyperStack October 2020)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--9ce0b5a6-b0e8-45b3-9c5c-bbb6b891a216`.
