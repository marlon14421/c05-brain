---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0135"
target_object: "T1071.003"
stix_relationship_id: "relationship--ae96c6fa-4ea2-4cc3-bae0-68f4e43a6110"
---
# Relationship 2065: DET0135 — detects → T1071.003

**Source object:** [[01 ATT&CK/DET0135 - Detection of Mail Protocol-Based C2 Activity (SMTP, IMAP, POP3)|DET0135: Detection of Mail Protocol-Based C2 Activity (SMTP, IMAP, POP3)]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1071.003 - Mail Protocols|T1071.003: Mail Protocols]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--ae96c6fa-4ea2-4cc3-bae0-68f4e43a6110`.
