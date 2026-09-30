---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0239"
target_object: "T1041"
stix_relationship_id: "relationship--cb297293-d9bb-484a-a9fb-b7b09477d38f"
---
# Relationship 3963: S0239 — uses → T1041

**Source object:** [[01 ATT&CK/S0239 - Bankshot|S0239: Bankshot]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1041 - Exfiltration Over C2 Channel|T1041: Exfiltration Over C2 Channel]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Bankshot](https://attack.mitre.org/software/S0239) exfiltrates data over its C2 channel.(Citation: McAfee Bankshot)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--cb297293-d9bb-484a-a9fb-b7b09477d38f`.
