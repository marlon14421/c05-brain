---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0600"
target_object: "T1057"
stix_relationship_id: "relationship--fbfb4e97-11d5-497a-8d57-a9ebe5254f56"
---
# Relationship 4839: S0600 — uses → T1057

**Source object:** [[01 ATT&CK/S0600 - Doki|S0600: Doki]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1057 - Process Discovery|T1057: Process Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Doki](https://attack.mitre.org/software/S0600) has searched for the current process’s PID.(Citation: Intezer Doki July 20)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--fbfb4e97-11d5-497a-8d57-a9ebe5254f56`.
