---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0638"
target_object: "T1486"
stix_relationship_id: "relationship--18355c9b-c3e8-4bc7-a389-425e5d7c6351"
---
# Relationship 3381: S0638 — uses → T1486

**Source object:** [[01 ATT&CK/S0638 - Babuk|S0638: Babuk]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1486 - Data Encrypted for Impact|T1486: Data Encrypted for Impact]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Babuk](https://attack.mitre.org/software/S0638) can use ChaCha8 and ECDH to encrypt data.(Citation: Sogeti CERT ESEC Babuk March 2021)(Citation: McAfee Babuk February 2021)(Citation: Medium Babuk February 2021)(Citation: Trend Micro Ransomware February 2021)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--18355c9b-c3e8-4bc7-a389-425e5d7c6351`.
