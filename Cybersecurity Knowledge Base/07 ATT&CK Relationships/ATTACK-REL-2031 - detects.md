---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0522"
target_object: "T1558"
stix_relationship_id: "relationship--d1276173-76de-43a0-be72-ef59ce90c44c"
---
# Relationship 2031: DET0522 — detects → T1558

**Source object:** [[01 ATT&CK/DET0522 - Detect Kerberos Ticket Theft or Forgery (T1558)|DET0522: Detect Kerberos Ticket Theft or Forgery (T1558)]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1558 - Steal or Forge Kerberos Tickets|T1558: Steal or Forge Kerberos Tickets]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d1276173-76de-43a0-be72-ef59ce90c44c`.
