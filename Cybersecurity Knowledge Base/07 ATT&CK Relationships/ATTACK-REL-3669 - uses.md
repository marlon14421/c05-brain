---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0473"
target_object: "T1027.003"
stix_relationship_id: "relationship--c748a743-6d63-4287-a86a-d799e14fcd99"
---
# Relationship 3669: S0473 — uses → T1027.003

**Source object:** [[01 ATT&CK/S0473 - Avenger|S0473: Avenger]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027.003 - Steganography|T1027.003: Steganography]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Avenger](https://attack.mitre.org/software/S0473) can extract backdoor malware from downloaded images.(Citation: Trend Micro Tick November 2019)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c748a743-6d63-4287-a86a-d799e14fcd99`.
