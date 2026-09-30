---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0453"
target_object: "T1027.016"
stix_relationship_id: "relationship--4b2fa1ed-6c4f-4974-a44e-beeadf3a887c"
---
# Relationship 4894: S0453 — uses → T1027.016

**Source object:** [[01 ATT&CK/S0453 - Pony|S0453: Pony]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027.016 - Junk Code Insertion|T1027.016: Junk Code Insertion]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Pony](https://attack.mitre.org/software/S0453) obfuscates memory flow by adding junk instructions when executing to make analysis more difficult.(Citation: Malwarebytes Pony April 2016)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--4b2fa1ed-6c4f-4974-a44e-beeadf3a887c`.
