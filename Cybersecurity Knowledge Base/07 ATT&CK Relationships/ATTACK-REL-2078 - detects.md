---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0241"
target_object: "T1558.002"
stix_relationship_id: "relationship--7d376833-15ae-4f33-9a3a-2873da760237"
---
# Relationship 2078: DET0241 — detects → T1558.002

**Source object:** [[01 ATT&CK/DET0241 - Detect Forged Kerberos Silver Tickets (T1558.002)|DET0241: Detect Forged Kerberos Silver Tickets (T1558.002)]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1558.002 - Silver Ticket|T1558.002: Silver Ticket]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--7d376833-15ae-4f33-9a3a-2873da760237`.
