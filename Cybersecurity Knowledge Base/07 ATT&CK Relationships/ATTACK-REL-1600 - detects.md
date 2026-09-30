---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0024"
target_object: "T1558.005"
stix_relationship_id: "relationship--4fd70bfe-cbf3-4f11-8a28-4ccbcce12446"
---
# Relationship 1600: DET0024 — detects → T1558.005

**Source object:** [[01 ATT&CK/DET0024 - Detect Kerberos Ccache File Theft or Abuse (T1558.005)|DET0024: Detect Kerberos Ccache File Theft or Abuse (T1558.005)]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1558.005 - Ccache Files|T1558.005: Ccache Files]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--4fd70bfe-cbf3-4f11-8a28-4ccbcce12446`.
