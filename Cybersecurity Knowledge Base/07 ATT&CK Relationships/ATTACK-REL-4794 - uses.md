---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9028"
target_object: "T1105"
stix_relationship_id: "relationship--631156f6-a414-4856-81b0-e4bd727e77ba"
---
# Relationship 4794: S9028 — uses → T1105

**Source object:** [[01 ATT&CK/S9028 - PHPsert|S9028: PHPsert]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1105 - Ingress Tool Transfer|T1105: Ingress Tool Transfer]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[PHPsert](https://attack.mitre.org/software/S9028) has the ability to retrieve remote payloads.(Citation: sentinelone operationDigitalEye Dec 2024)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--631156f6-a414-4856-81b0-e4bd727e77ba`.
