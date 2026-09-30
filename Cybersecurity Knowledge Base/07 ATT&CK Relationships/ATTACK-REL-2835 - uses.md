---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1026"
target_object: "T1055.001"
stix_relationship_id: "relationship--cc2dd0db-3679-4b14-b9a1-4aff659e2c4a"
---
# Relationship 2835: S1026 — uses → T1055.001

**Source object:** [[01 ATT&CK/S1026 - Mongall|S1026: Mongall]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1055.001 - Dynamic-link Library Injection|T1055.001: Dynamic-link Library Injection]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Mongall](https://attack.mitre.org/software/S1026) can inject a DLL into `rundll32.exe` for execution.(Citation: SentinelOne Aoqin Dragon June 2022)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--cc2dd0db-3679-4b14-b9a1-4aff659e2c4a`.
