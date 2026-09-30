---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0052"
target_object: "T1140"
stix_relationship_id: "relationship--e1fba82d-1cd2-4906-92db-ba3aafad72ca"
---
# Relationship 3123: S0052 — uses → T1140

**Source object:** [[01 ATT&CK/S0052 - OnionDuke|S0052: OnionDuke]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1140 - Deobfuscate-Decode Files or Information|T1140: Deobfuscate/Decode Files or Information]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[OnionDuke](https://attack.mitre.org/software/S0052) can use a custom decryption algorithm to decrypt strings.(Citation: ESET Dukes October 2019)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e1fba82d-1cd2-4906-92db-ba3aafad72ca`.
