---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0260"
target_object: "T1027"
stix_relationship_id: "relationship--9e8f8dce-1921-4738-ae7f-30290a350cf2"
---
# Relationship 4016: S0260 — uses → T1027

**Source object:** [[01 ATT&CK/S0260 - InvisiMole|S0260: InvisiMole]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027 - Obfuscated Files or Information|T1027: Obfuscated Files or Information]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[InvisiMole](https://attack.mitre.org/software/S0260) avoids analysis by encrypting all strings, internal files, configuration data and by using a custom executable format.(Citation: ESET InvisiMole June 2018)(Citation: ESET InvisiMole June 2020)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--9e8f8dce-1921-4738-ae7f-30290a350cf2`.
