---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0368"
target_object: "T1486"
stix_relationship_id: "relationship--aac8f64e-54d1-4aad-80ee-dd3cd887f30e"
---
# Relationship 2945: S0368 — uses → T1486

**Source object:** [[01 ATT&CK/S0368 - NotPetya|S0368: NotPetya]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1486 - Data Encrypted for Impact|T1486: Data Encrypted for Impact]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[NotPetya](https://attack.mitre.org/software/S0368) encrypts user files and disk structures like the MBR with 2048-bit RSA.(Citation: Talos Nyetya June 2017)(Citation: US-CERT NotPetya 2017)(Citation: US District Court Indictment GRU Unit 74455 October 2020)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--aac8f64e-54d1-4aad-80ee-dd3cd887f30e`.
