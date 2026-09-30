---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0395"
target_object: "T1114.002"
stix_relationship_id: "relationship--6c42fa31-80df-4d67-92d2-4273c22a4d5b"
---
# Relationship 4640: S0395 — uses → T1114.002

**Source object:** [[01 ATT&CK/S0395 - LightNeuron|S0395: LightNeuron]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1114.002 - Remote Email Collection|T1114.002: Remote Email Collection]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[LightNeuron](https://attack.mitre.org/software/S0395) collects Exchange emails matching rules specified in its configuration.(Citation: ESET LightNeuron May 2019)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--6c42fa31-80df-4d67-92d2-4273c22a4d5b`.
