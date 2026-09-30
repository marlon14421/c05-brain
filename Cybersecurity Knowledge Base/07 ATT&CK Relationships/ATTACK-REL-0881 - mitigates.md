---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1031"
target_object: "T1204.005"
stix_relationship_id: "relationship--4e35764e-ffcc-4d25-98b9-8bf44c3eb2ad"
---
# Relationship 0881: M1031 — mitigates → T1204.005

**Source object:** [[01 ATT&CK/M1031 - Network Intrusion Prevention|M1031: Network Intrusion Prevention]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1204.005 - Malicious Library|T1204.005: Malicious Library]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Network prevention intrusion systems and systems designed to scan and remove malicious downloads can be used to block activity.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--4e35764e-ffcc-4d25-98b9-8bf44c3eb2ad`.
