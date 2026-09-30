---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0679"
target_object: "T1120"
stix_relationship_id: "relationship--6b15c0bd-7b39-408b-91fa-cf942a52a933"
---
# Relationship 3923: S0679 — uses → T1120

**Source object:** [[01 ATT&CK/S0679 - Ferocious|S0679: Ferocious]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1120 - Peripheral Device Discovery|T1120: Peripheral Device Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Ferocious](https://attack.mitre.org/software/S0679) can run GET.WORKSPACE in Microsoft Excel to check if a mouse is present.(Citation: Kaspersky WIRTE November 2021)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--6b15c0bd-7b39-408b-91fa-cf942a52a933`.
