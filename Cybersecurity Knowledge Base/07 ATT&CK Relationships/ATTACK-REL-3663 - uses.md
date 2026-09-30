---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0431"
target_object: "T1106"
stix_relationship_id: "relationship--7066827b-795c-447c-9c07-05765ed1e07b"
---
# Relationship 3663: S0431 — uses → T1106

**Source object:** [[01 ATT&CK/S0431 - HotCroissant|S0431: HotCroissant]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1106 - Native API|T1106: Native API]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[HotCroissant](https://attack.mitre.org/software/S0431) can perform dynamic DLL importing and API lookups using LoadLibrary and GetProcAddress on obfuscated strings.(Citation: US-CERT HOTCROISSANT February 2020)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--7066827b-795c-447c-9c07-05765ed1e07b`.
