---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1048"
target_object: "T1190"
stix_relationship_id: "relationship--0c8fdb59-a28f-4f8f-a788-9e3e8928c6d5"
---
# Relationship 0789: M1048 — mitigates → T1190

**Source object:** [[01 ATT&CK/M1048 - Application Isolation and Sandboxing|M1048: Application Isolation and Sandboxing]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1190 - Exploit Public-Facing Application|T1190: Exploit Public-Facing Application]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Application isolation will limit what other processes and system features the exploited target can access.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--0c8fdb59-a28f-4f8f-a788-9e3e8928c6d5`.
