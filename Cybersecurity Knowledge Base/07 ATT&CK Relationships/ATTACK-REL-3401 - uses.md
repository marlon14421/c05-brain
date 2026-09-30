---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0352"
target_object: "T1553.001"
stix_relationship_id: "relationship--e735944e-9387-4cfb-bf2c-0a1c27d93bce"
---
# Relationship 3401: S0352 — uses → T1553.001

**Source object:** [[01 ATT&CK/S0352 - OSX_OCEANLOTUS.D|S0352: OSX_OCEANLOTUS.D]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1553.001 - Gatekeeper Bypass|T1553.001: Gatekeeper Bypass]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[OSX_OCEANLOTUS.D](https://attack.mitre.org/software/S0352) uses the command xattr -d com.apple.quarantine to remove the quarantine file attribute used by Gatekeeper.(Citation: Trend Micro MacOS Backdoor November 2020)(Citation: 20 macOS Common Tools and Techniques)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e735944e-9387-4cfb-bf2c-0a1c27d93bce`.
