---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0687"
target_object: "T1571"
stix_relationship_id: "relationship--f4a65903-0b28-4e52-ad3b-bb7c55772509"
---
# Relationship 4320: S0687 — uses → T1571

**Source object:** [[01 ATT&CK/S0687 - Cyclops Blink|S0687: Cyclops Blink]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1571 - Non-Standard Port|T1571: Non-Standard Port]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Cyclops Blink](https://attack.mitre.org/software/S0687) can use non-standard ports for C2 not typically associated with HTTP or HTTPS traffic.(Citation: NCSC Cyclops Blink February 2022)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--f4a65903-0b28-4e52-ad3b-bb7c55772509`.
