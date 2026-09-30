---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9012"
target_object: "T1055.012"
stix_relationship_id: "relationship--a418c81f-ab70-4d04-88f5-c1f49d0eceb4"
---
# Relationship 4535: S9012 — uses → T1055.012

**Source object:** [[01 ATT&CK/S9012 - TRAILBLAZE|S9012: TRAILBLAZE]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1055.012 - Process Hollowing|T1055.012: Process Hollowing]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[TRAILBLAZE](https://attack.mitre.org/software/S9012) has injected a hook into an existing process to load [BRUSHFIRE](https://attack.mitre.org/software/S9011) in the spaces allocated memory to include the Ivanti Connect Secure (ICS) web process named `web`.(Citation: Google UNC5221 Ivanti April 2025)(Citation: Picus Security UNC5221 Ivanti May 2025)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a418c81f-ab70-4d04-88f5-c1f49d0eceb4`.
