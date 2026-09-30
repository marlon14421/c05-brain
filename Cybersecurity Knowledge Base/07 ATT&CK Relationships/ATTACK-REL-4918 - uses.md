---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0397"
target_object: "T1014"
stix_relationship_id: "relationship--e9f52758-d5aa-4a16-b614-ea756a0cf270"
---
# Relationship 4918: S0397 — uses → T1014

**Source object:** [[01 ATT&CK/S0397 - LoJax|S0397: LoJax]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1014 - Rootkit|T1014: Rootkit]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[LoJax](https://attack.mitre.org/software/S0397) is a UEFI BIOS rootkit deployed to persist remote access software on some targeted systems.(Citation: ESET LoJax Sept 2018)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e9f52758-d5aa-4a16-b614-ea756a0cf270`.
