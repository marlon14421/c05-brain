---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0428"
target_object: "T1559.002"
stix_relationship_id: "relationship--7ed3bfbd-41a7-46c4-acf7-43330dd50784"
---
# Relationship 4507: S0428 — uses → T1559.002

**Source object:** [[01 ATT&CK/S0428 - PoetRAT|S0428: PoetRAT]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1559.002 - Dynamic Data Exchange|T1559.002: Dynamic Data Exchange]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[PoetRAT](https://attack.mitre.org/software/S0428) was delivered with documents using DDE to execute malicious code.(Citation: Talos PoetRAT April 2020)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--7ed3bfbd-41a7-46c4-acf7-43330dd50784`.
