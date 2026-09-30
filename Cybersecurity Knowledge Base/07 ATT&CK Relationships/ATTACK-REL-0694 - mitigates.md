---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1034"
target_object: "T1219"
stix_relationship_id: "relationship--9ae55ec5-a4f8-4619-8565-fe00433c574a"
---
# Relationship 0694: M1034 — mitigates → T1219

**Source object:** [[01 ATT&CK/M1034 - Limit Hardware Installation|M1034: Limit Hardware Installation]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1219 - Remote Access Tools|T1219: Remote Access Tools]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Block the use of IP-based KVM devices within the network if they are not required.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--9ae55ec5-a4f8-4619-8565-fe00433c574a`.
