---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0314"
target_object: "T1040"
stix_relationship_id: "relationship--0dcf6c3b-b899-4ee4-99ad-cad56967f9ca"
---
# Relationship 1604: DET0314 — detects → T1040

**Source object:** [[01 ATT&CK/DET0314 - Detection Strategy for Network Sniffing Across Platforms|DET0314: Detection Strategy for Network Sniffing Across Platforms]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1040 - Network Sniffing|T1040: Network Sniffing]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--0dcf6c3b-b899-4ee4-99ad-cad56967f9ca`.
