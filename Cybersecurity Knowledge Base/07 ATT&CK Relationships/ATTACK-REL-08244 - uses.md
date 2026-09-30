---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9035"
target_object: "T1082"
stix_relationship_id: "relationship--170e1e46-f3ea-4edb-a115-dde5a7c13e0f"
---
# Relationship 8244: S9035 — uses → T1082

**Source object:** [[01 ATT&CK/S9035 - LAMEHUG|S9035: LAMEHUG]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1082 - System Information Discovery|T1082: System Information Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[LAMEHUG](https://attack.mitre.org/software/S9035) has the ability to execute Windows commands returned from C2 to gather system information.(Citation: Splunk LAMEHUG SEP 2025)(Citation: Nov AI Threat Tracker)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--170e1e46-f3ea-4edb-a115-dde5a7c13e0f`.
