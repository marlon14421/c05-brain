---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0023"
target_object: "T1083"
stix_relationship_id: "relationship--838b4a52-1360-4ca7-ab25-1b549508e687"
---
# Relationship 3678: S0023 — uses → T1083

**Source object:** [[01 ATT&CK/S0023 - CHOPSTICK|S0023: CHOPSTICK]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1083 - File and Directory Discovery|T1083: File and Directory Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

An older version of [CHOPSTICK](https://attack.mitre.org/software/S0023) has a module that monitors all mounted volumes for files with the extensions .doc, .docx, .pgp, .gpg, .m2f, or .m2o.(Citation: ESET Sednit Part 2)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--838b4a52-1360-4ca7-ab25-1b549508e687`.
