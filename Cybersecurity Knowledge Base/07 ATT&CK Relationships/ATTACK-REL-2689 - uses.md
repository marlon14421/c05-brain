---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0140"
target_object: "T1036.004"
stix_relationship_id: "relationship--3c630128-27ba-4c71-b09a-c9ac39e7acac"
---
# Relationship 2689: S0140 — uses → T1036.004

**Source object:** [[01 ATT&CK/S0140 - Shamoon|S0140: Shamoon]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1036.004 - Masquerade Task or Service|T1036.004: Masquerade Task or Service]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Shamoon](https://attack.mitre.org/software/S0140) creates a new service named “ntssrv” that attempts to appear legitimate; the service's display name is “Microsoft Network Realtime Inspection Service” and its description is “Helps guard against time change attempts targeting known and newly discovered vulnerabilities in network time protocols.” Newer versions create the "MaintenaceSrv" service, which misspells the word "maintenance."(Citation: Palo Alto Shamoon Nov 2016)(Citation: McAfee Shamoon December 2018)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--3c630128-27ba-4c71-b09a-c9ac39e7acac`.
