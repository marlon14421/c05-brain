---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0030"
target_object: "T1036.005"
stix_relationship_id: "relationship--30ac4618-8059-4e7a-869a-4c3cb84577a2"
---
# Relationship 5828: C0030 — uses → T1036.005

**Source object:** [[01 ATT&CK/C0030 - Triton Safety Instrumented System Attack|C0030: Triton Safety Instrumented System Attack]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1036.005 - Match Legitimate Resource Name or Location|T1036.005: Match Legitimate Resource Name or Location]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

In the [Triton Safety Instrumented System Attack](https://attack.mitre.org/campaigns/C0030), [TEMP.Veles](https://attack.mitre.org/groups/G0088) renamed files to look like legitimate files, such as Windows update files or Schneider Electric application files.

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--30ac4618-8059-4e7a-869a-4c3cb84577a2`.
