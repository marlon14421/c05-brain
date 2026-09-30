---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0153"
target_object: "T1555.003"
stix_relationship_id: "relationship--4086a9d6-5574-48fb-be8d-e8406145e740"
---
# Relationship 3547: S0153 — uses → T1555.003

**Source object:** [[01 ATT&CK/S0153 - RedLeaves|S0153: RedLeaves]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1555.003 - Credentials from Web Browsers|T1555.003: Credentials from Web Browsers]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[RedLeaves](https://attack.mitre.org/software/S0153) can gather browser usernames and passwords.(Citation: Accenture Hogfish April 2018)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--4086a9d6-5574-48fb-be8d-e8406145e740`.
