---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0001"
target_object: "T1057"
stix_relationship_id: "relationship--08052557-0aa5-49d0-9254-722e4f04804f"
---
# Relationship 3260: C0001 — uses → T1057

**Source object:** [[01 ATT&CK/C0001 - Frankenstein|C0001: Frankenstein]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1057 - Process Discovery|T1057: Process Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

During [Frankenstein](https://attack.mitre.org/campaigns/C0001), the threat actors used [Empire](https://attack.mitre.org/software/S0363) to obtain a list of all running processes.(Citation: Talos Frankenstein June 2019)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--08052557-0aa5-49d0-9254-722e4f04804f`.
