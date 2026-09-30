---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0901"
target_object: "T1686.003"
stix_relationship_id: "relationship--3dd0c2d0-7b77-47ef-89d1-983c732dff28"
---
# Relationship 1566: DET0901 — detects → T1686.003

**Source object:** [[01 ATT&CK/DET0901 - Detect Windows Firewall|DET0901: Detect Windows Firewall]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1686.003 - Windows Host Firewall|T1686.003: Windows Host Firewall]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--3dd0c2d0-7b77-47ef-89d1-983c732dff28`.
