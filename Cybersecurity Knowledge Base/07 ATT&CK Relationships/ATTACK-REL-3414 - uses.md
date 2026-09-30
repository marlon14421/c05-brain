---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0431"
target_object: "T1573.001"
stix_relationship_id: "relationship--30da2329-c7ee-4ac9-a38d-af79e6c1389c"
---
# Relationship 3414: S0431 — uses → T1573.001

**Source object:** [[01 ATT&CK/S0431 - HotCroissant|S0431: HotCroissant]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1573.001 - Symmetric Cryptography|T1573.001: Symmetric Cryptography]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[HotCroissant](https://attack.mitre.org/software/S0431) has compressed network communications and encrypted them with a custom stream cipher.(Citation: Carbon Black HotCroissant April 2020)(Citation: US-CERT HOTCROISSANT February 2020)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--30da2329-c7ee-4ac9-a38d-af79e6c1389c`.
