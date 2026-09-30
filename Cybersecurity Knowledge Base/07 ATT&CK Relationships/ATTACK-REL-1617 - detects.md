---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0866"
target_object: "T1681"
stix_relationship_id: "relationship--63de6ee0-215c-4e2f-8dec-a8f63989cc10"
---
# Relationship 1617: DET0866 — detects → T1681

**Source object:** [[01 ATT&CK/DET0866 - Detection of Search Threat Vendor Data|DET0866: Detection of Search Threat Vendor Data]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1681 - Search Threat Vendor Data|T1681: Search Threat Vendor Data]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--63de6ee0-215c-4e2f-8dec-a8f63989cc10`.
