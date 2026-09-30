---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0440"
target_object: "T1216.002"
stix_relationship_id: "relationship--c71a06a1-1259-42de-b8d7-4599a228c7af"
---
# Relationship 2044: DET0440 — detects → T1216.002

**Source object:** [[01 ATT&CK/DET0440 - Detecting PowerShell Execution via SyncAppvPublishingServer.vbs Proxy Abuse|DET0440: Detecting PowerShell Execution via SyncAppvPublishingServer.vbs Proxy Abuse]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1216.002 - SyncAppvPublishingServer|T1216.002: SyncAppvPublishingServer]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c71a06a1-1259-42de-b8d7-4599a228c7af`.
