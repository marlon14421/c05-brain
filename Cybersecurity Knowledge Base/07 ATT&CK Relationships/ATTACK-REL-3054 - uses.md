---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0131"
target_object: "S0349"
stix_relationship_id: "relationship--a779fd0b-0fa0-4bcd-837f-4d3e12482ca1"
---
# Relationship 3054: G0131 — uses → S0349

**Source object:** [[01 ATT&CK/G0131 - Tonto Team|G0131: Tonto Team]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S0349 - LaZagne|S0349: LaZagne]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

(Citation: TrendMicro Tonto Team October 2020)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a779fd0b-0fa0-4bcd-837f-4d3e12482ca1`.
