---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0562"
target_object: "T1027"
stix_relationship_id: "relationship--41118997-c45e-4123-be61-1b0c5d456256"
---
# Relationship 4875: S0562 — uses → T1027

**Source object:** [[01 ATT&CK/S0562 - SUNSPOT|S0562: SUNSPOT]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027 - Obfuscated Files or Information|T1027: Obfuscated Files or Information]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[SUNSPOT](https://attack.mitre.org/software/S0562) encrypted log entries it collected with the stream cipher RC4 using a hard-coded key. It also uses AES128-CBC encrypted blobs for [SUNBURST](https://attack.mitre.org/software/S0559) source code and data extracted from the SolarWinds Orion process.(Citation: CrowdStrike SUNSPOT Implant January 2021)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--41118997-c45e-4123-be61-1b0c5d456256`.
