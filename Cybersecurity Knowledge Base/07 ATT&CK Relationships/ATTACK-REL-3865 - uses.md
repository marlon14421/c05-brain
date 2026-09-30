---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0356"
target_object: "T1041"
stix_relationship_id: "relationship--c6761f22-a8ed-4a9a-8d58-e8eee38ead88"
---
# Relationship 3865: S0356 — uses → T1041

**Source object:** [[01 ATT&CK/S0356 - KONNI|S0356: KONNI]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1041 - Exfiltration Over C2 Channel|T1041: Exfiltration Over C2 Channel]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[KONNI](https://attack.mitre.org/software/S0356) has sent data and files to its C2 server.(Citation: Talos Konni May 2017)(Citation: Malwarebytes Konni Aug 2021)(Citation: Malwarebytes KONNI Evolves Jan 2022)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c6761f22-a8ed-4a9a-8d58-e8eee38ead88`.
