---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0045"
target_object: "T1573.002"
stix_relationship_id: "relationship--d5bc22fc-16dd-4ab6-9599-828f4b33ec2b"
---
# Relationship 4706: S0045 — uses → T1573.002

**Source object:** [[01 ATT&CK/S0045 - ADVSTORESHELL|S0045: ADVSTORESHELL]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1573.002 - Asymmetric Cryptography|T1573.002: Asymmetric Cryptography]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

A variant of [ADVSTORESHELL](https://attack.mitre.org/software/S0045) encrypts some C2 with RSA.(Citation: Bitdefender APT28 Dec 2015)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d5bc22fc-16dd-4ab6-9599-828f4b33ec2b`.
