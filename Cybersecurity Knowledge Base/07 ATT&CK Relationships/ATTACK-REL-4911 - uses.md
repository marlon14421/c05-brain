---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0063"
target_object: "T1587.001"
stix_relationship_id: "relationship--580696cf-0816-4b7a-bfcf-ce61e59c6073"
---
# Relationship 4911: C0063 — uses → T1587.001

**Source object:** [[01 ATT&CK/C0063 - 2025 Poland Wiper Attacks|C0063: 2025 Poland Wiper Attacks]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1587.001 - Malware|T1587.001: Malware]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

During the [2025 Poland Wiper Attacks](https://attack.mitre.org/campaigns/C0063), the adversaries observed that their malware was initially detected by the victims EDR solutions, so they modified the payload and attempted to execute the new version within the same day.(Citation: CERT Polska)(Citation: ESET DynoWiper JAN 2026)(Citation: ESET DynoWiper Update JAN 2026)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--580696cf-0816-4b7a-bfcf-ce61e59c6073`.
