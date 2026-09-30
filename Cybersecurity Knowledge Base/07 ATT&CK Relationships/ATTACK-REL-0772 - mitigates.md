---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1047"
target_object: "T1685.001"
stix_relationship_id: "relationship--31ca8630-4b0a-4e5f-a3eb-45c8ee8841ad"
---
# Relationship 0772: M1047 — mitigates → T1685.001

**Source object:** [[01 ATT&CK/M1047 - Audit|M1047: Audit]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1685.001 - Disable or Modify Windows Event Log|T1685.001: Disable or Modify Windows Event Log]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Consider periodic review of auditpol settings for Administrator accounts and perform dynamic baselining on SIEM(s) to investigate potential malicious activity. Also ensure that the EventLog service and its threads are properly running.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--31ca8630-4b0a-4e5f-a3eb-45c8ee8841ad`.
