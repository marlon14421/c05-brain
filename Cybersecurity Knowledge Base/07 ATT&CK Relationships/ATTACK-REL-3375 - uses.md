---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0673"
target_object: "T1070"
stix_relationship_id: "relationship--f54e5455-c539-4bcb-9a06-92440314324f"
---
# Relationship 3375: S0673 — uses → T1070

**Source object:** [[01 ATT&CK/S0673 - DarkWatchman|S0673: DarkWatchman]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1070 - Indicator Removal|T1070: Indicator Removal]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[DarkWatchman](https://attack.mitre.org/software/S0673) can uninstall malicious components from the Registry, stop processes, and clear the browser history.(Citation: Prevailion DarkWatchman 2021)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--f54e5455-c539-4bcb-9a06-92440314324f`.
