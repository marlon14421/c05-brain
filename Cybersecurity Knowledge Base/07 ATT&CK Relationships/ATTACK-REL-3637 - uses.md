---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0641"
target_object: "T1048"
stix_relationship_id: "relationship--91cd43d9-17cb-41d3-b62d-4b79030f4384"
---
# Relationship 3637: S0641 — uses → T1048

**Source object:** [[01 ATT&CK/S0641 - Kobalos|S0641: Kobalos]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1048 - Exfiltration Over Alternative Protocol|T1048: Exfiltration Over Alternative Protocol]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Kobalos](https://attack.mitre.org/software/S0641) can exfiltrate credentials over the network via UDP.(Citation: ESET Kobalos Jan 2021)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--91cd43d9-17cb-41d3-b62d-4b79030f4384`.
