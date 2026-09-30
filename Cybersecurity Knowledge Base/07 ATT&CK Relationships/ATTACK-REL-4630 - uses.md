---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0247"
target_object: "T1055"
stix_relationship_id: "relationship--81bace85-005e-4edd-bb71-ca7a57bc8a07"
---
# Relationship 4630: S0247 — uses → T1055

**Source object:** [[01 ATT&CK/S0247 - NavRAT|S0247: NavRAT]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1055 - Process Injection|T1055: Process Injection]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[NavRAT](https://attack.mitre.org/software/S0247) copies itself into a running Internet Explorer process to evade detection.(Citation: Talos NavRAT May 2018)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--81bace85-005e-4edd-bb71-ca7a57bc8a07`.
