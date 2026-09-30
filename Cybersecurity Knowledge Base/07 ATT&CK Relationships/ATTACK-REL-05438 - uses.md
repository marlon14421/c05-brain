---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0006"
target_object: "T1569.002"
stix_relationship_id: "relationship--968911f0-2158-4c76-9fab-562a00ecc418"
---
# Relationship 5438: C0006 — uses → T1569.002

**Source object:** [[01 ATT&CK/C0006 - Operation Honeybee|C0006: Operation Honeybee]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1569.002 - Service Execution|T1569.002: Service Execution]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

During [Operation Honeybee](https://attack.mitre.org/campaigns/C0006), threat actors ran sc start to start the COMSysApp as part of the service hijacking and sc stop to stop and reconfigure the COMSysApp.(Citation: McAfee Honeybee)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--968911f0-2158-4c76-9fab-562a00ecc418`.
