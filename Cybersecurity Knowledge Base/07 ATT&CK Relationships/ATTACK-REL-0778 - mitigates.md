---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1016"
target_object: "T1210"
stix_relationship_id: "relationship--16fd4ddb-1ce4-4254-a301-8ac762573a77"
---
# Relationship 0778: M1016 — mitigates → T1210

**Source object:** [[01 ATT&CK/M1016 - Vulnerability Scanning|M1016: Vulnerability Scanning]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1210 - Exploitation of Remote Services|T1210: Exploitation of Remote Services]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Regularly scan the internal network for available services to identify new and potentially vulnerable services.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--16fd4ddb-1ce4-4254-a301-8ac762573a77`.
