---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0007"
target_object: "T1546.015"
stix_relationship_id: "relationship--54d3eadf-0363-47d1-b51d-a16d6a99c42e"
---
# Relationship 4288: G0007 — uses → T1546.015

**Source object:** [[01 ATT&CK/G0007 - APT28|G0007: APT28]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1546.015 - Component Object Model Hijacking|T1546.015: Component Object Model Hijacking]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[APT28](https://attack.mitre.org/groups/G0007) has used COM hijacking for persistence by replacing the legitimate MMDeviceEnumerator object with a payload.(Citation: ESET Sednit Part 1)(Citation: ESET Zebrocy May 2019)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--54d3eadf-0363-47d1-b51d-a16d6a99c42e`.
