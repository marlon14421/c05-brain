---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0587"
target_object: "T1041"
stix_relationship_id: "relationship--c92d9edc-e2a9-44e4-95ef-81632eaf14f9"
---
# Relationship 4667: S0587 — uses → T1041

**Source object:** [[01 ATT&CK/S0587 - Penquin|S0587: Penquin]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1041 - Exfiltration Over C2 Channel|T1041: Exfiltration Over C2 Channel]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Penquin](https://attack.mitre.org/software/S0587) can execute the command code do_upload to send files to C2.(Citation: Leonardo Turla Penquin May 2020)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c92d9edc-e2a9-44e4-95ef-81632eaf14f9`.
