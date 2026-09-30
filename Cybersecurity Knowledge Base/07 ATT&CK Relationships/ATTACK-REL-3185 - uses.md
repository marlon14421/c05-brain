---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1201"
target_object: "T1041"
stix_relationship_id: "relationship--3cc0db99-8172-41e5-b386-3488bfb41f43"
---
# Relationship 3185: S1201 — uses → T1041

**Source object:** [[01 ATT&CK/S1201 - TRANSLATEXT|S1201: TRANSLATEXT]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1041 - Exfiltration Over C2 Channel|T1041: Exfiltration Over C2 Channel]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[TRANSLATEXT](https://attack.mitre.org/software/S1201) has exfiltrated collected credentials to the C2 server.(Citation: Zscaler Kimsuky TRANSLATEXT)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--3cc0db99-8172-41e5-b386-3488bfb41f43`.
