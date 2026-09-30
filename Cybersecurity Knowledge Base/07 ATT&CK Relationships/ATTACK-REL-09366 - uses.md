---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0009"
target_object: "T1047"
stix_relationship_id: "relationship--d295beee-439c-44f9-9908-4cb194331de9"
---
# Relationship 9366: G0009 — uses → T1047

**Source object:** [[01 ATT&CK/G0009 - Deep Panda|G0009: Deep Panda]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1047 - Windows Management Instrumentation|T1047: Windows Management Instrumentation]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

The [Deep Panda](https://attack.mitre.org/groups/G0009) group is known to utilize WMI for lateral movement.(Citation: Alperovitch 2014)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d295beee-439c-44f9-9908-4cb194331de9`.
