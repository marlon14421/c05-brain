---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0043"
target_object: "T1082"
stix_relationship_id: "relationship--ea4c3651-b2a3-418e-8d3b-3c8075b988ef"
---
# Relationship 4360: S0043 — uses → T1082

**Source object:** [[01 ATT&CK/S0043 - BUBBLEWRAP|S0043: BUBBLEWRAP]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1082 - System Information Discovery|T1082: System Information Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[BUBBLEWRAP](https://attack.mitre.org/software/S0043) collects system information, including the operating system version and hostname.(Citation: FireEye admin@338)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--ea4c3651-b2a3-418e-8d3b-3c8075b988ef`.
