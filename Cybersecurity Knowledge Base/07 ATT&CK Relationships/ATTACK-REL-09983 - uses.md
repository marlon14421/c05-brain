---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0568"
target_object: "T1047"
stix_relationship_id: "relationship--ed656cf9-64ea-411b-82b8-5260c2694cfd"
---
# Relationship 9983: S0568 — uses → T1047

**Source object:** [[01 ATT&CK/S0568 - EVILNUM|S0568: EVILNUM]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1047 - Windows Management Instrumentation|T1047: Windows Management Instrumentation]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[EVILNUM](https://attack.mitre.org/software/S0568) has used the Windows Management Instrumentation (WMI) tool to enumerate infected machines.(Citation: Prevailion EvilNum May 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--ed656cf9-64ea-411b-82b8-5260c2694cfd`.
