---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0253"
target_object: "T1115"
stix_relationship_id: "relationship--d4f4974e-7918-4829-8379-5e2e98f2ae20"
---
# Relationship 4064: S0253 — uses → T1115

**Source object:** [[01 ATT&CK/S0253 - RunningRAT|S0253: RunningRAT]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1115 - Clipboard Data|T1115: Clipboard Data]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[RunningRAT](https://attack.mitre.org/software/S0253) contains code to open and copy data from the clipboard.(Citation: McAfee Gold Dragon)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d4f4974e-7918-4829-8379-5e2e98f2ae20`.
