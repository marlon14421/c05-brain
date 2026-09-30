---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0459"
target_object: "T1041"
stix_relationship_id: "relationship--03341b9d-6848-4430-a868-b2bc61b357ba"
---
# Relationship 4809: S0459 — uses → T1041

**Source object:** [[01 ATT&CK/S0459 - MechaFlounder|S0459: MechaFlounder]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1041 - Exfiltration Over C2 Channel|T1041: Exfiltration Over C2 Channel]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[MechaFlounder](https://attack.mitre.org/software/S0459) has the ability to send the compromised user's account name and hostname within a URL to C2.(Citation: Unit 42 MechaFlounder March 2019)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--03341b9d-6848-4430-a868-b2bc61b357ba`.
