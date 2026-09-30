---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0030"
target_object: "T1595"
stix_relationship_id: "relationship--ef19089b-8d71-4fdb-9fdc-2eb8521d634f"
---
# Relationship 5598: C0030 — uses → T1595

**Source object:** [[01 ATT&CK/C0030 - Triton Safety Instrumented System Attack|C0030: Triton Safety Instrumented System Attack]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1595 - Active Scanning|T1595: Active Scanning]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

In the [Triton Safety Instrumented System Attack](https://attack.mitre.org/campaigns/C0030), [TEMP.Veles](https://attack.mitre.org/groups/G0088) engaged in network reconnaissance against targets of interest.(Citation: FireEye TEMP.Veles 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--ef19089b-8d71-4fdb-9fdc-2eb8521d634f`.
