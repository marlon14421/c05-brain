---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0572"
target_object: "T1041"
stix_relationship_id: "relationship--a1c31042-ca50-4bcc-bd05-20eb48c655ef"
---
# Relationship 4592: S0572 — uses → T1041

**Source object:** [[01 ATT&CK/S0572 - Caterpillar WebShell|S0572: Caterpillar WebShell]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1041 - Exfiltration Over C2 Channel|T1041: Exfiltration Over C2 Channel]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Caterpillar WebShell](https://attack.mitre.org/software/S0572) can upload files over the C2 channel.(Citation: ClearSky Lebanese Cedar Jan 2021)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a1c31042-ca50-4bcc-bd05-20eb48c655ef`.
