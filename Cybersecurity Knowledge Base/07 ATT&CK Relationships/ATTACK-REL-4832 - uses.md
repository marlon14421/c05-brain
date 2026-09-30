---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0379"
target_object: "T1125"
stix_relationship_id: "relationship--2dc986cb-ed76-42ba-9dd9-edaba07b0cc7"
---
# Relationship 4832: S0379 — uses → T1125

**Source object:** [[01 ATT&CK/S0379 - Revenge RAT|S0379: Revenge RAT]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1125 - Video Capture|T1125: Video Capture]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Revenge RAT](https://attack.mitre.org/software/S0379) has the ability to access the webcam.(Citation: Cylance Shaheen Nov 2018)(Citation: Cofense RevengeRAT Feb 2019)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--2dc986cb-ed76-42ba-9dd9-edaba07b0cc7`.
