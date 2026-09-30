---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0524"
target_object: "T1205"
stix_relationship_id: "relationship--b014be93-7f58-428b-9612-069d50c1a9e8"
---
# Relationship 1814: DET0524 — detects → T1205

**Source object:** [[01 ATT&CK/DET0524 - Traffic Signaling (Port-knock - magic-packet → firewall or service activation) – T120|DET0524: Traffic Signaling (Port-knock / magic-packet → firewall or service activation) – T1205]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1205 - Traffic Signaling|T1205: Traffic Signaling]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--b014be93-7f58-428b-9612-069d50c1a9e8`.
